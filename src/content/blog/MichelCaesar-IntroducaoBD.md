---
draft: false
title: "Banco de Dados - Conceitos e Importância"
snippet: "Neste artigo, definiremos o significado de banco de dados e seus conceitos relacionados. Exploraremos alguns exemplos para que se demonstre a importância."
image: {
    src: "https://www.google.com/url?sa=i&url=https%3A%2F%2Fblog.datasafer.com.br%2Festruturas-de-bancos-de-dados%2F&psig=AOvVaw1r6RJWAUBXAjM61mbIdRWQ&ust=1727475733251000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCLDznfjS4YgDFQAAAAAdAAAAABAE",
    alt: "full stack web development"
}
publishDate: "2024-09-26 19:26"
category: "Tutorials"
author: "Michel Caesar"
tags: [programacao, front-end, back-end]
---

  

# Introdução

  

É muito difícil, senão impossível, citar quais empresas e profissionais de TI não trabalham com dados nos tempos atuais. Consequentemente, o dia-a-dia de praticamente qualquer pessoa nos dias atuais é impactado direta ou indiretamente por sistemas de banco de dados.

Afinal, o que é banco de dados? O que são sistemas de banco de dados? Entender esses conceitos provavelmente é o primeiro passo para a qualificação de um profissional de TI, este o qual determina se haverá impactos positivos ou negativos para os stakeholders do sistema desenvolvido. Neste artigo, explicaremos o que é um banco de dados e quais os conceitos relacionados. Citamos e exploramos alguns exemplos para que se demonstre a importância.

Para atribuir uma definição adequada primeiro é necessário definir alguns termos de relevância para que se entenda a distinção entre eles:

  

-   **Dado:** Um fato do mundo real que está registrado. Exemplo: endereço e número de telefone.
    
-   **Informação:** É um fato útil extraído direta ou indiretamente dos dados. Pode ser entendido como o significado que as pessoas associam aos dados através de convenções usadas em sua interpretação. Exemplo: endereço de entrega e número de telefone de uma pessoa.
    
-   **Conhecimento:** É o que se gera a partir de um ou mais conjunto de informações, abrangendo o discernimento, critério e experiência. Exemplo: Ricardo é um servidor público da Unioeste, por isso todos os dias da semana ele passa ao menos 8 horas na Unioeste.
    

  

De modo geral, um **banco de dados (BD)** pode ser entendido como um conjunto de dados relacionados, sendo uma coleção logicamente coerente de dados com algum significado inerente. Ou seja, se temos um agrupamento de informações relacionadas entre si e com algum interesse em comum, temos um BD.

Um BD representa algum aspecto do mundo real, algumas vezes chamado de “mini-mundo”. Mudanças no mini-mundo provocam mudanças na base de dados. Ao projetar um BD, é necessário descrever formalmente a sua estrutura. A forma mais conhecida de fazer isso é baseando-se na arquitetura “Three-schema”, proposta por Tsichritzis & Klug em 1978. O BD é separado nos modelos externo, lógico e interno, descritos brevemente abaixo.

  

-   **Externo/Visão:** Determina as visões dos usuários, ou seja: quais serão as partes do banco de dados que cada grupo de usuários terá acesso de acordo com seus interesses e necessidades;
    
-   **Conceitual:** Concentra-se em descrever como serão as entidades (ou seja, as abstrações do mundo real), os tipos de dados, relacionamentos e restrições;
    
-   **Interno/Físico:** Implementa o modelo lógico em um banco de dados real, atentando-se em questões como particionamento, índices, detalhes internos e organização física dos dados.
    

  

Um BD está sempre associado a aplicações e a usuários que têm interesse nele, então por exemplo: no contexto de uma universidade a relação entre alunos, professores, disciplinas, turmas, salas, cursos, departamentos, centros e funcionários seria útil para diferentes propósitos, como mostrado na imagem abaixo.

  
  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXeAom17FU1KY62X8uLC4Fp07D2UEy16WXhHHy6_-hPG7Qvex7-ikVr-sAVNlyFzWjPIgp40uOb7srRd4G6TYBj3Pxbx0zufh3tMh7tu18VQJpr86EFKAQZjXM99EqgHVJF0uD5QIxlwxEgTBuHgSWsumT0i?key=2pt5rhps4Jg9IUC6zpeWzA)

                                  Representação de um Banco de Dados.

Se tratando de aplicações simples, um BD pode ser acessado e manipulado de maneiras simples, como em um sistema de arquivos. Todavia, na grande maioria dos sistemas desenvolvidos, são necessários diversos recursos para evitar problemas, como por exemplo: o acesso multi-usuário, o controle de redundância e a representação de relacionamentos complexos. Estes recursos existem em um software Sistema Gerenciador de Banco de Dados, o qual exploraremos logo a seguir.

  
  

