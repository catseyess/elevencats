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

This repository is an dataset of over 10,000,000 enterprise registration data of 31 provinces in Chinese mainland from 1978 to 2019.

The enterprise registration data including 10 items: the name of enterprise,uniform social credit code,registration date,character of economy,legal representative,registered capital,business scope,province,city and registration address.

The dataset represents in three different types: CSV,Excel and JSON,which are located at Enterprise-Registration-Data/csv,Enterprise-Registration-Data/xls and Enterprise-Registration-Data/json respectively.

The order of 10 items in CSV and Excel is:name,code,registrationDay,character,legalRepresentative,capital,businessScope,province,city,address. And the record in the JSON file is represented as below:

```json
{
    "name":"the name of enterprise",
    "code":"uniform social credit code",
    "registrationDay":"registration date",
    "character":"character of economy",
    "legalRepresentative":"legal representative",
    "capital":"registered capital",
    "businessScope":"business scope",
    "province":"province",
    "city":"city",
    "address":"registration address"
}

```

The encoding of all those files are UTF-8.

This repository will be updated from time to time.Give me a star or fork this repository if you like it.

### License

本仓库数据集源自网络，本人不对数据的真实性负责，您引用本仓库内容或者对内容进行修改演绎时，请署名并以相同方式共享，谢谢。

The data of this repository is collected from the several open data web sites of Chinese government and this repository is released under [Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)



<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

