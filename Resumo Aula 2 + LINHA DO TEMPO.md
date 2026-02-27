
# RESUMO AULA 2:

# História dos Sistemas Operacionais  

## (Páginas 5 a 13) 
## – 📖 Sistemas Operacionais Modernos, 4ª edição


---


#  Introdução Geral

A história dos sistemas operacionais está diretamente ligada à evolução do hardware.

Cada avanço tecnológico no hardware exigiu novas formas de gerenciamento.

À medida que os computadores se tornavam mais rápidos e complexos, surgia a necessidade de softwares capazes de:

- Organizar recursos
- Automatizar tarefas
- Permitir múltiplos usuários
- Aumentar eficiência
- Garantir segurança


O livro organiza essa evolução em cinco gerações principais.

Cada geração representa uma mudança significativa tanto tecnológica quanto conceitual.


---


# 🖥 1ª Geração (1945–1955)  
## A Era das Válvulas


---


## Contexto Histórico

Após a Segunda Guerra Mundial, surgiram os primeiros computadores eletrônicos, essas grandes máquinas utilizavam válvulas a vácuo, consumiam grande quantidade de energia, geravam muito calor e falhavam com frequência.

---


## Características Técnicas


- Uso de válvulas eletrônicas
- Programação em linguagem de máquina
- Memória extremamente limitada
- Ausência de sistemas de armazenamento modernos
- Entrada e saída por cartões perfurados


---


## Funcionamento

Não existia sistema operacional, cada programa era carregado manualmente. O programador controlava diretamente o hardware, e se algo desse errado, era necessário reiniciar o processo inteiro. Não havia abstrações, não havia gerenciamento automático, e não havia proteção de memória.


---


## Modelo de Uso

- Um único usuário por vez.

- Uso exclusivo da máquina.

- Tempo extremamente caro.

- Ambiente restrito a governos e grandes centros de pesquisa.


---


## Conclusão da 1ª Geração

Não havia sistema operacional, o controle era totalmente manual.

Essa fase representa a pré-história dos sistemas operacionais.


---


# 🔄 2ª Geração (1955–1965)  
## A Era dos Transistores e Sistemas Batch


---


## Avanço Tecnológico

Substituição das válvulas por transistores.

Computadores tornaram-se:

- Menores
- Mais rápidos
- Mais confiáveis
- Menos propensos a falhas


---


## Mudança de Paradigma

Surge a necessidade de automatizar a execução de programas, logo operadores passam a intermediar o uso da máquina,e usuários entregam seus programas em cartões perfurados.


---


## Sistemas em Lote (Batch)

Programas são agrupados em lotes, executados sequencialmente, sem interação do usuário durante a execução.


---


## Funcionamento do Batch

1. Operador coleta os programas.
2. Organiza em sequência.
3. Carrega o lote na máquina.
4. Sistema executa automaticamente.


---


## Vantagens

- Melhor aproveitamento da CPU.
- Redução do tempo ocioso.
- Maior organização.

---

## Limitações

- Sem interação em tempo real.
- Erros só eram percebidos após a execução completa.
- Processos ainda simples.


---


## Surgimento dos Primeiros Sistemas Operacionais

Nesta geração surgem os primeiros softwares responsáveis por:

- Controlar execução de lotes.
- Gerenciar entrada e saída.
- Automatizar carregamento de programas.

Ainda eram simples.

Mas representam o nascimento dos sistemas operacionais.

---

# ⚙ 3ª Geração (1965–1980)  
## Circuitos Integrados e Multiprogramação

---

## Revolução Tecnológica

Introdução dos circuitos integrados, maior capacidade de processamento, maior memória e redução de custos.

---

## Problema Identificado

CPU ficava ociosa durante operações de entrada e saída, logo sendo necessário melhorar eficiência.


---


## Multiprogramação

- Vários programas na memória simultaneamente.

- Quando um aguardava E/S, outro utilizava a CPU.

- Isso aumentou drasticamente o desempenho.


---

## Gerenciamento de Memória

Surge a necessidade de:

- Alocação dinâmica.
- Proteção entre processos.
- Controle de espaço.

---

## Time-Sharing (Tempo Compartilhado)

Permite múltiplos usuários simultâneos.

Cada usuário recebe uma fatia de tempo da CPU.

Sistema alterna rapidamente entre tarefas.

Cria ilusão de execução simultânea.

---

## Impacto

Mudança completa no conceito de computação; de processamento isolado para ambiente compartilhado.

---

## Responsabilidades do Sistema Operacional

- Escalonamento de processos.
- Gerenciamento de memória.
- Controle de dispositivos.
- Proteção do sistema.


---

## Conclusão da 3ª Geração

