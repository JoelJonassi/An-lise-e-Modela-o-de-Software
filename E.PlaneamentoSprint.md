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


##  Caso de uso:  Valida Produtor(Cdu01.11)

Para cada caso de uso, precissamos desenvolver a narrativa , em pequenos user stories, e escrever os testes de aceitação.

### Narrativa da Cdu1.01

Basic Flow | Alternative Flows
-----|-----
1 Selecionar Produtor | A1.
2 Mostrar Produtores | A2. Select different canteen
3 Validar Registo | A3. No menu in selected date
4 Criar novo registo | A4. Insufficient account balance
5 Atualizar Registo | ...

### User stories para Cdu1.01
Cada user story forma o item do trabalho claro para o cliente.
Each user story form a work item that is of clear value to the customer.

**US1.1a** como gerente, quero validar os produtores que podem vender na plataforma.

**US1.1b** Como gerente, quero ver a quantidade de produtores na plataforma. 

**US1.1c** As a user, I want to buy a meal ticket even when my account balance is not enough, so that I avoid to pay the extra price of the ticket purchased at the POS.


### Testes de aceitação para US1.1a Default date meal (Purchase ticket)

* Try to create a ticket without existing menu
* Try different dish options
* Check the ticket was correctly created for the user
* Check the user credit was correctly updated
* Verify the ticket refers the current date and selected dish

### Testes de aceitação for US1.1b Select canteen and day (Purchase ticket)

* Try different dates: current day, past days, future days with menu and future days without menu
* Try for different canteens
* Verify the ticket refers the selected date and canteen


##  Caso de uso: Elimina Produtor(Cdu01.12)
Next, the details of UC 2.01.

### Narrative of UC2.01



## User stories for UC1.01 and UC 2.01
## User stories para Cdu 2.01


**US2.1a** Como administrador quero eliminar os produtores, que não estão na activa a mais de 6 meses dentro da plataforma.

**US2.1b** As a cashier, I want check the user tickets so that I can consult the user login, the account balance and the last tickets bought by the user.

**US2.1c** As a cashier, I want to validate the ticket of a user with negative account balance, so that the user can load money to his/her account to get access to the meal.

### Acceptance tests for US2.1a
### Testes de aceitação


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

A tabela asseguir inclui as user stories dos casos de uso ..


Cdu | User story | Fluxos | estimativa | 3rd SB
--- | --- | --- | --- | ---
1.1 Purchase ticket|1.1a Default date meal|BF |3d|X
1.1 Purchase ticket|1.1b Select canteen and day|BF, A1, A2|2d|X
1.1 Purchase ticket|1.1c Not enough credit|BF, A3, A4|4h|
2.1 Validate ticket|2.1a Valid ticket|BF|2d|X
2.1 Validate ticket|2.1b No ticket available|BF, A1, A2, A3|1d|
2.1 Validate ticket|2.1c Insufficient account balance|BF, A4|2d|


[Back Home](Home)
