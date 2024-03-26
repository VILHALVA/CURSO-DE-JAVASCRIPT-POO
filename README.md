# CURSO DE JAVASCRIPT POO
👨‍⚖️JAVASCRIPT É UMA LINGUAGEM DE PROGRAMAÇÃO.

<img src="FOTO.png" align="center" width="400"> <br>

## VISÃO PANORÂMICA:
| PERGUNTA | RESPOSTA |
| :---: | :---: |
| DATA DE CRIAÇÃO | 1995 |
| NOME DO CRIADOR | Brendan Eich | 
| SIGNIFICADO DO NOME | O nome "JavaScript" foi escolhido pela Netscape por razões de marketing, aproveitando o sucesso e popularidade da linguagem Java na época. |
| É BASEADA NO | C C++ |
| EXTENÇÃO DO ARQUIVO | .js |
| É MAIS USADA | Desenvolvimento web (FrontEnd) |

* O JavaScript foi criado por Brendan Eich em 1995, quando ele era um engenheiro da Netscape Communications Corporation. A linguagem foi inicialmente chamada de "Mocha" e posteriormente renomeada para "LiveScript" antes de adotar o nome "JavaScript".
* O nome "JavaScript" foi escolhido pela Netscape por razões de marketing, aproveitando o sucesso e popularidade da linguagem Java na época. No entanto, o JavaScript e o Java são linguagens distintas, com sintaxes e propósitos diferentes.
* O JavaScript é uma linguagem de programação de alto nível, dinâmica e orientada a objetos. Ela foi criada originalmente para adicionar recursos interativos aos navegadores web e permitir a criação de conteúdo dinâmico nas páginas da web.
* O JavaScript é amplamente usado no desenvolvimento web, principalmente para criar interatividade e funcionalidades dinâmicas nas páginas da web. Com o surgimento de tecnologias como o Node.js, o JavaScript também é utilizado para desenvolver aplicativos de servidor e aplicativos de linha de comando.
* Além do desenvolvimento web, o JavaScript tem sido usado em outras áreas, como desenvolvimento de jogos, aplicativos móveis híbridos, aplicações de desktop com ferramentas como o Electron, desenvolvimento de extensões de navegador e até mesmo para criação de scripts automatizados.
* O JavaScript também é a base para muitos frameworks e bibliotecas populares, como React, Angular e Vue.js, que são amplamente utilizados para desenvolvimento web moderno.
* A sintaxe do JavaScript foi influenciada por várias linguagens de programação, mas sua estrutura básica é derivada da linguagem de programação C, assim como muitas outras linguagens modernas. A sintaxe do JavaScript também possui semelhanças com a linguagem de programação Java, embora as duas linguagens sejam diferentes em suas características e propósitos.
* Embora o JavaScript compartilhe algumas semelhanças com o C e o Java em termos de sintaxe, ele possui recursos únicos e específicos, como manipulação de eventos, manipulação do DOM (Document Object Model) e recursos assíncronos. Esses recursos tornam o JavaScript uma linguagem poderosa e flexível para o desenvolvimento de aplicativos web interativos.
* É importante notar que, embora o nome "JavaScript" possa sugerir uma relação próxima com a linguagem de programação Java, as duas são linguagens independentes com propósitos e características diferentes. O JavaScript é uma linguagem interpretada e dinamicamente tipada, enquanto o Java é uma linguagem compilada e estaticamente tipada.
* Em resumo, o JavaScript foi criado por Brendan Eich e é uma linguagem de programação amplamente usada no desenvolvimento web. Ela fornece recursos interativos e dinâmicos às páginas da web e é utilizada para desenvolver uma variedade de aplicativos, desde websites interativos até aplicativos móveis, jogos e muito mais.

## REGRAS DO JAVASCRIPT:
1. JavaScript é uma linguagem de programação amplamente utilizada que pode ser executada em diferentes ambientes, sendo dois dos principais o navegador web e o ambiente Node.js no console. Aqui estão algumas informações sobre essas duas abordagens:

**JavaScript no Navegador (com HTML e DOM)**:
   - **Front-End**: No navegador, JavaScript é amplamente utilizado para criar aplicações web interativas e dinâmicas. Ele interage com o Document Object Model (DOM) do HTML para manipular a estrutura e o conteúdo das páginas web.
   - **Eventos**: JavaScript no navegador é usado para lidar com eventos do usuário, como cliques de mouse, pressionamentos de teclas e envio de formulários.
   - **Comunicação com Servidor**: Pode ser usado para fazer requisições AJAX para se comunicar com um servidor e atualizar partes de uma página sem a necessidade de recarregar a página inteira.
   - **Bibliotecas e Frameworks**: Existem muitas bibliotecas e frameworks JavaScript populares, como jQuery, React, Angular e Vue.js, que facilitam o desenvolvimento de aplicações web complexas.

