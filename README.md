# Uma introdução ao princípios de programação SOLID

Se você é um programado, é capaz de já ter se deparado com o termo [SOLID](https://en.wikipedia.org/wiki/SOLID) inúmeras vezes. E não é por acaso. 

Introduzido oficialmente à quase 20 anos, pelo engenharia de software, Robert C. Martin, famoso Uncle Bob, no livro _Princípios de Design e Padrões de Projeto_, nos dá diretrizes para construção de sistemas, com linguagens orientadas à objetos, com maior legibilidade, flexibilidade e que permita fácil manutenção.

Neste artigo, vou descrever cada significado e demostrar exemplo da minha vivência como programado de código que aplicam este princípio, e abrir para uma reflexão no entendimento se de fato isto nos tornou melhores programadores hoje.

1. O "S" refere-se ao (SRP) _Princípio de Responsabilidade Única_, que, de acordo com Robert Martin, significa que "uma classe deve ter apenas um motivo para mudar".

Considero este princípio a Bounded Context (padrão DDD) da OOP (_Object-oriented programming_). 

Lendo a primeira vista, me perguntei se era possível um objeto ser imutável em um contexto de aplicações em plena evolução. A ideia é, quanto mais motivos se tem para mudar uma classe, significa que, possivelmente, ela terá mais de um propósito. 

2. O "O" refere-se ao (OCP) _Princípio de Aberto e Fechado_,  que declara que as entidades de código devem estar abertas para extensão, mas fechadas para modificação.

3. O "L" refere-se ao (LSP) _Princípio da Substituição de Liskov_, que diz que qualquer tipo de filho de um tipo pai deve ser capaz de substituir aquele pai sem que as coisas saiam do controle.

4. O "I" refere-se ao (ISP) _Princípio de Segregação de Interface_, diz que você deve favorecer muitas interfaces específicas de cliente, menores, em uma interface maior e mais monolítica.

5. O "D" refere-se ao (DIP) _Princípio de Inversão de Dependência_, que incentiva você a escrever códigos que dependam de abstrações e não de detalhes concretos.
