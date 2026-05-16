# 📘 Miniguia de Estudos — Python para Iniciantes

Este miniguia foi desenvolvido com apoio do NotebookLM para consolidar os principais conceitos estudados durante o projeto.

O objetivo é servir como material rápido de revisão para iniciantes em Python.

---

# 🐍 O que é Python?

Python é uma linguagem de programação:

* simples;
* legível;
* versátil;
* muito utilizada em:

  * desenvolvimento web;
  * automação;
  * ciência de dados;
  * inteligência artificial;
  * análise de dados.

Uma das principais características do Python é sua sintaxe simples e próxima da linguagem humana.

---

# 🟢 Variáveis

Variáveis são utilizadas para armazenar informações dentro do programa.

## Exemplo:

```python
nome = "Aracele"
idade = 25
```

---

# 🟢 Tipos de Dados

Os principais tipos de dados em Python são:

| Tipo    | Exemplo    |
| ------- | ---------- |
| String  | `"Python"` |
| Integer | `10`       |
| Float   | `5.5`      |
| Boolean | `True`     |

---

# 🟢 Estruturas Condicionais

Permitem executar ações diferentes dependendo de uma condição.

## Exemplo:

```python
idade = 18

if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

---

# 🔁 Estruturas de Repetição

São utilizadas para repetir tarefas automaticamente.

## Exemplo com `for`

```python
for numero in range(5):
    print(numero)
```

## Exemplo com `while`

```python
contador = 0

while contador < 5:
    print(contador)
    contador += 1
```

---

# 📚 Listas

Listas armazenam múltiplos valores e podem ser alteradas.

## Exemplo:

```python
frutas = ["maçã", "banana", "uva"]
```

## Principais características:

* mutáveis;
* utilizam colchetes `[]`;
* aceitam diferentes tipos de dados.

---

# 📦 Tuplas

Tuplas também armazenam múltiplos valores, mas não podem ser alteradas.

## Exemplo:

```python
cores = ("azul", "verde", "amarelo")
```

## Principais características:

* imutáveis;
* utilizam parênteses `()`;
* mais seguras para dados fixos.

---

# ⚙️ Funções

Funções permitem reutilizar blocos de código.

## Exemplo:

```python
def saudacao(nome):
    print(f"Olá, {nome}")
```

## Vantagens:

* organização;
* reutilização;
* manutenção mais fácil do código.

---

# 🧠 Programação Orientada a Objetos (POO)

POO é um paradigma que organiza o código utilizando classes e objetos.

---

## 🟣 Classe

Uma classe funciona como um molde.

## Exemplo:

```python
class Pessoa:
    pass
```

---

## 🟣 Objeto

Objeto é uma instância da classe.

## Exemplo:

```python
pessoa1 = Pessoa()
```

---

## 🟣 Método

Métodos são funções dentro da classe.

## Exemplo:

```python
class Pessoa:
    
    def falar(self):
        print("Olá")
```

---

# 📏 Boas Práticas — PEP 8

PEP 8 é o guia oficial de estilo da linguagem Python.

## Recomendações:

* usar identação correta;
* utilizar nomes descritivos;
* evitar linhas muito grandes;
* manter código organizado.

---

# 📖 Glossário

| Termo       | Definição                             |
| ----------- | ------------------------------------- |
| Variável    | Espaço utilizado para armazenar dados |
| Loop        | Estrutura de repetição                |
| Função      | Bloco reutilizável de código          |
| Classe      | Estrutura utilizada na POO            |
| Objeto      | Instância de uma classe               |
| Método      | Função dentro de uma classe           |
| Lista       | Estrutura mutável                     |
| Tupla       | Estrutura imutável                    |
| Condicional | Estrutura baseada em condições        |
| Sintaxe     | Regras da linguagem                   |

---

# 🔁 Prompts Reutilizáveis

```txt
Explique [conceito] de forma simples para iniciantes.
```

```txt
Crie exercícios práticos sobre [tema].
```

```txt
Resuma [assunto] em formato de revisão rápida.
```

```txt
Explique os erros mais comuns em [tema].
```

```txt
Monte uma trilha de estudos sobre [assunto].
```

```txt
Explique este conceito utilizando analogias do cotidiano.
```

---

# 🚀 Conclusão

A utilização do NotebookLM como apoio aos estudos tornou o aprendizado de Python mais organizado, dinâmico e acessível.

Além de auxiliar na compreensão dos conteúdos, a IA também ajudou na criação de resumos, exercícios, revisões e organização da trilha de estudos, funcionando como um verdadeiro professor particular durante o processo de aprendizagem.
