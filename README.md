Aqui está o `README.md` com o conteúdo em um bloco único:

```markdown
# Sistema Financeiro

Este é um sistema financeiro desenvolvido em C# para gerenciamento de finanças pessoais e empresariais.
O projeto permite o controle de receitas, despesas, contas a pagar e receber, além de gerar relatórios financeiros detalhados.

## Funcionalidades

- Cadastro de receitas e despesas
- Cadastro de contas a pagar e receber
- Geração de relatórios financeiros
- Visualização de gráficos de desempenho financeiro
- Exportação de relatórios para Excel e PDF

## Requisitos

- .NET Core 3.1 ou superior
- Visual Studio 2019 ou superior (opcional)
- SQL Server (ou outro banco de dados compatível)

## Instalação

### Passo 1: Clonar o repositório

Clone o repositório para sua máquina local usando o comando:

```bash
git clone https://github.com/markesjp/Sistema-Financeiro.git
```

### Passo 2: Restaurar pacotes NuGet

Navegue até o diretório do projeto e execute o seguinte comando para restaurar os pacotes NuGet necessários:

```bash
dotnet restore
```

### Passo 3: Configurar o banco de dados

Atualize a string de conexão do banco de dados no arquivo `appsettings.json` de acordo com o ambiente e o servidor de banco de dados que você está utilizando.

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=SistemaFinanceiro;User Id=seu_usuario;Password=sua_senha;"
  }
}
```

### Passo 4: Executar as migrações do banco de dados

Aplique as migrações para criar as tabelas necessárias no banco de dados:

```bash
dotnet ef database update
```

### Passo 5: Executar o projeto

Finalmente, execute o projeto:

```bash
dotnet run
```

## Contribuição

Se você deseja contribuir com o projeto, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma nova branch com a sua feature: `git checkout -b minha-feature`.
3. Faça commit das suas alterações: `git commit -m 'Minha nova feature'`.
4. Envie para a branch principal: `git push origin minha-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob os termos da [MIT License](LICENSE).

## Contato

Para mais informações, entre em contato através do e-mail: `oliveira.marquesde@gmail.com`.
