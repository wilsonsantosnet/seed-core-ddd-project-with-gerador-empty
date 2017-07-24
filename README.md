# seed-core-ddd-project-with-gerador-empty
Seed vazio para projetos  SPA / DDD / Gerador

1-) Clonar Esse Rep

2-) rodar npm install

3-) abrir solution seed.sln

4-) compilar projeto

4.1-) Conferir arquivo ConfigExternalResources no greador para ver quais repositórios serão clonados

5-) Clicar com botão direito no projeto de gerador e rodar em debug

6-) escolher a opção 1 (clonar e copiar para aplicação)

7-) Compila

8-) no gerador configurar a classe ConfigContext com as tabelas que serão geradas

9-) Configurar connection string no gerador app.config

10-) Rodar gerador opção 3 (gerar código)

10-) Configurar SSO no arquivo GlobalService do  projeto de UI (informações do cliente , verificar isso no projeto de SSO arquivo Config)

11-) no projeto de API no arquivo  Program descomentar  essa linha ".UseStartup<Startup>()"

12-) no projeto de SSO no arquivo UserServices descomentar código


