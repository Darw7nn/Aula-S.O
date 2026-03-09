# Genealogia dos Sistemas Operacionais: Herança e Evolução

A história da computação é marcada por sistemas que não nasceram do zero, mas sim da necessidade de evoluir, adaptar ou simplificar arquiteturas anteriores. Este documento detalha cinco linhagens clássicas de Sistemas Operacionais, explorando o conceito de "Pai e Filho" na tecnologia.

---

## 1. A Busca pela Simplicidade: Multics (Pai) ➔ Unix (Filho)

### O Pai: Multics
![Logo do Multics](https://via.placeholder.com/150?text=Imagem+do+Multics)
* **Ano de Lançamento:** 1969 (Início do desenvolvimento em 1964).
* **Por que foi criado:** O *Multiplexed Information and Computing Service* foi um projeto do MIT, Bell Labs e General Electric. O objetivo era criar um sistema operacional de tempo compartilhado (time-sharing) massivo, funcionando como uma concessionária de energia para centenas de usuários simultâneos.

### O Filho: Unix
![Logo do Unix](https://via.placeholder.com/150?text=Imagem+do+Unix)
* **Ano de Lançamento:** 1971.
* **Por que foi criado:** O Multics tornou-se complexo e pesado. Ken Thompson e Dennis Ritchie queriam um ambiente mais simples para continuar suas pesquisas no Bell Labs. Assim nasceu o Unix, focado em ferramentas modulares e escrito em linguagem **C**, o que o tornou altamente portátil.

---

## 2. A Revolução dos Microcomputadores: CP/M (Pai) ➔ MS-DOS (Filho)

### O Pai: CP/M
![Logo do CP/M](https://via.placeholder.com/150?text=Imagem+do+CPM)
* **Ano de Lançamento:** 1974.
* **Por que foi criado:** Criado por Gary Kildall para ser um sistema operacional padrão para a indústria de microcomputadores de 8 bits, abstraindo o hardware e permitindo que o mesmo software rodasse em máquinas diferentes.

### O Filho: MS-DOS
![Logo do MS-DOS](https://via.placeholder.com/150?text=Imagem+do+MS-DOS)
* **Ano de Lançamento:** 1981.
* **Por que foi criado:** A IBM precisava de um sistema para o IBM PC. A Microsoft comprou o **QDOS**, que era essencialmente um clone de 16 bits do CP/M, refinou seu código, introduziu o sistema de arquivos FAT e o lançou como MS-DOS.

---

## 3. Da Sala de Aula para o Mundo: Minix (Pai) ➔ Linux (Filho)

### O Pai: Minix
![Logo do Minix](https://via.placeholder.com/150?text=Imagem+do+Minix)
* **Ano de Lançamento:** 1987.
* **Por que foi criado:** O professor Andrew S. Tanenbaum criou o Minix (baseado em microkernel) com propósitos puramente educacionais, para que seus alunos pudessem estudar o código-fonte de um sistema operacional completo.

### O Filho: Linux
![Logo do Linux](https://via.placeholder.com/150?text=Imagem+do+Linux)
* **Ano de Lançamento:** 1991.
* **Por que foi criado:** Linus Torvalds usava o Minix, mas queria algo que não tivesse restrições acadêmicas e aproveitasse o poder do processador 386. Ele usou o Minix como inspiração inicial para compilar seu próprio kernel monolítico, que se tornaria 100% código aberto.

---

## 4. O Retorno do Rei: FreeBSD / Mach (Pais) ➔ macOS (Filho)

### Os Pais: FreeBSD e Mach (via NeXTSTEP)
![Logo do FreeBSD e Mach](https://via.placeholder.com/150?text=Imagem+FreeBSD/Mach)
* **Ano de Lançamento:** Mach (1985), FreeBSD (1993).
* **Por que foram criados:** O Mach era uma pesquisa de microkernel, e o FreeBSD uma versão robusta do Unix. A empresa NeXT, de Steve Jobs, combinou essas tecnologias para criar o poderoso NeXTSTEP.

### O Filho: macOS (antigo Mac OS X)
![Logo do macOS](https://via.placeholder.com/150?text=Imagem+do+macOS)
* **Ano de Lançamento:** 2001.
* **Por que foi criado:** A Apple precisava modernizar seus sistemas clássicos. Ao comprar a NeXT, usaram o núcleo baseado em Mach/FreeBSD (batizado de Darwin) e adicionaram uma interface gráfica moderna e fluida, criando o macOS.

---

## 5. Democratizando o Open Source: Debian (Pai) ➔ Ubuntu (Filho)

### O Pai: Debian
![Logo do Debian](https://via.placeholder.com/150?text=Imagem+do+Debian)
* **Ano de Lançamento:** 1993.
* **Por que foi criado:** Ian Murdock criou o Debian para ser construído por uma comunidade, focado na filosofia do Software Livre e conhecido por ser um dos sistemas mais estáveis para servidores.

### O Filho: Ubuntu
![Logo do Ubuntu](https://via.placeholder.com/150?text=Imagem+do+Ubuntu)
* **Ano de Lançamento:** 2004.
* **Por que foi criado:** A empresa Canonical usou a base sólida do Debian para criar um sistema mais amigável, focado no usuário doméstico ("Linux for Human Beings"), com instalação fácil, ciclo de atualização fixo e drivers prontos para uso.

---

## Tabela Comparativa Geral

| Pai (Inspiração/Base) | Lançamento | Filho (Evolução/Derivação) | Lançamento | Principal Mudança Arquitetônica ou Filosófica |
| :--- | :---: | :--- | :---: | :--- |
| **Multics** | 1969 | **Unix** | 1971 | De monolítico e complexo para modular, simples e escrito em C. |
| **CP/M** | 1974 | **MS-DOS** | 1981 | Transição de 8-bits para 16-bits e adoção do sistema de arquivos FAT. |
| **Minix** | 1987 | **Linux** | 1991 | De microkernel educacional restrito para kernel monolítico de código aberto. |
| **FreeBSD / Mach** | 1989 / 1993| **macOS** | 2001 | Integração de um robusto kernel UNIX com uma interface gráfica para o consumidor final. |
| **Debian** | 1993 | **Ubuntu** | 2004 | De sistema voltado a servidores para um ambiente Desktop amigável. |

---

## Referências Bibliográficas

1. **Tanenbaum, A. S., & Bos, H. (2014).** *Modern Operating Systems* (4th ed.). Pearson. 
2. **Silberschatz, A., Galvin, P. B., & Gagne, G. (2018).** *Operating System Concepts* (10th ed.). Wiley.
3. **Raymond, E. S. (2003).** *The Art of UNIX Programming*. Addison-Wesley Professional. 
4. **Isaacson, W. (2011).** *Steve Jobs*. Simon & Schuster. 
5. **Documentações Oficiais:** [História do Debian](https://www.debian.org/doc/manuals/project-history/), [Ubuntu Philosophy](https://ubuntu.com/community/ethos).
