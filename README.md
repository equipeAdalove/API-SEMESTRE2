<h1 align="center"> API ADS 2º Semestre</h1>

<p align="center">
      <img src="Documentação/Assets/bannerAdaLove (1).jpg" alt="Adalove" width="700">
<br>

<hr>
<br>
<p align = "center">
  <a href = "#desafio"> Desafio </a>  |   
  <a href = "#mvp"> MVP </a>  |
<!-- <a href ="#prototipo"> Protótipo </a>  |  -->
  <a href = "#demo"> Demonstração </a>  |
  <a href = "#sprint"> Sprints </a> |
  <a href = "#requisitos"> Requisitos </a> | 
  <a href = "#metodologia"> Metodologia </a> |  
  <a href = "#backlog"> Backlog do Produto </a>  | 
  <!-- <a href ="#roadmap"> Roadmap </a>  | -->
  <a href = "#equipe"> Equipe </a>  |
  <a href = "#prof"> Professores </a>
</p>


<br>
<h4 align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=github,idea,java,figma,mysql" />
  </a>
</h4>


<br>
<br>

> Status do Projeto: Em progresso! 🛠

<br>

## 🏁 Desafio: Software para automatizar a extração de informações de documentos 
<a id="desafio"></a>

Muitas empresas lidam com milhares de documentos diariamente, como currículos, contas, notas fiscais e assim por diante. Porém, extrair informações destes documentos é uma atividade difícil que depende da atividade humana (mais lenta que computadores) pois apenas retirar o texto pode não ser suficiente visto que as informações dependem do layout visual.<br>
**O objetivo deste API é desenvolver um software para automatizar a extração de informações de documentos usando modelos de linguagem e visão.**
<br>

## 🫧 MVP (Minimal Viable Product) 
<a id="mvp"></a>

<div>
<b>Análise de Relatórios de Casos Clínicos</b> é um projeto voltado para facilitar o acesso e a análise de dados extraídos de relatórios clínicos, organizando as informações de forma estruturada para que profissionais da área de psicologia possam trabalhar de maneira mais eficiente.
  <br>
Descrição do Projeto: O objetivo é desenvolver um software que automatize a extração de informações essenciais dos relatórios clínicos, como diagnósticos, tratamentos e evolução do paciente, dentro de um hospital psiquiàtrico, organizando essas informações em um formato acessível.
<br>Nele, o usuário poderá:

- Cadastrar relatórios clínicos no banco de dados, de forma simples e ágil.
- Editar, atualizar, deletar e recuperar registros armazenados na aplicação
- Extrair as informações essenciais dos documentos,relacionadas aos pacientes.
- Acessar as informações extraídas dos relatórios.
</div>


<br>

## 🎥 Demonstração 
<a id="demo"></a>

[Vídeo de Demonstração](anexar o vídeo e espacificar a sprint)

<br>

## 📖 Metodologia 
<a id="metodologia"></a>

O metódo **Scrum** é um método ágil adaptativo, iterativo, flexível e eficaz. 
<br> Este método possui os seguintes princípios norteadores:

1. *Controle empírico*
2. *Auto-organização*
3. *Colaboração*
4. *Priorização da criação de valor*
5. *Time-boxing*
6. *Desenvolvimento iterativo*

Entre as ferramentas utilizadas no Scrum, uma é a divisão do projeto em **Sprints**. Para selecionar quais seriam as entregas das nossas Sprints, primeiro definimos nosso **MVP**, priorizando as tarefas que trariam maior entrega de valor para o cliente. Então, a partir das Tarefas foi construído o **Backlog do Produto**,  o qual foi aprovado pelo cliente e dividido em 4 Backlog de Sprint.
<br>

## 📅 Sprints 
<a id="sprint"></a>

🚀 SPRINT 1:  Em progresso!

🔒 SPRINT 2:  Ainda não iniciada!

🔒 SPRINT 3:  Ainda não iniciada!

🔒 SPRINT 4:  Ainda não iniciada!

<br>

## 🖇️ Requisitos
<a id="requisitos"></a>

<div align="center">

|          ID           |                     Descrição                      |         Origem          |
| :-------------------: | :----------------------------------------------------------: | :-------------: |
| RQ01 | O usuário poderá submeter documentos para modelos de linguagem e visão. |Lista de requisitos|
| RQ02 | O software deverá tratar a saída dada por esses modelos.|Lista de requisitos|
| RQ03 | Criar uma interface para cadastrar documentos.|Lista de requisitos|
| RQ04 | Criar uma interface para exibir resultados.|Lista de requisitos|
| RQ05 | O usuário poderá cadastrar informações extraídas em um banco de dados relacional.|Lista de requisitos|
| RQ06 | O usuário poderá recuperar informações do banco de dados.|Lista de requisitos|
| RQ07 | O usuário poderá editar informações do banco de dados.|Lista de requisitos|
| RQ08 | O usuário poderá deletar informações do banco de dados.|Lista de requisitos|
| RQ09 | O software não poderá utilizar nenhuma API externa.|Lista de requisitos|
| RQ10 | A aplicação precisa rodar localmente na máquina.|Lista de requisitos|
| RQ11 | O software deverá visar a privacidade dos dados, através de um sistema de controle de acesso.|Acordo com o cliente|
| RQ12 | A aplicação deve conter uma interface minimalista e intuitiva.|Lista de requisitos|
| RQ13 | O usuário poderá consultar os relatórios já cadastrados no banco de dados do sistema.|Acordo com o cliente|

