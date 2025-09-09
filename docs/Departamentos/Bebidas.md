---
layout: default
title: "Bebidas"
permalink: /Departamentos/Bebidas/
nav_order: 3
---

# Catálogo BEBIDAS

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — GASEOSAS"]
    R2["Rubro 2 — VINOS"]
    R3["Rubro 3 — JUGOS"]
    R4["Rubro 4 — AGUAS"]
    R5["Rubro 5 — FERNET"]
    R6["Rubro 6 — APERITIVOS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R8["Rubro 8 — BEBIDAS BLANCAS"]
    R9["Rubro 9 — CERVEZAS"]
    R10["Rubro 10 — CHAMPAGNES"]
    R12["Rubro 12 — ISOTONICAS"]
    R13["Rubro 13 — A BASE DE HIERBAS"]
    R14["Rubro 14 — ENERGIZANTES"]
  end

  %% Fila 3
  subgraph Row3[ ]
    direction LR
    R15["Rubro 15 — SIDRAS"]
    R17["Rubro 17 — HIELO"]
    R18["Rubro 18 — LICORES"]
    R19["Rubro 19 — WHISKYS"]
    R20["Rubro 20 — GENEROSOS"]
  end

  %% Enlaces del Depto a cada Rubro (mantiene LR y 3 filas)
  D3 --> R1 & R2 & R3 & R4 & R5 & R6
  D3 --> R8 & R9 & R10 & R12 & R13 & R14
  D3 --> R15 & R17 & R18 & R19 & R20
```

---

## Rubro 1 — GASEOSAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R1["Rubro 1 — GASEOSAS"]
    direction TB
    R1["Rubro 1 — GASEOSAS"]
    R1 --> F1_1["Familia 1 — COLA"]
    R1 --> F1_2["Familia 2 — GUARANA"]
    R1 --> F1_3["Familia 3 — LIMA LIMON"]
    R1 --> F1_4["Familia 4 — NARANJA"]
    R1 --> F1_5["Familia 5 — POMELO"]
    R1 --> F1_6["Familia 6 — TONICA"]
    R1 --> F1_7["Familia 7 — MANZANA"]
    R1 --> F1_8["Familia 8 — YERBA MATE SABORIZAD"]
  end
  D3 --> R1
```

## Rubro 2 — VINOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R2["Rubro 2 — VINOS"]
    direction TB
    R2["Rubro 2 — VINOS"]
    R2 --> F2_1["Familia 1 — VINOS BLANCOS"]
    R2 --> F2_2["Familia 2 — VINOS FRIZANTES"]
    R2 --> F2_3["Familia 3 — VINOS ROSADOS"]
    R2 --> F2_4["Familia 4 — VINOS TINTOS"]
  end
  D3 --> R2
```

## Rubro 3 — JUGOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R3["Rubro 3 — JUGOS"]
    direction TB
    R3["Rubro 3 — JUGOS"]
    R3 --> F3_1["Familia 1 — EN POLVO"]
    R3 --> F3_2["Familia 2 — FRESCOS"]
    R3 --> F3_3["Familia 3 — GRANADINA"]
    R3 --> F3_4["Familia 4 — LISTOS"]
  end
  D3 --> R3
```

## Rubro 4 — AGUAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R4["Rubro 4 — AGUAS"]
    direction TB
    R4["Rubro 4 — AGUAS"]
    R4 --> F4_1["Familia 1 — AGUAS CON GAS"]
    R4 --> F4_2["Familia 2 — AGUAS SABORIZADAS"]
    R4 --> F4_3["Familia 3 — AGUAS SIN GAS"]
  end
  D3 --> R4
```

## Rubro 5 — FERNET
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R5["Rubro 5 — FERNET"]
    direction TB
    R5["Rubro 5 — FERNET"]
    R5 --> F5_1["Familia 1 — FERNET"]
  end
  D3 --> R5
```

## Rubro 6 — APERITIVOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R6["Rubro 6 — APERITIVOS"]
    direction TB
    R6["Rubro 6 — APERITIVOS"]
    R6 --> F6_1["Familia 1 — APERITIVOS"]
  end
  D3 --> R6
```

## Rubro 8 — BEBIDAS BLANCAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R8["Rubro 8 — BEBIDAS BLANCAS"]
    direction TB
    R8["Rubro 8 — BEBIDAS BLANCAS"]
    R8 --> F8_1["Familia 1 — BEBIDAS BLANCAS"]
  end
  D3 --> R8
```

## Rubro 9 — CERVEZAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R9["Rubro 9 — CERVEZAS"]
    direction TB
    R9["Rubro 9 — CERVEZAS"]
    R9 --> F9_1["Familia 1 — CERVEZAS"]
  end
  D3 --> R9
```

## Rubro 10 — CHAMPAGNES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R10["Rubro 10 — CHAMPAGNES"]
    direction TB
    R10["Rubro 10 — CHAMPAGNES"]
    R10 --> F10_1["Familia 1 — CHAMPAGNES"]
  end
  D3 --> R10
```

## Rubro 12 — ISOTONICAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R12["Rubro 12 — ISOTONICAS"]
    direction TB
    R12["Rubro 12 — ISOTONICAS"]
    R12 --> F12_1["Familia 1 — ISOTONICAS"]
  end
  D3 --> R12
```

## Rubro 13 — A BASE DE HIERBAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R13["Rubro 13 — A BASE DE HIERBAS"]
    direction TB
    R13["Rubro 13 — A BASE DE HIERBAS"]
    R13 --> F13_1["Familia 1 — A BASE DE HIERBAS"]
  end
  D3 --> R13
```

## Rubro 14 — ENERGIZANTES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R14["Rubro 14 — ENERGIZANTES"]
    direction TB
    R14["Rubro 14 — ENERGIZANTES"]
    R14 --> F14_1["Familia 1 — ENERGIZANTES"]
  end
  D3 --> R14
```

## Rubro 15 — SIDRAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R15["Rubro 15 — SIDRAS"]
    direction TB
    R15["Rubro 15 — SIDRAS"]
    R15 --> F15_1["Familia 1 — SIDRAS"]
  end
  D3 --> R15
```

## Rubro 17 — HIELO
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R17["Rubro 17 — HIELO"]
    direction TB
    R17["Rubro 17 — HIELO"]
    R17 --> F17_1["Familia 1 — HIELO"]
  end
  D3 --> R17
```

## Rubro 18 — LICORES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R18["Rubro 18 — LICORES"]
    direction TB
    R18["Rubro 18 — LICORES"]
    R18 --> F18_1["Familia 1 — LICORES"]
  end
  D3 --> R18
```

## Rubro 19 — WHISKYS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R19["Rubro 19 — WHISKYS"]
    direction TB
    R19["Rubro 19 — WHISKYS"]
    R19 --> F19_1["Familia 1 — WHISKYS"]
  end
  D3 --> R19
```

## Rubro 20 — GENEROSOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D3["Depto 3 — BEBIDAS"]
  subgraph G_R20["Rubro 20 — GENEROSOS"]
    direction TB
    R20["Rubro 20 — GENEROSOS"]
    R20 --> F20_1["Familia 1 — GENEROSOS"]
  end
  D3 --> R20
```
