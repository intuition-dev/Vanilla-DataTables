# Vanilla-DataTables

---

A lightweight, extendable, dependency-free javascript HTML table plugin. Similar to jQuery DataTables, but without the dependencies.


Example: https://codepen.io/Mobius1/pen/VadmKb

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

* Extentable with custom plugins [See the wiki](https://github.com/Mobius1/Vanilla-DataTables/wiki/Plugins) (v1.6.0 and above)


[Documentation](https://github.com/Mobius1/Vanilla-DataTables/wiki) | [Latest Version](https://github.com/Mobius1/Vanilla-DataTables/releases/tag/1.6.16)

---

### Demos

* [Default Setup](https://codepen.io/Mobius1/pen/VadmKb)
* [Remote Data](https://codepen.io/Mobius1/pen/XaRepW?editors=0010)
* [Datetime Strings](https://codepen.io/Mobius1/pen/jwXPKN?editors=0010)
* [Column Manipulation](https://codepen.io/Mobius1/pen/WEmGwJ?editors=0010)
* [Editor Plugin](https://s.codepen.io/Mobius1/debug/rGpMMY)
* [Stress Test](https://s.codepen.io/Mobius1/pen/qjLaKd)
* [Programmatic Access](https://s.codepen.io/Mobius1/pen/rwGyJa)

---

### Quick Start

Then just initialise the plugin by either passing a reference to the table or a CSS3 selector string as the first parameter:

```javascript
var myTable = document.querySelector("#myTable");
var dataTable = new DataTable(myTable);

// or

var dataTable = new DataTable("#myTable");

```

You can also pass the options object as the second paramater:

```javascript
var dataTable = new DataTable("#myTable", {
	searchable: false,
	fixedHeight: true,
	...
});
```

Don't forget to check the [wiki](https://github.com/Mobius1/Vanilla-DataTables/wiki) out for further help.

---

Based on https://github.com/Mobius1/Vanilla-DataTables
