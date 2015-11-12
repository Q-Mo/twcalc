# twcalc
A simple calculator for TiddlyWiki
|editable|k
|''Name:''|twve.tcalc|
|''Description:''|A simple table calculator (spreadsheet) for ~TiddlyWiki|
|''Author:''|Vincent Yeh (qmo.wcy2@gmail.com)|
|''Source:''|* (minimized) http://twve.tiddlyspot.com/#twve.tcalc.min / http://twve.tiddlyspace.com/#twve.tcalc.min <br>* (regular) http://twve.tiddlyspot.com/#twve.tcalc / http://twve.tiddlyspace.com/#twve.tcalc|
|''Type:''|plugin|
|''Version:''|3.2.5|
|''Status:''|This plugin is still under development.<br>You are welcome to try and send feedback. :-)|
|''Date:''|2014/11/21 said goodbye to jQuery<br>2014/05/13 released 3.0.0 <br>2013/11/29 reformed <br>2013/06/02 released 1.0.0<br>2012/10/19 released 0.7.0<br>2012/09/04 started from ~TableCalculator 0.6.14|
|''License:''|MIT|
|''Core Version:''|2.6.5|
|''Needs to have:''|twve.core, twve.table|

!!Features
* Calculate numeric values in table cells.
* Cell references follow the ~OpenOffice.calc/Excel syntax.
** Column index starts from """A""" and ends at """ZZ""".
** Row index starts from 0 and has virtually no upper limit.
* ''Auto adjustment of cell references upon''
** __insertion/deletion of rows/columns__;
** __sorting with SortableGridPlugin or TableSortingPlugin__.
*** Block references such as """C4:H10""" are auto-adjusted only upon insertion/deletion of rows/columns, NOT upon sorting.
* Support several forms of decimal mark and thousands separation.
* Support user-defined functions written in Javascript.
** To define your own functions, see [[twve.tcalc--Defining your own functions]] or [[External link of that tiddler|http://twtable.tiddlyspace.com/#%5B%5BTWVE.tcalc--Defining%20your%20own%20functions%5D%5D]] for details.
** Several pre-defined functions are listed in section """Usage""" below.