# Data

## Case

| Name | Type | Description
|  -   |  -   | -
| ID | UUID v7 | RFC 9562
| CaseNumber | string | `{client_code}/{year_of_import}/{sequence_number_in_this_year}`
| CreditorId | FK |
| DebtorId | FK |
| NegotiatorId | FK |
| Status | Enum |
| TotalBalance | Money |
| CreatedAt | Date |
| DPD | int | Days Past Due

