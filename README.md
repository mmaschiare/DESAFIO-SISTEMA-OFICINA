# 🔧 Sistema de Gerenciamento de Oficina Mecânica

Sistema desenvolvido para otimizar a gestão de uma oficina mecânica, permitindo o cadastro e gerenciamento de clientes, veículos e agendamentos de serviços. O projeto busca substituir controles manuais por uma solução informatizada, organizada e segura.

## 📋 Sobre o Projeto

O projeto surgiu a partir da necessidade de solucionar problemas comuns na rotina de uma oficina mecânica, como perda de horários, duplicidade de informações e falhas no armazenamento de dados.

A aplicação tem como objetivo centralizar as informações, facilitar o gerenciamento dos serviços e garantir maior segurança no tratamento dos dados pessoais dos clientes, considerando as diretrizes da Lei Geral de Proteção de Dados (LGPD).

## 🚀 Funcionalidades

- **🔐 Autenticação de usuários:** login com validação em caso de falha na autenticação e controle de acesso com expiração de sessão.
- **🏠 Página principal:** exibição do nome do usuário autenticado, acesso aos recursos do sistema e opção de sair.
- **👥 Gerenciamento de clientes:** cadastro, busca e edição de informações dos clientes.
- **🚗 Gerenciamento de veículos:** cadastro de veículos associados a clientes previamente registrados.
- **📅 Gerenciamento de agendamentos:** listagem dos serviços agendados em ordem cronológica, com informações dos clientes e veículos relacionados.
- **✏️ Atualização de agendamentos:** alteração da data de serviços já cadastrados, com salvamento das modificações no banco de dados.
- **🔒 Proteção de dados:** armazenamento do CPF dos clientes de forma criptografada no banco de dados.

## 🛠️ Tecnologias Utilizadas

As tecnologias utilizadas no desenvolvimento devem ser documentadas de acordo com a implementação do projeto.

- **Linguagem de programação:** Python
- **Framework web:** Flask
- **Banco de dados:** [Informar o banco utilizado]
- **Frontend:** [Informar as tecnologias utilizadas]

## 🗄️ Banco de Dados

O banco de dados é responsável por armazenar e relacionar as informações dos usuários, clientes, veículos e agendamentos.

O projeto contempla:

- Estruturação das tabelas e definição dos tipos de dados.
- Utilização de chaves primárias e estrangeiras para manter a integridade dos registros.
- Relacionamento entre clientes, veículos e agendamentos.
- Script SQL para criação e população do banco de dados.
- Inserção de pelo menos três registros em cada tabela criada, conforme os requisitos do desafio.

## 🔐 Segurança

A segurança é um dos aspectos importantes do sistema. Entre os requisitos definidos, destacam-se:

- Validação das credenciais durante o login.
- Controle de expiração da autenticação.
- Criptografia do CPF dos clientes armazenado no banco de dados.
- Proteção dos dados pessoais conforme os princípios aplicáveis da LGPD.

## 📁 Estrutura do Projeto

A estrutura abaixo é uma sugestão de organização e deve ser adaptada aos arquivos reais do repositório.

```text
sistema-oficina-mecanica/
├── sistema/
│   ├── app.py
│   ├── templates/
│   └── static/
├── saep_db.sql
├── documentacao.pdf
├── der.png
└── README.md
```

## ⚙️ Como Executar

### Pré-requisitos

- Python instalado.
- Flask instalado.
- Banco de dados configurado.
- Script SQL do projeto disponível.

### Passos para execução

1. Clone o repositório:

   ```bash
   git clone URL_DO_SEU_REPOSITORIO
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd sistema-oficina-mecanica
   ```

3. Instale as dependências necessárias:

   ```bash
   pip install flask
   ```

4. Configure o banco de dados conforme as instruções do projeto e execute o script `saep_db.sql`.

5. Inicie a aplicação:

   ```bash
   python app.py
   ```

6. Acesse o endereço local informado pelo Flask no terminal.

**Observação:** os comandos e as dependências devem ser ajustados caso o projeto utilize outras bibliotecas ou configurações específicas.

## 📚 Documentação

O projeto prevê os seguintes documentos técnicos:

- **Documentação de software:** descrição dos requisitos funcionais e demais informações técnicas.
- **Diagrama Entidade-Relacionamento (DER):** representação visual das entidades e dos relacionamentos do banco de dados.
- **Script SQL:** criação e população das tabelas do banco de dados.

## 🎯 Objetivo do Projeto

Desenvolver uma solução que facilite a rotina de uma oficina mecânica por meio da organização dos cadastros, do controle dos agendamentos e da proteção das informações armazenadas.

---

Desenvolvido como projeto prático de desenvolvimento de sistemas, com foco em organização de dados, gerenciamento de informações e segurança de aplicações web.
