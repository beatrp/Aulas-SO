# Manual: Instalação do Oracle VirtualBox e Configuração de Máquina Virtual com Windows 7

## 1. Introdução

Este manual descreve **passo a passo** como:

- Baixar o Oracle VirtualBox
- Instalar o VirtualBox no computador
- Baixar uma imagem ISO do Windows 7
- Criar uma máquina virtual
- Configurar a ISO para instalar o Windows 7

A virtualização permite executar um sistema operacional dentro de outro sem alterar o sistema principal do computador.

---

# 2. Requisitos do Sistema

Antes de iniciar, verifique se seu computador possui:

- Processador com suporte à virtualização (Intel VT-x ou AMD-V)
- Pelo menos **4 GB de memória RAM** (8 GB recomendado)
- Pelo menos **30 GB de espaço livre em disco**
- Virtualização habilitada na **BIOS/UEFI**

---

# 3. Download do Oracle VirtualBox

## Passo 1 — Acessar o site oficial

Abra o navegador e acesse o site oficial do VirtualBox:

https://www.virtualbox.org/

Clique na opção **Downloads** no menu principal.

---

## Passo 2 — Escolher o sistema host

Na página de downloads, selecione a versão correspondente ao seu sistema operacional.

Opções disponíveis:

- Windows hosts
- macOS hosts
- Linux distributions

Se estiver usando Windows, clique em:

Windows Hosts

O download do instalador começará automaticamente.

O arquivo baixado será semelhante a:

VirtualBox-7.x.x-Win.exe

---

# 4. Instalação do VirtualBox

## Passo 1 — Executar o instalador

1. Localize o arquivo baixado na pasta **Downloads**.
2. Clique duas vezes no instalador:


VirtualBox-7.x.x-Win.exe

A tela de instalação será aberta.

---

## Passo 2 — Avançar na instalação

Clique em: Next

---

## Passo 3 — Selecionar componentes

Na tela de componentes, mantenha as opções padrão selecionadas:

- VirtualBox Application
- VirtualBox USB Support
- VirtualBox Networking
- VirtualBox Python Support

Clique em: Next

---

## Passo 4 — Configuração de atalhos

Escolha onde deseja criar atalhos:

- Menu iniciar
- Área de trabalho

Clique em: Next

---

## Passo 5 — Aviso de rede

Durante a instalação aparecerá um aviso informando que a rede poderá ser temporariamente desconectada.

Clique em: Yes

---

## Passo 6 — Iniciar instalação

Clique em: Install

A instalação será iniciada.

Aguarde até que o processo seja concluído.

---

## Passo 7 — Finalizar instalação

Após concluir, marque a opção para abrir o programa e clique em: Finish

O **Oracle VM VirtualBox** será iniciado.

---

# 5. Download da ISO do Windows 7

Para instalar o sistema na máquina virtual, é necessário possuir uma **imagem ISO do Windows 7**.

Uma ISO é um arquivo que contém todos os dados do sistema operacional.

O arquivo geralmente possui o formato:

Windows7.iso

Salve o arquivo em uma pasta fácil de localizar.

---

# 6. Criando uma Máquina Virtual

## Passo 1 — Abrir o VirtualBox

Abra o programa **Oracle VM VirtualBox**.

Na tela inicial, clique em: New

---

## Passo 2 — Nomear a máquina virtual

Preencha os campos:

Nome: Windows 7

Tipo: Microsoft Windows

Versão: Windows 7 (64-bit)

---

Clique em: Next

---

# 7. Configurar Memória RAM

Defina a quantidade de memória RAM que será usada pela máquina virtual.

Recomendação: 2048MB (2GB) ou mais


Clique em: Next


---

# 8. Criar Disco Virtual

Selecione a opção: Create a Virtual Hard Disk now

Clique em: Create now


---

## Passo 1 — Tipo de disco

Selecione: VDI (VirtualBox Disk Image)


Clique em: Next

---

## Passo 2 — Alocação do disco

Escolha: Dynamically Allocated

