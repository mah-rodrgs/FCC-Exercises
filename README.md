Este projeto foi desenvolvido como o desafio prático final da primeira parte (**Foundations of C#**) do treinamento oficial da Microsoft em parceria com o **freeCodeCamp**.

O objetivo principal é consolidar os fundamentos da linguagem C#, simulando um sistema que calcula e exibe o boletim e o GPA (Grade Point Average) de uma estudante, aplicando regras de formatação e conversão de tipos de dados.

## Conceitos Aplicados

Durante o desenvolvimento deste desafio, foram praticados os seguintes conceitos fundamentais:

* **Declaração e Inicialização de Variáveis:** Uso correto de tipos primitivos (`string`, `int`, `decimal`).
* **Operações Aritméticas e Atribuição Composta:** Cálculo de pontos de grade acumulados e soma de horas de crédito utilizando operadores como `+=` e `*`.
* **Conversão de Tipos (Casting):** Conversão explícita de `int` para `decimal` para evitar divisão inteira e extração de dígitos específicos usando o operador de módulo (`%`).
* **Formatação de String com Caracteres de Escape:** Uso de `\t` (tabulação) e `\n` (nova linha) para alinhar os dados no console em formato de tabela.
* **Interpolação de Strings:** Exibição dinâmica de variáveis dentro de literais de string formatados.

## Exemplo de Saída no Console

Ao executar a aplicação, o console exibe a tabela perfeitamente alinhada:

```text
Student Name: Sophia Johnson

Course                  Grade   Credit Hours
English 101             4       3
Algebra 101             3       3
Biology 101             3       4
Computer Science I      3       4
Psychology 101          4       3

Final GPA:              3.35