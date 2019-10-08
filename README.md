# Desenvolvimento de um pequeno jogo de tabuleiro

Criar um jogo interativo de jogo-da-velha com React.

## Fundamentos e Técnicas

Abaixo estão descritas os fundamentos e tecnicas utilizadas.

### Componentes

Usamos componentes para dizer ao React o que queremos ver na tela. Quando nossos dados forem alterados, o React atualizará e renderizará novamente com eficiência nossos componentes.

### Props

Um componente recebe parâmetros, chamados props (abreviação de propriedades).

### State

O state do componente é similar as props, mas é privado e totalmente controlado pelo componente.

### Arrow Functions (ES6)

Uma expressão arrow function possui uma sintaxe mais curta, semelhante as expressões lambda presente em linguagens como Java, F# entre outras.
As arrow functions possuem dois benefícios:
São menos verbosas do que as funções tradicionais e Seu valor de this é definido à partir das funções onde foram definidas. Ou seja, não é mais necessário fazer bind() ou armazenar o estado em that = this;

const sum = (num1, num2) => num1 + num2;

### Template literals (ES6)

Template literals são literals que representam uma String com suporte a interpolation e multiplas linhas.

let myVar = 'es6';
console.log(`Welcome ${myVar}!`);
