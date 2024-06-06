# Persian fonts
The most popular Persian fonts are included in this package.
- IranNastaliq
- Lotus
- Morvarid
- Nazanin
- Titr
- Traffic
- Yekan
- Zar
- Besmellah
- ShapedBesmellah

# Installation
## CDN
Import library from the ESM.SH CDN for fast and easy setup:
### In web browser
Simply include persian-fonts in your html `<header>` tag.
```html
<link rel="stylesheet" href="//esm.sh/gh/rahatool/persian-fonts/main.css" />
```
## NPM registry
Use the package manager npm to install persian-fonts.
```shell
$ npm install github:rahatool/persian-fonts
```
Fonts will be copied to `node_modules/@raha.group/persian-fonts` directory.

# Usage
![Sample of خوش‌نویسی](https://esm.sh/gh/rahatool/persian-fonts/sample.png)
```html
<html>
	<head>
		<link rel="stylesheet" href="//esm.sh/gh/rahatool/persian-fonts/main.css" />
		<style>
			.sample {
				font-family: 'IranNastaliq';
				font-size: 2rem;
			}
		</style>
	</head>
	<body>
		<p class="sample">
شاه‌نشینِ چشمِ من، تکیه‌گهِ خیـالِ توست<br />
جایِ دعاست شاهِ من، بی تو مباد جایِ تو
		</p>
	</body>
</html>
```