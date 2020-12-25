<h1 align="center">
    <img alt="BuilderTCC" title="#BuilderTCC" src="./images/banner-2.png" />
</h1>

<h4 align="center"> 
	🚧 Builder TCC 🚀 em construção... 🚧
</h4>


## 💻 Sobre o projeto

📝 Builder TCC - é uma plataforma criada principalmente para estudantes que estão desenvolvendo seus trabalhos de conclusão de curso. No Builder TCC é possível tranformar um texto comum em um texto com todas as formatações exigidas pela ABNT.


## 🎨 Layout

### Dashboard

A dashboard é a página inicial que o usuário acessa, ela possui tema claro, escuro e outras features:

| **Tema Escuro** | **Tema Claro** |
|-----------------|----------------|
| <img alt="Dashboard_Dark" title="#Dashboard Dark Mode" src="./images/dashboard_dark.png" width="800px"/> | <img alt="Dashboard_Light" title="#Dashboard Light Mode" src="./images/dashboard_light.png" width="800px"/> |

|                                                                                                                                                    Modal de confirmação de ação:                                                                                                                                                    	|
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:	|
| Para evitar que o usuário cometa erros e acabe perdendo o documento em progresso, é apresentado um modal com uma mensagem para confirmar a ação do usuário, por exemplo: se o usuário está com um documento aberto e tenta acessar as funcionalidade Editar ou Upload, a mensagem é apresentada aguardando a confirmação do usuário 	|
| <p align="center"><img alt="Modal de confirmação" title="#Modal de confirmação" src="./images/document-edit_upload.png" width="700px"/></p> |

	
|                                                    **Ocultar/Mostrar:**                                                 |
|:-----------------------------------------------------------------------------------------------------------------------:|
|                       A sidebar pode ser expandida ou ocultada através dos ícones mostrados abaixo                      |
| <img alt="Ocultar/Mostrar" title="#Ocultar/Mostrar" src="./images/app-drawer.png" width="200px"/> 	|


### Funcionalidades
Os usuários terão acesso a dashboard onde terão as seguinte opções:

|                                      **Novo:**                                       	|
|:---------------------------------------------------------------------------------:	|
| Exibe um espaço em branco onde será possível mexer no documento adicionando texto 	|
|        <img alt="Novo" title="#Novo" src="./images/document.png" width="700px"/>      |

|                                      **Editar:**                                       	|
|:---------------------------------------------------------------------------------:	        |
| Apresenta um modal para carregamento de um arquivo com a extensão específica do Builder TCC 	|
|          <img alt="Editar" title="#Editar" src="./images/dashboard-edit.png" width="700px"/>            |

|                                      **Upload:**                                      |
|:---------------------------------------------------------------------------------:	|
| Apresenta um modal para carregamento de um arquivo com qualquer extensão de texto 	|
|       <img alt="Upload" title="#Upload" src="./images/dashboard-upload.png" width="700px"/>       |


## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Expo][expo]
- [Node.js][nodejs]
- [React][reactjs]
- [React Native][rn]
- [TypeScript][typescript]


## 🚀 Como executar o projeto

Podemos considerar este projeto como sendo divido em três partes:
1. Back End (pasta server) 
2. Front End (pasta web)
3. Mobile (pasta mobile)

💡Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js][nodejs]. 
Além disto é bom ter um editor para trabalhar com o código como [VSCode][vscode]

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/tgmarinho/nlw1

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw1

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### 🧭 Rodando a aplicação web (Front End)

```bash
# Clone este repositório
$ git clone https://github.com/tgmarinho/nlw1

# Acesse a pasta do projeto no seu terminal/cmd
$ cd nlw1

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```
