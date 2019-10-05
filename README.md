
# vanillaDataTables

---

A lightweight, extendable table plugin. 

Forked from https://github.com/Mobius1/Vanilla-DataTables:



### Quick Start

Then just initialise the plugin by either passing a reference to the table or a CSS3 selector string as the first parameter:

```javascript
var myTable = document.querySelector("#myTable");
var dataTable = new DataTable(myTable);

// or

var dataTable = new DataTable("#myTable");

```

You can also pass the options object as the second parameter:

```javascript
var dataTable = new DataTable("#myTable", {
	searchable: false,
	fixedHeight: true,
	...
});
```

Old example: https://codepen.io/Mobius1/pen/VadmKb

Don't forget to check the [old wiki](https://github.com/Mobius1/Vanilla-DataTables/wiki).

---


### Features

* Sortable columns
* Pagination
* Searchable
* Customisable layout
* Customisable labels
* Customise column rendering
* Export to common formats like `csv`, `txt` `json`, and `sql`
* Control column visibility
* Reorder or swap columns



[Old Documentation](https://github.com/Mobius1/Vanilla-DataTables/wiki) 

---

### Old Demos

* [Default Setup](https://codepen.io/Mobius1/pen/VadmKb)
* [Remote Data](https://codepen.io/Mobius1/pen/XaRepW?editors=0010)
* [Datetime Strings](https://codepen.io/Mobius1/pen/jwXPKN?editors=0010)
* [Column Manipulation](https://codepen.io/Mobius1/pen/WEmGwJ?editors=0010)
* [Editor Plugin](https://s.codepen.io/Mobius1/debug/rGpMMY)
* [Stress Test](https://s.codepen.io/Mobius1/pen/qjLaKd)
* [Programmatic Access](https://s.codepen.io/Mobius1/pen/rwGyJa)

