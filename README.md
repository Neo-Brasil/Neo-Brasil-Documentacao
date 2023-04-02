<div align="center" id="menu">

![NEOBRASIL](https://user-images.githubusercontent.com/101027809/229370224-49488559-c598-48bf-946b-e3f2f60410cb.png)


<h3> Desenvolvimento de aplicação back-end com microserviços </h3>

<p>
    <a href="#sobre">Sobre</a> | 
    <a href="#repositorios">Repositórios</a> | 
    <a href="#entrega">Entregas de Sprints</a> |
    <a href="#backlog">Backlogs</a> | 
    <a href="#pastas">Configuração das pastas</a> | 
    <a href="#manual">Manual de Instalação</a> |
    <a href="#utilizacao">Manual de utilização</a> |
    <a href="#equipe">Equipe</a>
</p>

</div>
<br>

<span id="sobre">

## :pencil: Sobre o projeto
 O projeto tem como objetivo o desenvolvimento de um software para gestão de cobranças, onde nesse é necessário que se permita o cadastro de clientes, o  registro de cobranças das parcelas a receber e dos pagamentos efetuados, além da geração de relatórios de cobrança com diferentes tipos de busca por data e situação das parcelas.

> :gear: **Tecnologias Utilizadas:** [ReactJs](https://pt-br.reactjs.org/), [JavaScript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript), [TypeScript](https://www.typescriptlang.org/), [Node](https://nodejs.org/en/about/), [Java](https://www.oracle.com/br/java/technologies/downloads/ ), [MySQL](https://www.mysql.com/), [Spring](https://spring.io/), [HTML](https://developer.mozilla.org/pt-BR/docs/Web/HTML), [CSS](https://developer.mozilla.org/pt-BR/docs/Web/CSS), [Figma](http://www.figma.com), [Visual Studio Code](https://code.visualstudio.com/), [Eclipse](https://www.eclipse.org/downloads/),  [Insomnia](https://insomnia.rest/download), [GitHub](https://github.com/), [Excel](https://www.microsoft.com/pt-br/microsoft-365/free-office-online-for-the-web)

<br>

<span id="repositorios">

<h2> 🗂 Repositórios </h2>

- Repositório Backend: [https://github.com/Neo-Brasil/Neo-Brasil-Backend](https://github.com/Neo-Brasil/Neo-Brasil-Backend)
- Repositório Frontend: [https://github.com/Neo-Brasil/Neo-Brasil-Frontend](https://github.com/Neo-Brasil/Neo-Brasil-Frontend)
- Repositório Documentação: [https://github.com/Neo-Brasil/Neo-Brasil-Documentacao](https://github.com/Neo-Brasil/Neo-Brasil-Documentacao)

<span id="entrega">

## 🏁 Entregas de Sprints
| Sprint |        Previsão         |     Status     |     Relatório     | Tag
| :----: | :---------------------: | :------------: | :---------------: | :------------:
|   01   | 13/03/2023 à 02/04/2023 |  Finalizado ✔️  | [Ver relatório](https://github.com/Neo-Brasil/Neo-Brasil-Documentacao/tree/sprint-1) | [1.0.0](https://github.com/Neo-Brasil/Neo-Brasil-Documentacao/releases/tag/1.0.0)
|   02   | 03/04/2023 à 23/04/2023 | Não iniciada ❌ |                   |
|   03   | 24/04/2023 à 14/05/2023 | Não iniciada ❌ |                   |
|   04   | 15/05/2023 à 04/06/2023 | Não iniciada ❌ |                   |

<br>

<span id="backlog">  

## :pushpin: Backlog do Produto  

 #### Épicos (Requisitos Funcionais) 
| SPRINT | CÓDIGO | DESCRIÇÃO                                      | STATUS |
| :----: | :----: | :--------------------------------------------- | :----: |
|   1    |  RF1   | Crud de clientes e titulos                     |   ✅    |
|   1    |  RF2   | Registro de pagamentos                         |   ✅    |
|   1    |  RF3   | Relatório de entrada (fluxo de caixa)          |   ✅    |
|   1    |  RF4   | Login de administrador                         |   ✅    |
|   2    |  RF5   | Relatório de valores a receber                 |   ❌    |
|   2    |  RF6   | Login por setores                              |   ❌    |
|   2    |  RF7   | Crud de usuários                               |   ❌    |
|   2    |  RF8   | Relatório clientes inadimplentes e adimplentes |   ❌    |
|   3    |  RF9   | Filtro por datas nos relatórios                |   ❌    |
|   4    |  RF10  | Relatório cobranças                            |   ❌    |

#### Requisitos Não Funcionais  
| CÓDIGO | DESCRIÇÃO |
|:------:|:----------|
| RNF1 | Java                  |
| RNF2 | TypeScript |
| RNF3 | BPMN           |
| RNF4 | Documentação com mapeamento das regras de negócio do cliente |

<h4> Tecnologias Desejáveis </h4>

| CÓDIGO | DESCRIÇÃO                         |
| :----: | :-------------------------------- |
|  TD1   | Banco de Dados Relacional (MySQL) |

</div>

<a href="#menu">Voltar ao menu</a>

<span id="pastas">

## :file_folder: Configuração das pastas
* 📂 `doc`: onde estão armazenados a pasta data_base, com o modelo do banco de dados, a pasta bpmn, com o modelo BPMN e o arquivo manual_usuario.

  

<a href="#menu">Voltar ao menu</a>

<br>

<span id="manual">

 ## :scroll: Manual de instalação

* Depois de instalar as tecnologias necessárias para o projeto(NodeJS, MySql, MySQL Workbench, Java, Eclipse e Spring) digite no cmd:

  ```
  git clone https://github.com/Neo-Brasil/Neo-Brasil-Backend
  cd Neo-Brasil-Backend
  cd neobrasil-backend
  ```

- Abra a pasta neobrasil-backend  e configure os dados do seu banco de dados nos arquivos AplicacaoApplication e Application.properties

   ![aplicacaoaplication](https://user-images.githubusercontent.com/101027809/229372657-56edcc66-1a00-4591-a401-14d0a4f9e5a1.png)

   ![applicationproperties](https://user-images.githubusercontent.com/101027809/229372662-34f8ac1d-f3a3-4adf-9085-844d2d794dd6.png)
 

- Execute os seguintes comandos no MySQL Workbench:

  ![mysql](https://user-images.githubusercontent.com/101027809/229372701-fabb64af-5456-4f70-9e22-1f209373dac1.png)


- Execute o arquivo AplicacaoAplication.java 

* Após executar o backend, crie uma nova pasta e execute os seguintes comandos no cmd:

  ```
  git clone https://github.com/Neo-Brasil/Neo-Brasil-Frontend
  cd Neo-Brasil-Frontend
  npm install
  npm start
  ```
<a href="#menu">Voltar ao menu</a>
  
  <span id="utilizacao">
  
 ## :scroll: Manual de utilização
 
 [Acesse aqui o manual de utilização](https://github.com/Neo-Brasil/Neo-Brasil-Documentacao/blob/main/doc/manual_usuario.md)
 
 
 <br>

<span id="equipe"> 

## :busts_in_silhouette: Equipe

|    Função     | Nome                               |                      LinkedIn & GitHub                       |
| :-----------: | :--------------------------------- | :----------------------------------------------------------: |
| Product Owner | Carlos Eduardo Falandes            | [![Lattes Badge](https://img.shields.io/badge/-Lattes-orange?style=flat-square&logo=GitBook&logoColor=white&link=http://lattes.cnpq.br/2433599000300626)](http://lattes.cnpq.br/3579183651868833) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Desduh) |
| Scrum Master  | Júlia Sousa Gayotto                | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/júlia-gayotto/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JuliaGayotto) |
|   Dev Team    | Amanda Vieira de Oliveira          | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/amanda-vo/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/amandavo) |
|   Dev Team    | Julio Cesar Rodrigues Lucena Costa | [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/julio-lucena-2001/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/JulioL2001) |
|   Dev Team    | Lucas França Registro              | [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/LucasFrancaRegistro) |

<a href="#menu">Voltar ao menu</a>
