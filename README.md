# Projeto DIO sobre SQL e NoSQL
Anotações e conceitos sobre Bancos de Dados - resumo aqui no README e maiores detalhes nos arquivos em PDF.

---

## Bancos de Dados
"Bancos de dados ou bases de dados são coleções organizadas de dados que se relacionam de forma a criar algum sentido (informação) e dar mais eficiência durante uma pesquisa ou estudo." - devmedia



### Banco de Dados Relacional

Surgiu na década de 60;

Banco de dados relacional é uma coleção organizada de informações, modeladas em linhas e colunas, que armazena e fornece acesso a pontos de dados relacionados entre si;

Essa categoria de BD é utilizada quando há um esquema e uma consistência de dados bem rígida e com relacionamento entre eles.

Exemplos de SGBD's: MySQL (um dos mais utilizados no mercado), PostgreSQL, Oracle



### Banco de Dados NoSQL

Os Bancos de Dados NoSQL (Não somente SQL - Not Only) surgiram para **suprir** as deficiências do Bancos de Dados Relacionais, e não para substituí-los. Hoje em dia é muito comum utilizar os dois tipos de BD.

Permite manter uma estrutura de dados não rígida, atender à grande necessidade de tráfego de dados e um rápido desempenho no processamento dos mesmos. 

Os bancos de dados NoSQL se tornaram populares à medida que os aplicativos web se tornaram mais comuns e mais complexos.

Tipo de BD NoSQL: 

- Orientado a colunas;

- Orientado a grafos;

- Orientado a documentos;

- Chave-valor.

Exemplos de SGBD's: MongoDB, Cassandra, Redis



### Diferenças

Relacionais trabalham com <u>ACID</u> - Atomicidade, Consistência, Isolabilidade e Durabilidade;

NoSQL trabalham com <u>BASE</u> - Basicamente Disponível, Estado Leve e Eventualmente Consistente.


<u>Escalabilidade</u>
	Relacional - vertical (infla o hardware para ele ser capaz de suprir as necessidades);
	NoSQL - horizontal (particionando os dados) - escalabilidade infinita, principalmente se estiver na nuvem;

<u>Schema</u>
	Relacional - precisa moldar a estrutura antes - esquema rígido, maior consistência
	NoSQL - não precisa pré-definir quais dados o BD vai receber. Menos garantia de consistência.



### SGBD

Sistemas de Gerenciamento de Banco de Dados. Eles permitem a criação, inclusão, exclusão e atualização de dados dentro de um Banco de Dados.

O SGBD protege a base de dados de acessos não autorizados e assegura sempre um estado de consistência do BD.

<u>Ganhos ao utilizar SGBD</u>: Redução de tempo ao desenvolver a aplicação e otimizar recursos;             											Flexibilidade em termos de modificação (mas a modificação não é trivial);           											Nova inserção/atualização é refletida quase que automaticamente;    											Baixar o custo operacional e de gerenciamento.

<u>Quando não utilizar SGBD</u>: Se for algo simples, um projeto pequeno, precisa ponderar se é necessário mesmo a utilização de um SGBD.



---



### Engenharia e Ciência de Dados

São áreas complementares.

Engenheiro de dados - faz a preparação da informação e deixa disponível para o Cientista de Dados (que é um dos muitos que podem consumir essas informações). 

Cientista de Dados - aplica algum tipo de processamento na informação disponibilizada pelo Engenheiro. Ele traduz a informação em forma de insights para alavancar o negócio.



---



### Conclusão

É importante entender o conceito dos Bancos de Dados e SGBD's, entender a essência e o propósito dos tipos de BD pra saber onde e como utilizar e identificar a melhor opção para utilizar no projeto. Entender primeiro o contexto para depois partir para a tecnologia e aprofundamento técnico.

Estabelecendo bem os critérios técnicos, de orçamento e de profissionais envolvidos, fica mais fácil escolher as ferramentas a serem utilizadas que vão atender as necessidades. 
