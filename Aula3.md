<div align="center">
  <h1>Genealogia dos Sistemas Operacionais: Herança e Evolução</h1>
  <p><em>A história da computação é marcada por sistemas que não nasceram do zero, mas sim da necessidade de evoluir, adaptar ou simplificar arquiteturas anteriores.</em></p>
  <hr>
</div>

## 1. A Busca pela Simplicidade

A transição de mainframes gigantescos para sistemas mais ágeis e portáteis.

| <img src="https://img.shields.io/badge/Multics-000000?style=for-the-badge&logo=linux&logoColor=white" width="150" /> | ➔ | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Official_UNIX_logo.svg/200px-Official_UNIX_logo.svg.png" width="120" /> |
| :---: | :---: | :---: |
| **O Pai: Multics** | | **O Filho: Unix** |

* **Multics (1969):** O *Multiplexed Information and Computing Service* foi um projeto do MIT, Bell Labs e General Electric. O objetivo era criar um sistema operacional de tempo compartilhado (*time-sharing*) massivo, funcionando como uma concessionária de energia para centenas de usuários simultâneos.
* **Unix (1971):** O Multics tornou-se complexo e pesado. Ken Thompson e Dennis Ritchie queriam um ambiente mais simples para continuar suas pesquisas no Bell Labs. Assim nasceu o Unix, focado em ferramentas modulares e escrito na linguagem **C**, o que o tornou altamente portátil e o grande pilar da computação moderna.

<br>

## 2. A Revolução dos Microcomputadores

A mudança dos processadores de 8-bits para 16-bits e o início dos computadores pessoais.

| <img src="https://img.shields.io/badge/CP%2FM--80-005B9F?style=for-the-badge&logo=microchip&logoColor=white" width="130" /> | ➔ | <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f0/Microsoft_DOS.svg/200px-Microsoft_DOS.svg.png" width="150" /> |
| :---: | :---: | :---: |
| **O Pai: CP/M** | | **O Filho: MS-DOS** |

* **CP/M (1974):** Criado por Gary Kildall para ser um sistema operacional padrão para a indústria de microcomputadores de 8 bits, abstraindo o hardware e permitindo que o mesmo software rodasse em máquinas de marcas diferentes.
* **MS-DOS (1981):** A IBM precisava de um sistema para o IBM PC. A Microsoft comprou o **QDOS**, que era essencialmente um clone de 16 bits do CP/M, refinou seu código, introduziu o revolucionário sistema de arquivos FAT e o lançou como MS-DOS.

<br>

## 3. Da Sala de Aula para o Mundo

A transição de um núcleo restrito focado no ensino para o maior kernel de código aberto do planeta.

| <img src="https://upload.wikimedia.org/wikipedia/en/0/03/Minix3_Logo.png" width="120" /> | ➔ | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" width="100" /> |
| :---: | :---: | :---: |
| **O Pai: Minix** | | **O Filho: Linux** |

* **Minix (1987):** O professor Andrew S. Tanenbaum criou o Minix (baseado em arquitetura de microkernel) com propósitos puramente educacionais, para que seus alunos pudessem estudar o código-fonte de um sistema operacional completo.
* **Linux (1991):** Linus Torvalds usava o Minix, mas queria algo que não tivesse restrições acadêmicas e aproveitasse o poder do processador 386. Ele usou o Minix como inspiração inicial e ambiente de desenvolvimento para compilar seu próprio kernel monolítico.

<br>

## 4. O Retorno do Rei

A fusão de estabilidade de servidores robustos com interfaces gráficas de alto nível.

| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/freebsd/freebsd-original.svg" width="100" /> | ➔ | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apple/apple-original.svg" width="90" /> |
| :---: | :---: | :---: |
| **Os Pais: FreeBSD / Mach** | | **O Filho: macOS** |

* **FreeBSD e Mach (1985/1993):** O Mach era uma pesquisa de microkernel, e o FreeBSD uma versão robusta e de altíssima performance derivada do Unix. A empresa NeXT, fundada por Steve Jobs, combinou essas tecnologias para criar o formidável *NeXTSTEP*.
* **macOS (2001):** A Apple precisava modernizar seus sistemas clássicos que estavam obsoletos. Ao comprar a NeXT, usaram o núcleo baseado em Mach/FreeBSD (batizado de *Darwin*) e adicionaram a interface gráfica fluida *Aqua*, criando a base do que hoje é o macOS.

<br>

## 5. Democratizando o Open Source

O esforço para transformar sistemas de servidores voltados para *experts* em ambientes *desktop* amigáveis.

