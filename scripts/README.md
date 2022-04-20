## 精简tab栏
```ini
[scripts]
http-response ^https://app\.bilibili\.com/x/resource/show/tab(/v2)?\?access_key requires-body=1,max-size=0,script-path=https://raw.githubusercontent.com/Remawater/Rule/main/scripts/bilibili_tab.js
[Quantumult X]
^https://app\.bilibili\.com/x/resource/show/tab(/v2)?\?access_key url script-response-body https://raw.githubusercontent.com/yzqd9527/Rule/main/scripts/bilibili_tab.js
```
