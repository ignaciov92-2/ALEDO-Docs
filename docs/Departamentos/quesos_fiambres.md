---
layout: default
title: "Quesos y fiambres"
permalink: /Departamentos/quesos_fiambres/
nav_order: 3
---

# Catálogo QUESOS Y FIAMBRES

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — FIAMBRES"]
    R2["Rubro 2 — QUESOS"]
    R3["Rubro 3 — produccion elaborados"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R4["Rubro 4 — DULCES"]
    R5["Rubro 5 — SALCHICHAS"]
    R6["Rubro 6 — ENCURTIDOS ACEITUNAS"]
  end

  %% Enlaces del Depto a cada Rubro
  D16 --> R1 & R2 & R3
  D16 --> R4 & R5 & R6
```

---

## Rubro 1 — FIAMBRES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R1["Rubro 1 — FIAMBRES"]
    direction TB
    R1["Rubro 1 — FIAMBRES"]
    R1 --> F1_1["Familia 1 — FIAMBRES"]
    R1 --> F1_2["Familia 2 — JAMON COCIDO Y CRUDO"]
    R1 --> F1_3["Familia 3 — Bondiola"]
    R1 --> F1_4["Familia 4 — Mortadela"]
    R1 --> F1_5["Familia 5 — Pastron"]
    R1 --> F1_6["Familia 6 — Salchichon"]
    R1 --> F1_7["Familia 7 — Salame"]
    R1 --> F1_8["Familia 8 — Salamin"]
    R1 --> F1_9["Familia 9 — Lomo"]
    R1 --> F1_10["Familia 10 — Panceta"]
    R1 --> F1_11["Familia 11 — Paleta"]
    R1 --> F1_12["Familia 12 — Leber"]
    R1 --> F1_13["Familia 13 — Matambre Arrollado"]
    R1 --> F1_14["Familia 14 — De Cerdo"]
  end
  D16 --> R1
```

## Rubro 2 — QUESOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 7, 'rankSpacing': 10}, 'themeVariables': {'fontSize': '10px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R2["Rubro 2 — QUESOS"]
    direction TB
    R2["Rubro 2 — QUESOS"]
    R2 --> F2_1["Familia 1 — QUESOS PORT SALUT Y C"]
    R2 --> F2_2["Familia 2 — QUESOS ESPECIALES E I"]
    R2 --> F2_3["Familia 3 — QUESOS DUROS"]
    R2 --> F2_4["Familia 4 — QUESOS SEMIBLANDOS"]
    R2 --> F2_5["Familia 5 — QUESOS UNTABLES"]
    R2 --> F2_6["Familia 6 — RICOTA"]
    R2 --> F2_7["Familia 7 — Gouda"]
    R2 --> F2_8["Familia 8 — Sardo"]
    R2 --> F2_9["Familia 9 — Cheddar"]
    R2 --> F2_10["Familia 10 — Provolone"]
    R2 --> F2_11["Familia 11 — Fundidos"]
    R2 --> F2_12["Familia 12 — Hebras"]
    R2 --> F2_13["Familia 13 — QUESOS RALLADOS"]
    R2 --> F2_14["Familia 14 — De Campo"]
    R2 --> F2_15["Familia 15 — QUESO MUZZARELLA"]
    R2 --> F2_16["Familia 16 — Port Salut"]
    R2 --> F2_17["Familia 17 — Ricotta"]
  end
  D16 --> R2
```

## Rubro 3 — produccion elaborados
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R3["Rubro 3 — produccion elaborados"]
    direction TB
    R3["Rubro 3 — produccion elaborados"]
    R3 --> F3_1["Familia 1 — Pizzas"]
    R3 --> F3_2["Familia 2 — Sandwich"]
    R3 --> F3_3["Familia 3 — Ternera"]
    R3 --> F3_4["Familia 4 — Picada"]
  end
  D16 --> R3
```

## Rubro 4 — DULCES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R4["Rubro 4 — DULCES"]
    direction TB
    R4["Rubro 4 — DULCES"]
    R4 --> F4_1["Familia 1 — DULCES"]
  end
  D16 --> R4
```

## Rubro 5 — SALCHICHAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R5["Rubro 5 — SALCHICHAS"]
    direction TB
    R5["Rubro 5 — SALCHICHAS"]
    R5 --> F5_1["Familia 1 — Salchichas"]
    R5 --> F5_2["Familia 2 — Chorizos"]
  end
  D16 --> R5
```

## Rubro 6 — ENCURTIDOS ACEITUNAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D16["Depto 16 — QUESOS Y FIAMBRES"]
  subgraph G_R6["Rubro 6 — ENCURTIDOS ACEITUNAS"]
    direction TB
    R6["Rubro 6 — ENCURTIDOS ACEITUNAS"]
    R6 --> F6_1["Familia 1 — ENCURTIDOS ACEITUNAS"]
  end
  D16 --> R6
```
