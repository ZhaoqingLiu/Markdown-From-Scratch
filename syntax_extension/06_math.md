# Math

## 1st Method (Recommended): Using MathJax Engine
At the beginning of a Markdown text, adding:
```html
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
```

Example: x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}

Display: $$x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}$$

**NB: If the above method does not work, you can use Chrome with the extension 'GitHub with MathJax' added.**

## 2nd Method: Using External Server Providing Mathematical Formula Parsing Service
1. Through Google Chart: 

Syntax: \<img src="http://chart.googleapis.com/chart?cht=tx&chl= *Insert your Latex formula*" style="border:none;"\>

Example:
```html
<img src="http://chart.googleapis.com/chart?cht=tx&chl= x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" style="border:none;">
```

Display: <img src="http://chart.googleapis.com/chart?cht=tx&chl= x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}" style="border:none;">

2. Through Forkosh:

Syntax: \<img src="http://www.forkosh.com/mathtex.cgi? *Insert your Latex formula*"\>

Example:
```html
<img src="http://www.forkosh.com/mathtex.cgi? x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}">
```

Display: <img src="http://www.forkosh.com/mathtex.cgi? x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}">

