# @solumon/eslint-config-prettier

> fork from [@vue/eslint-config-prettier](https://github.com/vuejs/eslint-config-prettier)


## 安装
```sh
npm i -D  @solumon/eslint-config-prettier
```

> 确保你已经安装过 `prettier` 和 `eslint`.

## 使用

添加 `"@solumon/eslint-config-prettier"` 到ESlint配置文件 `"extends"` 字段中

```js

module.exports = {
  extends: [
    // ... other configs
    "@solumon/eslint-config-prettier"
  ]
}
```

## 了解

该配置默认使用 [`eslint-plugin-prettier`](https://github.com/prettier/eslint-plugin-prettier/#recommended-configuration) 推荐配置。
