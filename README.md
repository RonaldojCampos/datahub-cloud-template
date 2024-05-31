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

<Map
                autoZoomConfiguration={{
                    layerName: 'Points'
                }}
                center={{
                    latitude: 53.9614,
                    longitude: -1.0739
                }}
                layers={[
                    {
                        data: {
                            url: 'https://opendata.arcgis.com/datasets/9c58741995174fbcb017cf46c8a42f4b_25.geojson'
                        },
                        name: 'Points',
                        tooltip: {
                            propNames: [
                                'Location'
                            ]
                        }
                    }
                ]}
                title="Roads in York"

            />
            <Map
                autoZoomConfiguration={{
                    layerName: 'Points'
                }}
                center={{
                    latitude: 53.9614,
                    longitude: -1.0739
                }}
                layers={[
                    {
                        data: {
                            geojson: list as any
                        },
                        name: 'Points',
                        tooltip: {
                            propNames: [
                                'Location'
                            ]
                        }
                    }
                ]}
                title="Roads in York"
            />


