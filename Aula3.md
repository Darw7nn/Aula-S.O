<div align="center">
  <h1>Genealogia dos Sistemas Operacionais: Herança e Evolução</h1>
  <p><em>A história da computação é marcada por sistemas que não nasceram do zero, mas sim da necessidade de evoluir, adaptar ou simplificar arquiteturas anteriores.</em></p>
  <hr>
</div>

## 1. A Busca pela Simplicidade

A transição de mainframes gigantescos para sistemas mais ágeis e portáteis.

| ![Multics](https://img.shields.io/badge/Multics-101010?style=for-the-badge) | ➔ | ![Unix](https://img.shields.io/badge/Unix-222222?style=for-the-badge) |
| :---: | :---: | :---: |
| **O Pai: Multics** | | **O Filho: Unix** |

* **Multics (1969):** O *Multiplexed Information and Computing Service* foi um projeto do MIT, Bell Labs e General Electric. O objetivo era criar um sistema operacional de tempo compartilhado (*time-sharing*) massivo, funcionando como uma concessionária de energia para centenas de usuários simultâneos.
* **Unix (1971):** O Multics tornou-se complexo e pesado. Ken Thompson e Dennis Ritchie queriam um ambiente mais simples para continuar suas pesquisas no Bell Labs. Assim nasceu o Unix, focado em ferramentas modulares e escrito na linguagem **C**, o que o tornou altamente portátil e o grande pilar da computação moderna.

<br>

## 2. A Revolução dos Microcomputadores

A mudança dos processadores de 8-bits para 16-bits e o início dos computadores pessoais.

| ![CP/M](https://img.shields.io/badge/CP%2FM-005B9F?style=for-the-badge) | ➔ | ![MS-DOS](https://img.shields.io/badge/MS--DOS-000000?style=for-the-badge&logo=windows-terminal&logoColor=white) |
| :---: | :---: | :---: |
| **O Pai: CP/M** | | **O Filho: MS-DOS** |

* **CP/M (1974):** Criado por Gary Kildall para ser um sistema operacional padrão para a indústria de microcomputadores de 8 bits, abstraindo o hardware e permitindo que o mesmo software rodasse em máquinas de marcas diferentes.
* **MS-DOS (1981):** A IBM precisava de um sistema para o IBM PC. A Microsoft comprou o **QDOS**, que era essencialmente um clone de 16 bits do CP/M, refinou seu código, introduziu o revolucionário sistema de arquivos FAT e o lançou como MS-DOS.

<br>

## 3. Da Sala de Aula para o Mundo

A transição de um núcleo restrito focado no ensino para o maior kernel de código aberto do planeta.

| ![Minix](https://img.shields.io/badge/Minix-005192?style=for-the-badge) | ➔ | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| :---: | :---: | :---: |
| **O Pai: Minix** | | **O Filho: Linux** |

* **Minix (1987):** O professor Andrew S. Tanenbaum criou o Minix (baseado em arquitetura de microkernel) com propósitos puramente educacionais, para que seus alunos pudessem estudar o código-fonte de um sistema operacional completo.
* **Linux (1991):** Linus Torvalds usava o Minix, mas queria algo que não tivesse restrições acadêmicas e aproveitasse o poder do processador 386. Ele usou o Minix como inspiração inicial e ambiente de desenvolvimento para compilar seu próprio kernel monolítico.

<br>

## 4. O Retorno do Rei

A fusão de estabilidade de servidores robustos com interfaces gráficas de alto nível.

| ![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white) | ➔ | ![macOS](https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white) |
| :---: | :---: | :---: |
| **Os Pais: FreeBSD / Mach** | | **O Filho: macOS** |

* **FreeBSD e Mach (1985/1993):** O Mach era uma pesquisa de microkernel, e o FreeBSD uma versão robusta e de altíssima performance derivada do Unix. A empresa NeXT, fundada por Steve Jobs, combinou essas tecnologias para criar o formidável *NeXTSTEP*.
* **macOS (2001):** A Apple precisava modernizar seus sistemas clássicos que estavam obsoletos. Ao comprar a NeXT, usaram o núcleo baseado em Mach/FreeBSD (batizado de *Darwin*) e adicionaram a interface gráfica fluida *Aqua*, criando a base do que hoje é o macOS.

<br>

## 5. Democratizando o Open Source

O esforço para transformar sistemas de servidores voltados para *experts* em ambientes *desktop* amigáveis.

| ![Debian](https://img.shields.io/badge/Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white) | ➔ | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) |
| :---: | :---: | :---: |
| **O Pai: Debian** | | **O Filho: Ubuntu** |

* **Debian (1993):** Ian Murdock criou o Debian para ser construído por uma comunidade global, sendo regido estritamente pela filosofia do Software Livre e consagrando-se como um dos sistemas mais estáveis do mercado corporativo.
* **Ubuntu (2004):** A Canonical utilizou a base estrutural sólida do Debian para criar um sistema voltado para o usuário comum. Seu diferencial foi a instalação gráfica facilitada, ciclo de atualização previsível e drivers fechados pré-configurados.

<br>

---

<div align="center">
  <h2>📋 Tabela Comparativa de Arquitetura</h2>
</div>

| Herança | Lançamento | Derivação | Lançamento | Principal Mudança Arquitetônica ou Filosófica |
| :--- | :---: | :--- | :---: | :--- |
| **Multics** | 1969 | **Unix** | 1971 | De monolítico e altamente complexo para modular, simples e escrito em C. |
| **CP/M** | 1974 | **MS-DOS** | 1981 | Transição da arquitetura de 8-bits para 16-bits e adoção do sistema de arquivos FAT. |
| **Minix** | 1987 | **Linux** | 1991 | De microkernel educacional restrito para kernel monolítico de código aberto e alta performance. |
| **FreeBSD** | 1993 | **macOS** | 2001 | Integração de um robusto kernel UNIX (Darwin) com uma interface gráfica fluida para o consumidor final. |
| **Debian** | 1993 | **Ubuntu** | 2004 | De sistema voltado estritamente a administradores para um ambiente *Desktop* *user-friendly* (*Linux for Human Beings*). |

---

<div align="center">
  <p>📚 <em>Desenvolvido para fins de pesquisa e consolidação de conhecimentos em Arquitetura de Sistemas Operacionais.</em></p>
</div>
