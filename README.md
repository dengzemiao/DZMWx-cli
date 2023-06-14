# DZMWx-cli

- 基于 [miniprogram-ci](https://developers.weixin.qq.com/miniprogram/dev/devtools/ci.html) 封装的微信小程序自动化发包脚本，常用于各种情况的批量自动发包！

- 使用步骤

  1、`$ npm install`

  2、小程序后台添加导出上传私钥，并导入到 key 文件夹中

  3、修改小程序存放工程存放路径

  4、`package.json` 中 `scripts` 发包命令可以按现有的添加，也可以通过脚本动态更换 `APPID、版本` 相关信息，怎么方便怎么来。

  5、执行命令发包，配合自动化脚本批量发包
