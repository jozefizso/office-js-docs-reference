| Class | Fields | Description |
|:---|:---|:---|
|[CustomXmlPart](/javascript/api/excel/excel.customxmlpart)|[delete()](/javascript/api/excel/excel.customxmlpart#delete--)|Deletes the custom XML part.|
||[getXml()](/javascript/api/excel/excel.customxmlpart#getxml--)|Gets the custom XML part's full XML content.|
||[id](/javascript/api/excel/excel.customxmlpart#id)|The custom XML part's ID.|
||[namespaceUri](/javascript/api/excel/excel.customxmlpart#namespaceuri)|The custom XML part's namespace URI.|
||[setXml(xml: string)](/javascript/api/excel/excel.customxmlpart#setxml-xml-)|Sets the custom XML part's full XML content.|
|[CustomXmlPartCollection](/javascript/api/excel/excel.customxmlpartcollection)|[add(xml: string)](/javascript/api/excel/excel.customxmlpartcollection#add-xml-)|Adds a new custom XML part to the workbook.|
||[getByNamespace(namespaceUri: string)](/javascript/api/excel/excel.customxmlpartcollection#getbynamespace-namespaceuri-)|Gets a new scoped collection of custom XML parts whose namespaces match the given namespace.|
||[getCount()](/javascript/api/excel/excel.customxmlpartcollection#getcount--)|Gets the number of custom XML parts in the collection.|
||[getItem(id: string)](/javascript/api/excel/excel.customxmlpartcollection#getitem-id-)|Gets a custom XML part based on its ID.|
||[getItemOrNullObject(id: string)](/javascript/api/excel/excel.customxmlpartcollection#getitemornullobject-id-)|Gets a custom XML part based on its ID.|
||[items](/javascript/api/excel/excel.customxmlpartcollection#items)|Gets the loaded child items in this collection.|
|[CustomXmlPartScopedCollection](/javascript/api/excel/excel.customxmlpartscopedcollection)|[getCount()](/javascript/api/excel/excel.customxmlpartscopedcollection#getcount--)|Gets the number of CustomXML parts in this collection.|
||[getItem(id: string)](/javascript/api/excel/excel.customxmlpartscopedcollection#getitem-id-)|Gets a custom XML part based on its ID.|
||[getItemOrNullObject(id: string)](/javascript/api/excel/excel.customxmlpartscopedcollection#getitemornullobject-id-)|Gets a custom XML part based on its ID.|
||[getOnlyItem()](/javascript/api/excel/excel.customxmlpartscopedcollection#getonlyitem--)|If the collection contains exactly one item, this method returns it.|
||[getOnlyItemOrNullObject()](/javascript/api/excel/excel.customxmlpartscopedcollection#getonlyitemornullobject--)|If the collection contains exactly one item, this method returns it.|
||[items](/javascript/api/excel/excel.customxmlpartscopedcollection#items)|Gets the loaded child items in this collection.|
|[PivotTable](/javascript/api/excel/excel.pivottable)|[id](/javascript/api/excel/excel.pivottable#id)|ID of the PivotTable.|
|[RequestContext](/javascript/api/excel/excel.requestcontext)|[runtime](/javascript/api/excel/excel.requestcontext#runtime)|[Api set: ExcelApi 1.5]|
|[Runtime](/javascript/api/excel/excel.runtime)||[Workbook](/javascript/api/excel/excel.workbook)|[customXmlParts](/javascript/api/excel/excel.workbook#customxmlparts)|Represents the collection of custom XML parts contained by this workbook.|
|[Worksheet](/javascript/api/excel/excel.worksheet)|[getNext(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheet#getnext-visibleonly-)|Gets the worksheet that follows this one.|
||[getNextOrNullObject(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheet#getnextornullobject-visibleonly-)|Gets the worksheet that follows this one.|
||[getPrevious(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheet#getprevious-visibleonly-)|Gets the worksheet that precedes this one.|
||[getPreviousOrNullObject(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheet#getpreviousornullobject-visibleonly-)|Gets the worksheet that precedes this one.|
|[WorksheetCollection](/javascript/api/excel/excel.worksheetcollection)|[getFirst(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheetcollection#getfirst-visibleonly-)|Gets the first worksheet in the collection.|
||[getLast(visibleOnly?: boolean)](/javascript/api/excel/excel.worksheetcollection#getlast-visibleonly-)|Gets the last worksheet in the collection.|
