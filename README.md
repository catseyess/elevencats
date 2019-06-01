# Enterprise-Registration-Data-of-Chinese-Mainland

中国大陆 31 个省份 1978 年至 2019 年一千多万工商企业注册信息，包含企业名称、注册地址、统一社会信用代码、地区、注册日期、经营范围、法人代表、注册资金、企业类型。

数据以 CSV 、Excel 及 JSON 三种文件类型存储，相应文件分别保存在 Enterprise-Registration-Data/csv、Enterprise-Registration-Data/xls、Enterprise-Registration-Data/json 。

其中 CSV 与 Excel 的格式为：企业名称、统一社会信用代码、注册日期、企业类型、法人代表、注册资金、经营范围、所在省份、地区、注册地址，编码为 UTF-8

JSON 的编码为 UTF-8，文件格式如下：

```json
{
    "name":"企业名称",
    "code":"统一社会信用代码",
    "registrationDay":"注册日期",
    "character":"企业类型",
    "legalRepresentative":"法人代表",
    "capital":"注册资金",
    "businessScope":"经营范围",
    "province":"所在省份",
    "city":"地区",
    "address":"注册地址"
}

```
最新数据会不定期进行更新。

### License

本仓库数据集源自网络，本人不对数据的真实性负责，您引用本仓库内容或者对内容进行修改演绎时，请署名并以相同方式共享，谢谢。

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

