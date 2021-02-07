# Zull Api Gateway

Projeto de implementação do API Gateway conhecido como Zuul.

## Requisitos

- Ter os serviços **carshop** e **boleto** rodando.
    - [Link para o projeto carshop](https://github.com/amokawa/carshop)
    - [Link para o projeto boleto](https://github.com/amokawa/boleto)

## Como executar este serviço

- Baixar o projeto na máquina que rodará o serviço.
- Executar: `.\mvnw sprint-boot:run`

## Verificando a aplicação

- O serviço será executado na porta `8080`.
- Caso esteja executando localmente, basta acessar `http://localhost:8080/` e verificar se a página com o título
  `Whitelabel Error Page` é exibido.