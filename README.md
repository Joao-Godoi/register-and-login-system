# Register and Login System - RLS

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## Descrição

Projeto criado durante a aula de Segurança da Informação do curso de Engenharia de Sofware (Faculdade UMC). O projeto tem como objetivo o aprendizado e o entendimento da utlização de criptografia e autenticação em serviços online.
O sistem consiste em uma feature de registro de usuários através de email e senha, onde a senha será criptografada antes de ser salva e também uma feature de login, na qual irá gerar um token JWT caso o email e senha estejam corretos.

## Tecnologias Utilizadas

- **Python**: Linguagem utilizada para codificação do projeto.
- **Bcrypt**: Biblioteca para gerar hashing seguro de senhas.
- **PyJWT**: Biblioteca para autenticação via Tokens JWT.
- **Cryptography**: Biblioteca para AES e RSA.

## Funcionalidades

- **Cadastro de usuários**: Feature para criar usuários através de email e senha, a senha será salva de forma criptografada utilizando Bcrypt.
- **Login**: Feature para usuários já cadastrados poderem tentar se logar, caso email e senha estejam corretos será gerado um token JWT.
- **Enviar mensagem**: Feature responsável pelo envio de mensagens criptografadas com AES.
- **Receber mensagem**: Feature responsável pelo recebimento de mensagens criptografadas que serão descriptografadas utlizando RSA.
