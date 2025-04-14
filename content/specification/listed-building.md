---
{
  "specification": "listed-building",
  "name": "Listed building outline",
  "plural": "Listed building outlines",
  "specification-status": "piloting",
  "start-date": "",
  "end-date": "",
  "entry-date": "2025-02-28",
  "datasets": [
    {
      "dataset": "listed-building-outline",
      "fields": [
        {
          "field": "reference",
          "description": "the <a href=\"#reference\">reference</a> for the listed building",
          "guidance": "A reference or ID for each listed building that is:\n\n- unique within your dataset\n- permanent - it doesn't change when the dataset is updated\nIf you don't use a reference already, you will need to create one. It can be the Historic England reference used in the [register of listed buildings](https://historicengland.org.uk/listing/the-list/), or a short set of letters or numbers.\n\nExample: `LB1`\n"
        },
        {
          "field": "name",
          "description": "the name of the listed building",
          "guidance": "The name of the listed building, as listed in the [register of listed buildings](https://historicengland.org.uk/listing/the-list/).\n\nExample: `10 and 12, Lower Clapton Road E5`\n"
        },
        {
          "field": "listed-building",
          "description": "the Historic England identifier for the listed building, for example <a href=\"https://historicengland.org.uk/listing/the-list/list-entry/1024710\" class=\"govuk-link\">1024710</a>",
          "guidance": "The Historic England listed building reference for the listed building. This is recorded in the [register of listed buildings](https://historicengland.org.uk/listing/the-list/) as \"List Entry Number\".\n\nExample: `1480524`\n"
        },
        {
          "field": "geometry",
          "description": "the boundary of the area related to the listed building. Use curtilage (according to the <a href=\"https://historicengland.org.uk/images-books/publications/listed-buildings-and-curtilage-advice-note-10/heag125-listed-buildings-and-curtilage/\" class=\"govuk-link\">Historic England advice note</a>) if it\u2019s available.",
          "guidance": "The outline of the listed building as a single polygon or multipolygon value. All points in the polygon must be in the WGS84 coordinate reference system.\n\nIf you\u2019re providing geometry in a CSV, geometry should be in well-known text (WKT).\n\nExample: `MULTIPOLYGON (((1.188829 51.23478,1.188376 51.234909,1.188381 51.234917,1.187912 51.235022...`\n\nIf you\u2019re providing geometry in a GeoJSON, GML or Geopackage, use the associated geometry format.\n"
        },
        {
          "field": "notes",
          "description": "optional notes",
          "guidance": "Optional text on how this data was made or produced, or how it can be interpreted.\n"
        },
        {
          "field": "organisation",
          "description": "the organisation responsible for the listed building"
        },
        {
          "field": "entry-date",
          "description": "the date this information has been entered as a record",
          "guidance": "The date the entity was last updated.\n\nIf the entity has never been updated, enter the same date as start-date.\n\nWrite in `YYYY-MM-DD` format.\n\nExample: `2022-12-20`\n"
        },
        {
          "field": "start-date",
          "description": "the date the validity of the record starts",
          "guidance": "The date from which the building was listed, written in `YYYY-MM-DD` format.\n\nExample: `1984-03-28`\n"
        },
        {
          "field": "end-date",
          "description": "the date the validity of the record ends",
          "guidance": "Where the building is no longer listed, this should be the date that it was [no longer in effect](https://standards.planning-data.dev/principles/#we-shouldn%E2%80%99t-delete-entries-in-a-register), written in YYYY-MM-DD format. If it's still listed, leave the cell blank.\n\nExample: `1999-01-20`\n"
        }
      ]
    }
  ]
}---
