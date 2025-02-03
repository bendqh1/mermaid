From my experience, a General Communication Language (GCL) can be either:

1. Primarily Consonant
1. Primarily vowelant
1. Mixed with a tendency to consonant
1. Mixed with a tendency to vowelant

English and Russian are of type 1, while Thai and Vietnamese of type 4 and therefore type 1 speakers could learn each other's languages fast, but will have a hard time learning type 4 languages and vice versa.

But

Speakers of type 3 and type 4 could learn each other's language fast because both types are mixed.

```mermaid
flowchart TD

  subgraph A [Speaking GCLs]
    A1[Primarily Consonant GCL]
    A2[Primarily Vowelant GCL]
    A3[Mixed, Tendency to Consonant GCL]
    A4[Mixed, Tendency to Vowelant GCL]
  end

  subgraph B [Learning GCLs]
    B1[Primarily Consonant GCL]
    B2[Primarily Vowelant GCL]
    B3[Mixed, Tendency to Consonant GCL]
    B4[Mixed, Tendency to Vowelant GCL]
  end

  subgraph C [Ease of Learning]
    C1[Generally Easy]
    C2[Generally Hard]
  end

  A1 & B1 --> C1
  A2 & B2 --> C1

  A1 & B2 --> C2
  B1 & A2 --> C2

  A3 & B3 --> C1
  A4 & B4 --> C1

  B3 & B4 --> C1

  A3 & B4 --> XX1[Special case]
```
