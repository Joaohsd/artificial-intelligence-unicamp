# **Introdução a linguagem Python**

Python é uma linguagem de programação de alto nível, interpretada, de tipagem dinâmica e multiplataforma. Criada no final dos anos 80, a linguagem é utilizada em diversas áreas, como desenvolvimento web, ciência de dados, automação de tarefas e inteligência artificial. Python possui uma sintaxe clara e concisa, o que facilita o aprendizado e a leitura do código. Além disso, sua grande comunidade de desenvolvedores contribui para uma vasta biblioteca de módulos e pacotes, que tornam a programação mais eficiente e produtiva. A linguagem é multiplataforma, podendo ser executada em diversos sistemas operacionais, como Windows, Linux e macOS.

## **Estrutura básica de um programa**
O escopo de um bloco de código é definido pela indentação, ou seja um espaçamento.

* **Indentação CORRETA:** 
    ```python
    print('Hello, world!')
    print('Welcome to my GitHub!')
    ```
* **Indentação INCORRETA:** 
    ```python
    print('Hello, world!')
        print('Welcome to my GitHub!')
    ```

## **Objetos**

Qualquer dado em python é considerado um objeto, que é de certa maneira um tipo específico. Dito isso, o tipo de um objeto determina quais operações podem ser realizadas sobre o objeto. Por exemplo, o número **5** é representado como um objeto 5 do tipo **int** em Python. Abaixo estão mais alguns exemplos:

```python
print(type('I am a string'))
print(type(5))
print(type('5'))
```
```console
<class 'str'>
<class 'int'>
<class 'str'>
```

## **Variáveis**

Variáveis são uma forma de se associar um nome dado pelo programador com um objeto. Exemplos:

```python
altura = 10
largura = 3
a = 29
a = 'a'
```

Vale observar que o Python é uma linguagem fracamente tipada, ou seja, as variáveis não precisam ser explicitamente declaradas com um tipo de dados específico e podem mudar de tipo durante a execução do programa. Isso oferece maior flexibilidade e facilidade de uso para o programador, mas pode levar a erros de execução se não houver cuidado com o uso das variáveis.

## **Tipos de Dados em Python**

* **Numéricos**: Integer, Float, Complex (X + Yj)
* **Text**: String
* **Listas:** Pode ser heterogêneo e mutável
* **Tuplas:** Pode ser heterogêneo e imutável
* **Sets:** Pode ser heterogêneo e não permite elementos repetidos
* **Dicionários:** Heterogêneo e mutável

## **Funções em Python**

Em Python, funções são blocos de código que realizam uma tarefa específica e podem ser chamadas em diferentes partes do programa. Elas são definidas com a palavra-chave "def" seguida do nome da função e, opcionalmente, seus parâmetros. As funções podem receber entradas, executar operações e retornar um resultado, permitindo que o código seja reutilizado e modularizado.

```python
def multiplyByTwo(parameter):
    a = 2 * parameter
    return a
```