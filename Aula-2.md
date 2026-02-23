# Resumo: Sistemas Operacionais Modernos (4ª Edição)
**Autor:** Andrew S. Tanenbaum, Herbert Bos
**Trecho:** Páginas 5 a 13
**Capítulo 1:** Introdução

---

## 1.1 O que é um Sistema Operacional?

É difícil definir exatamente o que é um sistema operacional (SO), pois ele executa diversas tarefas complexas. O livro aborda o SO sob duas perspectivas principais, que são fundamentais para entender seu propósito.

### 1.1.1 O Sistema Operacional como uma Máquina Estendida (Visão Top-Down)

A arquitetura de um computador (processador, memória, discos, interfaces de rede) é incrivelmente complexa e difícil de programar diretamente. 

* **O Problema do Hardware Nu:**
  * Programar diretamente no hardware exige o conhecimento de sinais elétricos, temporizadores e registradores físicos.
  * Exemplo: Ler um dado de um disco rígido (HDD) requer conhecer os parâmetros do controlador de disco, setores, trilhas, cilindros e o movimento mecânico do braço de leitura.

* **A Solução (Abstração):**
  * O Sistema Operacional atua como uma **camada de abstração** de software que esconde toda essa complexidade física.
  * Ele cria o conceito de **Máquina Estendida** (ou máquina virtual), que é muito mais fácil de entender e programar do que o hardware real.
  * Exemplo prático: Em vez de lidar com trilhas e setores magnéticos, o SO nos entrega a abstração maravilhosa chamada **"Arquivo"**.
  * Para o programador, basta usar comandos simples como `open`, `read`, `write` e `close`. O SO faz o "trabalho sujo" por trás das cortinas.

### 1.1.2 O Sistema Operacional como um Gerenciador de Recursos (Visão Bottom-Up)

A segunda visão desce o nível de abstração e foca no controle e na organização.

* **O Problema do Caos:**
  * Computadores modernos rodam dezenas de programas simultaneamente. 
  * Se dois programas tentarem enviar dados para a mesma impressora ao mesmo tempo, o resultado será uma página com textos misturados e ilegíveis.

* **A Solução (Gerenciamento):**
  * O SO atua como um árbitro ou gerente. Sua função é prover uma alocação ordenada e controlada dos processadores, memórias e dispositivos de Entrada/Saída (E/S).
  * Ele realiza o compartilhamento do hardware, conhecido como **Multiplexação**.

* **Tipos de Multiplexação:**
  1. **Multiplexação no Tempo:**
     * Os programas se revezam no uso de um recurso.
     * Exemplo: A CPU. O SO permite que o programa A use a CPU por alguns milissegundos, depois pausa o A e entrega a CPU para o programa B, e assim por diante.
  2. **Multiplexação no Espaço:**
     * O recurso é dividido fisicamente e distribuído entre os programas simultaneamente.
     * Exemplo: A Memória RAM. O SO divide a memória, colocando o programa A em uma parte e o programa B em outra parte separada e protegida.

---

## 1.2 A História dos Sistemas Operacionais

O desenvolvimento dos Sistemas Operacionais está diretamente ligado à evolução histórica das arquiteturas de hardware. Tanenbaum divide essa evolução em gerações.

### 1.2.1 A Primeira Geração (1945 - 1955): Válvulas e Painéis de Conexão

* **Características do Hardware:**
  * Computadores gigantescos (como o ENIAC), que usavam milhares de tubos de vácuo (válvulas).
  * Eram extremamente lentos, esquentavam muito e queimavam válvulas constantemente.
* **O Processo de Programação:**
  * **Não existiam linguagens de programação.** Tudo era programado em linguagem de máquina absoluta, conectando fios em grandes painéis de conexões (plugboards).
  * Uma mesma equipe de engenheiros projetava, construía, programava, operava e dava manutenção na máquina.
* **Sistema Operacional:**
  * **Não existia.** Todo o controle era feito manualmente e fisicamente pelos operadores.

### 1.2.2 A Segunda Geração (1955 - 1965): Transistores e Sistemas em Lote

