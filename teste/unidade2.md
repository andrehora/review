Sobre boas práticas em testes de unidade:

- Testes devem, preferencialmente, utilizar as APIs públicas do sistema. x
- O foco dos testes deve ser o comportamento do sistema, e não seus métodos individuais. x
- Testes que dependem de detalhes internos de implementação tendem a ser mais frágeis. x

Sobre a boa prática de buscar testes estáveis:

- Testes devem ser alterados sempre que ocorrer uma refatoração.
- A adição de novas funcionalidades deve exigir a alteração dos testes existentes.
- Mudanças de comportamento do sistema podem exigir alterações nos testes existentes. x

Durante uma refatoração, espera-se que:

- Os testes existentes continuem válidos sem modificações. x
- Os testes sejam removidos e criados novamente.
- Apenas os testes dos métodos modificados precisem ser atualizados.

Quando um bug é encontrado em um sistema, a prática recomendada é:

- Corrigir o bug e não modificar a suíte de testes.
- Remover os testes que falharam.
- Escrever um novo teste que capture o bug. x

Qual é a principal recomendação da prática de testar através de APIs públicas:

- Alterar a visibilidade dos métodos internos para facilitar os testes.
- Escrever testes utilizando o sistema da mesma forma que seus "usuários". x
- Criar um teste para cada método implementado.

Qual é a principal vantagem de utilizar APIs públicas nos testes:

- Tornar os testes independentes do contrato do sistema.
- Reduzir o número de métodos públicos da aplicação.
- Tornar os testes menos suscetíveis a mudanças internas de implementação. x

Um teste é considerado frágil quando:

- Utiliza apenas interfaces públicas.
- Possui poucas asserções.
- Depende de detalhes internos de implementação. x
- Quebra após refatorações. x

Qual é o principal problema de escrever um teste para cada método do sistema:

- A cobertura de código tende a diminuir.
- Os testes ficam fortemente acoplados aos métodos implementados. x
- O sistema passa a depender de APIs públicas.

Qual das alternativas representa uma consequência de escrever testes focados em métodos, em vez de comportamentos:

- Os testes tornam-se mais resistentes a refatorações.
- Os testes ficam mais simples e independentes da implementação.
- Os testes tendem a crescer junto com os métodos, tornando-se mais difíceis de manter. x

Segundo a abordagem "Teste Comportamento, Não Métodos", um comportamento corresponde a:

- Um método público da classe.
- Uma sequência de linhas de código executadas.
- Uma garantia sobre como o sistema responde a determinadas entradas em um determinado estado. x
