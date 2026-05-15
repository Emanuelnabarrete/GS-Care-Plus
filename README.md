# Ward – Monitoramento de Saúde para Home Office

## 📌 Visão Geral

O **Ward** é um software inteligente desenvolvido para monitorar indicadores de saúde ocupacional durante a rotina de trabalho em home office.

O projeto foi criado no contexto do **FIAP Challenge em parceria com a Care Plus**, com o objetivo de expandir as possibilidades da plataforma **BluaDiagnostics**, tornando o cuidado remoto mais completo por meio de **monitoramento contínuo, análise comportamental e recomendações personalizadas de bem-estar**.

Utilizando a câmera do computador como principal sensor, o Ward coleta dados em tempo real sobre o usuário durante o expediente e os transforma em **informações estruturadas**, que são analisadas por um módulo de IA capaz de gerar um **indicador de bem-estar** e orientações práticas de saúde ocupacional.

---

## 🚨 Problema

Com o crescimento do **trabalho remoto**, muitos profissionais passaram a enfrentar problemas relacionados à saúde durante a rotina de trabalho, como:

- Fadiga ocular por tempo excessivo de tela
- Má postura e dores musculares
- Dores de cabeça e enxaquecas
- Cansaço físico e mental acumulado

Grande parte desses problemas ocorre porque **não há monitoramento contínuo da saúde durante o trabalho**, fazendo com que sinais de desgaste físico e emocional passem despercebidos — até que se tornem um problema real.

---

## 💡 Oportunidade

Plataformas de saúde digital como o **Blua** buscam ampliar o cuidado remoto além das teleconsultas. Existe uma oportunidade concreta de desenvolver **ferramentas que permitam o monitoramento passivo e contínuo de sinais de saúde**, possibilitando:

- Prevenção de problemas físicos e mentais
- Identificação precoce de fadiga e estresse
- Geração de dados confiáveis para acompanhamento médico
- Integração com plataformas de saúde digital

---

## 🧠 Solução – Ward

O **Ward** funciona em segundo plano durante a jornada de trabalho, utilizando a câmera do computador para coletar dados de forma passiva e não invasiva.

O sistema monitora três aspectos principais do usuário em tempo real:

| Indicador | O que é monitorado |
|---|---|
| 👁️ **Fadiga ocular** | Frequência e padrão de piscadas ao longo do tempo |
| 🪑 **Postura corporal** | Identificação de posições inadequadas, como curvatura excessiva |
| 🙂 **Estado emocional** | Reconhecimento de expressões faciais para inferir o humor e o nível de estresse |

Ao final da sessão, todos os dados coletados são **computados e tabelados**, e enviados para um módulo de Inteligência Artificial. Esse módulo interpreta o estado geral do usuário, gera um **indicador de bem-estar** e emite **dicas e sugestões personalizadas de saúde ocupacional**, orientando o usuário a melhorar seus hábitos com base no que foi identificado durante o monitoramento.

---

## 🔗 Integração com Blua

O Ward atua como uma **camada de coleta e estruturação de dados de saúde** para a plataforma **BluaDiagnostics**.

Os dados gerados podem:

- Alimentar os modelos de IA da Blua para análises mais profundas
- Apoiar check-ups digitais com dados comportamentais reais
- Fornecer histórico concreto para consultas médicas
- Permitir que o usuário acompanhe sua evolução de bem-estar ao longo do tempo

---

## ⚙️ Tecnologias Utilizadas

| Tecnologia | Função no projeto |
|---|---|
| **Python** | Linguagem principal do sistema |
| **OpenCV** | Captura e processamento de imagem via câmera |
| **MediaPipe** | Detecção de postura corporal e landmarks faciais |
| **Visão Computacional** | Análise de piscadas, postura e expressões faciais |
| **Inteligência Artificial** | Interpretação dos dados e geração de recomendações |

---

## 🎯 Impacto Esperado

O Ward transforma o cuidado com a saúde em algo **automático, contínuo e integrado ao dia de trabalho**, permitindo que usuários:

- Monitorem sua saúde sem interromper a rotina
- Identifiquem sinais de fadiga e estresse de forma precoce
- Melhorem postura e hábitos com base em dados reais
- Tenham informações concretas para consultas e acompanhamento médico

---

## 👨‍💻 Contexto do Projeto

Projeto desenvolvido para o **FIAP Challenge – Ciência da Computação**, com foco em criar soluções que ampliem as capacidades da plataforma **BluaDiagnostics**, tornando o cuidado remoto mais completo, preventivo e inteligente.

---

## 👥 Integrantes

- Eduardo Luiz
- Emanuel Nabarrete
- Lucas Mota
- Luiz Eduardo
- Miguel Bezerra
