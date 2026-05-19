QA Studies — Fundamentos de Teste de Software

Este repositório contém minhas anotações e estudos sobre Quality Assurance (QA), fundamentos de testes de software, princípios de teste, níveis de teste, causa raiz, regressão e metodologias de qualidade.

Testes de Software

Testes de software vão muito além de simplesmente executar funcionalidades.

O papel do QA é compreender os requisitos do sistema e garantir que a aplicação esteja funcionando corretamente de acordo com as regras de negócio e necessidades do usuário.

De forma simplificada:

o desenvolvedor implementa a funcionalidade;
o QA valida se tudo está funcionando conforme esperado;
caso existam falhas, o QA documenta os defeitos;
o desenvolvedor realiza a depuração e corrige o problema;
após a correção, o QA executa novos testes e verifica se nenhuma outra funcionalidade foi impactada.
Testes Estáticos

São testes realizados antes da execução do software.

Seu objetivo é identificar possíveis problemas no código ou documentação sem executar a aplicação.

Exemplos:
erros de sintaxe;
más práticas de programação;
falhas de segurança;
revisão de código;
revisão de requisitos.
Testes Dinâmicos

São testes realizados com o software em execução.

Seu objetivo é validar o comportamento da aplicação em funcionamento.

Exemplos:
testes de API;
testes de performance;
testes funcionais;
testes de interface;
testes de integração.
Causa Raiz

Causa raiz é a origem real de um defeito no sistema.

O QA identifica e documenta o problema, descrevendo:

como a falha acontece;
em quais condições ocorre;
qual o impacto causado.

Dependendo do nível técnico e do papel do QA, ele também pode auxiliar na investigação da causa raiz.

Exemplos de possíveis causas:
falha na API;
erro no JavaScript;
problemas de integração;
falhas de autenticação;
erros de validação.

Após a investigação, o desenvolvedor realiza a depuração e implementa a correção.

Princípios de Teste
O teste mostra a presença de defeitos e não a sua ausência

— Edsger Dijkstra

O principal objetivo do teste de software é identificar defeitos antes que eles cheguem aos usuários.

Mesmo executando muitos testes, não é possível garantir que um sistema esteja 100% livre de defeitos.

O papel do QA é reduzir riscos e aumentar a qualidade do software.

Testes exaustivos são impossíveis

É praticamente impossível testar todas as combinações possíveis de um sistema.

Por isso, os testes devem ser priorizados com foco em:

funcionalidades críticas;
riscos;
impacto no negócio;
áreas mais sensíveis do sistema.
O teste inicial economiza tempo e dinheiro

Quanto mais cedo um defeito é encontrado, menor será o custo da correção.

Esse princípio se conecta diretamente com metodologias ágeis, onde os testes acontecem desde o início do ciclo de desenvolvimento.

Exemplos:
revisão de requisitos;
validação de regras de negócio;
análise de riscos;
planejamento de testes.
Os defeitos se agrupam

Grande parte dos defeitos costuma estar concentrada em pequenas partes do sistema.

Uma ideia muito associada a esse princípio é:

“80% dos defeitos são encontrados em 20% do código.”

Por esse motivo, QA e desenvolvimento priorizam áreas críticas e de maior risco.

Áreas frequentemente críticas:
APIs;
integrações;
código legado;
funcionalidades recém-alteradas;
versões beta;
módulos complexos.
Paradoxo do Pesticida

Repetir os mesmos testes continuamente faz com que eles percam eficiência na descoberta de novos defeitos.

Por isso, os testes precisam evoluir constantemente através de:

novos cenários;
testes exploratórios;
novos dados;
atualização das automações;
diferentes estratégias de validação.
Teste de regressão

Os testes de regressão verificam se novas funcionalidades introduziram defeitos em funcionalidades antigas.

Exemplo:

Após adicionar pagamento via boleto em um e-commerce, o QA também retesta:

Pix;
cartão;
checkout;
criação do pedido;
fluxo de pagamento anterior.

O objetivo é garantir que a nova implementação não tenha impactado funcionalidades já existentes.

O teste depende do contexto

Cada sistema possui necessidades diferentes.

Os testes aplicados em:

um e-commerce;
uma rede social;
um sistema bancário;
um jogo online;

não serão exatamente iguais.

Os testes devem ser adaptados ao contexto, riscos e objetivos do software.

Ausência de erros é uma ilusão

Encontrar e corrigir defeitos não garante automaticamente o sucesso do software.

Um sistema pode estar tecnicamente correto e ainda assim:

não atender às necessidades do usuário;
possuir experiência ruim;
ser difícil de utilizar;
não resolver o problema esperado.

Qualidade não significa apenas ausência de bugs, mas também valor para o usuário.

Níveis de Teste
Teste de Componente (Teste Unitário)

Testes unitários validam pequenas partes isoladas do sistema.

São rápidos, baratos e executados em grande quantidade.

Exemplos:
funções;
métodos;
classes;
validações;
regras de negócio.

Esses testes representam a base da pirâmide de testes.

Teste de Integração

Os testes de integração validam a comunicação entre diferentes partes do sistema.

Exemplos:
frontend comunicando com backend;
autenticação;
APIs;
integração com banco de dados;
gateways de pagamento.

Esses testes possuem velocidade e custo intermediários na pirâmide de testes.

Teste de UI / End-To-End

Os testes de UI (Interface do Usuário) ou End-To-End validam o fluxo completo da aplicação pela perspectiva do usuário final.

Exemplos:
login;
cadastro;
checkout;
formulários;
navegação entre páginas.

Esses testes envolvem:

frontend;
backend;
APIs;
banco de dados;
integrações.

Por esse motivo, ficam no topo da pirâmide de testes, sendo os mais lentos, complexos e caros de manter.

Objetivo

Meu objetivo é aprofundar conhecimentos em:

QA Manual;
APIs;
automação de testes;
testes web;
qualidade de software;
processos ágeis;
testes de integração;
testes End-To-End.
Próximos Estudos
Postman
HTTP Methods
APIs REST
Cypress / Playwright
Automação Web
Git e GitHub
CI/CD
Testes Automatizados
