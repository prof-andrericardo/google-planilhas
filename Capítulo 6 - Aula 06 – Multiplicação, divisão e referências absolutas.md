# 📘 Aula 06 – Multiplicação, divisão e referências absolutas

🎯 **Objetivo da Aula**  
Ensinar os alunos a utilizar fórmulas de **multiplicação e divisão** no Google Planilhas e introduzir o conceito de **referência absoluta** usando o símbolo `$`, essencial para criar fórmulas que não mudam ao serem copiadas.

---

## ✖️ Multiplicação (`*`)

A multiplicação é feita com o **símbolo `*`** (asterisco).

### ✍️ Exemplo:

| Produto | Quantidade | Preço Unitário | Total |
| ------- | ---------- | -------------- | ----- |
| Lápis   | 5          | 1,50           |       |

Na célula **D2**, digite:

```excel
=B2*C2
```

🧠 Isso significa: 5 × 1,50 = 7,50

------

## ➗ Divisão (`/`)

A divisão é feita com o **símbolo `/`** (barra).

### ✍️ Exemplo:

```excel
=D2/B2
```

Isso divide o valor total pelo número de itens. Ex: 7,50 ÷ 5 = 1,50

------

## 📌 Dica: Arrastar fórmulas para outras linhas

Após escrever uma fórmula, clique na **alça azul no canto da célula** e arraste para baixo. O Planilhas aplica a fórmula nas outras linhas, **ajustando automaticamente as referências** (isso se chama referência relativa).

------

## 📍 O que é uma Referência Absoluta?

Às vezes, você precisa usar um valor fixo em várias fórmulas. Exemplo: uma **taxa** ou **desconto**.

Para isso, usamos o **símbolo `$`** antes da letra da coluna e do número da linha:

```excel
=$A$1
```

Isso **fixa** a célula A1, mesmo quando a fórmula for arrastada para outras linhas ou colunas.

------

### 🎯 Exemplo prático com desconto fixo:

```
| Produto  | Preço | Desconto | Valor Final |
|----------|-------|----------|-------------|
| Livro    | 30,00 |          |             |
| Caneta   | 10,00 |          |             |
```

1. Na célula **C1**, digite: `0,10` (10% de desconto fixo)
2. Em D2, digite a fórmula:

```excel
=B2 - (B2*$C$1)
```

🧠 Isso calcula o valor com desconto fixo. O uso de `$C$1` garante que, ao arrastar a fórmula, o valor do desconto **não mude**.

------

## 👨‍🏫 Atividade em Sala

Crie uma planilha chamada `Calculadora de Compras`.

```
| Item      | Quantidade | Preço Unitário | Subtotal | Desconto | Total |
|-----------|------------|----------------|----------|----------|--------|
| Caderno   | 3          | 12,00          |          | 0,10     |        |
| Mochila   | 1          | 150,00         |          | 0,10     |        |
```

1. Calcule o **subtotal**: `=B2*C2`
2. Calcule o **total com desconto**: `=D2 - (D2*$E$2)`
3. Aplique as fórmulas nas outras linhas

------

## 📝 Desafio

> Crie uma planilha chamada `Câmbio Escolar` com colunas: Produto, Preço em Real, Taxa de Conversão, Preço em Dólar.
>  Use `$C$1` para travar a taxa de conversão e converta os valores automaticamente com divisão.

------

## 📌 Tarefa para Casa

> Crie uma tabela chamada `Simulação de Loja` com pelo menos 5 produtos.
>  Aplique fórmulas de multiplicação, desconto com referência fixa e total final.

------

## 🪄 Próxima Aula

Na **Aula 07**, vamos aprender a **combinar funções úteis como SE, CONT.SE e HOJE()**, criando planilhas ainda mais inteligentes e interativas! 🧠📆

