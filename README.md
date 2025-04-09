# API Azure

Uma API (Interface de Programação de Aplicações) é um conjunto de regras e definições que permite que diferentes softwares se comuniquem entre si. 
Ela define como as requisições são feitas, como as respostas são estruturadas e quais dados podem ser acessados ou manipulados.

A API do Azure é uma interface que permite interagir com os serviços da plataforma de nuvem Azure da Microsoft,
 como armazenamento, máquinas virtuais, banco de dados e inteligência artificial. 
 Ela permite automatizar processos e integrar esses serviços em aplicações externas.
 
## Possibilidades com de uso com exemplos

Exemplo de uso da API do Azure:

1. Criar um recurso de armazenamento no Azure via API: Para criar um armazenamento, você pode usar a API REST do Azure. 
O endpoint seria algo assim:

```bash
POST https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.Storage/storageAccounts/{storageAccountName}?api-version=2021-04-01
```

2. Consultar dados em um banco de dados SQL no Azure: 
Com a API do Azure, você pode também executar comandos SQL em um banco de dados do Azure.
 Um exemplo seria conectar-se ao banco e fazer uma consulta simples, como:
 
```pgsql
 GET https://{your-server-name}.database.windows.net/{database-name}/tables/{table-name}?api-version=2020-02-02
```
 
## Referências

- [Azure API rest](https://learn.microsoft.com/pt-br/rest/api/azure/);
- [Azure API center](https://learn.microsoft.com/pt-br/azure/api-center/overview).
