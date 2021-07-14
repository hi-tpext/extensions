# 欢迎使用 tpext扩展仓库

## 格式

```json
[
    {
        "title": "名称，如：某某扩展",
        "name": "标识，如：cn.tpext.shop",
        "type": "类型，module或resource",
        "tags": "分类，如：oss",
        "description": "描述，简单的介绍",
        "composer": "如果是通过composer来安装，填写包名，否则填extend 自定义",
        "website": "项目主页或仓库地址",
        "platform": "支持的tp版本，如：tp5.1，tp6.0",
        "is_free": "是否免费，1为是，0为否",
        "extend_download": "如果是extend自定义扩展，填写zip压缩包的下载地址",
        "version": "如果是extend自定义扩展，填写当前最新版本号，如：1.0.1。为了方便升级，composer扩展请忽略此值。"
    }
]
```
