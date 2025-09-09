# Catálogo HOGAR Y TEXTIL

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — PLASTICOS"]
    R2["Rubro 2 — VIDRIOS"]
    R3["Rubro 3 — UTENSILLOS"]
    R4["Rubro 4 — FOCOS"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R11["Rubro 11 — ENCENDEDORES"]
    R12["Rubro 12 — HOGAR"]
    R13["Rubro 13 — COCINA"]
    R14["Rubro 14 — LIBRERIA"]
    R15["Rubro 15 — ORGANIZACION"]
  end

  %% Enlaces del Depto a cada Rubro
  D2 --> R1 & R2 & R3 & R4
  D2 --> R11 & R12 & R13 & R14 & R15
```

---

## Rubro 1 — PLASTICOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R1["Rubro 1 — PLASTICOS"]
    direction TB
    R1["Rubro 1 — PLASTICOS"]
    R1 --> F1_1["Familia 1 — PLASTICOS"]
  end
  D2 --> R1
```

## Rubro 2 — VIDRIOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R2["Rubro 2 — VIDRIOS"]
    direction TB
    R2["Rubro 2 — VIDRIOS"]
    R2 --> F2_1["Familia 1 — VIDRIOS"]
  end
  D2 --> R2
```

## Rubro 3 — UTENSILLOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R3["Rubro 3 — UTENSILLOS"]
    direction TB
    R3["Rubro 3 — UTENSILLOS"]
    R3 --> F3_1["Familia 1 — UTENSILLOS"]
  end
  D2 --> R3
```

## Rubro 4 — FOCOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R4["Rubro 4 — FOCOS"]
    direction TB
    R4["Rubro 4 — FOCOS"]
    R4 --> F4_1["Familia 1 — FOCOS"]
  end
  D2 --> R4
```

## Rubro 11 — ENCENDEDORES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R11["Rubro 11 — ENCENDEDORES"]
    direction TB
    R11["Rubro 11 — ENCENDEDORES"]
    R11 --> F11_1["Familia 1 — ENCENDEDORES"]
  end
  D2 --> R11
```

## Rubro 12 — HOGAR
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R12["Rubro 12 — HOGAR"]
    direction TB
    R12["Rubro 12 — HOGAR"]
    R12 --> F12_1["Familia 1 — HOGAR"]
  end
  D2 --> R12
```

## Rubro 13 — COCINA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 9, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R13["Rubro 13 — COCINA"]
    direction TB
    R13["Rubro 13 — COCINA"]
    R13 --> F13_1["Familia 1 — REPASADORES"]
    R13 --> F13_2["Familia 2 — INFUSIONES"]
    R13 --> F13_3["Familia 3 — ARTICULOS PARA HORNO"]
    R13 --> F13_4["Familia 4 — ACCESORIOS PARA COCI"]
    R13 --> F13_5["Familia 5 — BOLSA PARA HORNO Y F"]
  end
  D2 --> R13
```

## Rubro 14 — LIBRERIA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R14["Rubro 14 — LIBRERIA"]
    direction TB
    R14["Rubro 14 — LIBRERIA"]
    R14 --> F14_1["Familia 1 — LIBRERIA"]
  end
  D2 --> R14
```

## Rubro 15 — ORGANIZACION
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D2["Depto 2 — HOGAR Y TEXTIL"]
  subgraph G_R15["Rubro 15 — ORGANIZACION"]
    direction TB
    R15["Rubro 15 — ORGANIZACION"]
    R15 --> F15_1["Familia 1 — PERCHAS Y ORGANIZACI"]
  end
  D2 --> R15
```
