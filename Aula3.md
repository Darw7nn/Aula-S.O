<div align="center">
  <h1>Relatório de Arquitetura: Genealogia e Evolução dos Sistemas Operacionais</h1>
  <p><em>Análise técnica da evolução estrutural de sistemas legados para ecossistemas modernos.</em></p>
  <hr>
</div>

## 1. A Busca pela Simplicidade e Portabilidade

| ![Multics](https://img.shields.io/badge/Multics-101010?style=for-the-badge) | ➔ | ![Unix](https://img.shields.io/badge/Unix-222222?style=for-the-badge&logo=linux&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (Multics - 1969):** Arquitetura monolítica em mainframes para *time-sharing* massivo. Altamente complexo e acoplado ao hardware específico da época.
* **O Filho (Unix - 1971):** Projetado por Ken Thompson e Dennis Ritchie no Bell Labs como uma antítese à complexidade do Multics. Introduziu o conceito de ferramentas modulares (utilitários que fazem apenas uma coisa, interligados via *pipes*) e o sistema hierárquico de arquivos. Foi reescrito em **C**, garantindo portabilidade para diferentes arquiteturas de processadores.

<br>

## 2. A Revolução dos Microcomputadores de 16-bits

| ![CP/M](https://img.shields.io/badge/CP%2FM-005B9F?style=for-the-badge) | ➔ | ![MS-DOS](https://img.shields.io/badge/MS--DOS-000000?style=for-the-badge&logo=windows-terminal&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (CP/M - 1974):** O primeiro padrão real para microcomputadores de 8-bits. Utilizava o *Control Program/Monitor* para isolar o software do hardware subjacente (BIOS primitive).
* **O Filho (MS-DOS - 1981):** A IBM exigiu um SO de 16-bits para o IBM PC. A Microsoft adquiriu o QDOS (um clone estrutural do CP/M), aprimorando seu subsistema de discos com a introdução da **Tabela de Alocação de Arquivos (FAT)**, permitindo maior velocidade e armazenamento.

<br>

## 3. O Paradigma Corporativo de Alta Confiabilidade

| ![VMS](https://img.shields.io/badge/VMS-004B87?style=for-the-badge) | ➔ | ![Windows NT](https://img.shields.io/badge/Windows_NT-0078D6?style=for-the-badge&logo=windows&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (VMS - 1977):** Desenvolvido pela Digital Equipment Corporation (DEC), era o estado-da-arte em sistemas operacionais corporativos de alta disponibilidade, com multitarefa preemptiva real e gerenciamento de memória virtual avançado.
* **O Filho (Windows NT - 1993):** A Microsoft construiu um sistema robusto para substituir a base do MS-DOS. O **Windows NT** (New Technology) herdou os conceitos de segurança, HAL (*Hardware Abstraction Layer*) e permissões do VMS. O kernel NT é a base do Windows moderno.

<br>

## 4. O Triunfo do Código Aberto Colaborativo

| ![Minix](https://img.shields.io/badge/Minix-005192?style=for-the-badge) | ➔ | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| :---: | :---: | :---: |

* **O Pai (Minix - 1987):** Sistema de código aberto acadêmico baseado em **Microkernel** (núcleo mínimo focado em passagem de mensagens, com drivers rodando em *user space* para evitar falhas totais do sistema).
* **O Filho (Linux - 1991):** Linus Torvalds utilizou o Minix como inspiração e ambiente de compilação, mas divergiu arquitetonicamente ao criar um **Kernel Monolítico** (drivers e núcleo dividem o mesmo espaço de memória) focado em máxima performance.

<br>

## 5. A Engenharia de Desktop Baseada em Servidor

| ![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white) | ➔ | ![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (FreeBSD/Mach - 1993):** O microkernel Mach (foco em multiprocessamento) e o FreeBSD (foco em redes extremas e estabilidade) serviram como fundação para a infraestrutura de código aberto da época.
* **O Filho (macOS - 2001):** Após a aquisição da NeXT, a Apple fundiu essas tecnologias no projeto *Darwin*. O macOS introduziu um kernel híbrido (XNU) que combina a flexibilidade do Mach com a estabilidade do FreeBSD, com a interface gráfica *Aqua* por cima.

<br>

## 6. A Democratização do Linux Desktop

| ![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white) | ➔ | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (Debian - 1993):** Distribuição gerida por comunidade, famosa pela ferramenta de gerenciamento de pacotes e extrema rigidez em lançar atualizações apenas quando "absolutamente prontas e sem falhas".
* **O Filho (Ubuntu - 2004):** A Canonical derivou o ramo do Debian focando em usabilidade para o usuário comum. Adicionou instaladores gráficos, cronograma de lançamentos fixo e drivers proprietários pré-inclusos.

<br>

## 7. A Bifurcação Corporativa Open Source

| ![RHEL](https://img.shields.io/badge/Red_Hat_Ent-EE0000?style=for-the-badge&logo=redhat&logoColor=white) | ➔ | ![CentOS](https://img.shields.io/badge/CentOS-262577?style=for-the-badge&logo=centos&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (Red Hat Enterprise Linux - 2000):** O padrão ouro corporativo pago para data centers. Oferece suporte técnico vitalício e extrema homologação de hardware, sob licenciamento comercial.
* **O Filho (CentOS - 2004):** Desenvolvedores independentes pegavam o código-fonte que a Red Hat liberava, removiam as marcas registradas e recompilavam um sistema idêntico e totalmente gratuito para uso corporativo.

<br>

## 8. A Migração do Desktop para o Mobile

| ![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white) | ➔ | ![iOS](https://img.shields.io/badge/iOS-5FC9F8?style=for-the-badge&logo=ios&logoColor=white) |
| :---: | :---: | :---: |

* **O Pai (macOS/Darwin - 2001):** Sistema operacional de classe desktop completo, suporte a múltiplas janelas, multitarefa solta, acesso total ao terminal e sistema de arquivos pelo usuário.
* **O Filho (iOS - 2007):** A Apple usou o mesmo Kernel XNU do macOS para o iPhone, mas introduziu isolamento profundo (*Sandboxing*), removeu o acesso ao sistema de arquivos e introduziu a interface *Multi-Touch*.

<br>

---

<div align="center">
  <h2>📋 Matriz Comparativa de Arquitetura</h2>
</div>

| Sistema Espelhado (Pai) | Derivação Estratégica (Filho) | Camada Alvo | Principal Alteração Arquitetural |
| :--- | :--- | :---: | :--- |
| **Multics** | **Unix** | `Mainframe → Minicomputador` | Remoção do acoplamento de hardware; adoção de C e modularidade. |
| **CP/M** | **MS-DOS** | `8-bit → 16-bit PC` | Otimização do sistema de disco com o subsistema FAT. |
| **VMS** | **Windows NT** | `Servidor Fechado → Desktop` | Abstração da camada de hardware (HAL) e sistema de permissões. |
| **Minix** | **Linux** | `Acadêmico → Produção` | Substituição de Microkernel por Kernel Monolítico focado em performance. |
| **FreeBSD / Mach**| **macOS** | `Servidor → Usuário Doméstico` | Adoção do núcleo híbrido XNU com interface gráfica avançada. |
| **Debian** | **Ubuntu** | `SysAdmins → Usuários Leigos` | Adição de drivers fechados, ciclo de atualização de 6 meses e GUI facilitada. |
| **RHEL (Red Hat)**| **CentOS** | `Enterprise Pago → Free Server` | Recompilação binária do código RHEL sem as restrições de marca registrada. |
| **macOS (Darwin)**| **iOS** | `Desktop → Dispositivo Móvel` | Implementação de Sandboxing, framework Touch e limitação de background. |

<br>
