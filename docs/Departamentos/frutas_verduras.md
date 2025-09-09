# Catálogo FRUTAS Y VERDURAS
## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — FRUTAS"]
    R2["Rubro 2 — VERDURAS"]
    R3["Rubro 3 — HUEVOS"]
    R4["Rubro 4 — HIERBAS AROMATICAS Y"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R5["Rubro 5 — ORGANICOS"]
    R6["Rubro 6 — LEGUMBRES GRANOS Y SE"]
    R71["Rubro 71 — FRUTAS SECAS Y DISECA"]
  end

  %% Enlaces del Depto a cada Rubro
  D17 --> R1 & R2 & R3 & R4
  D17 --> R5 & R6 & R71
```

---

## Rubro 1 — FRUTAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R1["Rubro 1 — FRUTAS"]
    direction TB
    R1["Rubro 1 — FRUTAS"]
    R1 --> F1_1["Familia 1 — FRUTAS CONGELADAS"]
    R1 --> F1_2["Familia 2 — FRUTAS EMPAQUETADAS"]
    R1 --> F1_3["Familia 3 — FRUTAS SECAS Y DISECA"]
    R1 --> F1_4["Familia 4 — FRUTAS SUELTAS"]
  end
  D17 --> R1
```

## Rubro 2 — VERDURAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R2["Rubro 2 — VERDURAS"]
    direction TB
    R2["Rubro 2 — VERDURAS"]
    R2 --> F2_1["Familia 1 — HORTALIZAS LIVIANAS"]
    R2 --> F2_2["Familia 2 — HORTALIZAS PESADAS"]
    R2 --> F2_3["Familia 3 — VERDURAS EMPAQUETADAS"]
    R2 --> F2_4["Familia 4 — VERDURAS FRESCAS DE H"]
    R2 --> F2_5["Familia 5 — VERDURAS PROCESADAS Y"]
    R2 --> F2_6["Familia 6 — VERDURAS SECAS Y DESE"]
  end
  D17 --> R2
```

## Rubro 3 — HUEVOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R3["Rubro 3 — HUEVOS"]
    direction TB
    R3["Rubro 3 — HUEVOS"]
    R3 --> F3_1["Familia 1 — HUEVOS"]
  end
  D17 --> R3
```

## Rubro 4 — HIERBAS AROMATICAS Y
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R4["Rubro 4 — HIERBAS AROMATICAS Y"]
    direction TB
    R4["Rubro 4 — HIERBAS AROMATICAS Y"]
    R4 --> F4_1["Familia 1 — HIERBAS AROMATICAS Y"]
  end
  D17 --> R4
```

## Rubro 5 — ORGANICOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R5["Rubro 5 — ORGANICOS"]
    direction TB
    R5["Rubro 5 — ORGANICOS"]
    R5 --> F5_1["Familia 1 — ORGANICOS"]
  end
  D17 --> R5
```

## Rubro 6 — LEGUMBRES GRANOS Y SE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R6["Rubro 6 — LEGUMBRES GRANOS Y SE"]
    direction TB
    R6["Rubro 6 — LEGUMBRES GRANOS Y SE"]
    R6 --> F6_1["Familia 1 — LEGUMBRES GRANOS Y SE"]
  end
  D17 --> R6
```

## Rubro 71 — FRUTAS SECAS Y DISECA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D17["Depto 17 — FRUTAS Y VERDURAS"]
  subgraph G_R71["Rubro 71 — FRUTAS SECAS Y DISECA"]
    direction TB
    R71["Rubro 71 — FRUTAS SECAS Y DISECA"]
    R71 --> F71_1["Familia 1 — FRUTAS SECAS Y DISECA"]
  end
  D17 --> R71
```
