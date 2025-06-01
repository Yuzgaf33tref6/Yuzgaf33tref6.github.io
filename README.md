# Yuzgaf33tref6.github.io
---
![Static Badge](https://img.shields.io/badge/My%20Blog-8A2BE2?style=for-the-badge)
---
![Node.js](https://img.shields.io/badge/Node.js->=16,ok=22-red)
![hexo](https://img.shields.io/badge/hexo-/-blue)
![fluid](https://img.shields.io/badge/fluid-v%1.9.8-green)
[![GPLv3 License](https://img.shields.io/badge/license-GPLv3-red.svg)](LICENSE)
# 在这里提一个天坑！！！！！！！
如果不是用jekyll创建的，tmd得自己创建一个.nojekyll才能让死脑子actions不自动费劲脑力构建jekyll主题
---
### hexo的官方文档写得非常抽象，不是很建议参考
我个人实现hexo主页靠actions，老办法直接push是没法使用的

```markdown
- 1 需要.nojekyll标记不是jekyll否则github会拼尽全力解析；
- 2 github默认的pages需要在根目录或者/doc存在index.html或者index.md） /n
具体实现参考了官方文档的逻辑
```

中途也体验了各种掉头发的爽快解决问题体验，找时间总结一下。
