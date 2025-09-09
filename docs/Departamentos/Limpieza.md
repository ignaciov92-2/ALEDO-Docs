---
layout: default
title: "Limpieza"
parent: "Departamentos"
nav_order: 3
---
# Catálogo LIMPIEZA

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — CUIDADO PARA LA ROPA"]
    R2["Rubro 2 — LIMPIEZA DE COCINA"]
    R3["Rubro 3 — LIMPIEZA DE PISOS Y M"]
    R4["Rubro 4 — LIMPIEZA DE BANO"]
    R5["Rubro 5 — INSECTICIDAS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R6["Rubro 6 — DESODORANTES DE AMBIE"]
    R7["Rubro 7 — CALZADO"]
    R11["Rubro 11 — PAPELES"]
    R13["Rubro 13 — LAVANDINA"]
    R14["Rubro 14 — ACCESORIOS DE LIMPIEZ"]
  end

  %% Enlaces del Depto a cada Rubro
  D7 --> R1 & R2 & R3 & R4 & R5
  D7 --> R6 & R7 & R11 & R13 & R14
```

---

## Rubro 1 — CUIDADO PARA LA ROPA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R1["Rubro 1 — CUIDADO PARA LA ROPA"]
    direction TB
    R1["Rubro 1 — CUIDADO PARA LA ROPA"]
    R1 --> F1_1["Familia 1 — APRESTOS Y BLANQUEADO"]
    R1 --> F1_2["Familia 2 — CEPILLO PARA ROPA"]
    R1 --> F1_3["Familia 3 — DETERGENTE PARA ROPA"]
    R1 --> F1_4["Familia 4 — JABON EN PAN"]
    R1 --> F1_5["Familia 5 — PERFUMANTES"]
    R1 --> F1_6["Familia 6 — QUITAMANCHAS"]
    R1 --> F1_7["Familia 7 — SUAVIZANTES"]
  end
  D7 --> R1
```

## Rubro 2 — LIMPIEZA DE COCINA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R2["Rubro 2 — LIMPIEZA DE COCINA"]
    direction TB
    R2["Rubro 2 — LIMPIEZA DE COCINA"]
    R2 --> F2_1["Familia 1 — DETERGENTES"]
    R2 --> F2_2["Familia 2 — ESCARBADIENTES"]
    R2 --> F2_3["Familia 3 — FOSFOROS"]
    R2 --> F2_4["Familia 4 — LIMPIADORES"]
    R2 --> F2_5["Familia 5 — LIMPIAVIDRIOS"]
    R2 --> F2_6["Familia 6 — PRODUCTOS PARA LAVAVA"]
  end
  D7 --> R2
```

## Rubro 3 — LIMPIEZA DE PISOS Y M
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R3["Rubro 3 — LIMPIEZA DE PISOS Y M"]
    direction TB
    R3["Rubro 3 — LIMPIEZA DE PISOS Y M"]
    R3 --> F3_1["Familia 1 — CERAS Y AUTOBRILLOS"]
    R3 --> F3_2["Familia 2 — LIMPIADORES DE PISOS"]
    R3 --> F3_3["Familia 3 — LUSTRAMUEBLES"]
  end
  D7 --> R3
```

## Rubro 4 — LIMPIEZA DE BANO
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R4["Rubro 4 — LIMPIEZA DE BANO"]
    direction TB
    R4["Rubro 4 — LIMPIEZA DE BANO"]
    R4 --> F4_1["Familia 1 — DESINFECTANTES"]
    R4 --> F4_2["Familia 2 — DESTAPA CANERIAS"]
    R4 --> F4_3["Familia 3 — PASTILLAS Y BLOQUES"]
  end
  D7 --> R4
```

## Rubro 5 — INSECTICIDAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R5["Rubro 5 — INSECTICIDAS"]
    direction TB
    R5["Rubro 5 — INSECTICIDAS"]
    R5 --> F5_1["Familia 1 — AEROSOLES"]
    R5 --> F5_2["Familia 2 — APARATOS"]
    R5 --> F5_3["Familia 3 — CEBOS BOLILLAS Y PAST"]
    R5 --> F5_4["Familia 4 — REPELENTES"]
    R5 --> F5_5["Familia 5 — TABLETAS Y DIFUSORES"]
  end
  D7 --> R5
```

## Rubro 6 — DESODORANTES DE AMBIE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R6["Rubro 6 — DESODORANTES DE AMBIE"]
    direction TB
    R6["Rubro 6 — DESODORANTES DE AMBIE"]
    R6 --> F6_1["Familia 1 — ABSORBE HUMEDAD"]
    R6 --> F6_2["Familia 2 — AROMATIZANTES"]
    R6 --> F6_3["Familia 3 — DESODORANTES Y DESINF"]
  end
  D7 --> R6
```

## Rubro 7 — CALZADO
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R7["Rubro 7 — CALZADO"]
    direction TB
    R7["Rubro 7 — CALZADO"]
    R7 --> F7_1["Familia 1 — BRILLOS Y REVIVIDORES"]
    R7 --> F7_2["Familia 2 — LIMPIADORES"]
    R7 --> F7_3["Familia 3 — POMADAS PARA CALZADO"]
  end
  D7 --> R7
```

## Rubro 11 — PAPELES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R11["Rubro 11 — PAPELES"]
    direction TB
    R11["Rubro 11 — PAPELES"]
    R11 --> F11_1["Familia 1 — PANUELOS"]
    R11 --> F11_2["Familia 2 — PAPEL HIGIENICO"]
    R11 --> F11_3["Familia 3 — ROLLOS DE COCINA"]
    R11 --> F11_4["Familia 4 — SERVILLETAS"]
  end
  D7 --> R11
```

## Rubro 13 — LAVANDINA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 13}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R13["Rubro 13 — LAVANDINA"]
    direction TB
    R13["Rubro 13 — LAVANDINA"]
    R13 --> F13_1["Familia 1 — LAVANDINA"]
  end
  D7 --> R13
```

## Rubro 14 — ACCESORIOS DE LIMPIEZ
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 8, 'rankSpacing': 11}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D7["Depto 7 — LIMPIEZA"]
  subgraph G_R14["Rubro 14 — ACCESORIOS DE LIMPIEZ"]
    direction TB
    R14["Rubro 14 — ACCESORIOS DE LIMPIEZ"]
    R14 --> F14_1["Familia 1 — BALDES Y MOPAS"]
    R14 --> F14_2["Familia 2 — BOLSAS"]
    R14 --> F14_3["Familia 3 — BROCHES Y GANCHOS"]
    R14 --> F14_4["Familia 4 — ESCOBAS Y ESCOBILLONE"]
    R14 --> F14_5["Familia 5 — ESCOBILLAS"]
    R14 --> F14_6["Familia 6 — ESPONJAS Y GUANTES"]
    R14 --> F14_7["Familia 7 — PALAS Y CABOS"]
    R14 --> F14_8["Familia 8 — PANOS MULTIUSOS"]
    R14 --> F14_9["Familia 9 — SECADORES Y CEPILLOS"]
    R14 --> F14_10["Familia 10 — TRAPOS DE PISO"]
  end
  D7 --> R14
```
