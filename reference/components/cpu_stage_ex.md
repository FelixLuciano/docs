---
outline: 2
---

# EX - Executa

## Topologia

![alt text](/public/images/reference/report_components/cpu_stage_ex.drawio.svg)

## Interface genérica

### `GENERATE_REGISTERS` <Badge type="neutral" text="GENERIC" />

Define geração de registradores de pipeline.

- Tipo: `boolean `
- Padrão: `TRUE`

## Interface de portas

### `clock` <Badge type="success" text="INPUT" />

Entrada do sinal de clock.

- Tipo: `std_logic`

::: danger TO DO

Work in progress.

:::

## Usagem

::: danger TO DO

Work in progress.

:::

## Diagrama RTL

<pan-container>

![Diagrama de RTL do Decodifica Instrução](/images/reference/components/stage_ex_netlist.svg){.w-full .dark-invert}

</pan-container>

## Casos de teste

::: danger TO DO

```md
### Caso 1 <Badge type="info" text="tb_stage_ex_case_1" />

Forma de onda:

<pan-container :grid="false">

![Forma de onda do caso de teste 1 do Decodifica Instrução](/images/reference/components/tb_stage_ex_case_1.svg){.w-full .dark-invert}

</pan-container>

```

:::