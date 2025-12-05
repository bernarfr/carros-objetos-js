# Carros com Objetos JavaScript

Projeto simples e didático que demonstra o uso de **objetos JavaScript** para representar carros reais, exibindo seus dados tanto no **console** quanto na tela com manipulação de DOM.

## O que o projeto faz
- Cria vários objetos do tipo carro (marca, modelo, ano, cor, preço)
- Exibe todas as informações no console com `console.table()`
- Gera cards automaticamente na página HTML usando JavaScript puro
- Mostra na prática: criação de objetos, acesso a propriedades e saída dinâmica

## Tecnologias utilizadas
- HTML5
- JavaScript vanilla (sem bibliotecas ou frameworks)
- Manipulação de objetos e arrays
- DOM (criação dinâmica de elementos)
- Console API (`console.table`, `console.log`)

## Como executar
1. Clone o repositório
2. Abra o arquivo `index.html` no navegador
3. Abra o DevTools (F12) → aba Console para ver a tabela bonita dos carros

## Exemplo de objeto criado
```javascript
const carro = {
  marca: "Fiat",
  modelo: "Uno Mille",
  ano: 2010,
  cor: "Vermelho",
  preco: 18500
};
