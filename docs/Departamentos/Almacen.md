# Catálogo ALMACEN

## Índice (Depto → Rubros)
```mermaid
%% Vista horizontal estilo A4 (índice)
%% Ajustes de densidad para caber en A4
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 12, 'rankSpacing': 16}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]

  %% Fila 1
  subgraph Row1[ ]
    direction LR
    R1["Rubro 1 — ACEITES Y VINAGRES"]
    R2["Rubro 2 — ARROZ Y LEGUMBRES"]
    R3["Rubro 3 — HARINAS"]
    R4["Rubro 4 — CALDOS SOPAS PURE Y B"]
    R6["Rubro 6 — PASTAS SECAS Y SALSAS"]
    R11["Rubro 11 — SAL PIMIENTA Y ESPECI"]
  end

  %% Fila 2
  subgraph Row2[ ]
    direction LR
    R12["Rubro 12 — PANIFICADOS"]
    R16["Rubro 16 — DESAYUNO Y MERIENDA"]
    R19["Rubro 19 — ADEREZOS"]
    R24["Rubro 24 — CONSERVAS"]
  end

  %% Fila 3
  subgraph Row3[ ]
    direction LR
    R30["Rubro 30 — SNACKS"]
    R31["Rubro 31 — GOLOSINAS Y CHOCOLATE"]
    R35["Rubro 35 — PARA PREPARAR"]
    R49["Rubro 49 — MESA DULCE NAVIDEÑA"]
  end

  %% Enlaces del Depto a cada Rubro (mantiene LR y 3 filas)
  D1 --> R1 & R2 & R3 & R4 & R6 & R11
  D1 --> R12 & R16 & R19 & R24
  D1 --> R30 & R31 & R35 & R49
```

---

## Rubro 1 — ACEITES Y VINAGRES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R1["Rubro 1 — ACEITES Y VINAGRES"]
    direction TB
    R1["Rubro 1 — ACEITES Y VINAGRES"]
    R1 --> F1_1["Familia 1 — ACEITES COMUNES"]
    R1 --> F1_2["Familia 2 — ACEITES ESPECIALES"]
    R1 --> F1_3["Familia 3 — ACETOS"]
    R1 --> F1_4["Familia 4 — JUGOS DE LIMON"]
    R1 --> F1_5["Familia 5 — VINAGRES"]
  end
  D1 --> R1
```

## Rubro 2 — ARROZ Y LEGUMBRES
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R2["Rubro 2 — ARROZ Y LEGUMBRES"]
    direction TB
    R2["Rubro 2 — ARROZ Y LEGUMBRES"]
    R2 --> F2_1["Familia 1 — ARROZ"]
    R2 --> F2_2["Familia 2 — ARROZ LISTOS"]
    R2 --> F2_3["Familia 3 — LEGUMBRES"]
  end
  D1 --> R2
```

## Rubro 3 — HARINAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R3["Rubro 3 — HARINAS"]
    direction TB
    R3["Rubro 3 — HARINAS"]
    R3 --> F3_1["Familia 1 — HARINAS"]
    R3 --> F3_2["Familia 2 — AVENAS Y SEMOLAS"]
  end
  D1 --> R3
```

## Rubro 4 — CALDOS SOPAS PURE Y B
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R4["Rubro 4 — CALDOS SOPAS PURE Y B"]
    direction TB
    R4["Rubro 4 — CALDOS SOPAS PURE Y B"]
    R4 --> F4_1["Familia 1 — CALDOS"]
    R4 --> F4_2["Familia 2 — PURE"]
    R4 --> F4_3["Familia 3 — SOPAS"]
  end
  D1 --> R4
```

## Rubro 6 — PASTAS SECAS Y SALSAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R6["Rubro 6 — PASTAS SECAS Y SALSAS"]
    direction TB
    R6["Rubro 6 — PASTAS SECAS Y SALSAS"]
    R6 --> F6_1["Familia 1 — PASTAS LISTAS"]
    R6 --> F6_2["Familia 2 — PASTAS SECAS GUISERAS"]
    R6 --> F6_3["Familia 3 — PASTAS SECAS LARGAS"]
    R6 --> F6_4["Familia 4 — SALSAS"]
  end
  D1 --> R6
```

## Rubro 11 — SAL PIMIENTA Y ESPECI
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R11["Rubro 11 — SAL PIMIENTA Y ESPECI"]
    direction TB
    R11["Rubro 11 — SAL PIMIENTA Y ESPECI"]
    R11 --> F11_1["Familia 1 — ESPECIAS"]
    R11 --> F11_2["Familia 2 — SAL"]
  end
  D1 --> R11
```

## Rubro 12 — PANIFICADOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R12["Rubro 12 — PANIFICADOS"]
    direction TB
    R12["Rubro 12 — PANIFICADOS"]
    R12 --> F12_1["Familia 1 — INTEGRAL Y SALVADO"]
    R12 --> F12_2["Familia 2 — LACTEADOS"]
    R12 --> F12_3["Familia 3 — PAN PARA HAMBURGUESAS"]
    R12 --> F12_4["Familia 4 — PAN RALLADO Y REBOZAD"]
    R12 --> F12_5["Familia 5 — TOSTADAS Y GRISINES"]
  end
  D1 --> R12
