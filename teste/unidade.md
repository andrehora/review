Por que os testes de unidade são considerados a "base da pirâmide de testes":

- Porque são os mais difíceis de automatizar
- Porque testam o sistema inteiro de ponta a ponta
- Porque são numerosos, rápidos e simples de escrever x
- Porque dependem de banco de dados e rede para funcionar

Quais são as principais características dos testes de unidade:

- Estáveis x
- Manuais
- Lentos
- Pequenos x

Qual é a principal razão pela qual empresas adotam os testes de unidade:

- Para substituir a necessidade de revisão de código
- Para garantir que apenas gerentes aprovem mudanças
- Para detectar problemas cedo, antes que ele chegue à produção x
- Porque é uma exigência legal de compliance

Por que a "fixture" de um teste é importante para garantir que um teste seja repetível:

- Porque ela documenta o código-fonte automaticamente
- Porque ela impede que o teste seja executado mais de uma vez
- Porque ela substitui a necessidade de asserts
- Porque ela define um estado inicial conhecido e controlado x

O método de Setup é executado quantas vezes durante a execução de uma classe de teste:

- Uma única vez, antes de todos os testes da classe
- Apenas quando o primeiro teste falha
- Uma vez antes de cada método de teste da classe x
- Uma vez ao final da execução de todos os testes

Quando é mais apropriado usar @BeforeAll em vez de @Before:

- Quando se deseja recriar o estado do zero antes de cada teste individual
- Quando a inicialização é custosa (eg, conexão com recursos) e pode ser compartilhada entre todos os testes da classe x
- Quando se quer garantir que cada teste comece com um estado totalmente isolado dos demais

Qual é a ideia central por trás de escrever um teste para reproduzir um bug reportado por um usuário:

- Documentar formalmente a reclamação do usuário
- Substituir a necessidade de comunicação com o usuário
- Criar uma evidência de que o bug existe e garantir que, uma vez corrigido, ele não volte a ocorrer x
- Servir apenas como registro histórico sem função técnica

O que significam as letras do padrão AAA em testes de unidade:

- Assert, Arrange, After
- Analyze, Act, Assert
- Arrange, Act, Assert x
- Arrange, Act, After

Qual é a semelhança entre os padrões AAA, Given-When-Then e Four-Phase:

- Todos servem para organizar um teste em fases lógicas semelhantes x
- Todos eliminam a necessidade de fixtures
- Todos são específicos para testes de interface gráfica
- Todos requerem bancos de dados reais para funcionar

Assinale verdadeiro (T) ou falso (F):
- Testes de unidade verificam automaticamente pequenas unidades do código, como um método ou uma classe. t
- Testes de unidade formam o topo da pirâmide de testes, sendo os menos comuns em um sistema de software. f
- É uma boa prática implementar todos os testes de unidade somente depois que o sistema estiver completamente pronto. f
- Fixture é o estado do sistema necessário para o teste (dados, objetos, etc.), garantindo que o teste seja repetível. t
