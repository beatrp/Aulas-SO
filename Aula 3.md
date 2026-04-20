# RESUMO AULA 3: 

## Conceitos, Funções e Tipos de Sistemas Operacionais

# Aula 03 – Conceitos, Funções e Tipos de Sistemas Operacionais


---


# 1. Introdução aos Sistemas Operacionais

## 1.1 O que é um Sistema Operacional?

Um Sistema Operacional (SO) é o software fundamental que atua como intermediário entre o hardware do computador e os programas/aplicações do usuário.

Ele é responsável por:

- Gerenciar recursos de hardware (CPU, memória, disco, dispositivos de entrada e saída)
- Fornecer uma interface para o usuário
- Garantir execução correta e eficiente dos programas
- Controlar acesso e segurança

Sem um sistema operacional, o uso do computador seria extremamente complexo, pois cada programa precisaria controlar diretamente o hardware.

---

## 1.2 Principais Funções de um Sistema Operacional

### 1.2.1 Gerenciamento de Processos

- Criação e finalização de processos
- Escalonamento da CPU
- Controle de concorrência
- Sincronização
- Comunicação entre processos

O sistema operacional decide qual processo será executado e por quanto tempo.

---

### 1.2.2 Gerenciamento de Memória

- Controle de alocação e desalocação de memória
- Memória virtual
- Paginação e segmentação
- Proteção de memória entre processos

Permite que múltiplos programas utilizem memória de forma segura e eficiente.

---

### 1.2.3 Gerenciamento de Arquivos

- Criação, leitura, escrita e exclusão de arquivos
- Organização em diretórios
- Controle de permissões
- Estruturação do sistema de arquivos

---

### 1.2.4 Gerenciamento de Dispositivos

- Comunicação com periféricos
- Uso de drivers
- Controle de entrada e saída (E/S)

---

### 1.2.5 Segurança e Controle de Acesso

- Autenticação de usuários
- Autorização
- Criptografia
- Auditoria

---

# 2. Tipos de Sistemas Operacionais

Os sistemas operacionais variam de acordo com sua aplicação, arquitetura e finalidade.

---

# 2.1 Sistemas de Grande Porte (Mainframes)

Projetados para:

- Alta capacidade de Entrada/Saída
- Processamento massivo de transações
- Operação com milhares de usuários simultâneos

Características principais:

- Alta confiabilidade
- Alta disponibilidade
- Segurança avançada
- Processamento em lote
- Processamento em tempo compartilhado

São muito utilizados em:

- Bancos
- Grandes varejistas
- Instituições financeiras
- Sistemas governamentais

Exemplos históricos e atuais:

- OS/360  
- OS/390  
- Linux em ambientes de mainframe  
- Variantes UNIX  

Mainframes ainda são usados como:

- Servidores web de grande escala
- Plataformas de e-commerce
- Sistemas bancários críticos

---

# 2.2 Sistemas Operacionais de Servidor

Focados em:

- Atender múltiplos usuários via rede
- Fornecer serviços como:
  - Web
  - Banco de dados
  - Arquivos
  - Autenticação

Características:

- Estabilidade
- Escalabilidade
- Segurança
- Compartilhamento de recursos

Principais exemplos:

- Linux (ampla adoção em servidores)
- Windows Server (integração com Active Directory)

---

# 2.3 Sistemas de Multiprocessadores

Utilizam:

- Múltiplas CPUs
- Múltiplos núcleos

Objetivo:

- Processamento paralelo
- Alto desempenho

Desafios:

- Balanceamento de carga
- Sincronização entre processos
- Condições de corrida
- Coerência de cache

Soluções:

- Locks
- Semáforos
- Algoritmos lock-free
- Escalonadores avançados

Aplicações:

- Servidores de alto desempenho
- Computação científica
- Inteligência artificial
- Big Data

---

# 2.4 Sistemas de Computadores Pessoais

Voltados para:

- Uso individual
- Interface gráfica amigável
- Execução de múltiplos programas

Características:

- Foco em usabilidade
- Compatibilidade com aplicações
- Suporte multimídia

Exemplos:

- Windows
- macOS
- Linux (desktop)

---

# 2.5 Sistemas Operacionais Portáteis

Utilizados em:

- Smartphones
- Tablets

Principais aspectos:

- Gerenciamento agressivo de energia
- API para sensores (GPS, câmera, acelerômetro)
- Segurança por permissões
- Sandboxing

Exemplos:

- Android
- iOS

Foco:

- Segurança
- Integração com hardware
- Distribuição via lojas oficiais

---

# 2.6 Sistemas Embarcados

Executam em:

- Dispositivos dedicados
- Recursos limitados
- Hardware específico