```

## Rubro 16 — DESAYUNO Y MERIENDA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R16["Rubro 16 — DESAYUNO Y MERIENDA"]
    direction TB
    R16["Rubro 16 — DESAYUNO Y MERIENDA"]
    R16 --> F16_1["Familia 1 — AZUCAR Y EDULCORANTES"]
    R16 --> F16_2["Familia 2 — BIZCOCHUELOS BUDINES"]
    R16 --> F16_3["Familia 3 — CACAO Y SABORIZANTES"]
    R16 --> F16_4["Familia 4 — CAFES"]
    R16 --> F16_5["Familia 5 — CEREALES"]
    R16 --> F16_6["Familia 6 — GALLETITAS DULCES"]
    R16 --> F16_7["Familia 7 — GALLETITAS SALADAS"]
    R16 --> F16_8["Familia 8 — LECHES"]
    R16 --> F16_9["Familia 9 — MERMELADAS Y JALEAS"]
    R16 --> F16_10["Familia 10 — PIONONOS"]
    R16 --> F16_11["Familia 11 — TES"]
    R16 --> F16_12["Familia 12 — YERBAS"]
  end
  D1 --> R16
```

## Rubro 19 — ADEREZOS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R19["Rubro 19 — ADEREZOS"]
    direction TB
    R19["Rubro 19 — ADEREZOS"]
    R19 --> F19_1["Familia 1 — KETCHUP"]
    R19 --> F19_2["Familia 2 — MAYONESAS"]
    R19 --> F19_3["Familia 3 — MOSTAZAS"]
    R19 --> F19_4["Familia 4 — OTROS CONDIMENTOS"]
    R19 --> F19_5["Familia 5 — SALSAS FRIAS"]
    R19 --> F19_6["Familia 6 — SALSAS GOLF"]
  end
  D1 --> R19
```

## Rubro 24 — CONSERVAS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R24["Rubro 24 — CONSERVAS"]
    direction TB
    R24["Rubro 24 — CONSERVAS"]
    R24 --> F24_1["Familia 1 — CONSERVAS DE CARNE"]
    R24 --> F24_2["Familia 2 — CONSERVAS DE FRUTAS"]
    R24 --> F24_3["Familia 3 — CONSERVAS DE PESCADO"]
    R24 --> F24_4["Familia 4 — CONSERVAS DE VERDURAS"]
  end
  D1 --> R24
```

## Rubro 30 — SNACKS
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R30["Rubro 30 — SNACKS"]
    direction TB
    R30["Rubro 30 — SNACKS"]
    R30 --> F30_1["Familia 1 — FRUTAS SECAS Y DISECA"]
    R30 --> F30_2["Familia 2 — MANI"]
    R30 --> F30_3["Familia 3 — NACHOS"]
    R30 --> F30_4["Familia 4 — PALITOS DE MAIZ"]
    R30 --> F30_5["Familia 5 — PALITOS SALADOS"]
    R30 --> F30_6["Familia 6 — PAPAS FRITAS"]
    R30 --> F30_7["Familia 7 — POCHOCLOS"]
    R30 --> F30_8["Familia 8 — SNACKS"]
  end
  D1 --> R30
```

## Rubro 31 — GOLOSINAS Y CHOCOLATE
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R31["Rubro 31 — GOLOSINAS Y CHOCOLATE"]
    direction TB
    R31["Rubro 31 — GOLOSINAS Y CHOCOLATE"]
    R31 --> F31_1["Familia 1 — ALFAJORES"]
    R31 --> F31_2["Familia 2 — BOCADITOS Y POSTRES"]
    R31 --> F31_3["Familia 3 — BOMBONES"]
    R31 --> F31_4["Familia 4 — CARAMELOS Y CHICLES"]
    R31 --> F31_5["Familia 5 — CHOCOLATES"]
    R31 --> F31_6["Familia 6 — TURRONES Y GRAGEAS"]
  end
  D1 --> R31
```

## Rubro 35 — PARA PREPARAR
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 12}, 'themeVariables': {'fontSize': '11px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R35["Rubro 35 — PARA PREPARAR"]
    direction TB
    R35["Rubro 35 — PARA PREPARAR"]
    R35 --> F35_1["Familia 1 — BIZCOCHUELOS BROWNIES"]
    R35 --> F35_2["Familia 2 — COMIDAS"]
    R35 --> F35_3["Familia 3 — FLANES"]
    R35 --> F35_4["Familia 4 — GELATINAS"]
    R35 --> F35_5["Familia 5 — HELADOS"]
    R35 --> F35_6["Familia 6 — MOUSSE"]
    R35 --> F35_7["Familia 7 — PASTELERIA"]
    R35 --> F35_8["Familia 8 — POSTRES"]
  end
  D1 --> R35
```

## Rubro 49 — MESA DULCE NAVIDEÑA
```mermaid
%%{init: {'flowchart': {'htmlLabels': true, 'curve': 'linear', 'nodeSpacing': 10, 'rankSpacing': 14}, 'themeVariables': {'fontSize': '12px'}}}%%
flowchart LR
  D1["Depto 1 — ALMACEN"]
  subgraph G_R49["Rubro 49 — MESA DULCE NAVIDEÑA"]
    direction TB
    R49["Rubro 49 — MESA DULCE NAVIDEÑA"]
    R49 --> F49_1["Familia 1 — MESA DULCE NAVIDEÑA"]
  end
  D1 --> R49
```
