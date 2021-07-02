# mini-program-json-schema

小程序全局配置和页面配置的 json schema

(最低基础库：``)

## `app.json`代码提示使用说明

在 VS Code 的`settings.json`填写以下配置：

```json
{
  "json.schemas": [
    {
      "fileMatch": ["/app.json"],
      "url": "https://raw.githubusercontent.com/bugszhou/mini-program-json-schema/main/src/wechatApp.json"
    }
  ]
}
```

## `page`中`json`代码提示使用说明

在 VS Code 的`settings.json`填写以下配置：

```json
{
  "json.schemas": [
    {
      "fileMatch": ["/index.json"],
      "url": "https://raw.githubusercontent.com/bugszhou/mini-program-json-schema/main/src/wechatPage.json"
    }
  ]
}
```
