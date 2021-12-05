# Arquitetura Técnica

Os componentes funcionais tem diferentes requisitos técnicos. Os produtos devem ser acessiveis de qualquer lugar, por isso será desenvolvida uma aplicação web, usando ferramentas baratas, as mais utilizadas e as de fácil utilização.

O foco principal desta plataforma e-commerce, é que seja de fácil utilização seguindo os padrões das plataformas e-commerce existentes, de fácil usabilidade, ou seja, uma plataforma simples e objetiva que atenda as necessidades dos utilizadores.

![image](Images\ArquiteturaTecnica.png)

# Preparação do Product Backlog (PB)
A prioridade das actividades no projecto:  

**PB Codigo**   |   **PB Nome** |   **Prioridade** 
-----|-----|----- 
PB001           |   Registar cliente    |   Must    
PB002           |   Selecionar produtos |   Must    
PB003           |   Selecionar método de pagamento  |   Should  
PB004           |   Validar e autorizar no sistema a venda  |   Must    
PB005   |   Validar Moradas de entrega   |  Must       
PB006   |   Inserir produtos   |    Must     
PB003           |   Validar e autorizar no sistema a venda  |   Must    
PB004   |   Validar Moradas de entrega   | Must  
PB005   |   Incluir produtos para venda    |    Must
PB006           |   Selecionar método de pagamento  |   Should    
PB007   |   Historicos de compras   |   Could         
PB008   |   Avaliar comerciantes    |   Could       
PB009   |   Email confirmação      |     Could

## Prioridade dos Casos de Uso (Cdu)

As técnicas de prioridade MoSCoW permitem determinar  o que é e não é essencial para o projeto, ou seja, é um metodo rigoroso que indica onde o foco deve estar, permitindo que a equipa determine quanto esforço será despendido para cada Cdu. 

Cdu codigo |Nome do Cdu| Prioridade
-----|-----|-----
Cdu01.01 | Novo Registo | Must
Cdu01.02 | Define username| Must
Cdu01.03 | Define password | Must
Cdu01.04 | Regista NIF | Must
Cdu01.05 | Insere Morada| Must
Cdu01.06 | Insere Contato | Must
Cdu01.07 | Insere e-mail | Must
Cdu01.08 | Login | Must
Cdu01.09 | User Profile | Could
Cdu01.10 | Logout | Must
Cdu01.11 | Valida Produtor | Must
Cdu01.12 | Elimina Produtor | Must
Cdu01.13 | Consulta Stock | Could
Cdu01.14 | Regista Produtor | Should
Cdu01.15 | Insere/Elimina produto | Should
Cdu02.01 | Gerir Carrinho | Must
Cdu02.02 | Apagar artigos | Must
Cdu02.03 | Adicionar artigos | Must
Cdu02.04 | Ver Itens| Could
Cdu02.05 | Confirmar dados de envio | Must
Cdu02.06 | Efetuar Compra | Must
Cdu02.07 | CheckOut | Must
Cdu02.08 | Login | Must
Cdu03.01 | Notifica Data/Hora entrega | Could
Cdu03.02 | Verifica Encomenda | Could
Cdu03.03 | Valida encomenda | Could
Cdu03.04 | Notifica produtor | Should


[Back Home](Home)