---
layout: default
title: "Perfumeria"
permalink: /Departamentos/perfumeria/
parent: "Departamentos"
nav_order: 3
---

# Catálogo PERFUMERIA

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — CUIDADO ORAL"]
    R2["Rubro 2 — CUIDADO CAPILAR"]
    R3["Rubro 3 — PERFUMES Y COLONIAS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R7["Rubro 7 — FARMACIA"]
    R8["Rubro 8 — CUIDADO PERSONAL"]
  end

  %% Fila 3
  subgraph Row3[ ]
    direction LR
    R34["Rubro 34 — CUIDADO DE LA PIEL"]
    R38["Rubro 38 — MAQUILLAJE"]
  end

  %% Enlaces del Depto a cada Rubro
  D11 --> R1 & R2 & R3
  D11 --> R7 & R8
  D11 --> R34 & R38
```

---

## Rubro 1 — CUIDADO ORAL
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R1["Rubro 1 — CUIDADO ORAL"]
    direction TB
    R1["Rubro 1 — CUIDADO ORAL"]
    R1 --> F1_1["Familia 1 — ACCESORIOS DENTALES"]
    R1 --> F1_2["Familia 2 — CEPILLOS DENTALES"]
    R1 --> F1_3["Familia 3 — ENJUAGUES BUCALES"]
    R1 --> F1_4["Familia 4 — PASTAS DENTALES"]
  end
  D11 --> R1
```

## Rubro 2 — CUIDADO CAPILAR
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R2["Rubro 2 — CUIDADO CAPILAR"]
    direction TB
    R2["Rubro 2 — CUIDADO CAPILAR"]
    R2 --> F2_1["Familia 1 — ACONDICIONADOR"]
    R2 --> F2_2["Familia 2 — CEPILLOS PARA PELO"]
    R2 --> F2_3["Familia 3 — COLORACION"]
    R2 --> F2_4["Familia 4 — FIJACION"]
    R2 --> F2_5["Familia 5 — PEDICULOSIS"]
    R2 --> F2_6["Familia 6 — REPARACION Y TRATAMIE"]
    R2 --> F2_7["Familia 7 — SHAMPOO"]
  end
  D11 --> R2
```

## Rubro 3 — PERFUMES Y COLONIAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R3["Rubro 3 — PERFUMES Y COLONIAS"]
    direction TB
    R3["Rubro 3 — PERFUMES Y COLONIAS"]
    R3 --> F3_1["Familia 1 — HOMBRE"]
    R3 --> F3_2["Familia 2 — MUJER"]
    R3 --> F3_3["Familia 3 — NIÑOS"]
  end
  D11 --> R3
```

## Rubro 7 — FARMACIA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R7["Rubro 7 — FARMACIA"]
    direction TB
    R7["Rubro 7 — FARMACIA"]
    R7 --> F7_1["Familia 1 — ALCOHOL"]
    R7 --> F7_2["Familia 2 — ALGODON"]
    R7 --> F7_3["Familia 3 — APOSITOS"]
    R7 --> F7_4["Familia 4 — OTROS"]
    R7 --> F7_5["Familia 5 — PRESERVATIVOS"]
  end
  D11 --> R7
```

## Rubro 8 — CUIDADO PERSONAL
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 7, 'rankSpacing': 10}, 'themeVariables': {'fontSize': '10px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R8["Rubro 8 — CUIDADO PERSONAL"]
    direction TB
    R8["Rubro 8 — CUIDADO PERSONAL"]
    R8 --> F8_1["Familia 1 — CEPILLOS Y ESPONJAS"]
    R8 --> F8_2["Familia 2 — DEPILACION"]
    R8 --> F8_3["Familia 3 — DESODORANTES DE HOMBR"]
    R8 --> F8_4["Familia 4 — DESODORANTES DE MUJER"]
    R8 --> F8_5["Familia 5 — DESODORANTES Y POLVOS"]
    R8 --> F8_6["Familia 6 — GELES DE DUCHA"]
    R8 --> F8_7["Familia 7 — HIGIENE PREVENTIVA"]
    R8 --> F8_8["Familia 8 — JABONES"]
    R8 --> F8_9["Familia 9 — PRODUCTOS PARA AFEITA"]
    R8 --> F8_10["Familia 10 — PROTECCION ADULTOS"]
    R8 --> F8_11["Familia 11 — PROTECCION FEMENINA"]
    R8 --> F8_12["Familia 12 — CUIDADO DE UÑAS"]
  end
  D11 --> R8
```

## Rubro 34 — CUIDADO DE LA PIEL
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R34["Rubro 34 — CUIDADO DE LA PIEL"]
    direction TB
    R34["Rubro 34 — CUIDADO DE LA PIEL"]
    R34 --> F34_1["Familia 1 — CREMAS CORPORALES"]
    R34 --> F34_2["Familia 2 — CREMAS DESMAQUILLANTE"]
    R34 --> F34_3["Familia 3 — CREMAS FACIALES"]
    R34 --> F34_4["Familia 4 — SOLARES Y POST SOLARE"]
    R34 --> F34_5["Familia 5 — BALSAMOS"]
  end
  D11 --> R34
```

## Rubro 38 — MAQUILLAJE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D11["Depto 11 — PERFUMERIA"]
  subgraph G_R38["Rubro 38 — MAQUILLAJE"]
    direction TB
    R38["Rubro 38 — MAQUILLAJE"]
    R38 --> F38_1["Familia 1 — CUIDADO DE UÑAS"]
  end
  D11 --> R38
```