**JavaScript no Console (Node.js)**:
   - **Back-End**: Node.js é um ambiente de execução JavaScript no lado do servidor. Ele permite que você crie aplicativos de servidor, APIs, scripts de linha de comando e muito mais usando JavaScript.
   - **Módulos e NPM**: Node.js facilita a organização de código em módulos e a instalação de bibliotecas de terceiros usando o npm (Node Package Manager).
   - **Manipulação de Arquivos**: É possível acessar o sistema de arquivos, criar, ler e escrever arquivos com JavaScript no Node.js.
   - **Programação Assíncrona**: JavaScript no Node.js lida bem com programação assíncrona, tornando-o adequado para operações de entrada/saída intensivas, como solicitações de rede e operações de arquivo.

A escolha de usar JavaScript no navegador ou no console (Node.js) depende dos requisitos do seu projeto:

- Se você está criando uma aplicação web, JavaScript no navegador é essencial para adicionar interatividade às suas páginas web.
- Se você precisa criar um servidor web, automatizar tarefas no sistema operacional ou executar tarefas de linha de comando, Node.js é a escolha apropriada.

Em muitos casos, desenvolvedores full-stack usam JavaScript tanto no front-end quanto no back-end para criar aplicativos web completos. Isso permite compartilhar lógica entre o cliente e o servidor e simplificar o desenvolvimento. No entanto, é importante ter em mente que os contextos de execução do JavaScript no navegador e no Node.js têm algumas diferenças, especialmente quando se trata de APIs disponíveis, portanto, é necessário estar ciente dessas diferenças ao trabalhar em ambos os ambientes.

2. Você não é obrigado a terminar os comandos com `;`.

3. Tem um padrão comum usado em código JavaScript/Node.js que envolve o uso de parênteses e chaves para criar blocos de código. Esse padrão é frequentemente usado para criar módulos e funções autoexecutáveis (também conhecidas como Immediately Invoked Function Expressions - IIFE).

Aqui está uma explicação desse padrão:

**Parênteses Externos**:
   - Os parênteses externos `()` são usados para definir uma expressão de função. Isso é necessário porque no JavaScript, quando você declara uma função usando a palavra-chave `function`, ela é considerada uma declaração de função e não pode ser chamada diretamente.

**Parênteses Internos**:
   - Os parênteses internos `( )` são usados para envolver uma função anônima. Isso cria uma função que é definida e executada imediatamente.

**Chaves**:
   - As chaves `{ }` são usadas para definir o corpo da função. O código dentro das chaves é executado quando a função é chamada.

Este padrão é frequentemente usado em módulos Node.js para encapsular o escopo de um módulo e evitar que variáveis locais do módulo poluam o escopo global. 

4. No JavaScript, "let", "var" e "const" são três palavras-chave usadas para declarar variáveis, mas elas têm diferenças importantes em relação ao escopo e à mutabilidade. Aqui está uma breve explicação de cada uma:

**var**:
   - **Escopo de função**: Variáveis declaradas com `var` têm escopo de função, o que significa que elas são visíveis em toda a função em que foram declaradas.
   - **Hoisting**: As declarações `var` são "elevadas" (hoisted) para o topo da função ou escopo em que estão, o que significa que elas podem ser usadas antes mesmo de serem declaradas. No entanto, o valor atribuído a elas só é definido no momento em que são declaradas.
   - **Mutabilidade**: Variáveis `var` podem ser reatribuídas e atualizadas em qualquer lugar do escopo em que foram declaradas.

**let**:
   - **Escopo de bloco**: Variáveis declaradas com `let` têm escopo de bloco, o que significa que elas são visíveis apenas dentro do bloco em que foram declaradas (um bloco é delimitado por chaves `{}`). Isso inclui escopos de função, loops `for`, condicionais `if`, etc.
   - **Hoisting**: Assim como as variáveis `var`, as declarações `let` também são "elevadas" para o topo do escopo de bloco, mas elas não são inicializadas até que a execução alcance a declaração.
   - **Mutabilidade**: Variáveis `let` podem ser reatribuídas, mas não podem ser redeclaradas no mesmo escopo.

**const**:
   - **Escopo de bloco**: Variáveis declaradas com `const` também têm escopo de bloco, assim como o `let`.
   - **Hoisting**: Assim como o `let`, as declarações `const` são "elevadas" para o topo do escopo de bloco, mas também não são inicializadas até que a execução alcance a declaração.
   - **Mutabilidade**: A principal diferença entre `const` e `let` é que as variáveis `const` não podem ser reatribuídas após a atribuição inicial. Isso significa que uma vez que você atribui um valor a uma variável `const`, você não pode alterá-lo posteriormente.

É uma boa prática usar `const` sempre que possível, pois ajuda a tornar o código mais previsível e menos propenso a erros. Use `let` quando você precisa reatribuir variáveis e evite o uso de `var`, pois pode levar a problemas de escopo inesperados.

