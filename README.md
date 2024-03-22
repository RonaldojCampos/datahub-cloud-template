---
datapackage:
  title: Dataset Template
  description: A template for a dataset to publish on DataHub. Uses the Data Package metadata.
  licenses:
  - path: http://opendatacommons.org/licenses/pddl/
    title: Open Data Commons Public Domain Dedication and License v1.0
  resources:
  - path: corporate-investment-in-artificial-intelligence-by-type.csv
    title: Annual global corporate investment in IA
    name: corporate-investment-in-artificial-intelligence-by-type
    format: csv
    schema:
      fields:
      - name: Entity
        type: Entity
      - name: Year
        type: Year
      - name: Total corporate investment - inflation adjusted
        type: Total corporate investment - inflation adjusted
---

Here's some text.

You can add as much text as you like.

The data files will be automatically displayed here.

We can add a chart:

<LineChart
  data="./data.csv"
  title="C02 per decade"
  xAxis="year"
  yAxis="co2"
/>
