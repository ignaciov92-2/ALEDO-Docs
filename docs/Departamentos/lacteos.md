---
layout: default
title: "Lacteos"
permalink: /Departamentos/lacteos/
parent: "Departamentos"
nav_order: 3
---

# Catálogo LACTEOS

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — YOGURES"]
    R2["Rubro 2 — POSTRES"]
    R3["Rubro 3 — CREMAS"]
    R5["Rubro 5 — MANTECAS Y MARGARINAS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R6["Rubro 6 — LECHES"]
    R8["Rubro 8 — DULCE DE LECHE"]
    R9["Rubro 9 — PASTAS Y TAPAS"]
  end

  %% Enlaces del Depto a cada Rubro
  D10 --> R1 & R2 & R3 & R5
  D10 --> R6 & R8 & R9
```

---

## Rubro 1 — YOGURES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R1["Rubro 1 — YOGURES"]
    direction TB
    R1["Rubro 1 — YOGURES"]
    R1 --> F1_1["Familia 1 — YOGURES DESCREMADOS"]
    R1 --> F1_2["Familia 2 — YOGURES ENTEROS"]
  end
  D10 --> R1
```

## Rubro 2 — POSTRES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R2["Rubro 2 — POSTRES"]
    direction TB
    R2["Rubro 2 — POSTRES"]
    R2 --> F2_1["Familia 1 — POSTRES"]
  end
  D10 --> R2
```

## Rubro 3 — CREMAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R3["Rubro 3 — CREMAS"]
    direction TB
    R3["Rubro 3 — CREMAS"]
    R3 --> F3_1["Familia 1 — CREMAS"]
  end
  D10 --> R3
```

## Rubro 5 — MANTECAS Y MARGARINAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R5["Rubro 5 — MANTECAS Y MARGARINAS"]
    direction TB
    R5["Rubro 5 — MANTECAS Y MARGARINAS"]
    R5 --> F5_1["Familia 1 — MANTECA"]
    R5 --> F5_2["Familia 2 — MARGARINAS"]
    R5 --> F5_3["Familia 3 — GRASA"]
  end
  D10 --> R5
```

## Rubro 6 — LECHES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R6["Rubro 6 — LECHES"]
    direction TB
    R6["Rubro 6 — LECHES"]
    R6 --> F6_1["Familia 1 — BEBIDAS VEGETALES"]
    R6 --> F6_2["Familia 2 — LECHES LARGA VIDA"]
    R6 --> F6_3["Familia 3 — LECHES REFRIGERADAS"]
    R6 --> F6_4["Familia 4 — LECHES SABORIZADAS"]
  end
  D10 --> R6
```

## Rubro 8 — DULCE DE LECHE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R8["Rubro 8 — DULCE DE LECHE"]
    direction TB
    R8["Rubro 8 — DULCE DE LECHE"]
    R8 --> F8_1["Familia 1 — DULCE DE LECHE"]
  end
  D10 --> R8
```

## Rubro 9 — PASTAS Y TAPAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D10["Depto 10 — LACTEOS"]
  subgraph G_R9["Rubro 9 — PASTAS Y TAPAS"]
    direction TB
    R9["Rubro 9 — PASTAS Y TAPAS"]
    R9 --> F9_1["Familia 1 — GRASAS"]
  end
  D10 --> R9
```
