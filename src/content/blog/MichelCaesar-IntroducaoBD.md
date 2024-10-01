---
draft: false
title: "Banco de Dados - Conceitos e Importância"
snippet: "Neste artigo, definiremos o significado de banco de dados e seus conceitos relacionados. Exploraremos alguns exemplos para que se demonstre a importância."
image: {
    src: "data:image/jpeg;base64,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",
    alt: "full stack web development"
}
publishDate: "2024-10-01 08:00"
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