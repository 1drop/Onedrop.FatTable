# Onedrop.FatTable

This package provides the possibility to maintain HTML tables in Neos with real content (not Aloha).
The NodeType ``Onedrop.FatTable:Table`` is added and can be placed anywhere.

It's currently optimized to have table, row and cell properties and functionality that maps Bootstrap3.

## Compatibility

| Neos Version     | Onedrop.FatTable Version  |
|------------------|---------------------------|
| Neos 3.x         | 2.x                       |
| Neos 2.3 LTS     | 1.x                       |

## How-To:

### Install:

Use the command ``composer require onedrop/fattable`` to add this package as a requirement to your Neos project.
(Or: Download the zip and unpack it to ``Packages/Application/Onedrop.FatTable``)

### Usage:

Just place the new table NodeType anywhere and add TableRows inside the table and TableCells inside the rows.
Inside the TableCells you can use any content you like.

## Future improvements:

- Provide an easy way to bootstrap a table (row, column config) and to quickly add and remove rows and cols
- Make TableRow and TableCell nodeType only visible inside the expected ContentCollection (currently global visible)