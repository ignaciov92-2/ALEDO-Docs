---
layout: default
title: "Congelados"
permalink: /Departamentos/congelados/
parent: "Departamentos"
nav_order: 3
---

# Catálogo CONGELADOS

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — POLLO Y CARNES"]
    R2["Rubro 2 — PESCADOS Y MARISCOS"]
    R4["Rubro 4 — VEGETALES"]
    R6["Rubro 6 — FRUTAS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R9["Rubro 9 — HAMBURGUESAS Y MILANE"]
    R12["Rubro 12 — COMIDAS CONGELADAS"]
    R18["Rubro 18 — HELADOS Y POSTRES"]
  end

  %% Enlaces del Depto a cada Rubro
  D18 --> R1 & R2 & R4 & R6
  D18 --> R9 & R12 & R18
```

---

## Rubro 1 — POLLO Y CARNES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R1["Rubro 1 — POLLO Y CARNES"]
    direction TB
    R1["Rubro 1 — POLLO Y CARNES"]
    R1 --> F1_1["Familia 1 — POLLO Y CARNES"]
  end
  D18 --> R1
```

## Rubro 2 — PESCADOS Y MARISCOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R2["Rubro 2 — PESCADOS Y MARISCOS"]
    direction TB
    R2["Rubro 2 — PESCADOS Y MARISCOS"]
    R2 --> F2_1["Familia 1 — PESCADOS Y MARISCOS"]
  end
  D18 --> R2
```

## Rubro 4 — VEGETALES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R4["Rubro 4 — VEGETALES"]
    direction TB
    R4["Rubro 4 — VEGETALES"]
    R4 --> F4_1["Familia 1 — VEGETALES"]
  end
  D18 --> R4
```

## Rubro 6 — FRUTAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R6["Rubro 6 — FRUTAS"]
    direction TB
    R6["Rubro 6 — FRUTAS"]
    R6 --> F6_1["Familia 1 — FRUTAS"]
  end
  D18 --> R6
```

## Rubro 9 — HAMBURGUESAS Y MILANE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R9["Rubro 9 — HAMBURGUESAS Y MILANE"]
    direction TB
    R9["Rubro 9 — HAMBURGUESAS Y MILANE"]
    R9 --> F9_1["Familia 1 — HAMBURGUESAS Y MILANE"]
  end
  D18 --> R9
```

## Rubro 12 — COMIDAS CONGELADAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R12["Rubro 12 — COMIDAS CONGELADAS"]
    direction TB
    R12["Rubro 12 — COMIDAS CONGELADAS"]
    R12 --> F12_1["Familia 1 — COMIDAS CONGELADAS"]
    R12 --> F12_2["Familia 2 — EMPANADAS Y TARTAS"]
    R12 --> F12_3["Familia 3 — PIZZAS"]
  end
  D18 --> R12
```

## Rubro 18 — HELADOS Y POSTRES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D18["Depto 18 — CONGELADOS"]
  subgraph G_R18["Rubro 18 — HELADOS Y POSTRES"]
    direction TB
    R18["Rubro 18 — HELADOS Y POSTRES"]
    R18 --> F18_1["Familia 1 — HELADOS"]
    R18 --> F18_2["Familia 2 — POSTRES"]
  end
  D18 --> R18
```
