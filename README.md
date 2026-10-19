# TaskFlow Console

Aplicação de console desenvolvida em C# com .NET 10 para gerenciamento de tarefas. O projeto permite organizar tarefas e acompanhar seu status de conclusão.

## Tecnologias utilizadas

- C#
- .NET 10
- xUnit para testes unitários
- Git e GitHub para controle de versão

## Funcionalidades

- Criar tarefas.
- Listar tarefas cadastradas.
- Marcar tarefas como concluídas.
- Buscar tarefas pelo identificador.
- Validar títulos de tarefas vazios ou nulos.
- Gerenciar tarefas em memória.

## Estrutura do projeto

```text
taskflow-console/
├── TaskFlow.sln
├── TaskFlow.Console/
│   ├── TaskFlow.Console.csproj
│   └── Program.cs
├── TaskFlow.Tests/
│   ├── TaskFlow.Tests.csproj
│   └── TaskManagerTests.cs
├── README.md
└── .gitignore
```

> A estrutura acima representa a organização planejada para a solução. Os arquivos e nomes definitivos podem variar conforme a implementação.

## Pré-requisitos

Antes de executar o projeto, instale:

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Git para Windows](https://git-scm.com/downloads/win)

Para conferir as instalações pelo Git CMD:

```bash
dotnet --version
git --version
```

## Como clonar o repositório

Abra o Git CMD e execute:

```bash
git clone https://github.com/Benadinhog/taskflow-console.git
cd taskflow-console
```

Se o repositório já estiver clonado no computador, entre na pasta existente em vez de clonar novamente.

## Como compilar

Na pasta raiz do projeto, execute:

```bash
dotnet restore
dotnet build TaskFlow.sln
```

## Como executar

Para iniciar a aplicação de console:

```bash
dot
