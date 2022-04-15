# 📙 Primeiro Desafio - PB Trilha NodeJS
## 👩‍💻 Graciela Parente


## 📝 Perguntas e Respostas:



### 1. Para que serve o método Scrum? 
#### R: É um framework simples para gerenciar projetos complexos. Sua finalidade é justamente “quebrar” um projeto complexo em várias partes para fazer pequenas entregas. É um método para gerenciar uma equipe.

### 2. Como funciona o método Scrum? 
#### R: O método scrum funciona principalmente com time-boxes, que são caixas de tempo com capacidade definida, rígida e não negociável. Cada time-box possui um tempo limite pré determinado que será delimitado dependendo de cada projeto. Segue as seguintes etapas: product backlog, sprint backlog, planning meeting, sprint, daily sprint, review meeting e a sprint retrospective.

### 3. O que é Git?
#### R: Git é um sistema de controle de versões de software. 

### 4. O que é um scrum Product Owner? 
#### R: P.O é o representante do cliente dentro do time. É ele quem detém e organiza o product backlog. O ”Owner” é justamente por ele “ter” o product backlog.

### 5. Qual o comando para criação de um novo repositório no Git? 
####  R: Dentro da pasta desejada, usa-se:
```bash
$ git init
```

### 6. O que é o HTTP? 
#### R: O HTTP é um protocolo que define as regras de comunicação entre cliente e servidor na Internet.

### 7. Como funciona o HTTP? 
#### R: No modelo cliente-servidor, o cliente faz uma requisição, o HTTP transfere para o servidor e retorna para o cliente a resposta da sua requisição.

### 8. Com o Git Você pode propor mudanças (adicioná-las ao Index) usando um comando. Qual é esse comando? 
#### R: 
```bash
$ git add <nome do arquivo>
```

### 9. O que é a Branch master e para que serve? 
#### R: As branches delimitam onde cada alteração vai acontecer, sendo a branch master a principal, ao iniciar o projeto, a primeira branch que teremos será a branch master. Ela serve para conter o conteúdo total do projeto. As demais serão ramificações dela. 

### 10. Quais são os comandos usados para atualizar um repositório local e fazer merge de um outro branch ao seu branch ativo? 
#### R: Para atualizar um repositório local:
```bash
$ git pull
```
#### Para fazer merge de um branche para outro, usa-se:
```bash
$ git merge <nome da branch> 
```

### 11. Pensando em Bases de dados, sendo elas, Relacionais (SQL) e Não Relacionais (NoSQL). Quais alternativas abaixo estão corretas? 

- [ ] MySQL = MongoDB 
- [ ] PostgreSQL = Redis 
- [ ] Oracle = CouchDB 
- [x] Todas as alternativas estão corretas. 


### 12. O que é MongoDB? 
#### R: MongoDB é um banco de dados não relacional, orientado a documentos.

### 13. O que é o MySQL? 
#### R: MySQL é um Sistema de Gerenciamento de Banco de Dados ou SGBD que permite manipular dados de um BD relacional com SQL.

### 14. Qual a diferença entre git e GitHub? 
#### R: Git é um sistema de controle de versões de repositórios locais e/ou remotos. GitHub é o ambiente onde é possível ter um repositório remoto.

### 15. Quais os dois verbos http que podemos utiizar para realizar um update? Explique a diferença entre eles. 
#### R: Existem os métodos GET e POST. Sendo o GET utilizado para receber dados dentro da URL com parâmetros não sigilosos; já o POST serve para submeter dados, geralmente sigilosos (como o de um login) onde os parâmetros serão repassados no corpo da requisição.

### 16. Qual o status code que pode ser usado na criação de um novo usuário? 
#### R: Pode ser usado o status code 201. Ele significa que a requisição e a criação de um novo recurso foram bem sucedidos.

### 17. Quais são os três status code que podem ser utilizados para realizar o delete? 
#### R: Fiquei com dúvida nessa questão, mas procurando pelo developer mozila, encontrei as seguintes informações:
#### Se um método DELETE for aplicado com sucesso, os três status codes que podem ser utilizados são:
#### Um status code 202 (Accepted) se a ação provavelmente teve sucesso, porém ainda não foi realizada.
#### Um status code 204 (No Content) se a ação foi realizada e nenhuma outra informação deve ser fornecida.
#### Um status code 200 (OK) se a ação foi realizada e a mensagem de resposta inclui uma representação descrevendo o status.

### 18. Qual a extensão ".xxx" contêm as definições da tabela? 

- [x] Commands.myi 
- [ ] Commands.frm 
- [ ] Commands.myd 
- [ ] {mysqlDirectory}/data 


### 19. A pasta "C:\ProgramData" é uma pasta oculta, portanto, você deve digitá-la no endereço do Windows Explorer para chegar lá. Nessa pasta de dados, quais opções apresentam o caminho correto para acessar os bancos de dados que foram denominados? 

- [ ] /{database_name_folder}/{database_tables_and_files}. 
- [ ] C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.frm 
- [ ] C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\mytable.ibd 
- [ ] C:\ProgramData\MySQL\MySQL Server 5.6\data\mydatabase\data-recovery 
#### Verifiquei no meu pc e o caminho vai até a pasta data (C:\ProgramData\MySQL\MySQL Server 8.0\Data). Nesse caminho é onde ficam os bancos de dados criados.

### 20. Qual a extensão ".xxx" que contêm os dados da tabela? 
#### R: Extensao.ibd

### 21. Qual comando usa-se para extração de arquivos em MongoDB durante a instalação? 
#### R: Essa foi a única questão em que não sabia nem por onde começar. Pesquisando, encontrei a sintaxe do comando extract do mongoDB, que é:
```
mongoexport --collection=<coll> <options> <connection-string>
```
#### Porém não tenho certeza se é isso mesmo.

### 22. Para que usamos o MongoDB?
#### R: Utilizamos o MongoDB para armazenar um grande números de dados e por não ser orientado a tabelas, é possível fazer uma busca de forma mais eficiente.

### 23. Exemplifique para que serve os metódos http 1xx, 2xx, 3xx, 4xx e 5xx. De uma forma macro (geral)! 
#### R: 1xx - para demonstrar apenas que a requisição foi recebida pelo servidor
####    2xx - para demonstrar que a requisição foi bem sucedida 
####    3xx -  para demonstrar que foi necessário fazer um redirecionamento de página
####   4xx - para demonstrar que ocorreu uma requisição equivocada do cliente (ex.: digitou o recurso errado)
####   5xx - para demonstrar que o servidor está com algum problema interno sendo impossível acessá-lo naquele momento


### 24. Conta pra gente como foi sua experiência na Sprint#01 do programa de bolsa @node.js_mar22 e quais suas expectativas a partir de agora: 
#### R: Para mim está sendo uma experiência incrível, tô muito feliz e realizada por estar fazendo parte desse processo. Me sinto muito acolhida pelos instrutores e o conhecimento adquirido tá sendo extremamente valioso. Minhas expectativas a partir de agora são conseguir colocar mais em prática o git e github e aprender a linguagem javascript.
