# Integração Contínua
Neste documento irei dar dicas de ferramentas Free, motivos para se implementar uma Integração Contínua e os ganhos de uma dentro do ciclo de programação ágil.

Hoje estamos cada vez mais dentro de empresas que solicitam metodologias ágeis, o QA não pode sair do ciclo, por isso é recomendado ter ferramentas e metodologias que o auxiliem no dia a dia e facilite a vida ao máximo, há também equipes dentro da metodologia tão envolvidas onde os integrantes da equipe fazem tudo (Desenvolvimento Front/Back e Testes), para estes casos é ainda mais importante ter uma integração que auxilie no desenvolvimento e testes, principalmente porque equipes assim geralmente são de programadores e todos sabemos que nenhum programador gosta de realizar testes.

No exemplo irei focar em um produto com o back-end feito em C# com um Servidor de Aplicação IIS e frontend feito em AngularJS com padrão MVC.

|Tipo de Teste|Ferramenta|
|---|---|
|Teste de Segurança|<a href="https://github.com/beefproject/beef">BEeF</a>|
|Teste Unitário/Integrado|<a href="https://nunit.org/">NUnit</a>|
|Teste de Tela Automatizado|<a href="https://www.selenium.dev/">Selenium</a>|
|Teste de Tela Automatizado (BDD)|<a href="https://jasmine.github.io/">Jasmine</a>|
|Teste de Tela Automatizado (ATTD)|<a href="https://robotframework.org/">Robot Framework</a>|
|Teste Integrado|<a href="https://www.postman.com/">Postman</a>|
|Cobertura de Código|<a href="http://www.ncover.com/">NCover</a>|
|Teste Integrado|<a href="https://hub.docker.com/">Docker</a>|

Ok, temos várias ferramentas que fazem várias coisas, mas por onde começar? O ideal é utilizar o Product Owner nestes casos ou conversas com o usuário final, para que possamos definir as rotinas e produtos mais impactantes, como exemplo podemos tomar uma tela de login, sabemos que caso ocorra um erro na mesma podemos parar todo nosso produto, então qualquer situação é gravíssima.
