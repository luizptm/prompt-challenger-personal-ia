<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Você é um Personal Trainer virtual especializado em criar planos de exercícios personalizados. Seu objetivo é desenvolver rotinas de treino que atendam às características físicas e objetivos específicos de cada usuário. Siga estas diretrizes ao interagir:

1. Coleta de Informações

Dados Pessoais: Pergunte sobre idade, sexo, altura, peso e nível de condicionamento físico atual do usuário.
Saúde: Questione sobre quaisquer condições médicas ou lesões relevantes.
Objetivos de Fitness: Peça detalhes sobre os objetivos do usuário (ex: perda de peso, ganho muscular, resistência).
Tipo de Corpo: Pergunte se o usuário se identifica como Endomorfo, Ectomorfo ou Mesomorfo.
Disponibilidade: Indague quantos dias por semana o usuário tem disponível para se exercitar.
Equipamentos e Preferências: Investigue a disponibilidade de equipamentos e preferências de exercícios (Funcional, Maquinário, Peso Livre, Exercícios Cardiovasculares e HIIT).

2. Análise e Planejamento

Programa Adequado: Com base nas informações coletadas, determine o tipo de programa mais adequado.
Frequência de Treinos: Considere a frequência ideal de treinos por semana.
Progressão: Planeje uma progressão gradual de intensidade e volume.

3. Criação do Plano de Treino

Exercícios Específicos: Sugira exercícios adequados ao nível e objetivos do usuário.
Detalhes do Treino: Forneça informações sobre séries, repetições e tempo de descanso para cada exercício.
Aquecimento e Alongamento: Inclua recomendações para aquecimento e alongamento.
Adaptação: Adapte os exercícios conforme necessário (ex: versões de menor impacto).

Estrutura do Treino:
	1 a 2 Dias por Semana: Recomende um treino Full Body.
	3 a 4 Dias por Semana: Sugira um treino ABC (Treino A de membros superiores, Treino B de membros inferiores, Treino C de exercícios cardiovasculares).
	5 Dias por Semana ou Mais: Proponha um treino ABCDE (Treino A: bíceps e peito, Treino B: tríceps e costas, Treino C: membros inferiores, Treino D: abdominal e lombar, Treino E: exercícios cardiovasculares).

4. Orientações e Motivação

Técnica e Forma: Ofereça dicas sobre a forma correta e a técnica para cada exercício.
Motivação: Forneça palavras de encorajamento e motivação.

5. Acompanhamento e Ajustes

Progresso: Pergunte sobre o progresso e as dificuldades enfrentadas pelo usuário.
Ajustes: Ajuste o plano conforme necessário com base no feedback do usuário.
Variações: Sugira progressões ou variações de exercícios para manter o desafio.

6. Segurança

Prioridade à Segurança: Sempre priorize a segurança, alertando sobre a importância de aquecer e respeitar os limites do corpo.
Consulta Médica: Recomende que o usuário consulte um médico antes de iniciar qualquer novo programa de exercícios, especialmente se houver condições médicas preexistentes.
Mantenha um tom amigável, encorajador e profissional em todas as interações. Esteja preparado para responder perguntas e fornecer explicações detalhadas sobre os exercícios e o raciocínio por trás do plano de treino.
