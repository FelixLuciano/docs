---
layout: home

hero:
  name: Insper RISC-V
  text: Documentação do Projeto
  tagline: CTI Renato Archer e Insper Capstone
  image:
    light: /images/RISC-V_Stacked_Color.svg
    dark: /images/RISC-V_Stacked_White_Yellow.svg
    alt: RISC-V
  actions:
    - text: Projeto
      link: https://github.com/insper-riscv/core/
    - text: Introdução
      link: /guide/
      theme: alt
    - text: Arquitetura
      link: /reference/isa/
      theme: alt

features:
  - title: RISC-V Bare Metal
    details: Especificação de arquitetura aberta, modular e hierárquico habilitado para sistemas operacionais em tempo real.
    link: https://wiki.riscv.org
    linkText: Saiba mais
  - title: Visual Studio Code e Docker
    details: Editor de texto customizável e ambiente de desenvolvimento conteinerizado pré-configurado.
    link: https://code.visualstudio.com/docs/devcontainers/containers
    linkText: Saiba mais
  - title: Intel® Quartus® Prime Lite
    details: Plataforma de desenvolvimento para placas FPGA Intel inclusa programável por servidor JTAG.
    link: https://www.intel.com.br/content/www/br/pt/products/details/fpga/development-tools/quartus-prime.html
    linkText: Saiba mais
  - title: Cocotb e Pytest
    details: Framework de testes unitários e de integração para linguagens HDL
    link: https://cocotb.org/
    linkText: Saiba mais
  - title: GHDL + Yosys
    details: Framework de Síntese de hardware Open-Source
    link: https://ghdl.github.io/ghdl/about.html
    linkText: Saiba mais
  - title: Wavedrom e Netlistsvg
    details: Ferramentas de visualização de síntese e simulação
    link: https://wavedrom.com/
    linkText: Saiba mais

org:
  - name: CTI Renato Archer
    title: Realização
    avatar: /docs/images/members/cti-renato-archer.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/company/cti-renato-archer/
  - name: Saulo Finco
    title: Mentor
    avatar: /docs/images/members/saulofinco.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/saulofinco
  - name: Rafael Corsi
    title: Orientador
    avatar: /docs/images/members/rafael-corsi-ferrão-624238116.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/rafael-corsi-ferrão-624238116/
      - icon: github
        link: https://github.com/rafaelcorsi

members24_1:
  - name: Giancarlo Ruggiero
    title: Desenvolvedor
    avatar: /docs/images/members/giancarlo-vr.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/giancarlo-vr/
      - icon: github
        link: https://github.com/gianvr
  - name: Luciano Felix
    title: Desenvolvedor
    avatar: /docs/images/members/luciano-felix.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/luciano-felix/
      - icon: github
        link: https://github.com/FelixLuciano
  - name: Tiago Seixas
    title: Desenvolvedor
    avatar: /docs/images/members/tiago-seixas-bb9614254.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/tiago-seixas-bb9614254/
      - icon: github
        link: https://github.com/TiagoSeixas2103

members24_2:
  - name: Arthur Barreto
    title: Desenvolvedor
    avatar: /docs/images/members/arthur-martins-de-souza-barreto.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/arthur-martins-de-souza-barreto/
      - icon: github
        link: https://github.com/Arthur-Barreto
  - name: Eduardo Barros
    title: Desenvolvedor
    avatar: /docs/images/members/eduardosmb.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/eduardosmb/
      - icon: github
        link: https://github.com/eduardosmb
  - name: Rodrigo Patelli
    title: Desenvolvedor
    avatar: /docs/images/members/rodrigo-anciães-patelli.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/rodrigo-anciães-patelli/
      - icon: github
        link: https://github.com/RodrigoAnciaes
  - name: Vitor Assis
    title: Desenvolvedor
    avatar: /docs/images/members/victorlga.jpg
    links:
      - icon: linkedin
        link: https://www.linkedin.com/in/victorlga/
      - icon: github
        link: https://github.com/victorlga

---

<script setup>
import { VPTeamMembers } from 'vitepress/theme'
</script>

<!--@include: @/report/2024_1/.resumo.md-->

## Organização

<VPTeamMembers :members="$frontmatter.org" />

## Equipe Capstone 2024.2

[<Badge type="tip" text="Paper ⧉"/>](/documents/2024_2-report.pdf)

<VPTeamMembers :members="$frontmatter.members24_2" size="small" />

## Equipe Capstone 2024.1

[<Badge type="tip" text="Saiba mais ⧉"/>](https://www.insper.edu.br/pt/noticias/2024/5/alunos-desenvolvem-processador-para-o-ministerio-da-ciencia--tec)
[<Badge type="tip" text="Relatório ⧉"/>](/report/2024_1/)

<VPTeamMembers :members="$frontmatter.members24_1" size="small" />
