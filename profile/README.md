# Projeto Fast-Eats

Bem-vindo ao repositório do Projeto Fast-Eats, onde organizamos os trabalhos do Grupo 56 da turma SOAT1 da pós-graduação em Arquitetura de Software da FIAP.

## Entrega Fase 5

Na Fase 5, optamos por implementar uma saga coreografada em nosso sistema de pedidos devido às suas diversas vantagens. A SAGA coreografada permite uma arquitetura distribuída e desacoplada, alinhando-se perfeitamente com a natureza dinâmica de nosso projeto. Cada microserviço é responsável por uma parte do processo de pedidos, como criação, processamento de pagamentos e produção, operando de forma independente para garantir flexibilidade e escalabilidade.

Para acessar os documentos, vídeos e diagramas solicitados para a entrega da Fase 5, clique [aqui](https://1drv.ms/b/s!AumrZPBkIvJTh-0-DJUH2lZ3-raZiQ?e=9wKJHB).

## Aplicações

### Autenticação

- [Lambda STS](https://github.com/FIAP-Grupo56-SOAT1/LAMBDA_STS_FAST-EATS): Lambda responsável pelo serviço de Security Token Service.
- [Lambda Autenticação](https://github.com/FIAP-Grupo56-SOAT1/LAMBDA_AUTH_FAST-EATS): Lambda responsável pelo serviço de autenticação.
- [API Gateway](https://github.com/FIAP-Grupo56-SOAT1/INFRA_API_GATEWAY_FAST-EATS): API Gateway para gerenciar as requisições.

### Notificação
- [Lambda Notificação](https://github.com/FIAP-Grupo56-SOAT1/LAMBDA_CLIENT_NOTIFICATION_FAST-EATS): Lambda responsável pela notificação para o cliente.

### Pedido

- [Infra do Banco de Dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_FAST-EATS): Infraestrutura do banco de dados para o serviço de pedidos.
- [Infra da Aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_FAST-EATS): Infraestrutura da aplicação de pedidos.
- [Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PEDIDO_FAST-EATS): Microserviço responsável pelo serviço de pedidos.

### Pagamento

- [Infra do Banco de Dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_PAGAMENTO_FAST-EATS): Infraestrutura do banco de dados para o serviço de pagamentos.
- [Infra da Aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_PAGAMENTO_FAST-EATS): Infraestrutura da aplicação de pagamentos.
- [Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PAGAMENTO_FAST-EATS): Microserviço responsável pelo serviço de pagamentos.

### Produção

- [Infra do Banco de Dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_PRODUCAO_FAST-EATS): Infraestrutura do banco de dados para o ambiente de produção.
- [Infra da Aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_PRODUCAO_FAST-EATS): Infraestrutura da aplicação para o ambiente de produção.
- [Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PRODUCAO_FAST-EATS): Aplicação para o ambiente de produção.

## Autores

| [<img src="https://avatars.githubusercontent.com/u/5077265?v=4" width=115><br><sub>Jairo Teles</sub>](https://github.com/hardtelles) | [<img src="https://avatars.githubusercontent.com/u/47258234?v=4" width=115><br><sub>Wesley Gomes</sub>](https://github.com/Wesley-Gomes) | [<img src="https://avatars.githubusercontent.com/u/9051956?v=4" width=115><br><sub>Wilian Penaforte</sub>](https://github.com/wilianpenaforte) |
| :--------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------: |

Este README fornece uma visão geral do Projeto Fast-Eats, suas entregas e componentes. Para mais detalhes sobre cada aplicação e infraestrutura, consulte os respectivos links fornecidos.
