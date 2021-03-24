# Table

## Cell and Header

Using | to separate different cell, use - to separate header and other rows:

name | age
---- | ---
George | 30
Mike | 20

In order to aesthetic, you can use multiple Spaces to align cells in each row, and use | to mark each cell's boundary, although its display effect is exactly the same with the above:

| name   | age |
| ------ | --- |
| George | 30  |
| Mike   | 20  |


## Alignment

:---, ---:, and :--: mean bing aligned to the left, right, and center, respectively. Content in cells is left aligned by default, and content in header cells is always centered.

| left      |      center      |      right |
| :---      |       :--:       |       ---: |
| aa        |      bb          |         cc |

## Insert Other Content

You can insert other Markdown inline tags into a table:
 
|     name     | age |             blog                |
| ------------ | --- | ------------------------------- |
| _George_     | 12  | [George](http://george.com)     |
| __Mike__     | 32  | [Mike](http://mike.me)          |