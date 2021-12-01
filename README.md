# dio-live-coding-aws
Repositório para o Live Coding do dia 05/05/2021


Criar Usuários com Amazon Cognito
		
	-Manage User Pool
		Acesso a recursos
		
		*User and groups
			Gerenciar usuários
		
		
	-Manage Identity Pools
		Permissões
		Roles: Conjuntos de políticas de acesso

Criar as Tabelas no Dynamo DB
	- Chave pk
		
	- Campos
		Pode criar campos novos ao inserir registros na aba Items -> Create Item

Criar Função no AWS Lambda
	Escolher a linguagem de programação Node.JS


Criar os endpoints/rotas no API Gateway -> HTTP Api

	-Integrations
		Integrar as funcoes lambda com as rotas
		
-- Nesse ponto as rotas estão expostas falta apenas liberar o acesso
		
	- Configurations
		Role name -> link para o IAM
		
		* Attach policies
			pesquisar por dynamodb
			Full acess (não recomendado em produção)
