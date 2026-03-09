<div align="center">
  
  ![Corporate Report](https://img.shields.io/badge/Documento-Whitepaper_Técnico-005B9F?style=for-the-badge&logo=googledocs&logoColor=white)
  ![Status](https://img.shields.io/badge/Status-Aprovado_para_Revisão-success?style=for-the-badge)
  ![Arquitetura](https://img.shields.io/badge/Escopo-Arquitetura_de_Sistemas-8A2BE2?style=for-the-badge&logo=databricks&logoColor=white)

  <h1>Relatório de Arquitetura: Genealogia e Evolução dos Sistemas Operacionais</h1>
  <p><em>Análise técnica do impacto de mercado e evolução estrutural de sistemas legados para ecossistemas modernos.</em></p>
  <hr>
</div>

## 📌 Sumário Executivo

A engenharia de sistemas operacionais raramente adota o desenvolvimento *greenfield* (do zero) devido ao alto custo computacional e de estabilidade. Este relatório mapeia **8 linhagens críticas** da história da computação, onde bases de código, filosofias ou arquiteturas de sistemas anteriores ("Pais") foram espelhadas, reescritas ou paralelizadas para originar os líderes de mercado atuais ("Filhos"). 

Além da arquitetura, analisamos o **impacto de mercado**, demonstrando como a adaptação da tecnologia para novos escopos (ex: de servidores para desktops, ou de desktops para mobile) resultou em explosões de escala de usuários.

---

## 1. A Busca pela Simplicidade e Portabilidade

| ![Multics](https://img.shields.io/badge/Legado_Multics-101010?style=for-the-badge) | ➔ | ![Unix](https://img.shields.io/badge/Evolução_Unix-222222?style=for-the-badge&logo=linux&logoColor=white) |
| :---: | :---: | :---: |

### Análise de Arquitetura
* **O Pai (Multics - 1969):** Arquitetura monolítica em mainframes para *time-sharing* massivo. Altamente complexo e acoplado ao hardware específico da época.
* **O Filho (Unix - 1971):** Projetado por Ken Thompson e Dennis Ritchie no Bell Labs como uma antítese à complexidade do Multics. Introduziu o conceito de ferramentas modulares (utilitários que fazem apenas uma coisa, interligados via *pipes*) e o sistema hierárquico de arquivos. Foi reescrito em **C**, garantindo portabilidade para diferentes arquiteturas de processadores.

### Comparativo de Escalabilidade (Estimativa Histórica de Usuários)
```mermaid
xychart-beta
  title "Escala de Usuários Ativos (Fim da Década de 70)"
  x-axis ["Multics (Máquinas Dedicadas)", "Unix (Ambientes Acadêmicos/Pesquisa)"]
  y-axis "Milhares de Usuários" 0 --> 100
  bar [5, 85]