Os sistemas operacionais tornam-se complexos, assim passam a ser o núcleo central do funcionamento do computador.


---

# 💻 4ª Geração (1980–Presente)  
## A Era dos Computadores Pessoais, Computadores Móveis e Conectividade

Surgimento de smartphones, tablets e dispositivos portáteis. Conectividade deixa de ser opcional e passa a ser essencial + aplicações dependem da nuvem.


---


## Popularização

Computadores deixam de ser exclusivos de grandes instituições.

Passam a estar em casas e escritórios.

Uso individual se torna comum.


---

## Novas Demandas

- Interface amigável.
- Facilidade de uso.
- Ambientes gráficos.
- Interatividade constante.


---

## Mudanças no Papel do SO

Antes: foco em eficiência e compartilhamento.

Agora: foco em usabilidade.

---

## Interface Gráfica

Surge o modelo WIMP:

- Windows
- Icons
- Menus
- Pointer

Interação torna-se visual.

---

## Expansão de Aplicações

- Editores de texto.
- Planilhas.
- Jogos.
- Navegadores.

Sistema operacional precisa suportar diversidade.


---


## Evolução Contínua

Sistemas passam por versões sucessivas.

Mantêm compatibilidade com versões anteriores.

Aumentam tamanho e complexidade.

---


## Transformação Digital



---

## Novos Desafios

- Consumo de bateria.
- Interface por toque.
- Sensores integrados.
- Conectividade constante.

---

## Mudança Arquitetural

Sistemas precisam ser:

- Leves.
- Eficientes.
- Seguros.
- Conectados à internet.

---

## Segurança

- Aumento de ameaças.

- Necessidade de sandboxing.

- Permissões controladas.

- Isolamento de aplicações.

---

# 📊 Comparação Evolutiva

| Geração | Hardware | Característica Principal |
|----------|----------|--------------------------|
| 1ª | Válvulas | Não havia SO |
| 2ª | Transistores | Sistemas em lote |
| 3ª | Circuitos Integrados | Multiprogramação |
| 4ª | PCs | Interface gráfica |
| 5ª | Dispositivos móveis | Mobilidade e conectividade |

---
# 📜 Conclusão em Diagrama – Evolução das Gerações dos Sistemas Operacionais

A evolução dos sistemas operacionais pode ser compreendida como um processo contínuo de adaptação às mudanças do hardware e às necessidades dos usuários.

Abaixo, o desenvolvimento histórico organizado em formato de diagrama-resumo:

---

# 🧭 Evolução Histórica

1ª GERAÇÃO (1945–1955)
        ↓
[ NÃO EXISTE SISTEMA OPERACIONAL ]
        ↓
• Controle manual
• Programação em linguagem de máquina
• Um usuário por vez
• Sem abstrações
        ↓
➡ Computação totalmente dependente do programador


────────────────────────────────────────

2ª GERAÇÃO (1955–1965)
        ↓
[ SURGIMENTO DOS SISTEMAS BATCH ]
        ↓
Usuário → Operador → Sistema em Lote → Hardware
        ↓
• Execução automática de lotes
• Sem interação durante a execução
• Melhor aproveitamento da CPU
        ↓
➡ Início da automação do controle do computador


────────────────────────────────────────

3ª GERAÇÃO (1965–1980)
        ↓
[ MULTIPROGRAMAÇÃO E TIME-SHARING ]
        ↓
Usuários múltiplos
        ↓
Sistema Operacional
        ↓
CPU ↔ Memória ↔ Dispositivos
        ↓
• Vários programas na memória
• Alternância de processos
• Compartilhamento de recursos
• Proteção de memória
        ↓
➡ O sistema operacional torna-se o núcleo central do sistema


────────────────────────────────────────

4ª GERAÇÃO (1980–Presente)
        ↓
[ COMPUTADORES PESSOAIS ]
        ↓
Usuário
        ↓
Interface Gráfica
        ↓
Sistema Operacional
        ↓
Hardware
        ↓
• Foco em usabilidade
• Ambientes gráficos
• Uso individual
• Expansão de aplicações
        ↓
➡ O sistema operacional passa a fazer parte do cotidiano das pessoas


---


# 🎯 Conclusão Geral

Não existia SO
        ↓
Automação simples (Batch)
        ↓
Gerenciamento avançado e compartilhamento
        ↓
Usabilidade e popularização


A evolução das gerações demonstra que os sistemas operacionais passaram de inexistentes para elementos essenciais, responsáveis por organizar recursos, aumentar eficiência e tornar a computação acessível e funcional para diferentes tipos de usuários.


---


# Linha do tempo 



<img width="1090" height="2097" alt="image" src="https://github.com/user-attachments/assets/86a78976-83f1-4549-bc2d-a9d0d8294c4c" />


