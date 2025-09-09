---
layout: default
title: "Pastas frescas"
permalink: /Departamentos/pastas_frescas/
nav_order: 3
---

# Catálogo PASTAS FRESCAS

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — FIDEOS"]
    R2["Rubro 2 — PASCUALINAS"]
    R3["Rubro 3 — TAPAS DE EMPANADAS"]
    R4["Rubro 4 — ÑOQUIS"]
    R5["Rubro 5 — SORRENTINOS"]
    R6["Rubro 6 — CAPELETTIS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R7["Rubro 7 — RAVIOLES"]
    R8["Rubro 8 — PASTAS RELLENAS"]
    R9["Rubro 9 — TARTAS"]
    R10["Rubro 10 — PIZZA"]
    R11["Rubro 11 — MASAS Y LEVADURAS"]
  end

  %% Enlaces del Depto a cada Rubro
  D6 --> R1 & R2 & R3 & R4 & R5 & R6
  D6 --> R7 & R8 & R9 & R10 & R11
```

---

## Rubro 1 — FIDEOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R1["Rubro 1 — FIDEOS"]
    direction TB
    R1["Rubro 1 — FIDEOS"]
    R1 --> F1_1["Familia 1 — FIDEOS"]
  end
  D6 --> R1
```

## Rubro 2 — PASCUALINAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R2["Rubro 2 — PASCUALINAS"]
    direction TB
    R2["Rubro 2 — PASCUALINAS"]
    R2 --> F2_1["Familia 1 — PASCUALINAS"]
  end
  D6 --> R2
```

## Rubro 3 — TAPAS DE EMPANADAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R3["Rubro 3 — TAPAS DE EMPANADAS"]
    direction TB
    R3["Rubro 3 — TAPAS DE EMPANADAS"]
    R3 --> F3_1["Familia 1 — TAPAS DE EMPANADAS"]
  end
  D6 --> R3
```

## Rubro 4 — ÑOQUIS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R4["Rubro 4 — ÑOQUIS"]
    direction TB
    R4["Rubro 4 — ÑOQUIS"]
    R4 --> F4_1["Familia 1 — ÑOQUIS"]
  end
  D6 --> R4
```

## Rubro 5 — SORRENTINOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R5["Rubro 5 — SORRENTINOS"]
    direction TB
    R5["Rubro 5 — SORRENTINOS"]
    R5 --> F5_1["Familia 1 — SORRENTINOS"]
  end
  D6 --> R5
```

## Rubro 6 — CAPELETTIS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R6["Rubro 6 — CAPELETTIS"]
    direction TB
    R6["Rubro 6 — CAPELETTIS"]
    R6 --> F6_1["Familia 1 — CAPELETTIS"]
  end
  D6 --> R6
```

## Rubro 7 — RAVIOLES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R7["Rubro 7 — RAVIOLES"]
    direction TB
    R7["Rubro 7 — RAVIOLES"]
    R7 --> F7_1["Familia 1 — RAVIOLES"]
  end
  D6 --> R7
```

## Rubro 8 — PASTAS RELLENAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R8["Rubro 8 — PASTAS RELLENAS"]
    direction TB
    R8["Rubro 8 — PASTAS RELLENAS"]
    R8 --> F8_1["Familia 1 — PASTAS RELLENAS"]
  end
  D6 --> R8
```

## Rubro 9 — TARTAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R9["Rubro 9 — TARTAS"]
    direction TB
    R9["Rubro 9 — TARTAS"]
    R9 --> F9_1["Familia 1 — TARTAS"]
  end
  D6 --> R9
```

## Rubro 10 — PIZZA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R10["Rubro 10 — PIZZA"]
    direction TB
    R10["Rubro 10 — PIZZA"]
    R10 --> F10_1["Familia 1 — PIZZA"]
  end
  D6 --> R10
```

## Rubro 11 — MASAS Y LEVADURAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D6["Depto 6 — PASTAS FRESCAS"]
  subgraph G_R11["Rubro 11 — MASAS Y LEVADURAS"]
    direction TB
    R11["Rubro 11 — MASAS Y LEVADURAS"]
    R11 --> F11_1["Familia 1 — LEVADURAS"]
  end
  D6 --> R11
```
