# Guia para Criar um Servidor de Banco de Dados SQL no Azure

Este guia descreve o processo de criação de um servidor de banco de dados SQL no Azure usando o Azure Portal.

## Pré-requisitos

Antes de começar, certifique-se de que você tem:

- Uma conta ativa na [Azure](https://portal.azure.com/).
- Permissões suficientes para criar recursos no Azure.

## Passo a Passo

### 1. Acessar o Azure Portal

- Navegue até o [Azure Portal](https://portal.azure.com/).
- Faça login com suas credenciais.

### 2. Criar um Novo Recurso

1. No painel esquerdo, clique em **Create a resource**.
2. Na barra de pesquisa, digite `SQL Database` e selecione **SQL Database** nos resultados.
3. Clique em **Create** para iniciar o processo de criação.

### 3. Configurar o Banco de Dados SQL

#### 3.1. Configurar o Servidor de Banco de Dados

1. **Subscription**: Selecione a assinatura na qual o banco de dados será criado.
2. **Resource Group**: Escolha um grupo de recursos existente ou crie um novo clicando em **Create new**.
3. **Database name**: Insira um nome exclusivo para o banco de dados.
4. **Server**: Clique em **Create new** para configurar um novo servidor SQL:
   - **Server name**: Insira um nome único para o servidor.
   - **Server admin login**: Insira um nome de usuário para o administrador do servidor.
   - **Password**: Defina uma senha forte.
   - **Location**: Escolha a região onde o servidor será hospedado.
5. **Want to use SQL elastic pool?**: Escolha **No** (opcional, para configurações básicas).
6. **Compute + storage**: Clique em **Configure database** para escolher a camada de desempenho e o tamanho de armazenamento. Selecione conforme suas necessidades e orçamento.

#### 3.2. Configurar a Rede

1. **Connectivity method**: Escolha **Public endpoint** para permitir conexões externas (recomendado para fins de teste).
2. **Firewall rules**: Configure as regras de firewall para permitir o acesso ao servidor SQL. Adicione o endereço IP do cliente ou clique em **Add client IP** para adicionar automaticamente o IP do seu computador.

### 4. Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Review + create**.
3. Após a validação, clique em **Create**.

### 5. Acompanhar a Implantação

- Aguarde enquanto o Azure provisiona o servidor de banco de dados SQL.
- Após a conclusão, clique em **Go to resource** para visualizar o banco de dados e o servidor.

### 6. Conectar-se ao Servidor SQL

- Utilize ferramentas como o **SQL Server Management Studio (SSMS)** ou **Azure Data Studio** para se conectar ao banco de dados SQL.
- Use o nome do servidor, o login do administrador e a senha que você criou.

### 7. Gerenciar o Banco de Dados

- Você pode criar novas bases de dados, gerenciar tabelas, realizar consultas SQL e configurar backups diretamente através do Azure Portal ou ferramentas de gerenciamento.

## Conclusão

Parabéns! Você criou com sucesso um servidor de banco de dados SQL no Azure. Agora você pode começar a gerenciar seus dados na nuvem.

## Referências

- [Documentação Oficial do Azure SQL Database](https://docs.microsoft.com/azure/azure-sql/)
- [Tutoriais do Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-tutorials)
