# autoViewerIframe Library Javascript

<h1 align="center">
  <img src="https://github.com/Huemul/trae/blob/master/assets/logo.png" alt="trae">
</h1>

Javascript library that Allow detecting when a url is entered in an entry, and create an iframe with this transformed url, it is extracted and detected with a regular explanation and the url is constructed with a constant

## Install 
```bash
<script src="src/autoViewerIframe.js" type="text/javascript"></script>
```

## Use 
```bash
$autoViewerYoutube.bind(document.getElementById("input"));
```

## Configurations  
```bash
options:{
    regexs:[
        {
          condition: /http(?:s?):\/\/(?:www\.)?youtu(?:be\.com\/watch\?v=|\.be\/)([\w\-\_]*)(&(amp;)?‌[\w\?‌=]*)?/,
          embed:"https://www.youtube.com/embed/"
        }
]

// edit in file "autoViewerIframe.js"

```

## Authors 
```bash
https://github.com/jpanqueva
https://github.com/archarry86
```

## License

[MIT License](https://github.com/Huemul/trae/blob/master/LICENSE).



