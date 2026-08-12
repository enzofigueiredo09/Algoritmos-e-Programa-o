# Algoritmos-e-Programa-o
Trabalho de Algoritmos e Programação

Processo da Compra de Ingressos na Disney

## Planejamento e Arquitetura do Projeto

Este projeto foi planejado antes da sua implementação para garantir que todas as regras de negócio de um sistema de ingressos fossem contempladas de forma simples e estruturada.

---

### 1.  Escopo e Objetivo
Construir um sistema simples de terminal para gerenciar o ciclo de vida de um ingresso para os parques da Disney, permitindo a emissão, consulta, alteração e cancelamento de reservas.

---

### 2.  Mapeamento do CRUD (Regras de Negócio)

 Operação CRUD | Ação do Usuário | Regra do Sistema.

 **C - Create** | Emitir Ingresso | Solicita nome e parque, cria a reserva com status inicial "Ativo". 

 **R - Read** | Ver Ingressos | Exibe a lista completa de ingressos com seus respectivos números identificadores. 

 **U - Update** | Mudar Parque | Permite escolher um ingresso existente e alterar o parque selecionado. 
 
 **D - Delete** | Cancelar Ingresso | Remove a reserva do sistema e libera a vaga do parque. 

---

### 3.  Modelo Conceitual de Dados

Cada registro de **Ingresso** possui os seguintes atributos necessários:

* **Identificador (ID):** Posição ou código único de cada ingresso no sistema.
* **Nome do Visitante:** Nome da pessoa vinculada ao bilhete.
* **Parque Selecionado:** Nome do parque temático escolhido (ex: *Magic Kingdom*, *Epcot*).
* **Status:** Estado atual da reserva (*Ativo* ou *Cancelado*).

---

### 4.  Fluxo de Navegação do Usuário

1. **Inicialização:** O sistema abre apresentando um menu principal numerado.
2. **Seleção de Opção:** O usuário digite o número da ação desejada (1 a 5).
3. **Execução:**
   - Se escolheu **1**, digita os dados para salvar.
   - Se escolheu **2**, visualiza os dados existentes.
   - Se escolheu **3 ou 4**, informa qual número de ingresso deseja modificar/remover.
   - Se escolheu **5**, o sistema encerra o ciclo.
4. **Retorno:** Após finalizar qualquer ação, o menu reaparece na tela.

---

###  Roadmap de Desenvolvimento (Passo a Passo de Construção)

- [x] **Fase 1: Mapeamento de Ideia e Requisitos** (Definição das regras de negócio).
- [x] **Fase 2: Estruturação dos Dados** (Definição da lista e variáveis).
- [x] **Fase 3: Construção do Loop e Menu** (Criação da interface de terminal).
- [x] **Fase 4: Documentação e Publicação** (Criação do README e envio ao GitHub).