| <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/debian/debian-original.svg" width="100" /> | ➔ | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" width="100" /> |
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
</div>* **Ano de Lançamento:** 1987.
* **Por que foi criado:** O professor Andrew S. Tanenbaum criou o Minix (baseado em microkernel) com propósitos puramente educacionais, para que seus alunos pudessem estudar o código-fonte de um sistema operacional completo.

### 🐧 O Filho: Linux
![Logo do Linux](imagens/linux.png)
* **Ano de Lançamento:** 1991.
* **Por que foi criado:** Linus Torvalds usava o Minix, mas queria algo que não tivesse restrições acadêmicas e aproveitasse o poder do processador 386. Ele usou o Minix como inspiração inicial para compilar seu próprio kernel monolítico, que se tornaria 100% código aberto.

---

<div align="center">
  <img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/54fb7eef-b1e8-41dc-be97-57e4180b3b24" width="400">
</div>

## 4. O Retorno do Rei: FreeBSD / Mach (Pais) ➔ macOS (Filho)

### ⚙️ Os Pais: FreeBSD e Mach (via NeXTSTEP)
![Logo do FreeBSD e Mach](imagens/freebsd.png)
* **Ano de Lançamento:** Mach (1985), FreeBSD (1993).
* **Por que foram criados:** O Mach era uma pesquisa de microkernel, e o FreeBSD uma versão robusta do Unix. A empresa NeXT, de Steve Jobs, combinou essas tecnologias para criar o poderoso NeXTSTEP.

### 🍎 O Filho: macOS (antigo Mac OS X)
![Logo do macOS](imagens/macos.png)
* **Ano de Lançamento:** 2001.
* **Por que foi criado:** A Apple precisava modernizar seus sistemas clássicos. Ao comprar a NeXT, usaram o núcleo baseado em Mach/FreeBSD (batizado de Darwin) e adicionaram uma interface gráfica moderna e fluida (Aqua), criando o macOS.

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212750680-266fa8aa-39f1-4e8b-8873-7181dbaf3d7c.gif" width="400">
</div>

## 5. Democratizando o Open Source: Debian (Pai) ➔ Ubuntu (Filho)

### 🛠️ O Pai: Debian
![Logo do Debian](imagens/debian.png)
* **Ano de Lançamento:** 1993.
* **Por que foi criado:** Ian Murdock criou o Debian para ser construído por uma comunidade, focado na filosofia do Software Livre e conhecido por ser um dos sistemas mais estáveis para servidores.

### 🌍 O Filho: Ubuntu
![Logo do Ubuntu](imagens/ubuntu.png)
* **Ano de Lançamento:** 2004.
* **Por que foi criado:** A empresa Canonical usou a base sólida do Debian para criar um sistema mais amigável, focado no usuário doméstico ("Linux for Human Beings"), com instalação fácil, ciclo de atualização fixo e drivers prontos para uso.

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/219923809-b86dc415-a0c2-4a38-bc88-ad6cf06395a8.gif" width="300">
  <h2>Tabela Comparativa Geral</h2>
</div>

| Pai (Inspiração/Base) | Lançamento | Filho (Evolução/Derivação) | Lançamento | Principal Mudança Arquitetônica ou Filosófica |
| :--- | :---: | :--- | :---: | :--- |
| **Multics** | 1969 | **Unix** | 1971 | De monolítico e complexo para modular, simples e escrito em C. |
| **CP/M** | 1974 | **MS-DOS** | 1981 | Transição de 8-bits para 16-bits e adoção do sistema de arquivos FAT. |
| **Minix** | 1987 | **Linux** | 1991 | De microkernel educacional restrito para kernel monolítico de código aberto. |
| **FreeBSD / Mach** | 1989 / 1993| **macOS** | 2001 | Integração de um robusto kernel UNIX com uma interface gráfica para o consumidor final. |
| **Debian** | 1993 | **Ubuntu** | 2004 | De sistema voltado a servidores para um ambiente Desktop amigável. |

---

## 📚 Referências Bibliográficas

1. **Tanenbaum, A. S., & Bos, H. (2014).** *Modern Operating Systems* (4th ed.). Pearson. 
2. **Silberschatz, A., Galvin, P. B., & Gagne, G. (2018).** *Operating System Concepts* (10th ed.). Wiley.
3. **Raymond, E. S. (2003).** *The Art of UNIX Programming*. Addison-Wesley Professional. 
4. **Isaacson, W. (2011).** *Steve Jobs*. Simon & Schuster. 
5. **Documentações Oficiais:** [História do Debian](https://www.debian.org/doc/manuals/project-history/), [Ubuntu Philosophy](https://ubuntu.com/community/ethos).

<br>

<div align="center">
  <h3><img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="30" /> Obrigado por visitar este repositório!</h3>
</div>
