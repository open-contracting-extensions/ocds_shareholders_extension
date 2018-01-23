# Shareholders Extension

The shareholder extension provides a way to describe the shareholders of the entities involved in a contracting process.

Understanding the shareholders of the bidders or successful suppliers is important for analysis of the different organizations involved in contracting processes. This is particularly important where bidders are consortia.

The extension introduces a new `Shareholder` building block and extends the `Organization` building block with a new `shareholders` field.

## Shareholders Field

The `Organization/shareholders` field is an array of `Shareholder` building blocks, describing the shareholders for the organization.

## Shareholder Building Block

The shareholder building block provides a way to:

* Link to the organization details of the shareholder
* Describe the amount of shares held by the shareholder
* Describe the voting rights associated with the shareholding

```eval_rst
.. extensiontable::
   :extension: shareholders
```


