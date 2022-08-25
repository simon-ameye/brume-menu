# brume-menu

Here is the menu of our coffeshop.

Visit us in Nice : https://goo.gl/maps/NQpQ787KMkiAHNmv6 :)

## Hosting

* Github hosts menu data as ```tsv``` table : https://raw.githubusercontent.com/simon-ameye/brume-menu/master/menu.tsv
* menu.html formats table data to HTML using JavaScript
* menu.html is hosted by Github pages : https://simon-ameye.github.io/brume-menu/menu.html
* Google sites hosts restaurant website : accessible via https://www.brumecoffeenice.fr/
* Google sites menu page embed Github page as Embed Website Widget 

## Data
Data is fetched using : ```fetch().then()``` synchronously

## Processing
JavaScript function ```process(input)``` processes table data and returns HTML format string.

English translation is eventually available for each word.

```process``` tries to parse translation if ```var language = 1``` thanks to ```onclick``` event.

```mermaid
	graph TD
		A[Github pages]
		B[Google sites]
		C[Github raw]
		A-->|embedded website| B
		C -->|menu tsv table| A
```