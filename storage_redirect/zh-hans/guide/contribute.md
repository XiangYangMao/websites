设置 JSON：

> 轻触应用内的“上传图标”（于 v4.3.0 版本添加），轻触“复制当前设置到剪贴板”并粘贴到下面。

```
{
  "device_info": {
    "locale": "zh-CN",
    "api": 33,
    "manufacturer": "Xiaomi"
  },
  "verified": false,
  "recommendation": "@recommended",
  "behaviors": [
    "@abuse"
  ],
  "non_standard_files": [
    "tencent"
  ],
  "package": "com.tencent.mm",
  "last_update": {
    "target_api": 29,
    "flags": "read_storage, write_storage",
    "version_name": "8.0.40",
    "timestamp": 1694424102,
    "version_code": 2420
  }
}
```

补充必要的信息：

> 1. 如果现有的规则存在错误，请指出。
> 2. 如果隔离后存在部分功能无法使用或有特别的注意事项，请说明。
> 3. 如果可以，介绍该应用使用存储空间的行为。
> 4. 对“可访问文件夹”规则和“导出被隔离的文件”规则，请说明它们的作用。
