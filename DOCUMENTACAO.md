# 🌵 SertãoCode - Documentação Completa da Linguagem

## 📖 Sobre a Linguagem

**SertãoCode** é uma linguagem esotérica de propósito geral inspirada na cultura nordestina brasileira. Os comandos utilizam expressões típicas do sertão, tornando a programação uma experiência única e culturalmente rica. Além de ser fortemente inspirada nas frases mais conhecidas do Filme: O Auto da Compadecida.

**Extensão dos arquivos:** `.sertao`  
**Traduz para:** Python (`.py`)  
**Tipo:** Linguagem de propósito geral  
**Paradigma:** Imperativo/Procedural

---

## 🎯 Tipos de Dados Suportados

A SertãoCode suporta três tipos de dados básicos:

| Tipo SertãoCode | Equivalente Python | Descrição           | Exemplo         |
|-----------------|--------------------|---------------------|-----------------|
| `Gato`          | `int`              | Números inteiros    | 42, -10, 0      |
| `Promessa`      | `str`              | Strings/texto       | "João", "Olá"   |
| `Milagre`       | `float`            | Números decimais    | 3.14, -2.5, 0.0 |

---

## 📝 Sintaxe da Linguagem

### 1. Estrutura Obrigatória do Programa

Todo programa em SertãoCode **DEVE** começar e terminar com:

```
Ô promessa sem jeito
    # Seu código aqui
Não sei, só sei que foi assim
```

**Importante:** Essas linhas são obrigatórias! O programa não funciona sem elas.

---

### 2. Comentários

Use `Reza:` para adicionar comentários (linhas ignoradas pelo tradutor):

```
Reza: Isso é um comentário
Reza: Serve para explicar o código
```

---

### 3. Declaração de Variáveis

**Sintaxe:**
```
Patrimônio (Tipo) NomeDaVariavel;
```

**Exemplos:**
```
Patrimônio (Gato) idade;
Patrimônio (Promessa) nome;
Patrimônio (Milagre) preco;
```

---

### 4. Atribuição de Valores

**Sintaxe:**
```
Rumo NomeDaVariavel = Valor;
```

**Exemplos:**
```
Rumo idade = 25;
Rumo nome = "João";
Rumo preco = 10.50;
Rumo total = idade + 5;
```

**Nota:** Você pode usar expressões matemáticas na atribuição.

---

### 5. Saída (Imprimir na Tela)

**Sintaxe:**
```
Pregação ValorOuVariavel;
```

**Exemplos:**
```
Pregação "Hello World!";
Pregação idade;
Pregação "O resultado é:";
```

---

### 6. Entrada (Ler do Usuário)

**Sintaxe:**
```
Pergunta do Bispo NomeDaVariavel;
```

**Exemplo:**
```
Patrimônio (Promessa) nome;
Pregação "Digite seu nome:";
Pergunta do Bispo nome;
Pregação nome;
```

**Nota:** O tradutor tenta converter automaticamente para número (int ou float) se possível.

---

### 7. Estrutura Condicional (IF)

**Sintaxe:**
```
Julgamento (do Diabo) (Condição)
    # Código se verdadeiro
Passar a Régua
```

**Exemplo:**
```
Julgamento (do Diabo) (idade >= 18)
    Pregação "É maior de idade";
Passar a Régua
```

---

### 8. Estrutura Condicional (IF-ELSE)

**Sintaxe:**
```
Julgamento (do Diabo) (Condição)
    # Código se verdadeiro
Passar a Régua

Julgamento (da Compadecida)
    # Código se falso
Passar a Régua
```

**Exemplo:**
```
Julgamento (do Diabo) (idade >= 18)
    Pregação "É maior de idade";
Passar a Régua

Julgamento (da Compadecida)
    Pregação "É menor de idade";
Passar a Régua
```

---

### 9. Estrutura de Repetição (WHILE)

**Sintaxe:**
```
Via Sacra (Condição)
    # Código que repete
Passar a Régua
```

**Exemplo:**
```
Patrimônio (Gato) contador;
Rumo contador = 1;

Via Sacra (contador <= 10)
    Pregação contador;
    Rumo contador = contador + 1;
Passar a Régua
```

---

### 10. Operações Matemáticas Especiais

#### Soma
```
Ajuntar A e B;
```
Imprime o resultado de A + B

**Exemplo:**
```
Ajuntar 10 e 20;    # Imprime: 30
```

#### Subtração
```
Minguar A de B;
```
Imprime o resultado de B - A

**Exemplo:**
```
Minguar 5 de 15;    # Imprime: 10
```

#### Multiplicação
```
Riqueza de Major A e B;
```
Imprime o resultado de A * B

**Exemplo:**
```
Riqueza de Major 4 e 5;    # Imprime: 20
```

#### Divisão
```
Partilha A por B;
```
Imprime o resultado de A / B

**Exemplo:**
```
Partilha 20 por 4;    # Imprime: 5.0
```