</div>

<br>

<br>

## 🐙 Backlog do Produto
<a id="backlog"></a>

<div align="center">
      
|   Rank  |   Requisito   | Prioridade |                          User Story                             | Sprint | Status  |
| :-----: | :-----------: | :--------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----: | :-----: |
|  1    |      RQ12     | Alta | Como contratante, quero um protótipo das interfaces da aplicação, de forma intuitiva e minimalista, com o objetivo de verificar sua navegabilidade.| 1 |  |
|  2    |      RQ05 - RQ01 - RQ03     | Alta | Como usuário do sistema, quero uma interface simples e intuitiva para cadastro de novos documentos na aplicação.| 2 |      |
|  3    |    RQ02       | Alta | Como requerente, quero que o sistema extraia informações textuais automaticamente dos documentos para que eu não precise fazer isso manualmente.| 2 |   |
|  4    |      RQ04     |  Alta | Como contratante, quero que a aplicação exiba os resultados dos dados extraídos de maneira estruturada e visual, para agilizar o uso do software.| 2 |     |
|  5    |      RQ05     | Alta | Como cliente, quero que as informações extraídas sejam armazenadas em um banco de dados, para que eu consiga consultar os relatórios já cadastrados no sistema.| 1 |      |
|  6    |      RQ09 - RQ10     | Média | Como administrador, quero garantir que a aplicação funcione localmente para preservar a privacidade dos dados e reduzir custos.| 1 | ✔️ |
|  7    |      RQ11     | Média | Como administrador, quero garantir que os relatórios submetidos estejam protegidos através de sistema controle de acesso para garantir a confidencialidade das informações.| 3 |     |
|  8    |      RQ08     | Baixa | Como administrador, quero ter a opção de deletar documentos e seus dados associados no banco de dados para manter apenas informações relevantes.| 3 |     |
|  9    |      RQ07     | Baixa | Como contratante, quero ter a opção de editar as informações extraídas dos relatórios, para corrigir erros ou atualizar informações.     | 3 |   |
|  10   |      RQ13     | Baixa | Como requerente, quero filtrar as informações extraídas dos relatórios através dos dados do paciente (nome, sexo, diagnóstico), para que eu possa encontrar facilmente os relatórios.|  4   |      |
|  11   |      RQ06     | Baixa | Como requerente, quero ter a opção de recuperar os relatórios submetidos para garantir a preservação das informações.| 4 |    |
|  12   |    RQ08     | Baixa | Como cliente, quero a otimização do sistema, e a correção de pequenos bugs, visando o uso rápido e eficiente da aplicação.| 4 |   |
</div>



<br>

<!--
## :moyai: Personas <a id='personas'></a>

| C-Level |
| :------:|
| Eu, como **C-Level** da *Ionic Health*, tenho como foco principal é fornecer informações claras e precisas aos nossos investidores sobre como estamos gerenciando nossos processos e cumprindo nossos objetivos. Preciso de relatórios que comuniquem de forma eficaz nosso sucesso e conformidade. |

| Gerente / Diretor |
| :------:|
| Eu, como **Gerente / Diretor** da *Ionic Health*, necessito da capacidade de criar, definir requisitos e acompanhar todos os detalhes dos projetos é fundamental para o sucesso da equipe. Preciso de uma ferramenta que me ajude a manter tudo sob controle de forma eficaz e eficiente. |

| Líder / Gestor |
| :----:|
|Eu, como **Líder / Gestor** da *Ionic Health*, é essencial ter uma ferramenta que me permita adicionar novas etapas com clareza e eficiência aos processos existentes. Isso simplifica a adaptação e o gerenciamento dos processos em constante evolução. Também é imperativo que possa fazer requisições das evidências necessárias para a validação de tais etapas, isso torna possível acompanhar o progresso e garantir que todos estejam alinhados com nossas metas. |

| Colaborador  |
| :----------: |
| Eu, como **Colaborador** da *Ionic Health*, preciso de uma maneira fácil e eficaz de gerenciar todas as evidências necessárias nos processos da empresa. Uma notificação clara e instruções precisas são essenciais para garantir que eu possa fazer o meu trabalho de forma eficiente.  |
-->

<br>

<div align="center">
      
## 🥇 Equipe 
<a id="equipe"></a>
      
|      Membro      |    Função     |                            Github                            |                           Linkedin                           |
| :--------------: | :-----------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
| Raphaela Monteiro  | Product Owner | <a href="https://github.com/raphaelamonteiro"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/raphaelamonteiro/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Vitor Ribeiro | Scrum Master | <a href="https://github.com/ribeirovitor04"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Angelina Borroni | Desenvolvedor  | <a href="https://github.com/borroniff"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Celso Rocha | Desenvolvedor | <a href="https://github.com/celsick"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Maria Fernanda Hansen | Desenvolvedor | <a href="https://github.com/Madhs31"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Matheus Germano | Desenvolvedor | <a href="https://github.com/m-germano"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href="https://www.linkedin.com/in/pedro-davi-jobs/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |
| Renan Tomasi | Desenvolvedor | <a href="https://github.com/renan21-tg"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a> | <a href=""><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a> |      

<br>

## 🖋️ Professores: 
<a id="prof"></a>

| PO²              | M²       |
| :-------------------: | :-----------: |
| <a href='http://lattes.cnpq.br/4377240827813491'>Prof° Giuliano Bertoti </a> | <a href='http://lattes.cnpq.br/9330552327454666'>Prof° Cláudio Lima </a> |


</div>


