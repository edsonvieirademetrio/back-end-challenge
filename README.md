# Back-End Challenge

Desafio para os futuros programadores back-end da Squad de Portais da Suno.

## Introdução

Desenvolva uma **REST API** que faça conversão de moedas.

**Especifícações**:

* A URL da requisição deve seguir o seguinte formato:
   * http://localhost:8000/exchange/{from}/{to}/?amount={amount}&price={price}
   * http://localhost:8000/exchange/BRL/USD/?amount=100&price=5.58
   * Onde **amount** equivale ao valor total a ser convertido.
   * Onde **price** equivale ao valor da cotação da moeda de referência. Em nosso exemplo estamos convertendo de real para dólar. Portanto, **price** é referente a cotação do dólar (5.58).
* A resposta deve seguir o seguinte formato:
   ```json
   {
     "convertedValue": 17.92,
     "symbol": "$"
   }
   ```
* Conversões:
    * De Real para Dólar;
    * De Dólar para Real;
    * De Real para Euro;
    * De Euro para Real;
* Serão executados testes automatizados para validação dos requisitos:
   * Levantar servidor embutido do PHP: `php -S localhost:8000 index.php`;
   * Executando testes: `composer test`;

## Instruções

1. Efetue o fork deste repositório e crie um branch com o seu nome e sobrenome. (exemplo: joazinho-desouza)
2. Após finalizar o desafio, crie um Pull Request.
3. Aguarde algum contribuidor realizar o code review.

## Pré-requisitos

* PHP >= 7.4
* Orientado a objetos

## Dúvidas

Em caso de dúvidas, crie uma issue.