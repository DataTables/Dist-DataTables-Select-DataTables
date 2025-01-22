# Select for DataTables with styling for [DataTables](https://datatables.net/)

This is the distribution package for the [Select extension](https://datatables.net/extensions/select) for [DataTables](https://datatables.net/) with styling for [DataTables](https://datatables.net/).

Select provides table item selection capabilities - rows, columns and cells can be selected individually or collectively. Complex selection operations such as operating system style selection (ctrl/cmd and shift click) for multiple rows can be enabled with a single option for a DataTable.


## Installation

### Browser

To use DataTables with a simple `<script>` tag, rather than using this package, it is recommended that you use the [DataTables download builder](//datatables.net/download) which can create CDN or locally hosted packages for you, will all dependencies satisfied.

### npm

For installation via npm, yarn and other similar package managers, install this package with your package manager - e.g.:

```
npm install datatables.net-dt
npm install datatables.net-select-dt
```

Then, to load and initialise the software in your code use:

```
import DataTable from 'datatables.net-dt';
import 'datatables.net-select-dt'

new DataTable('#myTable', {
    // initalisation options
});
```


## Documentation

Full documentation and examples for Select can be found [on the DataTables website](https://datatables.net/extensions/select).


## Bug / Support

Support for DataTables is available through the [DataTables forums](//datatables.net/forums) and [commercial support options](//datatables.net/support) are available.

### Contributing

If you are thinking of contributing code to DataTables, first of all, thank you! All fixes, patches and enhancements to DataTables are very warmly welcomed. This repository is a distribution repo, so patches and issues sent to this repo will not be accepted. Instead, please direct pull requests to the [DataTables/Select](http://github.com/DataTables/Select). For issues / bugs, please direct your questions to the [DataTables forums](//datatables.net/forums).


## License

This software is released under the [MIT license](//datatables.net/license). You are free to use, modify and distribute this software, but all copyright information must remain.

