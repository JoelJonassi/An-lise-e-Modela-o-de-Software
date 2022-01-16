# PLANEAMENTO DA SPRINT E DOCUMENTAÇÃO

##  Caso de uso:  Novo Registo(Cdu1.01)

### Narrativa da Cdu1.01

Fluxos Básicos | Fluxos Alternativos
-----|-----
1 Preencher dados | A1. Dados errados
2 Guardar registo | A2. Conta existente
3 Atualizar registo | A3. Email não verificado

### User stories para Cdu1.01

Como utilizador poderei criar e registar os meus dados na plataforma onde posso entrar e comprar os produtos.  

**US1.1a** Como novo utilizador sou encaminhado para registar uma conta na plataforma

**US1.1b** Como utilizador consigo fazer login para começar a comprar produtos

**US1.1c** Como utilizador tenho que fazer login para que possa completar o meu processo de registo.


### Testes de aceitação da US1.1a (Novo registo)

* Verificar deixei campos vazios nos campos obrigatorios e mostar mensagem de erro
* Tentar não registar/validar email para continuar a comprar
* Verificar se todos os dados foram preenchidos corretamente

### Testes de aceitação da US1.1b (Novo registo)

* Verificar quando loggado nao é reencaminho para nenhuma página de registo
* Verificar navegaçao entre páginas que o meu token de loggin nao é esquecido, premanecendo assim loggado

### Testes de aceitação da US1.1c (Novo registo)

* Verificar que token do loggin que me é dado não é alterado/modificado



##  Caso de uso: Gerir Carrinho(Cdu02.01)

### Narrativa da Cdu2.01

Fluxos Básicos | Fluxos Alternativos
-----|-----
1 Inserir produto no carrinho | A1. Produto inválido
2 Eliminar produto | A2. Produto continua no carrinho 
3 Mostrar carrinho | A3. Carrinho vazio
4 Mostrar total | A4. Preços inválidos

## User stories para Cdu 2.01  
Como utilizador, posso comprar qualquer produto na plataforma eleminando ou adicionando produtos ao carrinho mesmo antes de terminar a compra.

**US2.01a** Como utilizador posso consultar meu carrinho para ver os meus items selecionados

**US2.01b** Como utilizador posso adicionar/eliminar qualquer produto disponivel na plataforma para o meu carrinho

### Testes de aceitação para US2.1a(Gerir Carrinho)
* Tentar efetuar compra com carrinho vazio
* Verificar se existe botão para efetuar compra
* Verificar se total da compra é visivel
* Verificar se preço dos produtos é visível

### Testes de aceitação para US2.1b(Gerir Carrinho)
* Verificar se existe espaço para selecionar quantas unidades pertendo adicionar ao carrinho
* Verificar se seleçao vai para carrinho de compras
* Verificar se existe botão para eliminar




##  Caso de uso: Efetuar Compra (Cdu02.06)

### Narrativa de UC2.06
Basic Flow | Alternative Flows
-----|-----
1 Adicionar items no carrinho | A1. Carrinho vazio 
2 Mostrar total dos items | A2. Sem total visível
3 Selecionar tipo de pagamento | A3. Pagamento indisponivél
4 Confirmação de dados | A4. Dados errados
5 Cancelar a encomenda | A5 Sem encomenda efetuada

## User stories para Cdu2.06

**US2.06a** Como utilizador quero terminar a seleção de artigos para efetuar a compra

**US2.06b** Como utilizador quero comprar sem falhas de segurança para comprar novamente

**US2.06c** Como utilizador posso comprar todo os items para não ter que me deslocar ao mercado

### Testes de aceitação US2.06a
* Verificar botão de confirmção de compra ou selecionar mais items
* Verificar botão para pagamento

### Testes de aceitação US2.06b
* Verificar quando inseridos os dados do cartão de pagamento do cliente não existe falhas de segurança na plataforma

### Testes de aceitação US2.06c
* Verificar items selecionados permanecem na encomenda



##  Caso de uso: Valida Produtor(CdU1.11)

### Narrativa da Cdu1.11

Fluxos Básicos | Fluxos Alternativos
-----|-----
1 Registar produtor | A1. Produtor registado
2 Eliminar produtor | A2. Produtor continua na base de dados 
3 Mostrar items do produtor | A3. Carrinho vazio
4 Mostrar total | A4. Preços inválidos

## User stories para  Cdu1.11

Como produtor posso ser possso validado na plataforma para vender os meus produtos

**US1.11a**  Como produtor adiciono/elimino os meus produtos na plataforma para venda

**US1.11b** Como produtor dou a conhecer os meus produtos para a comunidade 

### Testes de aceitação US1.11a
* Verificar botão de registo para produtor
* Verificar formulário correto para produtor
### Teste de aceitação US1.11b
* Verificar todos os produtos do produtor tem informção correta

## Planeamento da Sprint

A tabela asseguir inclui as user stories dos casos de uso considerados.

Cdu | User story | Fluxos | estimativa | Terceiro SB
--- | --- | --- | --- | ---
1.01 Valida Produtor| 1.1a criar conta | BF, A1, A2, A3| 4d | x|
1.01 Valida Produtor| 1.1b verificar conta | BF, A2| 4d | x|
1.11 Valida Produtor| 1.1c validar conta | BF| 4d | x|
1.11 Valida Produtor| 1.1d ver produtos | BF, A3| 3d | x|
1.11 Valida Produtor| 1.1e eliminar conta | BF, A3, A4| 4d | x|
2.01 Gerir Carrinho| 2.1a carrinho vazio |BF, A1|2d|X|
2.01 Gerir Carrinho| 2.1b consultar carrinho |BF|4d|
2.01 Gerir Carrinho| 2.1c apagar itens no carrinho|BF, A4|7h|
2.06 Efetuar compra| 1.1a produtos mais vendidos |BF |4d|X|
2.06 Efetuar compra| 1.1b Escolher o produto |BF, A1|3d|X|
2.06 Efetuar compra| 1.1c Escolher o produtor |BF, A3, A4|6d|
2.06 Efetuar compra| 1.1d Produto indiponivel |BF, A5|2d|
2.06 Efetuar compra| 1.1e Adicionar item no carrinho |BF, A4|3d|
2.06 Efetuar compra| 1.1f Erro codigo-postal |BF, A4|5d|

[Back Home](Home)