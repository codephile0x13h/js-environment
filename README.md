# Установка JS окружения для Frontend

## 1. Установка Babel
```bash
npm install --save-dev @babel/core @babel/cli @babel/preset-env
```
## 2. Настройка Babel
Добавить запись в файл .babelrc
```
{
    "presets": ["@babel/preset-env"]
}
```
## 3. Установка ESLint
```bash
npm install --save-dev eslint babel-eslint
```
## 4. Настройка ESLint
```bash
npx eslint --init
```
Добавить запить в .eslintrc.json
```
"parser": "babel-eslint"
```
## 5. Установка Jest
```bash
npm install --save-dev jest babel-jest
```
