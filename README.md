# clash-rules-for-academic
为了方便学术研究，本文件在[前人基础](https://github.com/shxiaj/Clash-paperRule)上提供了一些常见的学术数据库和资源的Clash规则。这些规则可以帮助您更有效地访问和管理学术资源。
![image](https://github.com/stan1233/clash-rules-for-academic/assets/20401741/1dee52d3-8839-495f-b647-71ca58c241d7)
## 修改Settings-Profiles-Parsers
为了确保每次更新订阅地址时都会自动添加上述规则，您需要修改`Settings-Profiles-Parsers`。以下是修改后的配置示例：

```
parsers: # array
  - url: 此处填写订阅地址
    yaml:
      prepend-rules:
        - DOMAIN-SUFFIX,manual.gromacs.org,DIRECT
        - DOMAIN-KEYWORD,sci-hub,DIRECT
        - DOMAIN-SUFFIX,ccdc.cam.ac.uk,DIRECT
        - DOMAIN-KEYWORD,wiley,DIRECT
        - DOMAIN-KEYWORD,pubs,DIRECT
        - DOMAIN-KEYWORD,translate,DIRECT
        - DOMAIN-KEYWORD,docs,DIRECT
        - DOMAIN-KEYWORD,onenote,DIRECT
        - DOMAIN-KEYWORD,office,DIRECT
        - DOMAIN-KEYWORD,microsoft,DIRECT
        - DOMAIN-SUFFIX,digicert.com,DIRECT
        - DOMAIN-SUFFIX,sciencedirect.com,DIRECT
        - DOMAIN-SUFFIX,iresearchbook.cn,DIRECT
        - DOMAIN-SUFFIX,elsevier.com,DIRECT
        - DOMAIN-SUFFIX,nature.com,DIRECT
        - DOMAIN-SUFFIX,webofknowledge.com,DIRECT
        - DOMAIN-SUFFIX,acs.org,DIRECT
        - DOMAIN-SUFFIX,scitation.org,DIRECT
        - DOMAIN-SUFFIX,adobe.io,REJECT
        - DOMAIN-KEYWORD,webofscience,DIRECT
        - DOMAIN-KEYWORD,webofknowledge,DIRECT
        - DOMAIN-KEYWORD,clarivate,DIRECT
        - DOMAIN-KEYWORD,scfinder,DIRECT
        - DOMAIN-KEYWORD,elsevier,DIRECT
        - DOMAIN-KEYWORD,tandfonline,DIRECT
        - DOMAIN-KEYWORD,nature,DIRECT
        - DOMAIN-KEYWORD,acs,DIRECT
        - DOMAIN-KEYWORD,cas,DIRECT
        - DOMAIN-KEYWORD,rsc,DIRECT
        - DOMAIN-KEYWORD,sciencedirect,DIRECT
        - DOMAIN-KEYWORD,springer,DIRECT
        - DOMAIN-KEYWORD,wiley,DIRECT
        - DOMAIN-KEYWORD,JD,DIRECT
        - DOMAIN-KEYWORD,taobao,DIRECT
        - DOMAIN-KEYWORD,360buyimg,DIRECT
        - DOMAIN-KEYWORD,alicdn,DIRECT
        - DOMAIN-KEYWORD,scifinder,DIRECT
        - DOMAIN-KEYWORD,scifinder-n,DIRECT

```
