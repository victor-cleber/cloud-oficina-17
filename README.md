# Oficina de Projetos Nº 17

<p align="center">
  <a href="#HowToUseThisProject">The Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Lab">Lab</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>


<p align="justify">The project contain a list of labs developed to enhance my Terraform skills using diverse cloud providers.</p>

## 🚀 O PROBLEMA

A Upper Trends é uma startup que recebeu um aporte para escalar seu negócio e
conforme o contrato com investidores, precisa alcançar a marca de 2 milhões de
usuários em 1 ano com uma estimativa de 1 milhão de acessos por dia e as
campanhas de marketing começarão em 2 semanas.
Uma das principais exigências dos investidores é que a aplicação seja rápida e não
tenha quedas quando começarem os primeiros acessos.
Em testes feitos pela equipe técnica, a aplicação apresentou lentidão e analisando o
cenário atual constatou-se que a arquitetura não é tolerante a falhas.
O seu time de consultoria recebeu uma solicitação de proposta para execução do
projeto.

![plot](./diagrams/arquitetura_atual.jpeg)


## O OBJETIVO
O objetivo é que a aplicação tenha alta disponibilidade e escalabilidade com o
menor custo possível, cumprindo os pilares do Well Architect framework da AWS.

## DESCRIÇÃO TÉCNICA
Atualmente essa aplicação já está na AWS em uma instância EC2
Aplicação desenvolvida em Dotnet core 7
Banco de dados SQLServer
Deve ser executados scripts para popular o Banco
Scripts estão na plataforma de Ensino dentro do Projeto /Scripts do projeto

A aplicação já está usando como armazenamento de objetos o S3 da AWS.
Arquivos para o storage já estão na estrutura de pastas que deve ficar e estão
disponíveis na pasta /imagens no projeto
Arquivo de configuração da aplicação para conexão com o Banco de dados e
storage esta em Source/postcard/appsettings.json

## 📝 ITENS A SEREM AVALIADOS
- Apresentação - visão de negócio
- Apresentação - detalhes técnicos
- Arquitetura
- Painel de monitoramento com Notificação (discord, telegram, whatsapp,email,SMS)
- Documentação
- Testes
- Participação dos integrantes do grupo
- Demonstração
- Deploy


Happy project 😊

##  🔗 License

This project is under an MIT License. See more details in [LICENSE](LICENSE) for more information.

---