Isso faz o disco crescer conforme o uso.

Clique em: Next

---

## Passo 3 — Tamanho do disco

Defina o tamanho do disco virtual.

Recomendado para Windows 7: 20GB


Clique em: Create

A máquina virtual será criada.

---

# 9. Configurando a ISO do Windows 7

Agora será necessário conectar o arquivo ISO para iniciar a instalação.

---

## Passo 1 — Abrir configurações

Selecione a máquina virtual criada.

Clique em: Settings

---

## Passo 2 — Acessar armazenamento

No menu lateral clique em: Storage

Você verá um controlador de disco com um **disco vazio**.

Clique nele.

---

## Passo 3 — Selecionar arquivo ISO

Clique no ícone de **CD** ao lado.

Selecione: Choose a disk file

Localize o arquivo: Windows7.iso

Selecione e clique em **Open**.

Clique em: OK

---

# 10. Iniciando a Máquina Virtual

Com a ISO configurada, é possível iniciar a máquina virtual.

Selecione a máquina virtual e clique em: Start

A máquina virtual iniciará pela ISO do Windows 7.

A tela de instalação do Windows aparecerá.

---

# 11. Instalando o Windows 7

Siga os passos da instalação:

1. Escolher idioma e teclado
2. Clique em **Install Now**
3. Aceite os termos de licença
4. Selecione **Custom Installation**
5. Escolha o disco virtual criado
6. Clique em **Next**

O Windows começará a ser instalado.

Esse processo pode levar alguns minutos.

---

# 12. Primeira Inicialização

Após a instalação:

- O sistema reiniciará automaticamente
- O Windows 7 iniciará dentro da máquina virtual
- Configure nome de usuário, senha e preferências

---

# 13. Instalando Guest Additions

Para melhorar o desempenho da máquina virtual:

1. Com a máquina virtual ligada, vá ao menu superior
2. Clique em: Devices Insert Guest Additions CD Image

Dentro do Windows virtual, abra o CD e execute: VBoxWindowsAdditions.exe


Isso permitirá:

- Melhor resolução de tela
- Integração do mouse
- Melhor desempenho gráfico
- Área de transferência compartilhada

---

(Visualização)


<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/6b796071-725e-43a1-8d2b-6f088c264abb" />

<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/ae3ef856-4137-43c2-96d7-bf151223dd0a" />


---

# 14. Conclusão

Após seguir este manual, você terá:

- Oracle VirtualBox instalado
- Uma máquina virtual criada
- Windows 7 rodando dentro do seu computador

A virtualização é útil para:

- Testar sistemas operacionais
- Estudar informática
- Rodar softwares antigos
- Criar ambientes seguros de teste

---

# EM RESUMO:

A virtualização é uma tecnologia que permite criar versões virtuais de recursos físicos, como servidores, sistemas operacionais, armazenamento e redes. No contexto de sistemas operacionais, ela possibilita a execução de um sistema operacional dentro de outro, ou seja, a criação de uma "máquina virtual" (VM) que simula um ambiente computacional completo. Uma das principais vantagens da virtualização é a isolação: diferentes sistemas operacionais podem rodar simultaneamente no mesmo hardware, sem interferir entre si, o que aumenta a flexibilidade e segurança. Além disso, a virtualização facilita o gerenciamento de recursos, permitindo que o hardware seja utilizado de maneira mais eficiente, com a capacidade de alocar recursos como memória e CPU conforme a necessidade. Outro benefício importante é a criação de ambientes de teste sem riscos para o sistema principal, ideal para testar novas configurações ou sistemas operacionais. Ela também é essencial para consolidar servidores em data centers, aumentando a eficiência e reduzindo custos com hardware.


---

# Apresentação: GRUPO 2 (BEATRIZ MARCELLE MAVELYN E MAURO)
- OS ESCOLHIDO = PuppyLinux
- LINK SLIDES = https://www.canva.com/design/DAHEw3yyLc0/mjZLLATo4BORzIaYj4tBiQ




