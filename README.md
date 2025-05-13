# XP-IA-Fundamentals
Repositório para o curso XP IA fundamentals
Passos para criação de uma máquina virtual no Azure
Para configurar uma máquina virtual no Azure, você pode seguir os passos abaixo, que são baseados na documentação oficial do Azure:

Acesse o Portal do Azure: Entre no Portal do Azure.
Crie uma Máquina Virtual:
No portal, procure por "Máquinas Virtuais" e selecione a opção.
Clique em "Criar" e depois em "Máquina virtual do Azure".
Detalhes da Instância:
Insira o nome da máquina virtual.
Escolha a imagem do sistema operacional, como "Windows Server 2022 Datacenter" ou "Ubuntu 20.04 LTS".
Selecione a região onde a VM será criada.
Conta de Administrador:
Forneça um nome de usuário e uma senha para a conta de administrador.
Regras de Porta de Entrada:
Escolha as portas que devem ser acessíveis, como RDP (3389) para Windows ou SSH (22) para Linux.
Revisar e Criar:
Revise as configurações e clique em "Criar" para iniciar a implantação da máquina virtual.
Documentação oficial do Azure: https://learn.microsoft.com/en-us/azure/virtual-machines/windows/quick-create-portal?wt.mc_id=knowledgesearch_inproduct_copilot-in-azure
###
Criar um banco de dados no Azure
Criar Banco de dados no Azure

Definir o tipo de ambiente para o banco (IAAS, PAAS e SAAS)

Observar a medida que customiza o BD a calculadora de custos que oferece um resumo em tempo real.

Criar a máquina virtual

Vincular o BD e iniciar a criação deste.

1 -  Definir o tipo de Banco de dados

a) Azure SQL Database: Ideal para quem busca um banco de dados relacional gerenciado, com alta disponibilidade e escalabilidade automática.
b) Azure Cosmos DB: Perfeito para aplicações que exigem baixa latência e alta disponibilidade global, suportando múltiplos modelos de dados.
c) Azure Database for MySQL/PostgreSQL: Oferece um banco de dados relacional de código aberto, com suporte para MySQL ou PostgreSQL, garantindo flexibilidade e familiaridade para desenvolvedores.

Há outros fornecedores de banco de dados disponíveis via imagem com licenciamento específico.
Oracle, Db2 e NoSQL

Exemplo de BD SQL Server

Para criar um banco de dados SQL no Azure, você pode seguir este guia rápido usando o portal do Azure:

Acesse a página de opção de implantação do SQL no portal do Azure.
Em SQL databases, mantenha o Tipo de recurso como Single database e selecione Create.
Na guia Basics do formulário Create SQL Database, sob Project details, selecione a Subscription desejada.
Para Resource group, selecione Create new, insira myResourceGroup e clique em OK.
Para Database name, insira mySampleDatabase.
Para Server, selecione Create new e preencha o formulário New server com os seguintes valores:
Server name: Insira um nome único, como mysqlserver12345.
Location: Selecione uma localização da lista.
Authentication method: Selecione Use SQL authentication.
Server admin login: Insira azureuser.
Password: Insira uma senha que atenda aos requisitos e confirme-a.
Deixe Want to use SQL elastic pool como No.
Para Workload environment, especifique Development para este exercício.

Documentação oficial:
https://learn.microsoft.com/en-us/azure/azure-sql/database/single-database-create-quickstart?view=azuresql&wt.mc_id=knowledgesearch_inproduct_copilot-in-azure#create-a-single-database

###
