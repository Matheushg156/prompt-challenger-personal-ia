# 🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal

Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que auxilia na geração de um treino personalizado com base nas características e preferências do usuário, como biotipo corporal, dias disponíveis para treino e tipos de exercícios preferidos. Utilizando boas práticas de engenharia de prompts, este assistente é capaz de responder de forma personalizada e eficiente, fornecendo um plano de treino ideal para cada perfil.

## 📋 Índice
- [Introdução](#-introdução)
- [Biotipos Corporais](#-biotipos-corporais)
- [Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [Tipos de Exercícios](#-tipos-de-exercícios)
- [Regras de Negócio](#️-regras-de-negócio)
- [Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)
- [Exemplos de Respostas](#-exemplos-de-respostas)

---

## 📝 Introdução

Este projeto visa criar um assistente virtual de personal trainer automatizado que auxilia na geração de treinos personalizados. O usuário fornecerá informações específicas, e o assistente gerará um plano de treino com base nessas informações, respeitando as boas práticas de clareza, especificidade, contextualização e iteração da engenharia de prompts.

## 💪 Biotipos Corporais

A primeira variável para personalizar o treino é o biotipo corporal do usuário. Os principais biotipos incluem:

| Biotipo   | Descrição                                                                            |
|-----------|--------------------------------------------------------------------------------------|
| Ectomorfo | Corpo mais magro, com dificuldade em ganhar peso e massa muscular.                  |
| Mesomorfo | Corpo naturalmente musculoso, com facilidade para ganhar massa muscular e perder gordura. |
| Endomorfo | Corpo com tendência a acumular gordura, com maior dificuldade em perder peso.       |

*Nota:* Escolha o biotipo que mais se aproxima do seu corpo atual para garantir um treino mais eficiente.

## 📅 Dias Disponíveis para Treino

A segunda variável é a quantidade de dias por semana que o usuário pode dedicar aos treinos. Dependendo do número de dias, o treino sugerido varia:

| Dias por Semana | Tipo de Treino Sugerido    | Descrição                                                 |
|-----------------|----------------------------|-----------------------------------------------------------|
| 1 dia           | Full Body                  | Treino que trabalha o corpo todo em uma única sessão.     |
| 3 dias          | ABC                        | Divisão do treino em três dias com foco em grupos musculares diferentes. |
| 5 dias          | ABCDE                      | Divisão do treino em cinco dias com foco específico em cada grupo muscular. |

## 🏋️ Tipos de Exercícios

A terceira variável é o tipo de exercício preferido pelo usuário. As opções incluem:

| Tipo de Treino | Descrição                                                                 |
|----------------|---------------------------------------------------------------------------|
| Funcional      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais. |
| Maquinário     | Exercícios em máquinas, com foco em isolar grupos musculares específicos. |
| Peso Livre     | Exercícios com halteres e barras, que trabalham vários grupos musculares simultaneamente. |
| Cardio         | Exercícios para melhorar a resistência cardiovascular, como corrida ou ciclismo. |
| HIIT           | Treinos intervalados de alta intensidade, ideais para queima de gordura. |

## 🛠️ Regras de Negócio

- Identifique o biotipo corporal consultando a seção de biotipos.
- Determine quantos dias por semana você pode treinar e escolha o tipo de treino mais adequado.
- Selecione o tipo de exercício que melhor se encaixa nos seus objetivos.
- Utilize o prompt do assistente para gerar um plano de treino personalizado.

## 🎯 Prompt de Resposta Proposto

```plaintext
Olá! Sou seu assistente virtual de personal trainer. Vou te ajudar a criar um treino ideal com base nas suas preferências. Para isso, preciso que você me forneça as seguintes informações:

1. **Biotipo Corporal** (Escolha um): ectomorfo, mesomorfo, endomorfo.
2. **Dias Disponíveis para Treino por Semana** (Escolha um): 1, 3, 5.
3. **Tipo de Exercício Preferido** (Escolha um): funcional, maquinário, peso livre, cardio, HIIT.

Com essas informações, eu vou gerar um plano de treino personalizado que inclui:
- A divisão ideal de treino para os dias escolhidos (Full Body, ABC, ou ABCDE).
- Exercícios focados nas suas necessidades e preferências.
- Sugestões para otimizar seu treino com base no seu biotipo corporal.

*Exemplo de Resposta Esperada*:

- **Biotipo**: Mesomorfo
- **Dias de Treino**: 3
- **Tipo de Exercício**: Peso Livre

**Plano de Treino Sugerido**:
- Dia 1: Peito e tríceps - Supino com halteres, Rosca tricep.
- Dia 2: Costas e bíceps - Remada com barra, Rosca direta com halteres.
- Dia 3: Pernas e abdômen - Agachamento livre, Prancha.
```

## 🧑‍🏫 Exemplos de Respostas

### Exemplo 1

**Entrada**:
- **Biotipo**: Ectomorfo
- **Dias de Treino**: 5
- **Tipo de Exercício**: HIIT

**Resposta do Assistente**:
- **Plano de Treino**:
  - **Dia 1**: Full Body HIIT - Circuito de burpees, agachamentos e flexões.
  - **Dia 2**: HIIT Cardio - Corrida intervalada.
  - **Dia 3**: Full Body HIIT - Circuito de abdominais, polichinelos e saltos.
  - **Dia 4**: HIIT Cardio - Ciclismo com sprints.
  - **Dia 5**: Full Body HIIT - Circuito de pranchas, lunges e mountain climbers.

### Exemplo 2

**Entrada**:
- **Biotipo**: Endomorfo
- **Dias de Treino**: 3
- **Tipo de Exercício**: Peso Livre

**Resposta do Assistente**:
- **Plano de Treino**:
  - **Dia 1**: Peito e tríceps - Supino com halteres, Tríceps francês.
  - **Dia 2**: Costas e bíceps - Remada com barra, Rosca martelo.
  - **Dia 3**: Pernas e abdômen - Agachamento com halteres, Abdominais.

### Exemplo 3

**Entrada**:
- **Biotipo**: Mesomorfo
- **Dias de Treino**: 1
- **Tipo de Exercício**: Funcional

**Resposta do Assistente**:
- **Plano de Treino**:
  - Treino Full Body Funcional - Agachamento, flexão, elevação de joelhos, prancha e salto.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais para entender melhor o projeto e as práticas de engenharia de prompts:

- [Fundamentos de Engenharia de Prompt](#)
- [Boas Práticas de Prompt](#)

---

Esperamos que este assistente virtual de personal trainer seja útil para auxiliar na criação de planos de treino personalizados, promovendo uma experiência de treino mais eficiente e adaptada a cada usuário.

Bons treinos! 💪 

---
