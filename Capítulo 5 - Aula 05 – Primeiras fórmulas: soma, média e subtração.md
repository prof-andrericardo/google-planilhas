# 📘 Aula 05 – Primeiras fórmulas: soma, média e subtração

🎯 **Objetivo da Aula**  
Ensinar os alunos a utilizar fórmulas matemáticas básicas no Google Planilhas, como **SOMA**, **MÉDIA** e operações de **subtração simples**, com exemplos aplicados a situações do cotidiano escolar.

---

## 🧠 O que são fórmulas?

Fórmulas são **comandos que realizam cálculos automáticos** usando os dados que estão nas células. Toda fórmula no Google Planilhas começa com o sinal de igual `=`.

---

## ➕ Função `=SOMA()`

A função `SOMA` soma os valores de um intervalo de células.

### ✍️ Exemplo:

| Item    | Valor R$ |
| ------- | -------- |
| Lápis   | 2,00     |
| Caderno | 10,00    |
| Mochila | 150,00   |

- Na célula **B5**, digite:

```excel
=SOMA(B2:B4)
```

📌 Isso irá somar: 2 + 10 + 150 = **162**

------

## 📊 Função `=MÉDIA()`

A função `MÉDIA` calcula a média aritmética dos valores informados.

### ✍️ Exemplo:

```
| Matéria     | Nota 1 | Nota 2 |
|-------------|--------|--------|
| Matemática  | 7,5    | 8,5    |
```

- Na célula **D2**, digite:

```excel
=MÉDIA(B2:C2)
```

📌 Isso irá calcular: (7,5 + 8,5) ÷ 2 = **8,0**

------

## ➖ Subtração direta

Para subtrair valores, basta usar o sinal de menos `-`.

### ✍️ Exemplo:

```excel
=B3 - B2
```

📌 Subtrai o valor da célula B2 do valor em B3.

------

## 📌 Dica: Como entender o intervalo B2:B4?

O intervalo `B2:B4` significa: **da célula B2 até a B4**, incluindo todas as células no meio.

- `B2:B4` → B2, B3, B4
- `A1:D1` → A1, B1, C1, D1

------

## 👨‍🏫 Atividade em Sala

Crie uma planilha chamada `Controle de Gastos Escolares` com a seguinte tabela:

```
| Item         | Quantidade | Preço Unitário | Total |
|--------------|------------|----------------|--------|
| Lápis        | 10         | 1,50           |        |
| Caderno      | 2          | 12,00          |        |
| Mochila      | 1          | 150,00         |        |
```

### Faça o seguinte:

- Na coluna `Total`, use fórmula: `=B2*C2`, depois arraste para as outras linhas
- Ao final, em uma linha chamada `Total Geral`, use:

```excel
=SOMA(D2:D4)
```

------

## 📝 Desafio

Crie a tabela `Notas de Simulado` com as colunas:

```
| Aluno       | Nota 1 | Nota 2 | Média |
|-------------|--------|--------|--------|
| João        | 7,0    | 8,5    |        |
| Ana         | 9,0    | 9,5    |        |
| Caio        | 6,5    | 7,0    |        |
```

- Use a fórmula `=MÉDIA(B2:C2)` na coluna Média.
- Aplique a fórmula para todas as linhas.

------

## 📌 Tarefa para Casa

> Criar uma planilha chamada `Boletim Trimestre 1` com colunas: Matéria, Nota 1, Nota 2, Média.
>  Deve conter pelo menos 4 matérias e aplicar a função `MÉDIA()` corretamente.

------

## 🪄 Próxima Aula

Na **Aula 06**, vamos aprender a fazer **multiplicações, divisões e como travar células com o uso de referências absolutas (ex: $A$1)** para cálculos mais avançados! 📌