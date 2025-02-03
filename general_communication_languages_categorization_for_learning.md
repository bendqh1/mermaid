From my experience, a General Communication Language (GCL) can be either:

1. Primarily consonant
1. Primarily vowelant
1. Primarily consonant-vowel conjoined

English and Russian are of type 1, while Thai and Vietnamese of type 3 and therefore type 1 speakers could learn each other's languages fast, but will have a hard time learning type 3 languages and vice versa.

## Charts

```mermaid
flowchart TD

  subgraph A [Speaking]
    A1[Primarily Consonant]
    A2[Primarily Vowelant]
    A3[Primarily consonant-vowel conjoined]
  end

  subgraph B [Learning]
    B1[Primarily Consonant]
    B2[Primarily Vowelant]
    B3[Primarily consonant-vowel conjoined]
  end

  A1 --> |Easy| B1
  A2 --> |Easy| B2
  A3 --> |Easy| B3
  A1 --> |Hard| B2
  B2 --> |Hard| A1
```
