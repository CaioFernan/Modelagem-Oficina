# Sistema de Gerenciamento de Oficina Mecânica

Projeto desenvolvido para representar o funcionamento de uma oficina mecânica, permitindo o controle de clientes, veículos, equipes de mecânicos, serviços, peças e ordens de serviço.

O sistema tem como objetivo gerenciar o processo desde a entrada do veículo na oficina até a execução dos serviços autorizados pelo cliente.

### Funcionalidades e conceitos

* Cadastro e gerenciamento de clientes.
* Cadastro dos veículos dos clientes.
* Cadastro de mecânicos e suas especialidades.
* Organização dos mecânicos em equipes.
* Criação e gerenciamento de Ordens de Serviço (OS).
* Registro da data de emissão e previsão de conclusão da OS.
* Controle do status da Ordem de Serviço.
* Registro da autorização do cliente para execução dos serviços.
* Consulta de valores de mão de obra.
* Registro dos serviços realizados.
* Controle das peças utilizadas na execução dos serviços.
* Cálculo do valor total da Ordem de Serviço.
* Relacionamento entre clientes, veículos, equipes, serviços, peças e ordens de serviço.

### Modelagem do Banco de Dados

A estrutura do banco foi desenvolvida utilizando conceitos de **modelagem relacional**, incluindo:

* Chaves primárias e estrangeiras;
* Relacionamentos 1:N e N:N;
* Tabelas associativas;
* Integridade referencial;
* Separação entre cadastro de serviços e execução dos serviços;
* Registro dos valores praticados no momento da execução da OS.

O projeto tem como objetivo colocar em prática conhecimentos de **modelagem de dados e desenvolvimento de sistemas**, servindo também como base para uma futura implementação de uma API ou aplicação web para gerenciamento de oficinas mecânicas.
