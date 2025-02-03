From my experience, a General Communication Language (GCL) can be either:

1. Mixed but primarily consonant
1. Mixed but primarily vowelant
1. Mixed but primarily consonant-vowel conjoined

English and Russian are of type 1, while Thai and Vietnamese of type 3 and therefore type 1 speakers could learn each other's languages fast, but will have a hard time learning type 3 languages and vice versa.

## Mermaid

```mermaid
flowchart TD

  subgraph A [Speaking GCLs]
    A1[Primarily Consonant GCL]
    A2[Primarily Vowelant GCL]
    A3[Mixed but primarily consonant-vowel conjoined]
  end

  subgraph B [Learning GCLs]
    B1[Primarily Consonant GCL]
    B2[Primarily Vowelant GCL]
    B3[Mixed but primarily consonant-vowel conjoined]
  end

  subgraph C [Ease of Learning]
    C1[Generally Easy]
    C2[Generally Hard]
  end

  A1 & B1 --> C1
  A2 & B2 --> C1
  A3 & B3  --> C1

  A1 & B2 --> C2
  A1 & B3 --> C2

```
