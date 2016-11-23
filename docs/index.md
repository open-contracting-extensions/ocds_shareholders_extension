# Shareholder Extension

The shareholder extension provides a way to describe the shareholders of the entities involved in a contracting process.

Understanding the shareholders of the bidders or successful suppliers is important for analysis of the different organizations involved in contracting processes. This is particularly important where bidders are consortia.

The extension introduces a new ```shareholder``` building block and extends the ```organization``` building block with a new ```shareholders``` field.

## Shareholder Building Block

Multiple shareholder building blocks are used to:

* Link to the organization details of the shareholder
* Describe the amount of shares held by the shareholder
* Describe the voting rights assoicated with the shareholding

```eval_rst
.. csv-table::
   :header-rows: 1
   :widths: 20 65 15
   :file: ../docs/field_definitions/shareholder.csv
```

## Shareholders Field

The ```organization/shareholders``` field is an array of ```shareholder``` building blocks, describing the shareholders for the organization. 

```eval_rst
.. csv-table::
   :header-rows: 1
   :widths: 20 65 15
   :file: ../docs/field_definitions/shareholders.csv
```

