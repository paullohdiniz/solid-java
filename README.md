# Uma introdução ao princípio de programação SOLID

Se você é um programado, é capaz de já ter se deparado com o termo [SOLID](https://en.wikipedia.org/wiki/SOLID). Introduzido à quase 20 anos, pelo mestre da programação, Robert C. Martin, famoso Uncle Bob, no livro _Princípios de Design e Padrões de Projeto_, nos dá diretrizes para construção de sistema, com linguagem orientadas à objetos, com maior legibilidade, flexibilidade e que permita fácil manutenção.

Neste artigo, vou descrever cada significado e demostrar exemplo da minha vivência como programado de código que aplicam este princípio, e abrir para uma reflexão no entendimento se de fato, isto nos tornou melhores programadores hoje.

1. O "S" refere-se ao (SRP) _Princípio de Responsabilidade Única_, que, de acordo com Robert Martin, significa que "uma classe deve ter apenas um motivo para mudar".

Quando li pela primeira vez essa afirmação, não entendi à fundo o que ele quis dizer. A ideia é, quanto mais motivos para mudar uma classe, significa que ela poderá ter mais de um propósito. 

2. O "O" refere-se ao (OCP) _Princípio de Aberto e Fechado_,  que declara que as entidades de código devem estar abertas para extensão, mas fechadas para modificação.

3. O "L" refere-se ao (LSP) _Princípio da Substituição de Liskov_, que diz que qualquer tipo de filho de um tipo pai deve ser capaz de substituir aquele pai sem que as coisas saiam do controle.

4. O "I" refere-se ao (ISP) _Princípio de Segregação de Interface_, diz que você deve favorecer muitas interfaces específicas de cliente, menores, em uma interface maior e mais monolítica.

5. O "D" refere-se ao (DIP) _Princípio de Inversão de Dependência_, que incentiva você a escrever códigos que dependam de abstrações e não de detalhes concretos.
