---
title: Manipulate Table Elements
author: Anna Vekhina
---
# Manipulate Table Elements

## Select Table Elements
You can click a table cell to select it and [access its settings](../manipulate-report-elements/select-report-elements-and-access-their-settings.md). To select multiple cells, hold the CTRL key and click cells.

![](../../../../images/eurd-web-table-control-multiple-selected-cells.png)

Use the arrow that appears when a mouse cursor hovers over the table edges to select an entire row or column.

![](../../../../images/eurd-web-table-control-select-rows-and-columns.png)

Draw a rectangle around the table to select the whole control.

The [Properties](../../../report-designer/report-designer-tools/ui-panels/properties-panel.md) panel enables you to select the table element or the entire table and access their properties.

## Resize Table Elements
You can resize a table or its cell by dragging the rectangle drawn on its edge or corner. 

Resizing a column changes the next column's width without affecting the other columns (keeps the table dimensions intact).
	
![](../../../../images/eurd-web-table-control-column-resizing.png)

Resizing a row changes the next row's width without affecting the other rows (keeps the table dimensions intact).
	
![](../../../../images/eurd-web-table-control-row-resizing.png)

You can set the same size for multiple table columns or rows. Select the required rows or the whole table, right-click the selected area and choose **Distribute Rows Evenly**.

![](../../../../images/eurd-web-table-control-distribute-rows-evenly.png)

If the cell's content is partially visible in the resulting row, this row automatically increases its height to fit its content and also adjusts the other rows accordingly.

You can resize columns equally in a similar way by selecting the columns or the table itself and choosing **Distribute Columns Evenly** in the context menu.

![](../../../../images/eurd-web-table-control-distribute-columns-evenly.png)

## Reorder Table Cells

You can change table cells' order in the [Report Explorer](../../report-designer-tools/ui-panels/report-explorer.md). To do this, select a cell and drag it to a new position.

![](../../../../images/eurd-web-table-cells-report-explorer.png)

 During the drag-and-drop operation, the dragged and focused cells are swapped. 

 ![](../../../../images/eurd-web-table-dragged-cells-at-report-explorer.png)  

 ![](../../../../images/eurd-web-table-dragged-cells-at-report.png)  
 
 - The green light indicates where the cell can be dropped. 

    ![](../../../../images/eurd-web-table-green-light.png)  
 
 - The red light indicates where the cell can't be dropped.

    ![](../../../../images/eurd-web-table-cells-red-light.png) 


## Stretch Table Cells
You can stretch a cell to occupy several rows and columns. To stretch a cell across several columns, press DELETE or select the **Delete Cell** command in the **Action** category to remove a neighboring cell.

![](../../../../images/eurd-web-table-control-cell-column-span.png)

Use a table cell's **Row Span** property to specify the number of rows the table cell spans.

![](../../../../images/eurd-web-table-control-cell-rows-span.png)
