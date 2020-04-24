# Tender classification 

Adds an array of Classification objects to Tender in order to categorize the contracting process.

## Guidance

## Legal context

In the European Union, this extension's fields correspond to [eForms BG-261 (Classification)](https://github.com/eForms/eForms). See [OCDS for the European Union](http://standard.open-contracting.org/profiles/eu/master/en/) for the correspondences to Tenders Electronic Daily (TED).

## Example


```json
{
  "tender": {
    "classification": {
      "description": "Advertising management services",
      "id": "79341200-8",
      "scheme": "CPV"
    },
    "additionalClassifications": [
      {
        "description": "Advertising campaign services",
        "id": "79341400-0",
        "scheme": "CPV"
      },
      {
        "description": "Customer services",
        "id": "79342300-6",
        "scheme": "CPV"
      }
    ]
  }
}
```

## Issues

Report issues for this extension in the [ocds-extensions repository](https://github.com/open-contracting/ocds-extensions/issues), putting the extension's name in the issue's title.

## Changelog

This extension was originally discussed as part of the [OCDS for EU profile](https://github.com/open-contracting-extensions/european-union/issues) and in [pull requests](https://github.com/open-contracting-extensions/ocds_tenderClassification_extension/pulls?q=is%3Apr+is%3Aclosed).
