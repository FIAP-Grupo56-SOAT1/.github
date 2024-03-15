Documentação do projeto Fasteats SOAT1 grupo56

Como utilizar:<br>
1) Alterar as credenciais do github
2) Alterar as credenciais STS na AWS
3) Alterar a URL do EC2 nas credencias de Producao
4) Executar os pipeline abaixo:
   Infra das aplicações: Pedido, Pagamento, Produção

Obs: Caso as credenciais foram recriadas ou as aplicações, atualizar todas as credenciais na AWS e URLs de NLB, RDS, EC2

Aplicações:

Autenticacao:<br>

[Lambda STS](https://github.com/FIAP-Grupo56-SOAT1/LAMBDA_STS_FAST-EATS/actions/workflows/build-and-deploy.yml)<br>
[Lambda Autenticacao](https://github.com/FIAP-Grupo56-SOAT1/LAMBDA_AUTH_FAST-EATS/actions/workflows/build-and-deploy.yml)<br>
[API Gateway](https://github.com/FIAP-Grupo56-SOAT1/INFRA_API_GATEWAY_FAST-EATS/actions/workflows/deploy-producao.yml)<br>


Pedido:<br>
[Infra do banco de dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[infra da aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PEDIDO_FAST-EATS/actions)<br>

Pagamento:<br>
[Infra do banco de dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_PAGAMENTO_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[infra da aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_PAGAMENTO_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PAGAMENTO_FAST-EATS/actions)<br>

Produção:<br>
[Infra do banco de dados](https://github.com/FIAP-Grupo56-SOAT1/INFRA_DB_PRODUCAO_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[infra da aplicação](https://github.com/FIAP-Grupo56-SOAT1/INFRA_ECS_PRODUCAO_FAST-EATS/actions/workflows/deploy-producao.yml)<br>
[Aplicação](https://github.com/FIAP-Grupo56-SOAT1/MICROSERV_PRODUCAO_FAST-EATS/actions)<br>





<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
