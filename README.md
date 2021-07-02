# mini-program-json-schema

小程序全局配置和页面配置的 json schema

## `app.json`代码提示使用说明

在 VS Code 的`settings.json`填写以下配置：

```json
{
  "json.schemas": [
    {
      "fileMatch": ["/app.json"],
      "url": "/src/wechatApp.json"
    }
  ]
}
```