Exemplos de aplicação:

- Micro-ondas
- Smart TVs
- Automóveis
- Equipamentos industriais

Características:

- Software armazenado em ROM ou flash
- Usuário normalmente não altera o sistema
- Resposta rápida

Exemplos mais sofisticados:

- Embedded Linux
- QNX
- VxWorks

---

# 2.7 Sistemas de Nós Sensores

Dispositivos:

- Muito pequenos
- Alimentados por bateria
- Comunicação sem fio

Características:

- Baixo consumo de energia
- Protocolos leves
- Orientados a eventos

Aplicações:

- Monitoramento ambiental
- Vigilância
- Agricultura de precisão

Exemplos:

- TinyOS
- Contiki

---

# 2.8 Sistemas de Tempo Real

Dividem-se em:

## Hard Real-Time

- Perda de prazo pode causar desastre
- Exemplo: controle de voo, sistemas médicos críticos

## Soft Real-Time

- Pequenos atrasos são toleráveis
- Exemplo: streaming de vídeo

---

# 2.9 Sistemas de Cartões Inteligentes

Características:

- Recursos extremamente limitados
- Segurança avançada
- Uso de criptografia
- Isolamento por applets

Desafios:

- Gerenciamento fino de memória
- Resistência a ataques físicos

---

# 3. Introdução ao Git

## 3.1 O que é Git?

Git é um sistema de controle de versão distribuído.

Permite:

- Registrar alterações em arquivos
- Manter histórico de versões
- Restaurar versões anteriores
- Trabalhar em equipe

---

## 3.2 O que o Git pode fazer?

- Sincronizar com repositórios online
- Enviar e baixar código
- Criar ramificações (branches)
- Resolver conflitos
- Controlar histórico do projeto

---

# 4. Instalando o Git

Passos:

1. Acessar o site oficial
2. Escolher versão do sistema operacional
3. Baixar o instalador
4. Executar instalação
5. Testar com: "git --version"


Se retornar a versão instalada, está funcionando corretamente.

---

# 5. Configuração Inicial do Git

Configuração de usuário:

git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"


---

# 6. Criando um Repositório no VS Code

Passos:

1. Criar uma pasta
2. Abrir no VS Code
3. Criar arquivo .md
4. Ir na aba de Controle de Código-Fonte
5. Inicializar repositório
6. Fazer commit

---

# 7. Publicando no GitHub

Passos:

1. Clicar em "Publicar Branch"
2. Fazer login
3. Escolher público ou privado
4. Confirmar publicação

Depois disso:

- Acessar GitHub
- Verificar repositório
- Conferir arquivos enviados

---

# 8. Boas Práticas com Git

## 8.1 Commits Pequenos e Frequentes

- Facilitam manutenção
- Ajudam a identificar erros
- Permitem rollback fácil

---

## 8.2 Mensagens Claras

Descrever:

- O que foi alterado
- Por que foi alterado

---

## 8.3 Uso de Branches

- Manter branch principal estável
- Criar branches para novas funcionalidades
- Realizar merge após testes

---

## 8.4 Testes Automatizados

- Garantir funcionamento antes do merge
- Evitar que erros cheguem à produção

---

# 9. Atividades Propostas

## Atividade 1

Configurar:

- Integração entre IDE e GitHub
- Autenticação funcional
- Operações de commit, push e pull

---

## Atividade 2

1. Criar repositório
2. Adicionar arquivo inicial
3. Fazer commit
4. Sincronizar com GitHub
5. Apagar pasta local
6. Clonar novamente com: "git clone <url>"

7. Validar restauração

---

## Atividade 3

1. Pesquisar 5 projetos no GitHub
2. Clonar usando git clone
3. Analisar conteúdo dos repositórios

---

# 10. Referências Bibliográficas

- Tanenbaum & Bos – Sistemas Operacionais Modernos  
- Silberschatz, Galvin & Gagne – Fundamentos de Sistemas Operacionais  
- Stallings – Sistemas Operacionais: Conceitos e Projetos  
- Denardin & Barriquello – Sistemas de Tempo Real  
- Downey – Think OS  
- Documentação Red Hat  
- Documentação Docker  

---

# Conclusão

Nesta aula foram abordados:

- Conceitos fundamentais de Sistemas Operacionais
- Classificação e tipos de SO
- Aplicações práticas
- Introdução ao controle de versão com Git
- Boas práticas de versionamento
- Integração com IDE e GitHub

O aluno deve ser capaz de:

- Diferenciar tipos de sistemas operacionais
- Reconhecer aplicações e exigências de projeto
- Utilizar Git para versionamento
- Criar e publicar repositórios
- Aplicar boas práticas de desenvolvimento

---