# Sistema Gerenciador de Banco de Dados (SGBD)

  

## Definições e exemplos

  

Um Sistema Gerenciador de Banco de Dados (SGBD) pode ser entendido como uma coleção de programas que permitem ao usuário criar e manipular um banco de dados, facilitando o processo de definir, construir e manipular bancos de dados de diversas aplicações.

  

-   Definir um BD envolve especificar estruturas e tipos de dados para serem gravados no banco de dados, com uma descrição detalhada de cada tipo de dado.
    
-   Construir um banco de dados é o processo de armazenar os dados em algum meio que seja controlado pelo SGBD.
    
-   Manipular um banco de dados inclui funções como consulta por dados específicos e atualização para refletir as alterações no mundo real.
    

  

Um SGBD possui muitas capacidades úteis e amplamente aproveitadas, como o controle de redundância de dados, a restrição de acesso multi-usuário, a representação de relações complexas, o reforço às restrições de integridade e também a possibilidade de fazer backup e restauração.

Os dois principais modelos de SGBD são: *relacionais* e *não relacionais*. No geral tendo como principal diferença a estrutura utilizada, tais modelos podem ser descritos da seguinte forma:

  

-   **Relacional (SQL):** Expressam os dados em tabelas e os relacionamentos através de chaves, e utilizam a linguagem de busca SQL para relacionar os dados. Exemplos: PostgreSQL, MySQL e OracleSQL.
    
-   **Não Relacional (NoSQL):** São bancos de dados que não se limitam ao modelo relacional, permitindo interagir com um BD utilizando métodos diferentes, promovendo maior flexibilidade. Exemplos: MongoDB, Amazon DynamoDB, Cassandra.
    

  

Logo a seguir, exploraremos brevemente o PostgreSQL, um exemplo ideal para observar as características comuns aos SGBDs relacionais.

  

## PostgreSQL – O SGBD mais utilizado na BIT

Sendo um SGBD relacional amplamente estabelecido e usado no mercado de trabalho para diversas finalidades devido a sua robustez, confiabilidade e performance, o PostgreSQL é um software livre com mais de 35 anos de desenvolvimento. Algumas de suas principais características são descritas a seguir.

  

**Tipos de dados**

  

Além dos tipos primitivos, como inteiros, strings. numéricos e booleanos, uma ampla variedade de tipos é suportada, incluindo tipos estruturados (como date/time e UUID), tipos geométricos (como ponto, linha, círculo, polígono), tipos de documento (como JSON, XML) e até mesmo tipos customizados.

  

**Restrição de integridade**

  

É possível estabelecer restrições básicas, como:

  

-   UNIQUE: Indicando que um dado deve ser único;
    
-   NOT NULL: Indicando que um dado não pode ter valor nulo, então deve ser obrigatoriamente preenchido;
    
-   Primary Key (Chave Primária): Identifica a chave primária de uma tabela, que por sua vez identifica unicamente o conjunto de dados daquela tabela;
    
-   Foreign Key (Chave Estrangeira): Referencia uma chave primária de outra tabela, sendo útil para constituir relacionamentos;
    

  

**Segurança**

  

Tendo um sistema robusto de acesso e controle, o PostgreSQL trabalha com conceitos de atomicidade, integridade, consistência, multiusuário e controle de concorrência, além de oferecer recursos avançados de segurança, como criptografia de dados, certificados SSL e métodos avançados de autenticação.

  

**Compatibilidade**

  

O SGBD é compatível com todos os principais sistemas operacionais, incluindo Windows, Linux e MacOS.

  

**Desempenho**

  

O PostgreSQL pode gerenciar uma grande quantidade de dados e usuários simultâneos, tendo como ponto forte a escalabilidade.

  

**Extensibilidade**

  

Os usuários podem adicionar novos tipos de dados, operadores, tipos de índices e até mesmo linguagens de procedimento. Essa flexibilidade permite que o PostgreSQL seja personalizado para atender às necessidades específicas dos aplicativos.

  

**Documentação e suporte**

  

Existe uma comunidade ativa de código aberto que melhora e atualiza continuamente o sistema. Além disso, a grande quantidade de usuários favorece a disponibilidade de materiais na internet para instalação, configuração, uso e resolução de problemas.

  

Empresas como Apple, Twitch, Skype e Uber já usaram o PostgreSQL em seus sistemas. Além disso, na BIT-EJ utilizamos o PostgreSQL como principal SGBD para o desenvolvimento de sistemas e prestações de serviços.

  
  

