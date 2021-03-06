# Changelog

## [Unreleased]

## 18.1.55 (2020-06-02)

### TreeGrid

#### Bug Fixes

- `#278266` - Edit type `dropdownedit` is working properly in cell edit mode when enter key is pressed.

## 18.1.54 (2020-05-26)

### TreeGrid

#### New Features

- `#152599` - Provided support for toggling selection by adding `enableToggle` API in selection Settings

#### Bug Fixes

- `#277361` - Auto generated columns work fine when two treegrids are rendered on the same page.

## 18.1.52 (2020-05-13)

### TreeGrid

#### New Features

- Provided support for Editing with Frozen Columns.

## 18.1.48 (2020-05-05)

### TreeGrid

#### Bug Fixes

- `F153495` - Sorting after editing is working fine with cell edit mode.
- `#273309` - Editing the zeroth level added record works fine in Batch mode.

- `F153495` - Sorting after editing is working fine with cell edit mode.

## 18.1.45 (2020-04-21)

### TreeGrid

#### Bug Fixes

- `#272026` - `updateRow` method works fine for updating treegrid data source.
- `#272616` - In editing, add operation works fine in empty data source.
- `#272409`- Expand Collapse works fine when number of frozen columns is less than `treeColumnIndex`.

## 18.1.43 (2020-04-07)

### TreeGrid

#### Bug Fixes

- `#266963`- Drag and drop works fine in unordered list of data.
- `#F151795` - Localization support works fine in Add row, Above, Below Context Menu Items.
- `#F151795`- In Drag and drop, while dropping at first row, its border color is changed properly.
- `#267541`- ExpandAll works fine with Virtualization feature.

- `#266963`- Drag and drop works fine in unordered list of data.
- `#F151795` - Localization support works fine in Add row, Above, Below Context Menu Items.
- `#F151795`- In Drag and drop, while dropping at first row, its border color is changed properly.
- `#268348`- Index value properly updated for drag and drop data operation.

## 18.1.36-beta (2020-03-19)

### TreeGrid

#### New Features

- Provides support to copy the selected rows or cells data into clipboard.
- Provides support to load large amount of data on-demand in Virtual Scrolling.
- Provides batch editing support for bulk add, edit and delete operations.

#### Bug Fixes

- `#262583`- Dragging a row works fine, when Tree Grid is in Edit state.

## 17.4.39 (2019-12-17)

### TreeGrid

#### New Features

- AutoFill support has been provided that allows users to copy the data of selected cells and paste it to another cells by dragging.

#### Breaking Changes

- Default value of column's `disableHtmlEncode` is set to true, so the HTML tags can be displayed in the Grid header and content by default. To display it as html content `disableHtmlEncode` need to be set as false.

#### Bug Fixes

- `#148913` - Expand icon displays properly for the nested records in Custom Data Binding.

## 17.2.48-beta (2019-08-28)

### TreeGrid

#### New Features

- Checkbox selection support has been provided that allows users to select rows using checkbox.
- Checkbox Column support has been provided that allows users to check rows using checkbox in treegrid column.

#### Bug Fixes

- Change detection for properties `dataSource` and `query` were handled for remote data.
- Edited records can be searched/filtered.
- Inner level records will be collapsed/expanded after filtering/searching actions.

## 17.1.1-beta (2019-01-29)

### TreeGrid

#### Bug Fixes

- `Query` maintenance support provided for `refresh` method after expanding any child rows.
- Property change support for `height` property has been provided.
- Expand icon is prevented from displaying for the root/zeroth level record which has `hasChildMapping` field as false.
- Child records of third level or its successor displays properly based on their hierarchy relation in self reference data binding.

- Expand icon is prevented from displaying for the root/zeroth level record which has `hasChildMapping` field as false.

#### New Features

- `Excel-Like Filtering` support is provided that allows users to create complex filter criteria for a column by allowing users to select possible filter values from a checkbox list. The advanced filter can be used to build complex filter criteria.

## 16.4.45 (2019-01-02)

### TreeGrid

#### Bug Fixes

- Added events for the column menu feature and added `columnMenuItems` API to modify the column menu items in column menu.
- Added `sortComparer` API to perform custom sorting in TreeGrid.

## 16.4.44 (2018-12-24)

### TreeGrid

#### Bug Fixes

- Expanding and Collapsing records is working fine when `pageSizeMode` is set as `All`.
- `expandAtLevel`, `collapseAtLevel`, `expandAll` and `collapseAll` methods are working fine when `pageSizeMode` is set as `All`.


- `actionBegin`, `actionComplete` and `actionFailure` events are triggered properly.
- Additional parameters that are added using the `query` property of TreeGrid are passed to the server side when a parent record is expanded.


## 18.1.53 (2020-05-19)

### TreeGrid

#### Bug Fixes

- `#275113` - Destroying the Tree Grid component in **ngOnDestroy** method works fine.

