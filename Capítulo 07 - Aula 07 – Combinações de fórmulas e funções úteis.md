# 📘 Aula 07 – Combinações de fórmulas e funções úteis

🎯 **Objetivo da Aula**  
Ensinar os alunos a usar **funções úteis combinadas** no Google Planilhas, como `SE`, `CONT.SE` e `HOJE()`, para tornar suas planilhas **inteligentes**, **automatizadas** e **interativas**.

---

## 🔍 Função `SE` (condicional)

A função `SE` permite que você **verifique uma condição** e **retorne um valor diferente dependendo do resultado** (sim ou não).

### 🧠 Estrutura:
```excel
=SE(condição; valor_se_verdadeiro; valor_se_falso)
```

### ✍️ Exemplo:

```
=SE(B2>=7; "Aprovado"; "Reprovado")
```

🧠 Se o valor da célula B2 for **maior ou igual a 7**, retorna "Aprovado".
 Caso contrário, retorna "Reprovado".

------

## 🔢 Função `CONT.SE` (contagem com critério)

Conta quantas células em um intervalo **atendem a uma condição**.

### 🧠 Estrutura:

```excel
=CONT.SE(intervalo; critério)
```

### ✍️ Exemplo:

```excel
=CONT.SE(C2:C10; "Aprovado")
```

🔢 Conta quantas vezes a palavra "Aprovado" aparece no intervalo C2 até C10.

------

## 📆 Função `HOJE()`

Retorna automaticamente a **data atual** do dia em que você abre a planilha.

### ✍️ Exemplo:

```excel
=HOJE()
```

🗓️ Essa fórmula não precisa de argumentos. Sempre que a planilha for aberta, ela mostrará a data do dia.

------

## 👨‍🏫 Atividade em Sala

Crie uma planilha chamada `Resultados do Simulado` com os seguintes dados:

```
| Aluno       | Nota | Situação   |
|-------------|------|------------|
| João        | 8,0  |            |
| Maria       | 6,5  |            |
| Gabriel     | 9,0  |            |
```

### ✍️ Passos:

1. Na coluna **Situação**, use a fórmula:

```excel
=SE(B2>=7; "Aprovado"; "Reprovado")
```

1. Aplique para os outros alunos.
2. Em uma nova célula, conte quantos foram aprovados:

```excel
=CONT.SE(C2:C4; "Aprovado")
```

1. Adicione em outra célula a data do dia com:

```excel
=HOJE()
```

------

## 🧩 Dica: Combinação avançada com `SE` e `HOJE()`

Você pode usar essas funções para verificar prazos!
 Exemplo:

```excel
=SE(B2<HOJE(); "Atrasado"; "Em dia")
```

Isso verifica se a data de entrega (B2) é **menor que a data de hoje**.

------

## 📝 Desafio

Crie uma planilha chamada `Controle de Entregas`.

```
| Tarefa                     | Data Entrega | Status     |
|----------------------------|--------------|------------|
| Estudar para prova de História | 10/06     |            |
| Revisar exercícios         | 20/06        |            |
```

- Use `SE` para verificar se está “Em dia” ou “Atrasado” com base em `HOJE()`

------

## 📌 Tarefa para Casa

> Criar uma planilha chamada `Boletim Escolar – Final` com colunas: Nome, Nota 1, Nota 2, Média, Situação.
>  Usar `MÉDIA()` e `SE()` para calcular a média e definir se está aprovado.
>  Usar `CONT.SE()` para contar quantos foram aprovados.

------

## 🪄 Próxima Aula

Na **Aula 08**, colocaremos em prática tudo o que aprendemos sobre fórmulas, criando uma **planilha completa de simulado com notas, médias, conceitos e contadores automáticos!** 🎯📊

