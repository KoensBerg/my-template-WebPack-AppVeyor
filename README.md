# WebPack & AppVeyor (мой шаблон)

[![Build status](https://ci.appveyor.com/api/projects/status/3lm2wnnss52xt916?svg=true)](https://ci.appveyor.com/project/KoensBerg/my-template-webpack-appveyor)

Мой шаблон, включающий в себя WebPack, Babel, ESLint, JEST, AppVeyor, Husky + правильную структуру папок.

Команды для терминала:
- npm start: "webpack serve --mode development"
- npm run build: "webpack --mode production"
- npm run build-dev: "webpack --mode development"
- npm run lint: "eslint ./src"
- npm test: "jest"
- npm test -- --coverage