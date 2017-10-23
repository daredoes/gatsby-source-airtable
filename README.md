# gatsby-source-airtable

Gatsby source plugin for pulling rows from an Airtable.

## Install

`npm install --save gatsby-source-airtable`

## Usage

```javascript
// In gatsby-config.js
plugins: [
  {
    resolve: `gatsby-source-airtable`,
    options: {
      apiKey: `YOUR_AIRTABLE_KEY`,
      baseId: `YOUR_AIRTABLE_BASE_ID`,
      tableName: `YOUR_AIRTABLE_NAME`,
      tableView: `YOUR_AIRTABLE_VIEW_NAME`
    }
  },
]
```
