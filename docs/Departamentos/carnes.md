---
layout: default
title: "carnes"
permalink: /Departamentos/carnes/
nav_order: 3
---

# Catálogo CARNES

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — EMBUTIDOS"]
    R2["Rubro 2 — MENUDENCIAS"]
    R3["Rubro 3 — CARNE DE CERDO"]
    R4["Rubro 4 — CARNE VACUNA"]
    R5["Rubro 5 — POLLOS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R6["Rubro 6 — CARBON Y LENA"]
    R12["Rubro 12 — PRODUCCION CARNICERIA"]
    R15["Rubro 15 — ELABORACION RAMIRO"]
    R16["Rubro 16 — CORDERO LECHON CHIVIT"]
    R17["Rubro 17 — LISTOS PARA COCINAR"]
  end

  %% Enlaces del Depto a cada Rubro (mantiene LR y 2 filas)
  D4 --> R1 & R2 & R3 & R4 & R5
  D4 --> R6 & R12 & R15 & R16 & R17
```

---

## Rubro 1 — EMBUTIDOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R1["Rubro 1 — EMBUTIDOS"]
    direction TB
    R1["Rubro 1 — EMBUTIDOS"]
    R1 --> F1_1["Familia 1 — CHORIZOS"]
    R1 --> F1_2["Familia 2 — MORCILLA"]
    R1 --> F1_3["Familia 3 — SALCHICHAS"]
  end
  D4 --> R1
```

## Rubro 2 — MENUDENCIAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R2["Rubro 2 — MENUDENCIAS"]
    direction TB
    R2["Rubro 2 — MENUDENCIAS"]
    R2 --> F2_1["Familia 1 — MENUDENCIAS"]
  end
  D4 --> R2
```

## Rubro 3 — CARNE DE CERDO
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R3["Rubro 3 — CARNE DE CERDO"]
    direction TB
    R3["Rubro 3 — CARNE DE CERDO"]
    R3 --> F3_1["Familia 1 — CARNE DE CERDO"]
  end
  D4 --> R3
```

## Rubro 4 — CARNE VACUNA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R4["Rubro 4 — CARNE VACUNA"]
    direction TB
    R4["Rubro 4 — CARNE VACUNA"]
    R4 --> F4_1["Familia 1 — LA HACIENDA PREMIUM"]
    R4 --> F4_2["Familia 2 — NOVILLITO"]
    R4 --> F4_3["Familia 3 — NOVILLITO ESPECIAL"]
  end
  D4 --> R4
```

## Rubro 5 — POLLOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R5["Rubro 5 — POLLOS"]
    direction TB
    R5["Rubro 5 — POLLOS"]
    R5 --> F5_1["Familia 1 — POLLOS"]
  end
  D4 --> R5
```

## Rubro 6 — CARBON Y LENA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R6["Rubro 6 — CARBON Y LENA"]
    direction TB
    R6["Rubro 6 — CARBON Y LENA"]
    R6 --> F6_1["Familia 1 — CARBON Y LENA"]
  end
  D4 --> R6
```

## Rubro 12 — PRODUCCION CARNICERIA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R12["Rubro 12 — PRODUCCION CARNICERIA"]
    direction TB
    R12["Rubro 12 — PRODUCCION CARNICERIA"]
    R12 --> F12_1["Familia 1 — PRODUCCION CARNICERIA"]
  end
  D4 --> R12
```

## Rubro 15 — ELABORACION RAMIRO
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R15["Rubro 15 — ELABORACION RAMIRO"]
    direction TB
    R15["Rubro 15 — ELABORACION RAMIRO"]
    R15 --> F15_1["Familia 1 — ELABORACION RAMIRO"]
  end
  D4 --> R15
```

## Rubro 16 — CORDERO LECHON CHIVIT
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R16["Rubro 16 — CORDERO LECHON CHIVIT"]
    direction TB
    R16["Rubro 16 — CORDERO LECHON CHIVIT"]
    R16 --> F16_1["Familia 1 — CORDERO"]
    R16 --> F16_2["Familia 2 — LECHON"]
    R16 --> F16_3["Familia 3 — CHIVITO"]
    R16 --> F16_4["Familia 4 — CONEJO"]
  end
  D4 --> R16
```

## Rubro 17 — LISTOS PARA COCINAR
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D4["Depto 4 — CARNES"]
  subgraph G_R17["Rubro 17 — LISTOS PARA COCINAR"]
    direction TB
    R17["Rubro 17 — LISTOS PARA COCINAR"]
    R17 --> F17_1["Familia 1 — LISTOS PARA COCINAR"]
  end
  D4 --> R17
```
