# Storybook + React

## 起動方法

```
yarn storybook
```

## 同じ環境を作る手順

```
npx create-react-app storybook-example
cd storybook-example
npx -p @storybook/cli sb init --type react_scripts
yarn add -D @storybook/addon-knobs @storybook/addon-viewport \
 @storybook/addon-docs @storybook/source-loader
```

## 今度はaddon-docsも試したい

https://github.com/storybookjs/storybook/blob/master/addons/docs/README.md