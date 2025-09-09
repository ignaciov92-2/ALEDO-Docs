# Catálogo BEBES Y NINOS
## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — ALIMENTACION"]
    R2["Rubro 2 — JUGUETERIA"]
    R3["Rubro 3 — COCHECITOS BUTACAS Y"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R4["Rubro 4 — PIJAMAS"]
    R5["Rubro 5 — CUIDADO DEL BEBE"]
    R6["Rubro 6 — PANALES"]
  end

  %% Enlaces del Depto a cada Rubro (mantiene LR y 2 filas)
  D100 --> R1 & R2 & R3
  D100 --> R4 & R5 & R6
```

---

## Rubro 1 — ALIMENTACION
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R1["Rubro 1 — ALIMENTACION"]
    direction TB
    R1["Rubro 1 — ALIMENTACION"]
    R1 --> F1_1["Familia 1 — ALIMENTACION"]
  end
  D100 --> R1
```

## Rubro 2 — JUGUETERIA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R2["Rubro 2 — JUGUETERIA"]
    direction TB
    R2["Rubro 2 — JUGUETERIA"]
    R2 --> F2_1["Familia 1 — DISFRACES"]
    R2 --> F2_2["Familia 2 — ENSAMBLES Y ROMPECABE"]
    R2 --> F2_3["Familia 3 — JUEGOS DE MESA"]
    R2 --> F2_4["Familia 4 — JUGUETES"]
    R2 --> F2_5["Familia 5 — JUGUETES DE PLAYA Y A"]
    R2 --> F2_6["Familia 6 — JUGUETES PARA BEBES"]
    R2 --> F2_7["Familia 7 — MUNECAS Y MUNECOS"]
    R2 --> F2_8["Familia 8 — PELUCHES"]
    R2 --> F2_9["Familia 9 — VEHICULOS Y PISTAS"]
  end
  D100 --> R2
```

## Rubro 3 — COCHECITOS BUTACAS Y
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R3["Rubro 3 — COCHECITOS BUTACAS Y"]
    direction TB
    R3["Rubro 3 — COCHECITOS BUTACAS Y"]
    R3 --> F3_1["Familia 1 — COCHECITOS BUTACAS Y"]
  end
  D100 --> R3
```

## Rubro 4 — PIJAMAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R4["Rubro 4 — PIJAMAS"]
    direction TB
    R4["Rubro 4 — PIJAMAS"]
    R4 --> F4_1["Familia 1 — PIJAMAS"]
  end
  D100 --> R4
```

## Rubro 5 — CUIDADO DEL BEBE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R5["Rubro 5 — CUIDADO DEL BEBE"]
    direction TB
    R5["Rubro 5 — CUIDADO DEL BEBE"]
    R5 --> F5_1["Familia 1 — HIGIENE DEL BEBE"]
    R5 --> F5_2["Familia 2 — CHUPETES, MAMADERAS"]
  end
  D100 --> R5
```

## Rubro 6 — PANALES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D100["Depto 100 — BEBES Y NINOS"]
  subgraph G_R6["Rubro 6 — PANALES"]
    direction TB
    R6["Rubro 6 — PANALES"]
    R6 --> F6_1["Familia 1 — PANALES"]
  end
  D100 --> R6
```
