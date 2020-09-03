## Instruções

Necessário antes de rodar a aplicação, abrir o projeto e executar os commandos da migration no Package Manager Console para criar o banco de dados e as tabelas. Segue os comandos abaixo:

## Comando para criar migration: 

add-migration nomeDaMigration. 
Exemplo: add-migration primeiraMigration</p>

## Comando para criar bancos e tabelas: 

update-database

A connection atring está configurada para o banco de dados local. Segue a connection string: "Server=.;Database=AlbertEinsteinTesteContext;Trusted_Connection=True;MultipleActiveResultSets=true"

Caso não queria criar o banco de dados via migrations, rodar o script sql.

## Endpoints Serviço de Paciente
            
Funções: Obter Consultas por Paciente, Cadastrar, Atualizar e Excluir Paciente 
            
## Endpoints Serviço de Médico

Funções: Obter Médico por Id, Obter Médicos, Cadastrar, Atualizar e Excluir Médico

## Endpoints Serviço de Consulta

Funções: Obter Consultas por nome do Médico e Agendar Consulta

A API foi desenvolvida com o intuito de servir como referência no desenvolvimento de soluções com DotNET Core.
A mesma contempla as seguintes tecnologias:
1. DotNET Core 3.1
2. EntityFramework Core
3. Dapper
4. FluentValidation
5. Swagger
6. AutoMapper
7. Serilog


Qualquer dúvida enviar um e-mail para vitorfleal@hotmail.com



#### Serviço de pacientes:
- Deve ser possível marcar consultas, através do módulo de médicos;
- Deve ser possível consultar consultas por paciente;

<br/>

#### O que esperamos que você não esqueça de usar (requisitos):
- Deve ser desenvolvido em C# .net Core *(fala sério, show de bola né)*;
- Os dados devem ser persistidos em banco de dados MSSQL Server;
- O acesso a dados deve ser feito utilizando o Entity Framework Core;
- Utilize os padrões que você se sentir mais confortável mas mantenha o código limpo *(Queremos que você faça o teste como você gostaria de trabalhar)*;
- Utilize os princípios SOLID;
- Teste seu código, desenvolva testes usando as técnicas em que estiver mais familiarizado *(Não precisa inventar moda pra fazer bonito, faça bonito com o que você sabe ;D)*.

<br/>

#### Se por acaso você terminar em tempo record e quiser se destacar (opcionais):
- Avalie a concorrência na criação de consultas ou exames;
- Usar containers Docker;
- Criar um módulo de exames, onde pode solicitar exames e o paciente deve ser avisado da solicitação;
- Fazer log do que acontece nos módulos;
- Usar mensageria para comunicação entre módulos, se achar necessário;
- Usar orquestradores para os containers;

<br/>

*Dê o seu melhor.*

*Code como você gostaria de trabalhar*

*Faça um projeto que você se orgulhe*

*Venha preparado para as perguntas que faremos sobre o seu projeto porque nós gostamos de falar sobre código e arquitetura ;)*

<br/>

*Faça fork deste repositório para vermos seu processo de desenvolvimento*

**BOA SORTE!**

