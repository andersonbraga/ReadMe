# e-Agenda MedicalCare

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Tests](https://img.shields.io/badge/tests-100%25-success)
![License](https://img.shields.io/badge/license-MIT-blue)










O e-Agenda Médica é uma solução web inovadora para a gestão de cronogramas de clínicas médicas, permitindo um planejamento eficiente e a otimização dos procedimentos diários.

## Tabela de Conteúdos

- [Sobre o Projeto](#sobre-o-projeto)
- [Características](#características)
- [Tecnologias](#tecnologias)
- [Começando](#começando)
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Contribuindo](#contribuindo)
- [Licença](#licença)
- [Contato](#contato)
- [Agradecimentos](#agradecimentos)

## Sobre o Projeto

![sistema](https://github.com/andersonbraga/ReadMe/assets/11825153/4746023b-21f7-4b66-b6c0-503efdd31db0)





## Características

- Agendamento de consultas e cirurgias
- Gerenciamento de conflitos de agendamento
- Relatórios dinâmicos
- Autenticação segura

## Tecnologias

O projeto e-Agenda Médica utiliza várias tecnologias de ponta no desenvolvimento do frontend e backend.

### Frontend

- Angular `^16.2.0`
- Angular Material `^16.2.12`
- Bootstrap `^5.3.2`

### Backend

- ASP.NET Core `6.0`
- Entity Framework Core `7.13.0`
- AutoMapper `12.0.1`
- FluentValidation `11.8.0`

## Começando

### Pré-requisitos

Antes de iniciar, certifique-se de atender aos seguintes requisitos:

- [.NET 6 SDK](https://dotnet.microsoft.com/download)
- [Node.js e npm](https://nodejs.org/en/download/)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)

### Instalação

Siga estas etapas simples para iniciar o projeto localmente:

```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/e-agenda-medica.git](https://github.com/andersonbraga/eAgendaMedicalCare)

# Navegue até a pasta do projeto back-end
cd /backend

# Restaure os pacotes NuGet
dotnet restore

# Configure a string de conexão do banco de dados em appsettings.json

# Aplique as migrations do banco de dados
dotnet ef database update

# Inicie a API
dotnet run

# Em um novo terminal, navegue até a pasta do front-end
cd ../frontend

# Instale as dependências do projeto Angular
npm install

# Inicie o aplicativo Angular
ng serve

# O aplicativo estará disponível em http://localhost:4200 
```
## Uso

Após a instalação e execução do projeto, você pode começar a utilizar o e-Agenda Médica para gerenciar o cronograma da clínica. Aqui estão algumas das operações que você pode realizar:

- **Agendar uma nova consulta ou cirurgia**: Navegue até a seção de agendamento e preencha os detalhes da atividade médica.
- **Visualizar o cronograma**: Verifique o calendário para uma visão geral das atividades agendadas.
- **Modificar um agendamento existente**: Edite os detalhes de uma atividade médica caso haja alterações.
- **Relatório de atividades**: Acesse relatórios para analisar o volume de trabalho dos médicos.

Para uma demonstração mais interativa, aqui está um GIF mostrando o processo de agendamento de um medico. 
:



![inserirmedico](https://github.com/andersonbraga/ReadMe/assets/11825153/7c15bcd2-0229-428c-8cef-c1db134f443b)





## Contribuindo

Contribuições são o que tornam a comunidade open source um lugar incrível para aprender, inspirar e criar. Quaisquer contribuições que você fizer são **muito apreciadas**.

1. Faça um Fork do projeto
2. Crie sua Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Faça suas alterações e commit (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença

Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE.txt) para detalhes.

## Contato



Projeto Link: [https://github.com/andersonbraga/eAgendaMedicalCare](https://github.com/andersonbraga/eAgendaMedicalCare)

## Agradecimentos

- [Nome do Contribuidor](https://github.com/link-para-contribuidor)
- [Nome do Contribuidor](https://github.com/link-para-contribuidor)
- [Nome do Contribuidor](https://github.com/link-para-contribuidor)
