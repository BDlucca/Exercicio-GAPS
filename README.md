# Constru-ao-de-uma-casa

```mermaid
gantt
  title Construção de uma casa
dateFormat YYYY-MM-DD
section Seçao 1
Planejamento e aprovaçoes:active, a1, 2025-08-28, 20d
section Seçao 2
Preparaçao do terreno:a2, after a1, 10d
section Seçao 3
Escavaçao:a3, after a2, 15d
Fundaçao:a4, after a2, 30d
section Seçao 4
 Instalaçoes:a5, after a4, 20d
section Seçao 5
Acabamento Interno:a6,after a5, 25d
Acabamento Externo:a7, after a6, 15d
section Seçao 6
Inspeçao final:a8, after a7, 5d
```

```mermaid
graph TD
  subgraph Matriz
    A1["Situacao_1"]:::branco--> A2["D20"]:::amarelo--> A3["E50"]:::laranja--> A4["V100"]:::vermelho
    B1["C8"]:::branco--> B2["Situacao_2"]:::amarelo--> B3["E50"]:::laranja--> B4["V100"]:::vermelho
    C1["C8"]:::branco--> C2["D20"]:::amarelo--> C3["E50"]:::laranja--> C4["Situacao_3"]:::vermelho
    D1["C8"]:::branco--> D2["D20"]:::amarelo--> D3["Situacao_4"]:::laranja--> D4["V100"]:::vermelho
    E1["C8"]:::branco--> E2["Situaca_5"]:::amarelo--> E3["E50"]:::laranja--> E4["V100"]:::vermelho
    F1["C8"]:::branco--> F2["D20"]:::amarelo--> F3["Situacao_6"]:::laranja--> F4["V100"]:::vermelho
    G1["C8"]:::branco--> G2["D20"]:::amarelo--> G3["E50"]:::laranja--> G4["Situacao_7"]:::vermelho
    H1["C8"]:::branco--> H2["D20"]:::amarelo--> H3["E50"]:::laranja--> H4["Situacao_8"]:::vermelho
end

classDef branco fill:#fff,      stroke:#000,  stroke-width:1px;
classDef amarelo fill:#FFD84D,  stroke:#000,  stroke-width:1px;
classDef laranja fill:#FFA233,  stroke:#000,  stroke-width:1px;
classDef vermelho fill:#E64C3C, stroke:#000,  stroke-width:1px;

```
