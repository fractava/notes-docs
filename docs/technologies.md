- Electron
- [NativeScript](https://nativescript.org/)
- Vue.js
- Vuex
- supported plattforms:
  - Linux
  - Windows
  - Android

```
notebook/
	pageId/
		assets/
			img/
			files/
		page.json
```    

__example/1/page.json__:
```
{
	title: "Test",
	authors: ["Test", "Test 2"],
	background: "preset:lines",
	pageLayout: {
		size: "A4", /* or "letter" or "infinite" */,
		rotation: "landscape" /* or "portrait"; false if size == "infinite",
	},
	scrollOffsetX: 0,
	scrollOffsetY: 0,
	scale: 1,
	objects: {
		sketches: [
			{
				coordinates: [
					{
						x: 10,
						y: 15,
						width: 1,34,
					},
					...
				],
				color: "#000000",
			},
		],
		textBoxes: [
			{
				position: {
					x: 50,
					y: 50,
					width: 500,
					height: 600,
				},
				content: "This is a Test",
			},
		],
		forms: [
			{
				position: {
					x: 100,
					y: 150,
					width: 100,
					height: 100,
				},
				type: "circle", /* or sqare ... */
			},
		],
		images: [
			{
				position: {
					x: 200,
					y: 150,
					width: 160,
					height: 90,
				},
				src: "image.png", /* relative to example/1/assets/img/ */
			},
		],
		files: [
			{
				position: {
					x: 200,
					y: 500,
				},
				src: "test.zip", /* relative to example/1/assets/files/ */
			},
		],
	},
}
		
```
