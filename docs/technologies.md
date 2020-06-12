- Electron
- [NativeScript](https://nativescript.org/) (?)
- no framework
- supported plattforms:
  - Linux
  - Windows
  - Android

```
notebook/ <br>
	pageId/ <br>
		assets/ <br>
			img/ <br>
			files/ <br>
		page.xml <br>
		sketch.svg <br>
```    

__example/1/page.xml__:
```
<xml>
<head>
  <id>1</id>
  <title></title>
  <authors></authors>
  <currentZIndex></currentZIndex>
  <background src="preset:lines"></background>
  <pageLayout>A4 Landscape/Letter Portrait/infinite</pageLayout>
  ...
</head>
<body>
  <image x="" y="" src="image.jpg" z-index="1">
  <text x="" y="" content="# Markdown" z-index="2">
  <form x="" y="" type="circle" z-index="3">
</body>
```
