# 📘 Aula 04 – Organizando informações com listas e checklists

🎯 **Objetivo da Aula**  
Ensinar os alunos a **criar listas organizadas**, utilizar **caixas de seleção (checklists)** e conhecer os **recursos de validação de dados** para criar **listas suspensas**, facilitando o controle de tarefas ou estudos.

---

## 📋 O que é uma lista em planilhas?

Uma **lista** é uma sequência de informações organizadas verticalmente (linha por linha), muito útil para:

- Planejar estudos
- Organizar tarefas semanais
- Marcar o que já foi feito

---

## ✅ Usando Caixas de Seleção (Checklist)

O Google Planilhas permite adicionar **caixas de seleção** para marcar tarefas como feitas ou não feitas.

### ✍️ Passo a passo:

1. Crie uma nova planilha chamada `Lista de Tarefas`
2. Crie a tabela abaixo:

| Tarefa                        | Prazo | Feita? |
| ----------------------------- | ----- | ------ |
| Estudar para a prova          | 10/06 |        |
| Entregar trabalho de História | 11/06 |        |
| Revisar matemática            | 12/06 |        |

3. Selecione a coluna **“Feita?”**
4. Vá em **Inserir > Caixa de seleção**

🟢 Agora, ao clicar na célula, ela marcará automaticamente com um ✔️

---

## 📌 Dica: Formatação Condicional

Você pode fazer com que uma tarefa fique **verde quando feita** ou **vermelha quando atrasada**!

### 🧪 Exemplo:
- Selecione a linha toda
- Vá em **Formatar > Formatação condicional**
- Regra: “O texto contém ✔️” → cor de fundo verde
- Regra: “A data é menor que HOJE()” → cor vermelha

---

## 🔽 Criando Listas Suspensas (Validação de Dados)

Você pode criar uma **lista suspensa** para escolher entre opções fixas (por exemplo: “Sim”, “Não”, “Talvez”).

### ✍️ Passo a passo:

1. Crie a tabela:

| Atividade                    | Concluída? |
| ---------------------------- | ---------- |
| Ler capítulo de Ciências     |            |
| Resolver lista de exercícios |            |

2. Selecione a coluna “Concluída?”
3. Vá em **Dados > Validação de dados**
4. Em “Critérios”, escolha “Lista de itens” e digite:

Sim, Não, Em andamento

5. Clique em “Salvar”

🟡 Agora, cada célula terá uma setinha para o aluno escolher uma das opções!

---

## 👨‍🏫 Atividade em Sala

Crie uma planilha chamada `Controle de Estudos`.

A tabela deve conter:

| Matéria    | Data da Atividade | Tipo de Tarefa      | Concluído? |
| ---------- | ----------------- | ------------------- | ---------- |
| Matemática | 10/06             | Lista de exercícios |            |
| Geografia  | 11/06             | Leitura             |            |
| Português  | 12/06             | Redação             |            |

Use:
- **Caixas de seleção** para a coluna “Concluído?”
- **Lista suspensa** com: “Sim”, “Não”, “Precisa revisar” (opcional)
- Cor diferente para os cabeçalhos
- Bordas completas
- Título em **A1** com fonte maior

---

## 📌 Tarefa para Casa

> Criar uma planilha chamada `Planejamento da Semana`.  
> Deve conter:
- Lista de tarefas diárias
- Data de entrega
- Caixa de seleção
- Formatação condicional para destacar tarefas concluídas

---

## 🪄 Próxima Aula

Na **Aula 05**, vamos aprender a **usar fórmulas como SOMA e MÉDIA para fazer cálculos automáticos**! 🧮