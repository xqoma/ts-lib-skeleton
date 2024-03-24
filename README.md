# TypeScript Library Skeleton

This is a simple skeleton for the TypeScript library repository.
Feel free to clone it and use as a start point of your TypeScript library!

## Features

- Your library will be compatible with both ECMAScript and CommonJS standards
- [ESLint](https://eslint.org/) (with recommended rules configured)
- [Prettier](https://prettier.io/)
- [Webpack](https://webpack.js.org/)

## Build

To build a bundle you can easily run this npm script:

```bash
npm run build
```

## Testing

Before publishing, you can try your library locally in other project.

1. Create the package:
    ```bash
    npm run package
    ```
   It will generate the `<lib_package_name>.tgz` file in the root directory of your repository.
2. Navigate to the directory of the project in which you want to try your library:
   ```bash
   cd <path_to_project_repo>
   ```
3. Install your library:
   ```bash
   npm install <path_to_lib_repo>/<lib_package_name>.tgz
   ```
4. Try to use your library like a regular package by importing it


## Publishing

To publish your library to the npm Registry just run this command:

```bash
npm publish
```
