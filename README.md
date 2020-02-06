# CheckBox-in-DataGridView
Delete multiple row from a DataGridView using CheckBox

The DataGridView control provides a customizable table for displaying data. The DataGridView class allows customization of cells, rows, columns, and borders through the use of properties such as DefaultCellStyle, ColumnHeadersDefaultCellStyle, CellBorderStyle, and GridColor. For more information, see Basic Formatting and Styling in the Windows Forms DataGridView Control.

You can use a DataGridView control to display data with or without an underlying data source. Without specifying a data source, you can create columns and rows that contain data and add them directly to the DataGridView using the Rows and Columns properties. You can also use the Rows collection to access DataGridViewRow objects and the DataGridViewRow.Cells property to read or write cell values directly. The Item[String, Int32] indexer also provides direct access to cells.
As an alternative to populating the control manually, you can set the DataSource and DataMember properties to bind the DataGridView to a data source and automatically populate it with data. For more information, see Displaying Data in the Windows Forms DataGridView Control.

When working with very large amounts of data, you can set the VirtualMode property to true to display a subset of the available data. Virtual mode requires the implementation of a data cache from which the DataGridView control is populated. For more information, see Data Display Modes in the Windows Forms DataGridView Control.

For additional information about the features available in the DataGridView control, see DataGridView Control. The following table provides direct links to common tasks.

CheckBoxes allow the user to make multiple selections from a number of options. CheckBox to give the user an option, such as true/false or yes/no. You can click a check box to select it and click it again to deselect it. The CheckBox control can display an image or text or both.