## CARACTERISTICAS DA LINGUAGEM:
### POSITIVAS:
* **1 - Sintaxe Simples:** A sintaxe do JavaScript é relativamente simples e fácil de aprender. Ela é baseada em grande parte na sintaxe do C, o que facilita a transição para desenvolvedores que já estão familiarizados com outras linguagens como C++, Java ou C#.
* **2 - Linguagem Interpretada:** O JavaScript é uma linguagem interpretada, o que significa que não requer um processo de compilação antes da execução. Isso torna o desenvolvimento mais rápido, pois você pode fazer alterações no código e ver os resultados imediatamente.
* **3 - Suporte a Programação Orientada a Objetos:** Embora o JavaScript seja uma linguagem de programação multiparadigma, ele suporta programação orientada a objetos. Você pode criar classes, herdar propriedades e métodos, usar polimorfismo e encapsulamento, entre outros conceitos de OOP.
* **4 - Tipagem Dinâmica:** O JavaScript possui tipagem dinâmica, o que significa que as variáveis não têm um tipo fixo. Você pode atribuir diferentes tipos de valores a uma variável ao longo do tempo. Isso oferece flexibilidade e simplifica o desenvolvimento em certos cenários, pois você não precisa declarar explicitamente o tipo de variável.
* **5 - Manipulação de DOM:** O JavaScript é amplamente utilizado para manipular o Document Object Model (DOM) de uma página web. Isso permite interagir com elementos HTML, modificar seu conteúdo, estilo e comportamento dinamicamente, respondendo a eventos do usuário, como cliques ou rolagens.
* **6 - Suporte a Assíncrono:** O JavaScript é projetado para lidar com operações assíncronas de forma eficiente, como chamadas de API, manipulação de eventos e operações de I/O. Ele possui recursos embutidos, como callbacks, Promises e async/await, que facilitam a escrita de código assíncrono de forma mais clara e legível.
* **7 - Grande Ecossistema:** O JavaScript possui uma comunidade de desenvolvedores ativa e um vasto ecossistema de bibliotecas e frameworks, como React, Angular e Vue.js, que tornam o desenvolvimento web mais produtivo e poderoso.
* **8 - Execução no Navegador:** O JavaScript é a linguagem padrão para programação no navegador. Isso significa que qualquer dispositivo com um navegador moderno é capaz de executar código JavaScript, permitindo a criação de aplicações web interativas e responsivas.

### NEGATIVAS:
* **1 - Tipagem Fraca:** Enquanto a tipagem dinâmica do JavaScript pode ser uma vantagem em certos aspectos, também pode ser uma fonte de erros difíceis de detectar. Como as variáveis não possuem um tipo fixo, é possível realizar operações inesperadas em tempo de execução, o que pode resultar em erros difíceis de rastrear e depurar.
* **2 - Compatibilidade entre Navegadores:** Embora o JavaScript seja executado em todos os navegadores modernos, pode haver diferenças de compatibilidade entre as implementações do JavaScript em cada navegador. Isso pode levar a problemas de compatibilidade e requerer ajustes no código para garantir que ele funcione corretamente em diferentes navegadores.
* **3 - Gerenciamento de Escopo:** O JavaScript possui regras complexas para o escopo de variáveis e o gerenciamento de contexto. Isso pode levar a situações em que variáveis não têm o escopo desejado ou o contexto do this não é o esperado, o que pode ser confuso e levar a erros.
* **4 - Segurança:** Como o JavaScript é executado no lado do cliente, em um ambiente não confiável, há riscos de segurança associados. Os desenvolvedores devem estar cientes de práticas de segurança e evitar vulnerabilidades, como ataques de injeção de código ou acesso não autorizado a dados sensíveis.
* **5 - Código Assíncrono Complexo:** Embora o JavaScript possua recursos para lidar com operações assíncronas, como callbacks, Promises e async/await, a manipulação de código assíncrono complexo pode se tornar difícil de ler e entender. O aninhamento excessivo de callbacks, por exemplo, pode levar a um padrão conhecido como "callback hell" (inferno de callbacks), que pode tornar o código complexo e difícil de manter.
* **6 - Escalabilidade e Manutenção:** À medida que os projetos em JavaScript crescem, pode se tornar desafiador manter um código bem estruturado e modular. A falta de um sistema de tipos estático pode dificultar a detecção de erros antes da execução e aumentar a carga de trabalho de testes e depuração.
* **7 - Lentidão em Operações Intensivas:** O JavaScript pode ser menos eficiente em operações intensivas de CPU em comparação com outras linguagens, devido à sua natureza interpretada e à otimização limitada do mecanismo de execução em alguns cenários. No entanto, o JavaScript é frequentemente usado em conjunto com outras tecnologias para superar essa limitação.

## SUBSIDIOS:
- [CURSO CRIADO PELO "VIVO DE CÓDIGO"](https://youtube.com/playlist?list=PLTULYczsbNmoLrNyVESgaqJTxMUEPl9Gv&si=BhPMBp0a9k0rlIVd)
- [CURSO FEITO PELO VILHALVA](https://github.com/VILHALVA)
- [VEJA A DOCUMENTAÇÃO](https://devdocs.io/javascript/)
- [VEJA A SINTAXE](./SINTAXE.md)
- [CURSO DE JAVASCRIPT](https://github.com/VILHALVA/CURSO-DE-JAVASCRIPT)
- [VEJA OS PROJETOS](https://github.com/VILHALVA?tab=repositories&q=+topic:JAVASCRIPT)
