# Директории - на архетипах

См. документацию Hugo: [Directory based archetypes](https://gohugo.io/content-management/archetypes/#directory-based-archetypes)

Hugo ^0.49 дает возможность использовать в качестве архетипов не только файлы, но и целые директории, содержащие шаблоны сразу нескольких файлов и графических объектов: .MD, HTML, .CSS, .JS. При этом графические объекты можно поместить в отдельной директории `images`. Это особо актуально для шаблонов файлов .SVG

Для создания директории по архетипу предусмотрена команда:

``` bash
hugo new --kind tmp-bundle cmir/wdev/css/css-vars
```
