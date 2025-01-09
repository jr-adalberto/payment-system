# Sistema de Pagamento Pix - Spring Boot

## Descrição

Este projeto foi desenvolvido para fins educacionais, com o objetivo de criar um sistema de pagamento via Pix integrado à instituição EFI Bank. Através da geração de um token, um QR Code é gerado para realizar pagamentos via Pix.

O sistema foi desenvolvido utilizando o framework **Spring Boot** com a configuração de **Spring Security** para autenticação e segurança. A aplicação foi testada utilizando **Postman** e configurada com **Docker** para simplificar o processo de execução em ambientes isolados.

## Funcionalidades

- **Autenticação**: Implementação de segurança usando Spring Security.
- **Geração de Token**: Criação de tokens de autenticação e autorização.
- **Geração de QR Code**: A partir do token gerado, um QR Code é criado para realizar o pagamento via Pix.
- **Testes com Postman**: Realizados testes de integração da API.
- **Uso de Docker**: Dockerizado para facilitar o deploy e testes em qualquer ambiente.

## Tecnologias Utilizadas

- **Spring Boot**: Framework para desenvolvimento de aplicativos Java.
- **Spring Security**: Autenticação e controle de segurança.
- **Postman**: Ferramenta para testes de APIs.
- **Docker**: Para ambientes isolados e portabilidade.
- **MySQL Workbench**: Banco de dados utilizado no projeto.


## Tecnologias Utilizadas

 - Gostaria de agradecer ao @leminhosdev pelo excelente curso e conteúdo que me ajudaram a desenvolver este projeto. Sua abordagem prática e detalhada sobre o uso de tecnologias para a construção de sistemas de pagamento foi essencial para o meu aprendizado.

## Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/SeuUsuario/sistema-pagamento-pix.git