**Nota:** Essas operações **imprimem** automaticamente o resultado.

---

### 11. Fim de Bloco

Use `Passar a Régua` para marcar o fim de blocos de código:
- Fim de `Julgamento (do Diabo)`
- Fim de `Julgamento (da Compadecida)`
- Fim de `Via Sacra`

---

## 🔢 Operadores Suportados

### Operadores Aritméticos
```
+    # Adição
-    # Subtração
*    # Multiplicação
/    # Divisão
```

### Operadores de Comparação
```
==   # Igual
!=   # Diferente
>    # Maior que
<    # Menor que
>=   # Maior ou igual
<=   # Menor ou igual
```

### Operadores Lógicos
```
and  # E lógico
or   # OU lógico
not  # NÃO lógico
```

**Exemplo de uso:**
```
Julgamento (do Diabo) (idade >= 18 and idade <= 65)
    Pregação "Idade válida";
Passar a Régua
```

---

## 📋 Tabela de Referência Rápida

| Funcionalidade          | Comando SertãoCode              | Equivalente Python |
|-------------------------|---------------------------------|                    |
| Início do programa      | `Ô promessa sem jeito`          | -                  |
| Fim do programa         | `Não sei, só sei que foi assim` | -                  |
| Comentário              | `Reza: texto`                   | `# texto`          |
| Declarar variável       | `Patrimônio (Tipo) var;`        | `var = None`       |
| Atribuir valor          | `Rumo var = valor;`             | `var = valor`      |
| Imprimir                | `Pregação valor;`               | `print(valor)`     |
| Ler entrada             | `Pergunta do Bispo var;`        | `var = input()`    |
| If                      | `Julgamento (do Diabo) (cond)`  | `if cond:`         |
| Else                    | `Julgamento (da Compadecida)`   | `else:`            |
| While                   | `Via Sacra (cond)`              | `while cond:`      |
| Fim de bloco            | `Passar a Régua`                | -                  |
| Soma (imprime)          | `Ajuntar A e B;`                | `print(A + B)`     |
| Subtração (imprime)     | `Minguar A de B;`               | `print(B - A)`     |
| Multiplicação (imprime) | `Riqueza de Major A e B;`       | `print(A * B)`     |
| Divisão (imprime)       | `Partilha A por B;`             | `print(A / B)`     |

---

## 💡 Exemplos Completos

### Exemplo 1: Hello World Básico

```
Ô promessa sem jeito

Pregação "Hello World!";

Não sei, só sei que foi assim
```

---

### Exemplo 2: Variáveis e Entrada

```
Ô promessa sem jeito

Patrimônio (Promessa) nome;
Patrimônio (Gato) idade;

Pregação "Digite seu nome:";
Pergunta do Bispo nome;

Pregação "Digite sua idade:";
Pergunta do Bispo idade;

Pregação "Olá,";
Pregação nome;
Pregação "Você tem";
Pregação idade;
Pregação "anos!";

Não sei, só sei que foi assim
```

---

### Exemplo 3: Condicional Simples

```
Ô promessa sem jeito

Patrimônio (Gato) numero;

Pregação "Digite um número:";
Pergunta do Bispo numero;

Julgamento (do Diabo) (numero > 0)
    Pregação "Número positivo";
Passar a Régua

Julgamento (da Compadecida)
    Pregação "Número negativo ou zero";
Passar a Régua

Não sei, só sei que foi assim
```

---

### Exemplo 4: Loop (Contagem)

```
Ô promessa sem jeito

Patrimônio (Gato) i;
Rumo i = 1;

Pregação "Contando até 5:";

Via Sacra (i <= 5)
    Pregação i;
    Rumo i = i + 1;
Passar a Régua

Pregação "Fim da contagem!";

Não sei, só sei que foi assim
```

---

### Exemplo 5: Calculadora Simples

```
Ô promessa sem jeito

Patrimônio (Milagre) num1;
Patrimônio (Milagre) num2;
Patrimônio (Milagre) resultado;

Pregação "=== CALCULADORA ===";
Pregação "Digite o primeiro número:";
Pergunta do Bispo num1;

Pregação "Digite o segundo número:";
Pergunta do Bispo num2;

Pregação "SOMA:";
Rumo resultado = num1 + num2;
Pregação resultado;

Pregação "SUBTRAÇÃO:";
Rumo resultado = num1 - num2;
Pregação resultado;

Pregação "MULTIPLICAÇÃO:";
Rumo resultado = num1 * num2;
Pregação resultado;

Pregação "DIVISÃO:";
Rumo resultado = num1 / num2;
Pregação resultado;

Não sei, só sei que foi assim
```

---

## ⚠️ Regras Importantes

### Regras Obrigatórias

1. ✅ Todo programa **DEVE** começar com `Ô promessa sem jeito`
2. ✅ Todo programa **DEVE** terminar com `Não sei, só sei que foi assim`
3. ✅ Todo comando **DEVE** terminar com ponto-e-vírgula `;`
4. ✅ Todo bloco **DEVE** terminar com `Passar a Régua`
5. ✅ Variáveis **DEVEM** ser declaradas antes de usar

