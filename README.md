
# 34SCJ - Trabalho de Conclusão - Mobile Development

## Integrantes: 

| RM     	| NOME                     	    |
|--------	|-------------------------------|
| 334242  | BRUNO DELPHINO ZAMBOTTI       |
| 334110  | HENRIQUE SUEL DA SILVA        |
| 334151  | MARCELO TADEU MARCHESONI ZANI |

## Repositório

### [Link do repositório](https://github.com/bruno-zambotti/trabalho-mobile-development-34scj)

## Informações do Projeto

### Telas

| Tela | Exemplo | 
|:--------|:--------:|
| Login  | ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| Criação de usuário | ![Smartphone] (https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| Cadastro | ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| SplashScreen | ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| Lista de Exibição dos Dados| ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| Edição dos dados | ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento
| Sobre | ![Smartphone](https://img.icons8.com/android/26/000000/touchscreen-smartphone.png) Em desenvolvimento

## Como executar a aplicação

### Executando a API REST 
O projeto utiliza uma API REST baseada em arquivo que expõe todos os verbos necessários ao nosso aplicativo, a saber GET, POST, PUT e DELETE.

Para realizar a instalação, é necessário executar os passos a seguir:

Importante: Nos computadores da FIAP deve-se executar o comando abaixo antes de instalar a dependência do json-server. 
npm set strict-ssl false

1. Instalar a dependência do json-server execute o comando abaixo:
npm install -g json-server

2. Executar na linha de comandos do sistema operacional (ex: terminal, cmd, powershell, etc), o seguinte comando
json-server --watch api.json
Pode ser necessário navegar até a pasta em que o arquivo api.json encontra-se antes de executar o comando.

3.  Após aparecer a seguinte mensagem na linha de comando:
	~~~ 
	\{^_^}/ hi!

	Loading api.json
	Done

	Resources
	http://localhost:3000/notes

	Home
	http://localhost:3000

	Type s + enter at any time to create a snapshot of the database
	Watching... 
	  ~~~
  
	Abra o navegador de sua preferência e digite a seguinte url:
    http://localhost:3000/notes

4. Após abrir a url informada no passo anterior você deverá visualizar as seguintes informações:

![Exemplo](https://raw.githubusercontent.com/bruno-zambotti/trabalho-mobile-development-34scj/master/exemplo-json.png)

5. Tendo realizado todos os passos anteriores com sucesso a aplicação já poderá consumir e manipular os dados dessa API normalmente.

### Executando o projeto
Em desenvolvimento.
