# seed-core-ddd-project-with-gerador-empty
Seed vazio para projetos  SPA / DDD / Gerador

1-) Clonar Esse Rep (git clone https://github.com/wilsonsantosnet/seed-core-ddd-project-with-gerador-empty.git)

2-) abrir solution seed.sln

3-) compilar projeto

4-) Conferir arquivo ConfigExternalResources no greador para ver quais repositórios serão clonados

5-) Clicar com botão direito no projeto de gerador e rodar em debug

6-) escolher a opção 1 (clonar e copiar para aplicação)

7-) Compilar

8-) rodar npm install

9-) no gerador configurar a classe ConfigContext com as tabelas que serão geradas

10-) Configurar connection string no gerador app.config

11-) Rodar gerador opção 3 (gerar código)

12-) Configurar SSO no arquivo GlobalService do  projeto de UI (informações do cliente , verificar isso no projeto de SSO arquivo Config)

13-) no projeto de API no arquivo  Program descomentar  essa linha ".UseStartup<Startup>()"

14-) no projeto de SSO no arquivo UserServices descomentar código


