# 📘 Guia Completo: Como criar um Computador Virtual com AntiLinux

Bem-vindo! Se você acha que testar um novo sistema no computador é perigoso ou muito complicado, este guia vai te mostrar que é tão simples quanto instalar um aplicativo no celular. Vamos usar uma "caixa de areia" digital segura para rodar o **AntiLinux**, um sistema incrivelmente leve e rápido, sem alterar absolutamente nada no seu computador atual.

---

## 🛠️ Parte 1: Como baixar e instalar o VirtualBox (A sua "Oficina")

<img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Virtualbox_logo.png" width="150" alt="Logo do VirtualBox">

O Oracle VirtualBox é o programa que vai criar o nosso computador virtual. Ele é totalmente gratuito e seguro.

### 1. Indo até a página oficial
* Abra o seu navegador de internet (Google Chrome, Edge, Firefox, etc.).
* Digite na barra de endereços lá em cima: **virtualbox.org** e aperte "Enter".
* Na página principal, você verá um botão grande em destaque (geralmente azul) escrito **"Download VirtualBox"**. Clique nele.

### 2. Escolhendo o arquivo certo
* O site vai carregar uma lista de opções. Como a maioria dos computadores usa o sistema Windows, clique no link escrito **"Windows hosts"**.
* O download vai começar automaticamente. Aguarde o arquivo terminar de baixar (ele vai direto para a sua pasta de "Downloads").

### 3. Instalando o programa
* Dê um clique duplo no arquivo que você acabou de baixar.
* Uma tela de instalação vai aparecer. O processo é muito simples: clique em **"Next"** (Avançar) nas primeiras telas.
* **Aviso importante:** Em um momento, surgirá uma tela com um alerta escrito "Warning: Network Interfaces". Não se preocupe! O programa está apenas avisando que sua conexão com a internet pode dar uma rápida piscada de alguns segundos para configurar a rede virtual. Clique em **"Yes"** (Sim) e depois em **"Install"** (Instalar).
* Se o Windows pedir permissão de administrador para fazer alterações no dispositivo, clique em "Sim".
* Quando terminar, clique em **"Finish"** (Concluir). O VirtualBox está instalado e pronto para uso!

---

## 📥 Parte 2: Como baixar o AntiLinux

Agora precisamos do sistema operacional em si.Ele vem em um formato de arquivo chamado **ISO**, que funciona como um "pen drive digital" ou um pacote de instalação contendo todo o sistema desejado pronto para ser descompactado e usado.

### 1. Acessando o site do sistema
* Abra o navegador novamente e digite **antixlinux.com** (o endereço oficial do projeto que estamos adotando como AntiLinux).
* No menu superior do site, procure e clique na aba **"Download"**.

### 2. Baixando o pacote ISO
* Você verá algumas opções de servidores (chamados de *mirrors* ou espelhos) para baixar. Escolha um servidor próximo a você (como os do Brasil, se houver na lista, ou os globais).
* Baixe a versão principal (geralmente chamada de "antiX-full"). O arquivo terminará obrigatoriamente com a extensão **.iso**.
* Aguarde o fim do download. Esse arquivo tem cerca de 1 a 2 GB, então pode levar alguns minutos dependendo da velocidade da sua internet.

---

## 🏗️ Parte 3: Construindo seu Computador Virtual

Com a oficina (VirtualBox) aberta e o pacote digital do sistema (ISO) em mãos, vamos montar a máquina.

1. Abra o VirtualBox e clique no ícone **"Novo"** (uma estrela azul ou símbolo de adição) para começar.
2. **Nome e Tipo:** No campo "Nome", digite **AntiLinux**. O programa automaticamente deve mudar o campo "Tipo" para **Linux**. Se não mudar sozinho, selecione manualmente a opção "Linux".
3. **Memória RAM (Desempenho):** O computador precisa de memória para rodar rápido e processar as informações.Mova a barrinha para escolher **2048 MB** (que equivale a 2 GB), que é a quantidade recomendada para sistemas leves.
4. **Disco Rígido (Armazenamento):** Deixe marcada a opção para criar um novo disco virtual (VHD) agora.Na tela de tamanho, arraste a barra para reservar um espaço de armazenamento entre **20 GB e 40 GB**. Clique em "Criar".

---

## 🚀 Parte 4: Ligando e Instalando o Sistema

Sua máquina virtual está fisicamente "montada", mas ela ainda está vazia por dentro. Vamos conectar aquele nosso "pen drive digital" (o arquivo ISO) e dar a partida.

### 1. Conectando o pacote de instalação
* Na tela principal do VirtualBox, clique uma vez sobre o seu recém-criado "AntiLinux" na lista à esquerda para selecioná-lo.
* Clique no botão **"Configurações"** (ícone de uma engrenagem).
* No menu lateral esquerdo dessa nova janela, clique em **"Armazenamento"**.
* No meio da tela, você verá um ícone de um disco escrito "Vazio". Clique nele.
* No canto direito, adicione o arquivo ISO como um drive. Para isso, clique em um pequeno ícone azul de disco e escolha **"Escolher um arquivo de disco..."**.
* Navegue até a pasta onde você baixou o arquivo **.iso** do AntiLinux (Parte 2), selecione-o e clique em "Abrir". Depois, clique em "OK" para salvar e fechar as configurações.

### 2. A Mágica Acontece
* Agora, com tudo pronto, basta clicar no botão **"Iniciar"** (uma seta verde) na tela principal do VirtualBox para dar boot na máquina virtual a partir desse disco.
* O seu novo computador virtual vai ligar dentro de uma janela! Ele fará a leitura daquele arquivo ISO automaticamente, abrindo a tela inicial do AntiLinux.
* A partir daqui, é só seguir as instruções visuais que aparecerem na tela da máquina virtual para finalizar a configuração de idioma, teclado e criar o seu usuário. Aproveite o seu novo sistema!
