# ES6 jade static blog website generator

參考wintersmith

## 資料結構

```
.
├── build
├── contents
│   ├── articles
│   └── scss
├── gen.js
├── package.json
├── README.md
└── templates
    ├── Html.jade
    └── Index.jade
```

`build`: 編譯好的html. css檔案放這
`contents`: 來源檔案, markdown file, scss file
`templates`: jade templates
`gen.js`用來編譯所有來源檔案到build資料夾

## build成品

build的成品有: 
`index.html`: blog標題副標題, 作者介紹, 文章列表
`posts`: 包含所有markdown編譯過來的文章html
