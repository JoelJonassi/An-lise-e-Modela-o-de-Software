# TEM MAIS HAVER COM REQUISITOS
Escolher 4 casos de uso em ordem de prioridade 
Fazer narrativas 

Fuxos alternativos
    A cocorrencia de erros
    funcionalidades adicionais fora do fluxo base

 # Sprint planning & documentation

Durante o planeamento da soprint, os casos de uso são detalhados no desenvolvimento das narrativas
During the sprint planning, the use higl priority use cases are detailed through the development of narratives.

Em ordem para prepar o próximo sprint, os casos de uso são pedaço das user stories. Para cada user case, é definido user sotory que deve completar o comportamento total do caso de uso.

In order to prepare the next sprint, the UC are split into user stories. For each use case, the set of user stories must complete the use case full behaviour. 

Considerando a prioridade da table dos casos de uso,  17 são de alta prioridade neste caso consideraremos apenas 4 casos de uso.

Considering the UC prioritization table, 2 UC are in high priority.


##  Caso de uso:  Novo Registo(Cdu1.01)
Cdu01.01 | Novo Registo  

### Narrative of UC1.01

Fluxos Básicos | Fluxos Alternativos
-----|-----
1 Preencher dados | A1. Conta não registada no sistema
2 Guardar registo | A2. Credênciais erradas
3 Atualizar registo | A3. Email não verificado
4 Carrega foto | A4. 

### User stories para Cdu1.01
Como utilizador poderei criar e registar os meus dados na plataforma onde posso entrar e comprar os produtos.  

**US1.1a** Como novo utilizador sou encaminhado para registar uma conta na plataforma.

**US1.1b** Como utilizador, consigo fazer login e começar a comprar produtos.

**US1.1c** Como utilizador consigo ver o meu nome e fotografia depois de entrar na página.

### Testes de aceitação para US1.1a (Novo registo)

* Tentar não inserir dados nos campos obrigatoriose mostar mensagem de erro
* Tentar não registar/validar email
* Verificar se todos os dados foram preenchidos corretamente

### Testes de aceitação for US1.1b (Novo registo)

* Verificar quando loggado nao é reencaminho para nenhuma página de registo

### Testes de aceitação for US1.1c (Novo registo)

* Verificar dados corretos

##  Caso de uso: Gerir Carrinho(Cdu02.01)
Cdu02.01 | Gerir Carrinho

### Narrative of UC2.01

Fluxos Básicos | Fluxos Alternativos
-----|-----
1 Inserir produto no carrinho | A1. Produto inválido
2 Eliminar produto | A2. Produto continua no carrinho 
3 Mostrar carrinho | A3. carrinho vazio
4 Mostrar total | A4. Preços inválidos

## User stories for UC1.01 and UC 2.01
## User stories para Cdu 2.01  
Como utilizador, posso comprar qualquer produto na plataforma.

**US2.01a** Como utilizador posso consultar minha dashboard para ver as minhas compras.

**US2.01b** Como utilizador consigo comprar qualquer produto disponivel na plataforma

**US2.01c** 

### Acceptance tests for US2.1a
### Testes de aceitação

* Tentar efetuar compra com carrinho vazia
* Verificar se existe botão para efetuar compra
* Verificar se total da compra é visivel
* Verificar se preço dos produtos é visível

##  Caso de uso: Efetuar Compra (Cdu02.06)


### Narrative of UC2.01
Basic Flow | Alternative Flows
-----|-----
1 Selecionar Produtos | A1.
2 Mostrar Produtor | A2. Select different canteen
3 Adicionar produtos ao carrinho | A3. No menu in selected date
4 Efetua  a encomenda | A4. Insufficient account balance
5 Cancelar a encomenda | ...


## User stories for UC1.01 and UC 2.01
## User stories para UC 1.01


**US2.1a** As a cashier, I want to validate the user ticket so that I can confirm the user can receive a meal.

**US2.1b** As a cashier, I want check the user tickets so that I can consult the user login, the account balance and the last tickets bought by the user.

**US2.1c** As a cashier, I want to validate the ticket of a user with negative account balance, so that the user can load money to his/her account to get access to the meal.

### Acceptance tests for US2.1a
### Testes de aceitação





##  Caso de uso: Efetuar Compra (Cdu02.06)
Next, the details of UC 2.01.

### Narrative of UC2.01



## User stories for UC1.01 and UC 2.01
## User stories para UC 1.01

Each user story form a work item that is of clear value to the customer.

**US2.1a** As a cashier, I want to validate the user ticket so that I can confirm the user can receive a meal.

**US2.1b** As a cashier, I want check the user tickets so that I can consult the user login, the account balance and the last tickets bought by the user.

**US2.1c** As a cashier, I want to validate the ticket of a user with negative account balance, so that the user can load money to his/her account to get access to the meal.

### Acceptance tests for US2.1a
### Testes de aceitação

Cdu03.03 | Valida encomenda
##  Caso de uso: Valida encomenda(Cdu03.03)
Next, the details of UC 2.01.

### Narrative of UC2.01



## User stories for UC1.01 and UC 2.01
## User stories para UC 1.01

Each user story form a work item that is of clear value to the customer.

**US2.1a** As a cashier, I want to validate the user ticket so that I can confirm the user can receive a meal.

**US2.1b** As a cashier, I want check the user tickets so that I can consult the user login, the account balance and the last tickets bought by the user.

**US2.1c** As a cashier, I want to validate the ticket of a user with negative account balance, so that the user can load money to his/her account to get access to the meal.

### Acceptance tests for US2.1a
### Testes de aceitação


## Planeamento da Sprint

A tabela asseguir inclui as user stories dos casos de uso considerados.


Cdu | User story | Fluxos | estimativa | 3rd SB
--- | --- | --- | --- | ---
02.06 Efetuar compra|1.1a Default date meal|BF |3d|X
1.1 Purchase ticket|1.1b Esolher o produto|BF, A1, A2|2d|X
1.1 Purchase ticket|1.1c Produto indiponivel|BF, A3, A4|4h|
2.1 Validar encomenda|2.1a Encomenda paga|BF|2d|X
2.1 Validate ticket|2.1b Encomenda a espera de pagamento|BF, A1, A2, A3|1d|
2.1 Validate ticket|2.1c Paga aguarda o envio|BF, A4|2d|


[Back Home](Home)
