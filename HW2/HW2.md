Relations with SOA:

Os micro-serviços possuem um estilo arquitetural e padrão de desenvolvimento de software que satisfazem as novas demandas das tecnologias e negócio. Contudo, o princípio de micro serviços está em seus containers serem independentes, autossustentáveis e autônomos. Já SOA possui uma visão com um alto nível de abstração do serviço, contratos, Forte preocupação com o reuso, interoperabilidade, descobrimento de novos serviços e conteúdo arquitetural.

Concepts and principles:
Os benefícios do micro serviço estão relacionados a mudança de paradigma dos desenvolvedores na visão dos processos de negócio a serem implementados e fornecidos como software. Alcançando as necessidades ofertadas pela nova demanda do mercado, essa arquitetura passa a oferece um padrão complementar as novas tendências como Devops e Cloud, trazendo agilidade ao projeto de desenvolvimento e rapidez na entrega do serviço ao cliente. Com esse estilo arquitetural é mais fácil e menos custoso realizar alterações com novos módulos ou fazer novas versões do sistema.
Os micro serviços possuem um estilo arquitetural e padrão de desenvolvimento de software que satisfazem as novas demandas das tecnologias e negócio. Contudo, o seu princípio está nos seus containers serem independentes, autossustentáveis e autônomos.

Service-oriented integration:
O micro serviço possui um grande ambiente integrado para o fornecimento de diversos serviços. É possível fazer o deploy em uma maquina virtual, ou mesmo em um contêiner, realizando um cluster de vários containers onde cada um possuirá um micro serviço; conectados aos seus respectivos bancos de dados e aos eventos dos outros containers da aplicação, mantendo a integridade dos dados e aumentando o desempenho e a escalabilidade da aplicação.

Legacy Modernization:
 O micro serviço possue um estilo arquitetural que permite a utilização de diferentes estruturas individuais e autônomas para cada tipo de serviço. Desta forma é possível estar em execução num mesmo sistema diferentes tecnologias com diferentes linguagens de programação o que permite um ágil gerenciamento de versões do software, em diferentes componentes sem que o usuário perceba em qual versão se encontra. 

Monolithic migration using SOA:
Para que um sistema monolítico passe a ter uma arquitetura orientada a serviços é preciso separar os componentes e funcionalidades do sistemas e modela-los como serviços individuais que possuem suas dependências, seus banco de dados e que interagem com um barramento de serviços que é o ambiente na qual o usuário terá contato com a aplicação.  

Question 2:
The twelve Factores app são as características e boas práticas observadas em diversos projetos e equipes que trabalham com aplicações e que possuem uma arquitetura orientada a serviço; listando 12 fatores importantes que todo participante da equipe de desenvolvimento de software deve ter como visão para aplicar nas atividades adotando assim um perfil Devops.
Os fatores envolvem: Ter uma única codebase para revisão e controle do código, declaração explicita de dependências isoladas, configurar o ambiente cloud onde estarão toda as containers com os micro serviços, Serviços controlando seus recursos individuais; controle do versionamento das relases no mesmo ambiente de serviços, execução de um ou mais processos rodando em paralelo, Exporta acesso ao serviço via porta específica, alta escalabilidade via modelo de processo, Alta disponibilidade, dev e Productions trabalhando em conjunto, logs dos eventos em streams e processos de gerenciamento das tasks visíveis no ambiente.

Question 3
A Netflix possuía um ambiente monolítico (Java) com um repositório imenso no Git onde era armazenado o código do sistema. Com o passar do tempo houve a explosão de múltiplos usuários que queria usar o sistema e seria preciso se preocupar com a quantidade de maquinas e instancias do sistema para sustentar todos os acessos. Com isso os donos da empresa decidiram mudar a arquitetura separando sistema em vários componentes de serviços e utilizando servidores da AWS da amazon para sustentar o processamento das requisições e etc. Com isso o sistema ganhou em escalabilidade e velocidades e hoje já possui mais de 100 milhões de usuários.

O uber é uma empresa de transporte particulares que começou com um sistema monolítico java mas quando cresceu o número de usuários por cidades pelo mundo teve que tomar uma mudança radical. Mudou sua estrutura para SOA, contratando diversos times para que eles desenvolvessem vários serviços da uber em linguagens e frameworks diferentes, integrados e fornecendo dados em ambiente rodando em paralelo mostrando os verdadeiros conceitos e princípios dos micro serviços.

