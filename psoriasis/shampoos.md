## Markdown

Applying color in Mermaid in year 2025 can be cumbersome so here is a way in a Markdown:

| Shampoo type                    | Purpose                         |
|---------------------------------|---------------------------------|
| Zinc pyrithione                 | Mainly for Seborrhea            |
| Azoles                          | Mainly for Seborrhea            |
| Piroctone olamine               | Mainly for Seborrhea            |
| Ciclopirox                      | Mainly for Seborrhea            |
|                                 |                                 |
| Coal tar                        | Mainly for Psoriasis            |
| Coal tar solution               | Mainly for Psoriasis            |
| Clobetasol                      | Mainly for Psoriasis            |
|                                 |                                 |
| Selenium Sulfide                | Mainly for both                 |
| Salicylic acid                  | Mainly for both                 |
| Tea Tree Oil                    | Mainly for both                 |

## Mermaid

```mermaid
graph TD

A1[Zinc Pyrithione Shampoo]
A2[Ketoconazole Shampoo]
A3[Piroctone olamine shampoo]
A4[Ciclopirox shampoo]

B1[Coal Tar Shampoo]
B2[Coal Tar Solution Shampoo]
B3[Clobetasol shampoo]

C1[Selenium Sulfide shampoo]
C2[Salicylic acid shampoo]
C3[Tea Tree Oil shampoo]

XX1[Seborrhea]
XX2[Psoriasis]
XX3[Both]

A1 & A2 & A3 & A4 --> XX1
B1 & B2 & B3 --> XX2
C1 & C2 & C3 --> XX3
```
