# Darwin Core Data Package

This is a proof of concept to test how a Darwin Core Archive could be represented as a [Data Package](https://datapackage.org/).

1. Input ([data/dwc](data/dwc)): a Darwin Core Archive (derived from [this dataset](https://ipt.inbo.be/resource?r=meetnetten-libellen-transect-occurrences)) with an Event core and Occurrence and MeasurementOrFact extensions.
2. Transform ([src/transform.qmd]([src/transform.qmd]))
3. Output ([data/raw](data/raw)): a Data Package with an `event` table (Events and Occurrences combined) and `measurementorfact` table.
