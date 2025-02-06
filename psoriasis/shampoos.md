## Markdown

Applying color in Mermaid in year 2025 can be cumbersome so here is a way in a Markdown:

| Shampoo Name                  | Main Use(s)            |
|-------------------------------|------------------------|
| <span style="color:green">Zinc Pyrithione Shampoo</span>    | Seborrhea              |
| <span style="color:green">Ketoconazole Shampoo</span>       | Seborrhea              |
| <span style="color:blue">Selenium Sulfide Shampoo</span>    | Seborrhea, Psoriasis   |
| <span style="color:blue">Salicylic Acid Shampoo</span>      | Seborrhea, Psoriasis   |
| <span style="color:red">Coal Tar Shampoo</span>             | Psoriasis              |
| <span style="color:red">Coal Tar Solution Shampoo</span>    | Psoriasis              |
## Mermaid

```mermaid
graph TD
    A[Zinc Pyrithione Shampoo] --> B[Seborrhea]
    C[Ketoconazole Shampoo] --> B[Seborrhea]
    D[Selenium Sulfide Shampoo] --> B[Seborrhea]
    D[Selenium Sulfide Shampoo] --> C[Psoriasis]
    E[Salicylic Acid Shampoo] --> B[Seborrhea]
    E[Salicylic Acid Shampoo] --> C[Psoriasis]
    F[Coal Tar Shampoo] --> C[Psoriasis]
    G[Coal Tar Solution Shampoo] --> C[Psoriasis]
```
