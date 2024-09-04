# Guia para Criar uma Máquina Virtual (VM) no Azure

Este guia descreve o processo de criação de uma máquina virtual (VM) no Azure usando o Azure Portal.

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
2. Na barra de pesquisa, digite `Virtual Machine` e selecione **Virtual machine** nos resultados.
3. Clique em **Create** para iniciar o processo de criação.

### 3. Configurar a Máquina Virtual

1. **Subscription**: Selecione a assinatura na qual a VM será criada.
2. **Resource Group**: Escolha um grupo de recursos existente ou crie um novo clicando em **Create new**.
3. **Virtual machine name**: Insira um nome exclusivo para a VM.
4. **Region**: Escolha a região onde a VM será hospedada.
5. **Availability options**: Configure as opções de disponibilidade, como zona de disponibilidade (opcional).
6. **Image**: Selecione a imagem do sistema operacional (por exemplo, Windows Server, Ubuntu).
7. **Size**: Selecione o tamanho da VM com base nas suas necessidades de CPU, RAM e armazenamento.

### 4. Configurar as Opções de Administração

1. **Username**: Insira um nome de usuário para o administrador.
2. **Password**: Defina uma senha forte para o usuário administrador.
3. **Inbound port rules**: Selecione as portas que devem ser abertas, como **RDP (3389)** para Windows ou **SSH (22)** para Linux.

### 5. Configurações Avançadas (Opcional)

- **Disks**: Configure o tipo e o tamanho dos discos de armazenamento.
- **Networking**: Configure a rede virtual, sub-rede e outros parâmetros de rede.
- **Management**: Configure opções de monitoramento, backup e outras configurações de gerenciamento.

### 6. Revisar e Criar

1. Revise todas as configurações.
2. Clique em **Review + create**.
3. Após a validação, clique em **Create**.

### 7. Acompanhar a Implantação

- Aguarde enquanto o Azure provisiona a máquina virtual.
- Após a conclusão, clique em **Go to resource** para acessar a VM.

### 8. Acessar a Máquina Virtual

- **Windows**: Use o Remote Desktop (RDP) para conectar-se à VM. Utilize o endereço IP público e as credenciais definidas anteriormente.
- **Linux**: Use o SSH para conectar-se à VM. Abra o terminal e execute:
  
  ```bash
  ssh <username>@<IP-da-VM>
