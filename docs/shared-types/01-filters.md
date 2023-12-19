# Action Types

## `IFilter`

| Attribute         | Type               | Description                                        |
| ----------------- | ------------------ | -------------------------------------------------- |
| id <Required/>    | `number \| string` | ID of filter                                       |
| label <Required/> | `string`           | Label of filter                                    |
| active            | `boolean`          | Indicates if the filter is active/displayed or not |
| component         | `ReactElement`     | The content of filter, typically an input          |
