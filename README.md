# Create React App Vite migration

Bash or Node.js ? script to migrate a basic React project created with [CRA](https://create-react-app.dev/) to [Vite](https://vitejs.dev/)

## Steps

[_] Make a copy a the project to migrate
[_] Remove CRA scripts from the `package.json` file.
[_] Add Vite scripts to the `package.json` file.
[_] Add the `vite.config.ts` file at the root of the project.
[_] Update/replace the `tsconfig.json` file. How to merge and or replace ?
[_] Replace in all js, jsx, ts or tsx files in the `src` folder the string : `process.env` with `import.meta.env`
[_] Replace in all `*.env*` files placed on the root of the project the string : `REACT_APP_` with `VITE_`
[_] Move and update the `index.html` file.
[_] Update the `index.html` file.

## References

- <https://javascript.plainenglish.io/migrating-a-create-react-app-cra-application-to-vite-788b13243b5a>

- <https://craftsmenltd.com/blog/2022/06/23/migrating-your-create-react-app-project-to-vite/>

- <https://cathalmacdonnacha.com/migrating-from-create-react-app-cra-to-vite>