* **Características do Hardware:**
  * Invenção do **Transistor**, que tornou as máquinas mais confiáveis e menores.
  * Surgimento dos Mainframes (computadores de grande porte) que ficavam trancados em salas refrigeradas.
  * Divisão de trabalho: Pela primeira vez, havia uma separação clara entre projetistas, construtores, operadores, programadores e pessoal de manutenção.
* **O Problema da Ociosidade:**
  * Programar agora era feito em cartões perfurados usando linguagens como FORTRAN.
  * O programador entregava os cartões ao operador. O operador colocava os cartões no leitor. O programa rodava e a saída era impressa.
  * O tempo que o operador humano levava andando pela sala para carregar as fitas e cartões deixava a caríssima CPU parada (ociosa).
* **A Solução: Sistemas em Lote (Batch Systems):**
  * Foi a primeira forma de sistema operacional (ex: FMS - Fortran Monitor System).
  * A ideia era juntar uma bandeja cheia de trabalhos (jobs) em uma fita magnética usando um computador menor e barato (como o IBM 1401).
  * Essa fita era levada para o computador principal e caro (como o IBM 7094), que lia a fita e executava um trabalho logo após o outro, **automaticamente**, sem interrupção humana.
  * A saída era gravada em outra fita, que depois era levada de volta ao computador menor para ser impressa.
  * **Objetivo principal:** Manter a CPU do computador principal trabalhando 100% do tempo.

### 1.2.3 A Terceira Geração (1965 - 1980): CIs e Multiprogramação

* **Características do Hardware:**
  * Uso de **Circuitos Integrados (CIs)**. Os computadores ficaram mais rápidos e com melhor custo-benefício.
  * A IBM unificou suas linhas de computadores comerciais (voltados para caracteres) e científicos (voltados para cálculos pesados) na famosa família **System/360**.
* **Surgimento do OS/360:**
  * Foi o sistema operacional projetado para rodar em todas as máquinas da família 360.
  * Era um software gigantesco e cheio de bugs, mas introduziu conceitos que usamos até hoje.
* **Multiprogramação:**
  * Nos sistemas em lote da 2ª geração, quando um programa precisava ler algo de uma fita magnética (operação de E/S), a CPU ficava parada esperando o dado chegar.
  * A Multiprogramação resolveu isso dividindo a memória física em várias **partições**.
  * Vários trabalhos ficavam carregados na memória ao mesmo tempo. Se o trabalho A estivesse esperando o disco, o SO imediatamente entregava a CPU para o trabalho B. A CPU parou de ficar ociosa durante operações de E/S.
* **Spooling (Simultaneous Peripheral Operation On Line):**
  * Eliminou a necessidade de carregar cartões em fitas magnéticas usando um computador menor.
  * O computador principal lia os cartões diretamente para o disco rígido e, assim que um trabalho terminava, o SO puxava o próximo trabalho direto do disco.
* **Tempo Compartilhado (Timesharing):**
  * A multiprogramação em lote era eficiente para a CPU, mas ruim para os programadores (se houvesse um erro de vírgula, o programador só descobriria horas depois, quando o papel fosse impresso).
  * O tempo compartilhado permitiu que múltiplos usuários se conectassem ao computador principal através de terminais (teclados e monitores simples).
  * O SO dividia o tempo da CPU em frações de segundo entre os usuários. Cada usuário tinha a ilusão de possuir o computador inteiro só para ele, permitindo **interatividade**.
  * O primeiro sistema de tempo compartilhado foi o **CTSS** (Compatible Time Sharing System), desenvolvido no MIT.
* **MULTICS e UNIX:**
  * O sucesso do CTSS levou ao ambicioso projeto **MULTICS** (Multiplexed Information and Computing Service), que visava criar uma máquina capaz de atender centenas de usuários simultaneamente, como uma rede de energia elétrica.
  * O projeto MULTICS não decolou comercialmente na época devido à complexidade.
  * Porém, um dos cientistas do projeto (Ken Thompson), pegou as ideias do MULTICS e criou uma versão menor e mais simples para um minicomputador PDP-7. Esse sistema acabou sendo batizado de **UNIX**.

---
**Fim do Resumo (Páginas 5 a 13)**
