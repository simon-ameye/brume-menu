# brume-menu

Here is the menu of our restaurant.

Github pages hosts menu.html website : https://simon-ameye.github.io/brume-menu/menu.html

Google sites hosts restaurant website : https://www.brumecoffeenice.fr/

Google sites menu page embeddes Github page

Github hosts menu data as ```tsv``` : https://raw.githubusercontent.com/simon-ameye/brume-menu/master/menu.tsv

menu.html formats data to HTML using JavaScript

## Data
Data is fetched using : ```fetch()```

## Processing
JavaScript function ```process(input)``` processes table data and returns HTML format string.

English translation is eventually available for each word.

```process``` tries to parse translation if ```var language = 1``` thanks to ```onclick``` event.

```mermaid
	graph TD
		A[Github pages]
		B[Google sites]
		C[Github raw]
		A-->|embedded| B
		C -->|menu data| A
```