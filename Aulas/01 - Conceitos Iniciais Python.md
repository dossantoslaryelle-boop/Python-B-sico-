# 📘 README — Introdução à Programação com Python

## 🎯 Objetivo
Este material tem como objetivo organizar e facilitar seus estudos iniciais em Python, apresentando os conceitos fundamentais de forma clara, prática e fácil de revisar.

---

## 🧠 1. Estrutura Básica do Python
- O Python executa o código **de cima para baixo**
- Não é necessário usar `main`
- Sintaxe simples e legível

### Exemplo:
`print("Olá, mundo!")`

---

## 💬 2. Comentários
Comentários servem para explicar o código e não são executados.

### ✔ Comentário de uma linha
`# Isso é um comentário`

### ✔ Comentário de múltiplas linhas (docstring)
`"""
Comentário mais detalhado
em várias linhas
"""`

---

## 📦 3. Variáveis
Variáveis armazenam dados na memória.

### 🔹 Características:
- Não precisam de tipo declarado
- Tipagem dinâmica
- Podem mudar de valor

### Exemplo:
`nome = "Ana"`
`idade = 20`
`altura = 1.65`

---

## 🔢 4. Tipos de Dados
| Tipo | Descrição | Exemplo |
|------|----------|--------|
| int | Número inteiro | `10` |
| float | Número decimal | `19.9` |
| str | Texto | `"Python"` |
| bool | Verdadeiro/Falso | `True` |

---

## 🔍 5. Função `type()`
Usada para verificar o tipo de uma variável.

`print(type(nome))`  
`print(type(idade))`

---

## ⌨️ 6. Entrada de Dados
A função `input()` permite que o usuário digite informações.

`nome = input("Digite seu nome: ")`  
`print("Olá,", nome)`

📌 **Importante:** Tudo que vem do `input()` é do tipo `str`.

---

## 🔄 7. Conversão de Tipos (Casting)
Converte valores para outros tipos.

`idade = int(input("Digite sua idade: "))`  
`altura = float(input("Digite sua altura: "))`

---

## ➕ 8. Operadores Aritméticos
| Operador | Função |
|----------|--------|
| + | Soma |
| - | Subtração |
| * | Multiplicação |
| / | Divisão |
| // | Divisão inteira |
| % | Resto |
| ** | Potência |

### Exemplo:
`a = 10`  
`b = 3`  

`print(a + b)`  
`print(a * b)`  
`print(a ** b)`

---

## ✅ 9. Boas Práticas
- Use nomes claros (`nome`, `idade`, `media_final`)
- Evite espaços e acentos
- Use padrão `snake_case`
- Mantenha o código organizado

---

## 🧪 10. Exercícios para Praticar

### 📝 Exercício 1
`nome = input("Digite seu nome: ")`  
`idade = int(input("Digite sua idade: "))`  
`print("Olá,", nome, "você tem", idade, "anos")`

### 📝 Exercício 2
`n1 = float(input("Digite um número: "))`  
`n2 = float(input("Digite outro número: "))`  
`print("Soma:", n1 + n2)`

### 📝 Exercício 3
`n1 = float(input("Nota 1: "))`  
`n2 = float(input("Nota 2: "))`  
`n3 = float(input("Nota 3: "))`  

`media = (n1 + n2 + n3) / 3`  
`print("Média:", media)`

---

## 🚀 Dica Final
A melhor forma de aprender programação é **praticando**. Teste, erre, corrija e evolua constantemente.

---

## 📌 Organização sugerida do repositório
`📁 estudos-python`  
` ┣ 📄 README.md`  
` ┣ 📁 exemplos`  
` ┣ 📁 exercicios`  
` ┗ 📁 projetos`

---

💡 **Conclusão:**  
Este README serve como base para seus estudos iniciais. Conforme você evoluir, pode ir adicionando novos conteúdos como estruturas de decisão, loops, funções e projetos mais avançados.
