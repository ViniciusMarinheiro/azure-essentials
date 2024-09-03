# Guia para Criar uma Azure Storage Account

Este guia descreve o processo de criação de uma Azure Storage Account usando o Azure Portal.

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
2. Na barra de pesquisa, digite `Storage Account` e selecione **Storage account** nos resultados.
3. Clique em **Create** para iniciar o processo de criação.

### 3. Configurar a Storage Account

1. **Subscription**: Escolha a assinatura na qual o recurso será criado.
2. **Resource Group**: Selecione um grupo de recursos existente ou crie um novo clicando em **Create new**.
3. **Storage account name**: Insira um nome exclusivo para a sua conta de armazenamento.
4. **Region**: Escolha a região onde o recurso será hospedado.
5. **Performance**: Selecione o tipo de desempenho (Standard ou Premium).
6. **Redundancy**: Escolha a redundância dos dados, como LRS (Locally-redundant storage) ou GRS (Geo-redundant storage).

### 4. Configurações Avançadas (Opcional)

- **Networking**: Configure a rede se necessário.
- **Data Protection**: Configure as opções de proteção de dados.
- **Encryption**: Escolha as configurações de criptografia.

### 5. Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Review + create**.
3. Após a validação, clique em **Create**.

### 6. Verificar a Criação do Recurso

- Aguarde enquanto o Azure provisiona a Storage Account.
- Após a conclusão, clique em **Go to resource** para visualizar a nova Storage Account.

## Conclusão

Parabéns! Você criou com sucesso uma Azure Storage Account. Agora você pode gerenciar seus dados diretamente no Azure Portal.

## Referências

- [Documentação Oficial da Azure Storage](https://docs.microsoft.com/azure/storage/)
- [Tutoriais do Azure](https://docs.microsoft.com/azure/tutorials/)

