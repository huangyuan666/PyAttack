# PyAttack .......

## 基于python的批量漏洞检测（抓鸡）脚本......

### Usage:
```bash
[*]python mass_attack.py -n ewebeditor,webdav,struts2 -t http://www.xxx.com    针对单网站指定漏洞检测

[*]python mass_attack.py -n 1(ewebeditor)  针对批量网站进行单个漏洞检测

[*]python mass_attack.py -n all    针对批量网站进行所有漏洞检测
```

### 支持漏洞列表:

[1]ewebeditor

[2]webdav

[3]struts2    S_016  S_019  S_032


### Options:
```bash
  -h, --help  show this help message and exit</br>

  -n NAME, --name=NAME  漏洞名称(*必填*)</br>

  -t TARGET, --target=TARGET  目标url,默认为自动抓取(*可选*)</br></br>
```
  
#### @版本:1.0   
#### @author:by nmask
#### @time: 2016.04.22    