# Sistemas de Banco de Dados

  

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcDco6z1_3GTlRRcPLORW-xX4ZmQUk5HY41HIo4yIAkwhT3970ciHusoSnY57CdLrz-U_g5kKtXuGYFkcM0ZHilzlyQF0GoVhzG0UDfzhLkyHoJDm_vRdZpSyDp5hpIwbBFGAnW9neot5hSBpR3o7wzYWDP?key=2pt5rhps4Jg9IUC6zpeWzA)

             Ilustração de um SBD (O.K. Takai et. al., 2005)

  

Sendo composto por programas de aplicações, SGBD e BD, um Sistema de Banco de Dados (SBD) é uma forma adequada de representar boa parte dos sistemas desenvolvidos atualmente. Um SBD geralmente tem diversos tipos de usuários, que podem ser divididos em 4 tipos principais, sendo estes:

  

-   **Programadores de aplicações:** Profissionais em computação que interagem com o sistema por meio de Linguagens de Manipulação de Dados envolvidas em programas escritos em diferentes linguagens hospedeiras.
    
-   **Usuários sofisticados:** Interagem com os sistemas usando Linguagens de Manipulação de Dados.
    
-   **Usuários especialistas:** Usuários sofisticados que escrevem aplicações especializadas.
    
-   **Usuários navegantes:** Usuários comuns que interagem com o sistema através das “interfaces”.
    

  

Existem diversos exemplos de aplicações que compõem um SBD: o serviço de streaming Netflix, o aplicativo Uber e o Youtube. O que todos esses serviços e muitos outros têm em comum é que eles lidam com imensas quantidades de dados, e dependem essencialmente de um SBD para permitir que muitos usuários de diversos tipos possam interagir simultaneamente com o serviço.

Outra vantagem característica de um SBD é que não há dependência entre dados e programas: o usuário não precisa se preocupar com os detalhes internos ou com a estratégia de armazenamento, pois apenas basta que seus dados estejam armazenados de forma segura e íntegra em algum lugar. Portanto, na ausência de um SBD os custos seriam muito maiores, pois haveria diversos problemas como menor desempenho, menor segurança, maior redundância de dados e maior dificuldade para fazer manutenção.

  
  

# Referências

  

**Sistemas de Banco de Dados**. (Cap. 1) Abraham Silberchatz, Henry F. Korth e S. Sudarshan. 5ª Edição. Ed. Campus, 2006.

  

**Introdução a Banco de Dados (Apostila), (Cap. 1-3)**. Osvaldo Kotaro Takai, Isabel Cristina Italiano, João Eduardo Ferreira. DCC-IME-USP, 2005.

  

**Aspectos Básicos de Banco de Dados (Apostila)**. Rogério Gonçalves Bittencourt. Florianópolis, 2004.

  

**Projeto de Banco de Dados**. Carlos Alberto Heuser. Volume 4 da Série Livros didáticos informática UFRGS, Porto Alegre, 2009.

  

GOOGLE CLOUD. **PostgreSQL x SQL Server: quais são as principais diferenças?** Google, [202-?].  Disponível em: [https://cloud.google.com/learn/postgresql-vs-sql?hl=pt-BR](https://cloud.google.com/learn/postgresql-vs-sql?hl=pt-BR).

  

MICROSOFT. **O que é PostgreSQL?** Microsoft, [202-?]. Disponível em: [https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-postgresql](https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-postgresql).

  

ADAPTIVE. **Sistema PostgreSQL: o que é e como ele pode tornar os processos das empresas mais eficientes**. Adaptive, [202-?]. Disponível em: [https://adaptive.com.br/blog/sistema-postgresql-o-que-e-e-como-ele-pode-tornar-os-processos-das-empresas-mais-eficientes/#](https://adaptive.com.br/blog/sistema-postgresql-o-que-e-e-como-ele-pode-tornar-os-processos-das-empresas-mais-eficientes/#).

  

LEYENDECKER, Davi. **Os três níveis da modelagem de dados: conceitual, lógico e físico**. DIO, 2023. Disponível em: [https://www.dio.me/articles/os-tres-niveis-da-modelagem-de-dados-conceitual-logico-e-fisico](https://www.dio.me/articles/os-tres-niveis-da-modelagem-de-dados-conceitual-logico-e-fisico)

  

The PostgreSQL Global Development Group. **PostgreSQL: The World's Most Advanced Open Source Relational Database**. PostgreSQL, 2024. Disponível em: [https://www.postgresql.org/](https://www.postgresql.org/about/).

  

RICARDO. **Conceitos Fundamentais de Banco de Dados**. DevMedia, 2006. Disponível em: [https://www.devmedia.com.br/conceitos-fundamentais-de-banco-de-dados/1649](https://www.devmedia.com.br/conceitos-fundamentais-de-banco-de-dados/1649).