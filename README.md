﻿# <p style="text-align: center; padding: 20px;"><img src="https://tcc1sumare.blob.core.windows.net/tcc/LOGO_PNG.png" width="700" height="400"></p>

SRM - Smart Recycling Management, é uma API para ajudar a gerenciar o processo de reciclagem de materiais e monitorar seu consumo mensal sobre eles.


<https://smartmanagementrecycling.herokuapp.com/>



# BACKEND (SRM)
### Nosso serviço de backend é uma API a serem consumidas pelo frontend através do padrão RESTAPI.
#### - Com ela é possivel realizar as seguintes operações:
#### - Cadastrar diversos usuários;
#### - Cadastrar uma lista de compras para ser utilizado posteriormente na extração de relátórios;
#### - Cadastrar produtos adicionais ao banco de dados, para aumentar a gama de produtos disponíveis;
#### - Receber dados de consumo mensais como o número de itens consumidos, o valor total gasto, e o valor total a ser pago;




## Pré-requisitos para rodar o projeto localmente



Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

* [GIT](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)
* [Java 11](https://www.oracle.com/br/java/technologies/javase/jdk11-archive-downloads.html)
* [Maven](https://maven.apache.org/)
* [MySQL](https://dev.mysql.com/downloads/installer/)

## Baixar o projeto em sua maquina



### 💾Clone o repositório:



Em seu terminal use o comando:



```bash

$ git clone https://github.com/Andre0Luis/SmartRecyclingManagement_backend.git

```



Vá para a pasta do projeto clonado:



```bash

$ cd SmartRecyclingManagement_backend

```




## 🎲Rodar o projeto



use o comando:



```

$ mvn spring-boot:run

```



O comando **mvn spring-boot:run** efetua a execução do serviço através do Maven que vai rodar o framework do Spring-boot.
Após executar esse comando para iniciar o serviço, ele irá carregar todas suas configurações e fazer algumas validações internas, então ele estará pronto para uso na porta 8080.


## GIT e GIT FLOW



Os comandos abaixo são utilizados para as seguintes funções:



```

$ git checkout [nome da branch]

Além de mudar de branch, o git checkout pode ser usado para voltar um determinado arquivo para seu estado na staged area.

  

$ git checkout -b [nome da branch]

Cria-se uma nova branch a partir da branch atual do projeto.

  

$ git add

Git add adiciona uma alteração no diretório ativo à área de staging. Ele diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit.

  

$ git add .

esse comando adiciona todas as alterações no diretório ativo à área de staging.

  

$ git commit -m "[descrição do commit]"

Os commits são as unidades estruturais de um cronograma de projeto Git. Podem ser considerados instantâneos ou marcos ao longo do cronograma de um projeto Git. São criados com o comando git commit para capturar o estado de um projeto naquele momento.

  

$ git push

O comando git push é mais usado para publicar modificações locais a um repositório central. Após um repositório local ter sido modificado, um comando push é executado para compartilhar as modificações com membros da equipe remota.

```



- MAIN - Branch destinada a build de produção.

- DEVELOPMENT - Branch destinada a build de desenvolvimento.

- [feature branch] - Branch destinada a build de desenvolvimento de novas features do produto.



Quando você faz a clonagem dos repositorios do projeto, precisa criar uma branch com o nome de development ```git checkout -b development``` e nela vc cria uma outra branch ```git checkout -b (coloca um nome que tenha referencia a sua tarefa)``` para fazer os commits e depois fazer o pull request no GitHub. 
### Passo a passo de como fazer pull request: 
* 1: Sempre seleciona a branch que vc criou para fazer os commits; 
* 2: Sempre selecione a development; 
* 3: Marcar os avaliadores, sempre o lider do projeto e outra pessoa que auxilia; 
* 4: Aguardar a validação do lider.
* 5: Se o lider aprovar, vc pode fazer o pull request.



## Atenção



Mantenha as branch **development** em sua forma mais atualizada, utilizando o método de **_pull resquests_**, pois ela é essencial para o fluxo(**_git flow_**), durante o processo de desenvolvimento e deploy da aplicação.


## Swagger

Esse serviço possui o [Swagger](https://swagger.io/) para documentação do projeto. O SRM em si, por ser construído com Spring Framework, grande parte de sua documentação é reconhecida através de sua sintaxe, sendo possível também utilizarmos algumas anotações extras para melhor documentação.

Para acessarmos o Swagger do projeto, basta iniciarmos o projeto localmente e em seu navegador utilizar o seguinte endereço: https://smartmanagementrecycling.herokuapp.com/swagger-ui/index.html

Com isso ele carregará uma página mostrando seus endpoints disponíveis, estrutura para acessa-los e efetuar testes na API online.

Acessando essa documentação é possivel verificar todos os endpoints disponíveis, seus parâmetros, retorno, etc.

E fazer testes reais de leitura, inserção, atualização e exclusão de dados.


É possivel encontrar mais detalhes de como funciona o Swagger desse serviço na [Em sua documentação oficial](https://swagger.io/tools/open-source/open-source-integrations/).

## ⏳Status do projeto



🚧 **SRM - Smart Recycling Management** 🚀 Em construção... 🚧



## 🛠 Tecnologias



<img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo--v1.png" width="40"  height="40"  style="margin: 0px 3px"/>

<img src="https://img.icons8.com/color/48/000000/spring-logo.png"  width="40"  height="40"  style="margin: 0px 3px">

<img src="https://img.icons8.com/color/48/000000/git.png"  width="40"  height="40"  style="margin: 0px 3px">

<img src="https://miro.medium.com/max/300/1*2DKX6fd0wlVbbjff_noWHg.png"  width="40"  height="40"  style="margin: 0px 3px">




## Licença



[André Luis Teixeira](https://github.com/Andre0Luis).
