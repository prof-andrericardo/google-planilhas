# 📘 Aula 08 – Atividade prática com fórmulas

🎯 **Objetivo da Aula**  
Consolidar os conhecimentos das aulas anteriores com a construção de uma **planilha completa de simulado escolar**, utilizando várias fórmulas: `MÉDIA()`, `SE()`, `CONT.SE()`, `HOJE()`, multiplicação e soma.

---

## 🧠 Revisão rápida das fórmulas que serão usadas

| Fórmula      | Função                                            |
| ------------ | ------------------------------------------------- |
| `=SOMA()`    | Soma um intervalo de valores                      |
| `=MÉDIA()`   | Calcula a média dos valores                       |
| `=SE()`      | Verifica uma condição e retorna um resultado      |
| `=CONT.SE()` | Conta quantas células atendem a uma condição      |
| `=HOJE()`    | Insere automaticamente a data atual               |
| `=A1*B1`     | Multiplica os valores de duas células diretamente |

---

## 👨‍🏫 Atividade Principal: Planilha de Resultados do Simulado

1. Crie uma planilha chamada **Simulado Final – 1º Trimestre**

2. Monte a seguinte estrutura:

| Aluno  | Nota 1 | Nota 2 | Média | Situação | Data Registro |
| ------ | ------ | ------ | ----- | -------- | ------------- |
| Laura  | 7,5    | 8,0    |       |          |               |
| Pedro  | 6,0    | 6,5    |       |          |               |
| Bianca | 9,0    | 9,5    |       |          |               |
| Felipe | 5,5    | 4,0    |       |          |               |

---

### ✍️ Passo a passo das fórmulas:

#### 📊 1. Calcular a média:
```excel
=MÉDIA(B2:C2)
```

→ Aplique para todos os alunos

#### ✅ 2. Definir situação com `SE()`:

```excel
=SE(D2>=7; "Aprovado"; "Reprovado")
```

→ Copie para todas as linhas

#### 📅 3. Inserir data automática com `HOJE()`:

```excel
=HOJE()
```

→ Use na coluna “Data Registro” para mostrar a data da correção

#### 🔢 4. Contar quantos foram aprovados:

Em uma célula separada (ex: G1), digite:

```excel
=CONT.SE(E2:E5; "Aprovado")
```

------

## 🎨 Dica de formatação visual

- Cabeçalho com cor suave (azul claro ou cinza)
- Negrito e centralizado nas colunas
- Bordas internas e externas em toda a tabela
- Utilize **cores condicionais**: verde para “Aprovado” e vermelho para “Reprovado”

------

## 🧩 Desafio Avançado (opcional)

Crie uma coluna chamada **Conceito** com base na média:

```excel
=SE(D2>=9;"A";SE(D2>=7;"B";"C"))
```

🧠 Isso classifica os alunos com conceito A, B ou C.

------

## 📌 Tarefa para Casa

> Criar uma planilha chamada `Simulado 2º Trimestre` com pelo menos 6 alunos.
>  Aplicar as mesmas fórmulas (média, situação, data, conceito).
>  Utilizar `CONT.SE()` para contar quantos tiraram “A”.

------

## 🪄 Próxima Aula

Na **Aula 09**, vamos mudar de foco e aprender a **criar gráficos automáticos com os dados das planilhas**, como gráficos de colunas, pizza e linhas para representar resultados! 📊📈