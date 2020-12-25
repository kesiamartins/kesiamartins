<h4 align="center"> 
	 Criptografia RSA 🚀
</h4>


## 💻 Sobre o projeto

🔐 Criptografia RSA - Trabalho de conclusão do segundo semestre da faculdade. A criptografia RSA é uma forma de criptografia muito conhecida que permite a transmissão segura de dados. Neste projeto de criptografia que desenvolvi, o sistema encripta a chave pública, ao mesmo tempo que gera a chave de decriptação, que é secreta (chave privada).

## :heavy_exclamation_mark: Entendendo o projeto

Abaixo temos uma tabela com algumas ações possíveis no sistema: 

| Funcionalidade              	| Ações possíveis                                                                                                                                	| Imagem          	|
|-----------------------------	|------------------------------------------------------------------------------------------------------------------------------------------------	|-----------------	|
|   Tela inicial do programa  	| Realizar login ou criar um novo registro                                                                                                       	| <img alt="Tela Inicial do Programa" title="#Tela Inicial do Programa" src="./images/1.png"/> 	|
| Criar um novo registro      	| Informar um login e uma senha para criação do novo registro                                                                                    	| <img alt="Criar um novo registro" title="#Criar um novo registro" src="./images/4.png"/> 	|
| Usuário logado              	| 1. Ler mensagem recebida ou enviada (decriptada)<br>2. Escrever mensagem para um usuário<br>3. Ver os créditos do programa<br>4. Fazer logoff  	| <img alt="Usuário logado" title="#Usuário logado" src="./images/5.png"/> 	|
| Escrever mensagem 1         	| Escolher um usuário para enviar a mensagem                                                                                                     	| <img alt="Escrever mensagem 1" title="#Escrever mensagem 1" src="./images/6.png"/> 	|
| Escrever mensagem 2         	| Escrever a mensagem a ser enviada                                                                                                              	| <img alt="Escrever mensagem 2" title="#Escrever mensagem 2" src="./images/7.png"/> 	|
| Ler mensagem 1              	| Selecionar uma mensagem a ser lida                                                                                                             	| <img alt="Ler mensagem 1" title="#Ler mensagem 1" src="./images/10.png"/> 	|
| Ler mensagem 2              	| Ler a mensagem enviada para outro usuário (decriptada)                                                                                         	| <img alt="Ler mensagem 2" title="#Ler mensagem 2" src="./images/11.png"/> 	|
| Logoff                      	| Usuário é retornado para Tela inicial do programa                                                                                              	| <img alt="Logoff" title="#Logoff" src="./images/13.png"/> 	|
| Fazer login                 	| Informar o login e a senha do usuário que recebeu a mensagem                                                                                   	| <img alt="Fazer login" title="#Fazer login" src="./images/15.png"/> 	|
| Ler mensagem 1              	| Selecionar uma mensagem a ser lida                                                                                                             	| <img alt="Ler mensagem 1" title="#Ler mensagem 1" src="./images/17.png"/> 	|
| Ler mensagem 2              	| Ler a mensagem recebida por outro usuário (decriptada)                                                                                         	| <img alt="Ler mensagem 2" title="#Ler mensagem 2" src="./images/18.png"/> 	|
| Pasta src/banco             	| Abrir arquivo users.txt<br>Todos usuários criados são apresentados                                                                             	| <img alt="Pasta src/banco" title="#Pasta src/banco" src="./images/19.png"/> 	|
| Pasta src/msgs/Nome-Usuário 	| Abrir arquivo .txt<br>A mensagem é exibida encriptada                                                                                          	| <img alt="Pasta src/msgs/Nome-Usuário" title="#Pasta src/msgs/Nome-Usuário" src="./images/20.png"/> 	|

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- Linguagem
	- [Python](https://www.python.org/) (estruturado)
- Bibliotecas
	- [Random](https://docs.python.org/3/library/random.html)
	- [Math](https://docs.python.org/3/library/math.html)
	- [Datetime](https://docs.python.org/3/library/datetime.html)
	- [Sys](https://docs.python.org/3/library/sys.html)
	- [os](https://docs.python.org/3/library/os.html)
	- [Shutil](https://docs.python.org/3/library/shutil.html)
	- [Getpass](https://docs.python.org/pt-br/3/library/getpass.html)
	- [Platform](https://docs.python.org/pt-br/3/library/platform.html)
	- [JSON](https://docs.python.org/3/library/json.html)


## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, é  importante você ter previamente instalado em seu computador o [Git](https://git-scm.com) e o [Python](https://www.python.org/).

### ⏳ Rodando a aplicação

```bash
# Clone este repositório
$ git clone https://github.com/iam-ianc/encript-rsa

# Acesse a pasta src do projeto no terminal/cmd
$ cd encript-rsa/src

# Execute a aplicação
$ py main.py

```
