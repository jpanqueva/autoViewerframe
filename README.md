# autoViewerIframe Library Javascript

<h1 align="center">
  <img src="https://github.com/jpanqueva/autoViewerframe/blob/master/scren.png?raw=true" alt="Example Grafic autoViewerIframe" 
   style="width: 100%;
    max-width: 410px;" />
</h1>

Javascript library that Allow detecting when a url is entered in an entry, and create an iframe with this transformed url, it is extracted and detected with a regular explanation and the url is constructed with a constant

## Install 
```bash
<script src="src/autoViewerIframe.js" type="text/javascript"></script>
```

## Use HTML
```bash

<input id="input_example" 
			type="text" onload="$autoViewerYoutube.bind(this);" 
			data-container-id="container_view_id" 
			class="form-control" 
			placeholder="Paste Your link youtube here..." />

<div id="container_view_id"></div>

```

The "data-container-id" is the container id of iframe

## Use JavaScript
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



