<h1 align="center">Sistema de Academia</h1>

<h2 align="center"> 
	🚧  Projeto  em construção...  🚧
</h2>

## Descrição do Projeto
<p> Este projeto é um sistema desenvolvido para gerenciamento de academias </p>
<p> O sistema possui cinco funcionalidades básicas: </p>

 - [x] Cadastrar alunos
 - [x] Cadastrar instrutor
 - [x] Cadastrar aulas 
 - [x] Agendar aulas
 - [x] Mostrar agendamento

## Funcionalidades básicas
1 - Cadastrar alunos:
- O usuário do sistema deve ser capaz de registrar um novo aluno no banco de dados.  
   Após o cadastro ter sido realizado é possivel, ainda, atualizar ou remover este aluno da base. 

2 - Cadastrar instrutores:
- O usuário do sistema também deve ser capaz de registrar um novos instrutores no banco de dados.  
 Um instrutor pode estar associado a uma ou mais aulas.

3 - Cadastrar aula:
- O usuário do sistema também deve ser capaz de registrar novas aulas no banco de dados da academia.  
 Uma aula pode estar associada a um ou mais instrutores.
  
4 - Agendar aulas:
- O usuário do sistema deve ser capaz de realizar o agendamento de uma aula para determinado aluno, bastando que este aluno esteja matriculado no sistema da academia.  
 Um aluno pode estar agendado para uma ou mais aulas, mas nunca no mesmo dia e horário.

5 - Mostrar agendamentos:
- O aluno deve ser capaz de visualizar seus agendamentos.  
 Uma vez agendado para uma aula, ele será capaz de ver as seguintes informações: "MATRICULA, NOME, DIA_HORARIO_AGENDADO, NOME_AULA, NOME_INSTRUTOR".
  


 ## Pré-requisitos

 Java 8 ou superior
 Oracle (ou outro banco de dados de sua escolha)
 Maven para construção

### 🎲 Configuração do Banco de Dados

Necessário criar um banco de dados local com as seguintes configurações:
 
 Credenciais
 ``` 
driver = "oracle.jdbc.OracleDriver";
caminho = "jdbc:oracle:thin:@localhost:1521:xe";
usuario = <Usuario do seu banco local>;
senha = <Senha do seu banco local>;
 ```

 Tabelas
 ``` 
TB_AULA
TB_ALUNO
TB_INSTRUTOR
TB_AGENDAMENNTO_AULA
 ```
###  Querys DDL para criação do banco de dados:
O script de criação das tabelas necessárias estão dentro do projeto na pasta "src/main/resources", no arquivo: "Create_Tables_Academia.sql".



### 🛠 Tecnologias utilizadas
 [Git](https://git-scm.com/)  
 [Intellij](https://www.jetbrains.com/idea/)  
 [JUinit](https://junit.org/junit5/)   
 [Java](https://www.java.com/pt-BR/)  
 [Oracle BD](https://www.oracle.com/br/database/)  

 ### 📺 Link da apresentação
 [Youtube](https://www.youtube.com/watch?v=hBKUweneIzM)
