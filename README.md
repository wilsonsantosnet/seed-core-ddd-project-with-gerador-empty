# seed-core-ddd-project-with-gerador-empty
Seed vazio para projetos  SPA / DDD / Gerador


0-) Instalar git shell [https://git-for-windows.github.io/]

0.1) Instalar o Conemu [https://www.fosshub.com/ConEmu.html/ConEmuSetup.161206.exe]

1-) Clonar Esse Rep na pasta C:\Projetos (git clone [https://github.com/wilsonsantosnet/seed-core-ddd-project-with-gerador-empty.git])

2-) abrir solution seed.sln

3-) compilar projeto

4-) Conferir arquivo ConfigExternalResources no greador para ver quais repositórios serão clonados

5-) Clicar com botão direito no projeto de gerador e rodar em debug

6-) escolher a opção 1 (clonar e copiar para aplicação)

6.1) No projeto Seed.Gen Mostar Todos os Arquivos 

6.2) Incluir na pasta template as pastas Back e Front

6.3) Selecionar todos os aquivos da pasta Back e Front, clicar com botão direito , opção property e marcar para Copiar Sempre (Copy Always)

7-) Compilar

8-) abrir prompt de comando entrar na pasta Seed.Spa.UI rodar npm install (Instalar node.js caso ainda não tenha [https://nodejs.org/en/])

9-) no gerador configurar a classe ConfigContext com as tabelas que serão geradas [linha 46]

10-) Configurar connection string no gerador app.config

11-) Verifica no arquivo App.Config os caminhos onde serão gerador os arquivos de Back e front variaves de appSettings

12-) Rodar gerador opção 3 (gerar código)

13-) No projeto Seed.ui pasta Presentation, encontrar o arquivo /src/app/global.service.ts, nesse arquivo existe uma classe chamanda AuthSettings com uma propriedade chamada CLIENT_ID, essa propriedade deve conter o valor  da propriedade ClientId confirada no item do tipo implicit, no método GetClients do arquivo Config.cs do projeto de Sso.Server.Api da pata SSO\Auth 

14-) no projeto de Seed.API da pasta Services no arquivo  Program descomentar  essa linha ".UseStartup<Startup>()"

15-) no projeto de SSO no arquivo UserServices descomentar código