### Boas Práticas

- 📝 Use comentários para explicar o código
- 🔤 Use nomes descritivos para variáveis
- 📐 Mantenha a indentação consistente (facilita leitura)
- ✨ Teste seu código após cada modificação

---

## 🔧 Processo de Tradução

### Como o Tradutor Funciona

1. **Lê** o arquivo `.sertao`
2. **Analisa** cada linha do código
3. **Traduz** os comandos SertãoCode para Python
4. **Gera** um arquivo `.py` executável

### Exemplo de Tradução

**Código SertãoCode:**
```
Ô promessa sem jeito

Patrimônio (Gato) x;
Rumo x = 10;
Pregação x;

Não sei, só sei que foi assim
```

**Código Python Gerado:**
```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-
# Código traduzido de SertãoCode para Python

x = None  # tipo: Gato
x = 10
print(x)
```

---

## 🚫 Limitações Conhecidas

1. **Não suporta funções definidas pelo usuário**
2. **Não suporta arrays/listas nativamente** (mas pode usar variáveis múltiplas)
3. **Não suporta estruturas de dados complexas** (dicionários, classes)
4. **Não suporta import de bibliotecas**
5. **Evite `else` muito aninhados** (pode causar problemas de indentação)

---

## 🎓 Filosofia da Linguagem

A SertãoCode foi criada com os seguintes princípios:

- 🌵 **Cultural**: Valorizar a cultura nordestina brasileira (Inspiração em Auto da Compadecida)
- 📚 **Educacional**: Facilitar o aprendizado de programação
- 🎨 **Criativa**: Tornar a programação mais divertida
- 🔧 **Funcional**: Ser uma linguagem de propósito geral real

---

## 📚 Glossário de Termos

| Termo SertãoCode              | Significado Cultural         | Função na Linguagem    |
|-------------------------------|------------------------------|------------------------|
| Ô promessa sem jeito          | Expressão de surpresa/início | Início do programa     |
| Não sei, só sei que foi assim | Expressão popular nordestina | Fim do programa        |
| Patrimônio                    | Bens/posses                  | Declaração de variável |
| Rumo                          | Direção/destino              | Atribuição             |
| Pregação                      | Pregar/anunciar              | Imprimir               |
| Pergunta do Bispo             | Autoridade religiosa pergunta| Entrada de dados       |
| Julgamento do Diabo           | Julgamento negativo          | Condicional IF         |
| Julgamento da Compadecida     | Misericórdia/perdão          | Condicional ELSE       |
| Via Sacra                     | Caminho/jornada              | Loop WHILE             |
| Passar a Régua                | Medir/finalizar              | Fim de bloco           |
| Gato                          | Esperto/inteligente          | Tipo inteiro           |
| Promessa                      | Palavra dada                 | Tipo string            |
| Milagre                       | Evento especial              | Tipo float             |
| Ajuntar                       | Juntar/unir                  | Soma                   |
| Minguar                       | Diminuir                     | Subtração              |
| Riqueza de Major              | Fortuna multiplicada         | Multiplicação          |
| Partilha                      | Dividir/repartir             | Divisão                |
| Reza                          | Oração                       | Comentário             |

---

## 🎯 Exercícios Propostos

### Nível Básico

1. Crie um programa que leia seu nome e imprima "Olá, [nome]!"
2. Faça um programa que some dois números digitados pelo usuário
3. Crie um contador que vai de 1 até 10

### Nível Intermediário

4. Faça um programa que determine se um número é par ou ímpar
5. Crie uma tabuada de um número escolhido pelo usuário
6. Faça um programa que calcule a média de 3 notas

### Nível Avançado

7. Crie um jogo de adivinhação (usuário tenta adivinhar um número)
8. Faça um conversor de temperatura (Celsius para Fahrenheit)
9. Crie um programa que calcule fatorial de um número

---

## 🌟 Contribuindo

Ideias para expandir a linguagem:

- 📝 Adicionar mais operações matemáticas
- 🔄 Implementar for loops
- 🎯 Adicionar suporte a funções
- 📊 Criar estruturas de dados nativas
- 🎨 Expandir o vocabulário nordestino

---

## 📞 Suporte e Ajuda

Se você encontrar problemas ou tiver dúvidas:

1. Consulte a seção de **Regras Importantes**
2. Verifique os **Exemplos Completos**
3. Revise a **Tabela de Referência Rápida**
4. Confira o arquivo **README.md** para comandos de execução
5. Caso queira contacte nossa **Equipe de Desenvolvimento**, ficaremos felizes em ajudar.

## 🎉 Conclusão

A SertãoCode é mais que uma linguagem de programação - é uma celebração da cultura nordestina através do código! 

**Oxente, bora programar! 🌵**

---

**Versão:** 1.0  
**Data:** Dezembro 2025  
**Licença:** Projeto Acadêmico