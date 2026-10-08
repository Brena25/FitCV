# 🚀 FitCV - ATS Resume Optimizer

![Status](https://img.shields.io/badge/status-concluído-success)

## 📖 Sobre o Projeto

O **FitCV** é uma aplicação web desenvolvida para ajudar candidatos a aumentarem suas chances de aprovação em processos seletivos utilizando uma análise baseada em **ATS (Applicant Tracking System)**.

O ATS é um sistema utilizado por empresas para filtrar e classificar currículos antes mesmo que eles sejam analisados por recrutadores.

A aplicação compara um currículo com uma descrição de vaga, identifica compatibilidade, analisa palavras-chave relevantes e gera uma versão ATS Friendly do currículo, sem alterar a veracidade das informações do candidato.

---

## 🎯 Problema Resolvido

Muitos profissionais são eliminados ainda na etapa automática dos processos seletivos porque seus currículos não estão otimizados para sistemas ATS.

Os principais problemas encontrados são:

- Ausência de palavras-chave importantes;
- Estrutura inadequada para leitura automatizada;
- Resumos profissionais pouco objetivos;
- Competências mal destacadas;
- Baixa aderência às exigências da vaga.

O FitCV ajuda a identificar esses pontos e melhorar a apresentação do currículo de forma ética e transparente.

---

## ✅ Regra Principal

> O FitCV nunca inventa experiências profissionais, certificações, cursos, idiomas ou competências que não existem no currículo original.

A ferramenta apenas:

- Reorganiza informações;
- Melhora a clareza dos textos;
- Destaca competências existentes;
- Otimiza a leitura para ATS;
- Sugere melhorias baseadas na vaga.

---

## ✨ Funcionalidades

### 📄 Análise ATS

O usuário informa:

- Descrição da vaga;
- Currículo atual.

A aplicação realiza uma análise automática e apresenta:

- Score ATS;
- Compatibilidade da vaga;
- Palavras-chave encontradas;
- Palavras-chave ausentes;
- Recomendações de melhoria.

---

### 🤖 Currículo ATS Friendly

Após a análise, o sistema gera uma versão otimizada do currículo organizada para aumentar a aderência aos sistemas de recrutamento.

---

### 📊 Dashboard

Acompanhamento de métricas e evolução das análises realizadas.

---

### 📁 Histórico

Registro de análises anteriores para consulta futura.

---

### 📤 Exportação

Exportação do currículo otimizado em:

- DOCX

---

## 🧠 Como Funciona

### 1. O usuário cola a descrição da vaga

Exemplo:

```text
Desenvolvedor React com experiência em TypeScript, Scrum e AWS.
```

### 2. O usuário cola seu currículo

O currículo é enviado para análise.

### 3. Extração de palavras-chave

A IA identifica informações importantes presentes na vaga.

Exemplos:

- React
- TypeScript
- Scrum
- AWS
- Docker

### 4. Comparação com o currículo

As informações da vaga são comparadas com as informações presentes no currículo.

### 5. Cálculo do Match ATS

A compatibilidade é calculada e apresentada em percentual.


### 6. Identificação de Keywords

A aplicação exibe:

#### ✅ Encontradas

- React
- TypeScript
- Scrum

#### ⚠️ Ausentes

- AWS
- Docker
- Kubernetes

### 7. Geração do currículo otimizado

A aplicação cria uma nova versão ATS Friendly utilizando apenas informações existentes no currículo original.

---

## 🎨 Design System

O projeto foi construído utilizando o design system do **shadcn/ui**.

### Referências Visuais

- Stripe
- Linear
- Notion
- Vercel

### Paleta de Cores

| Cor | Hex |
|------|------|
| Roxo Principal | #8B5CF6 |
| Amarelo Claro | #FDE68A |
| Branco | #FFFFFF |
| Surface | #F8FAFC |
| Texto Principal | #111827 |
| Sucesso | #10B981 |
| Alerta | #F59E0B |
| Erro | #EF4444 |

### Componentes

- Button
- Card
- Badge
- Dialog
- Progress
- Accordion
- Tooltip
- Table
- Toast

---

## 🛠️ Tecnologias Utilizadas

### Frontend

- React
- TypeScript
- Tailwind CSS
- Shadcn/UI

### Backend

- Supabase

### Inteligência Artificial

- OpenAI

### UX/UI

- Framer Motion
- Lucide Icons

### Plataforma Low-Code

- Lovable

---

# 🤖 Engenharia de Prompt

O desenvolvimento foi realizado utilizando IA Generativa através do Lovable.

O projeto passou por duas fases principais.

---

## 1️⃣ Mega Prompt Inicial

O primeiro passo foi criar um mega prompt descrevendo toda a aplicação.
# FITCV – ATS FRIENDLY RESUME OPTIMIZER

## CONTEXTO

Crie uma aplicação SaaS moderna chamada **FitCV**, desenvolvida no Lovable utilizando React, TypeScript, TailwindCSS, Shadcn/UI, Supabase e OpenAI.

O FitCV é um gerador inteligente de currículos ATS Friendly capaz de comparar uma descrição de vaga com um currículo fornecido pelo usuário, calcular compatibilidade ATS, identificar palavras-chave relevantes, sugerir melhorias e gerar uma nova versão do currículo otimizada para sistemas de recrutamento.

O objetivo é aumentar as chances do candidato passar pelos filtros ATS antes que o currículo seja visualizado pelo recrutador.

A experiência deve parecer um produto premium, comparável a Stripe, Linear, Notion, Ramp e Vercel.

---

# REGRA DE NEGÓCIO MAIS IMPORTANTE

A inteligência artificial nunca pode inventar informações.

PROIBIDO:

- Inventar experiências profissionais.
- Inventar empresas.
- Inventar certificações.
- Inventar cursos.
- Inventar idiomas.
- Inventar tecnologias.
- Inventar formações acadêmicas.

PERMITIDO:

- Reescrever conteúdos.
- Melhorar clareza.
- Melhorar estrutura.
- Reorganizar informações.
- Destacar competências existentes.
- Otimizar palavras-chave já presentes.

Sempre preserve a veracidade do currículo.

Caso uma palavra-chave da vaga não esteja presente no currículo, ela deve aparecer como recomendação, nunca ser adicionada automaticamente.

---

# OBJETIVO DO PRODUTO

Permitir que qualquer profissional:

1. Cole uma vaga.
2. Cole seu currículo.
3. Analise a compatibilidade ATS.
4. Descubra palavras-chave encontradas.
5. Descubra palavras-chave ausentes.
6. Receba sugestões de melhoria.
7. Gere um currículo ATS Friendly.
8. Exporte em PDF.
9. Exporte em DOCX.
10. Salve análises para comparação futura.

---

# EXPERIÊNCIA DE USUÁRIO

A experiência deve ser extremamente simples.

Fluxo ideal:

- Menos de 3 minutos para concluir uma análise.
- Interface intuitiva.
- Não exigir conhecimento técnico.
- Mobile First.
- Alta velocidade.
- Feedback visual durante processamento.
- Visual profissional e moderno.

---

# DESIGN SYSTEM

## REFERÊNCIAS VISUAIS

Inspirar-se em:

- Stripe
- Linear
- Notion
- Vercel
- Arc Browser
- Brex
- Ramp

Evitar aparência de:

- Bootstrap genérico.
- Templates antigos.
- Dashboards poluídos.
- Interfaces excessivamente corporativas.

---

# IDENTIDADE DA MARCA

Nome:

FitCV

Slogan:

Seu currículo pronto para passar pelos filtros ATS.

Personalidade:

- Inteligente
- Moderna
- Profissional
- Confiável
- Objetiva

---

# PALETA DE CORES

## Primary

```css
#8B5CF6
```

## Primary Hover

```css
#7C3AED
```

## Primary Light

```css
#EDE9FE
```

## Secondary

```css
#FDE68A
```

## Secondary Hover

```css
#FCD34D
```

## Background

```css
#FFFFFF
```

## Surface

```css
#F8FAFC
```

## Border

```css
#E5E7EB
```

## Text Primary

```css
#111827
```

## Text Secondary

```css
#6B7280
```

## Success

```css
#10B981
```

## Warning

```css
#F59E0B
```

## Error

```css
#EF4444
```

Todos os contrastes devem seguir WCAG AA.

---

# TIPOGRAFIA

Fonte principal:

```text
Inter
```

## H1

```css
56px
font-weight: 800
```

## H2

```css
40px
font-weight: 700
```

## H3

```css
28px
font-weight: 600
```

## H4

```css
20px
font-weight: 600
```

## Body

```css
16px
font-weight: 400
```

## Small

```css
14px
font-weight: 400
```

---

# ESPAÇAMENTO

Utilizar escala consistente:

```text
4px
8px
12px
16px
24px
32px
48px
64px
96px
```

---

# BORDAS

Botões:

```css
rounded-xl
```

Inputs:

```css
rounded-xl
```

Cards:

```css
rounded-3xl
```

Modais:

```css
rounded-3xl
```

---

# SOMBRAS

Cards:

```css
shadow-sm
```

Hover:

```css
shadow-md
```

Modal:

```css
shadow-xl
```

---

# ANIMAÇÕES

Usar Framer Motion.

Hover de botão:

```css
scale(1.03)
```

Hover de card:

```css
translateY(-3px)
```

Duração:

```css
200ms
ease-out
```

---

# SHADCN/UI

Utilizar:

- Button
- Card
- Badge
- Tabs
- Dialog
- Sheet
- Progress
- Skeleton
- Tooltip
- Table
- Dropdown Menu
- Alert
- Toast
- Separator
- Accordion
- Avatar

---

# ÍCONES

Lucide React.

Utilizar principalmente:

- Sparkles
- Search
- FileText
- User
- Download
- Brain
- Target
- CheckCircle
- AlertTriangle
- TrendingUp
- BarChart3
- Briefcase

---

# TELA 1 – LANDING PAGE

## HERO

Layout dividido em duas colunas.

### Lado Esquerdo

Título:

# Seu currículo pronto para passar pelos filtros ATS

Subtítulo:

Compare seu currículo com qualquer vaga e receba uma versão otimizada em segundos.

CTA Primário:

Analisar Meu Currículo

CTA Secundário:

Ver Demonstração

---

### Lado Direito

Mockup interativo.

Mostrar:

```text
Match ATS: 92%
```

Badges:

✅ React

✅ TypeScript

✅ Scrum

⚠ AWS

⚠ Docker

⚠ Kubernetes

Botão:

Gerar Currículo ATS

---

# SEÇÃO COMO FUNCIONA

3 cards horizontais.

---

### Passo 1

Cole a vaga.

---

### Passo 2

Cole seu currículo.

---

### Passo 3

Receba uma versão ATS Friendly.

---

# BENEFÍCIOS

Grid de 6 cards.

---

### Compatibilidade ATS

Aumente sua taxa de aprovação.

---

### Identificação de Keywords

Descubra o que falta.

---

### Currículo Otimizado

Pronto para envio.

---

### Exportação PDF

Formato profissional.

---

### Histórico

Salve suas análises.

---

### Dashboard

Acompanhe sua evolução.

---

# TELA 2 – ANÁLISE ATS

Layout moderno.

Desktop:

50% vaga.

50% currículo.

Mobile:

100%.

---

## CARD 1

Título:

Descrição da Vaga

Campo:

Textarea grande.

Placeholder:

Cole aqui a descrição completa da vaga.

---

## CARD 2

Título:

Seu Currículo

Campo:

Textarea grande.

Placeholder:

Cole aqui seu currículo.

---

## BOTÃO PRINCIPAL

Texto:

Analisar Compatibilidade

Ícone:

Sparkles

---

# PROCESSAMENTO

Ao clicar em analisar:

Mostrar loading elegante.

Mensagem:

```text
Analisando vaga...
Extraindo palavras-chave...
Comparando currículo...
Calculando compatibilidade ATS...
Gerando currículo otimizado...
```

---

# FLUXO DA IA

Etapa 1:

Extrair palavras-chave da vaga.

Categorias:

- Hard Skills
- Soft Skills
- Ferramentas
- Linguagens
- Certificações
- Idiomas

---

Etapa 2:

Extrair palavras-chave do currículo.

---

Etapa 3:

Comparar os conjuntos.

---

Etapa 4:

Calcular Score ATS.

Fórmula:

```text
(palavras encontradas ÷ palavras totais) × 100
```

---

Etapa 5:

Gerar recomendações.

---

Etapa 6:

Gerar currículo ATS Friendly.

---

# TELA 3 – RESULTADO

## HEADER

Título:

Resultado da Análise

Subtítulo:

Veja sua aderência à vaga e melhore seu currículo.

---

# SCORE ATS

Componente visual:

Gauge Chart.

Valor:

0 a 100.

---

## CORES

90-100

Verde.

---

70-89

Amarelo.

---

0-69

Vermelho.

---

# KPI CARDS

## Score ATS

Exemplo:

87%

---

## Keywords Encontradas

Quantidade.

---

## Keywords Ausentes

Quantidade.

---

## Potencial de Compatibilidade

Estimativa baseada na análise.

---

# KEYWORDS ENCONTRADAS

Exibir badges verdes.

Exemplo:

- React
- TypeScript
- Agile
- Scrum
- Next.js

---

# KEYWORDS AUSENTES

Exibir badges amarelas.

Exemplo:

- AWS
- Docker
- Kubernetes

---

# KEYWORDS CRÍTICAS

Exibir badges vermelhas.

São palavras altamente relevantes para a vaga.

---

# RECOMENDAÇÕES

Exemplos:

- Reforçar experiência com React.
- Melhorar resumo profissional.
- Destacar tecnologias principais.
- Reorganizar competências técnicas.
- Utilizar palavras-chave já presentes em posições estratégicas.

---

# CURRÍCULO ATS FRIENDLY

Exibir versão completa.

Formato:

## Resumo Profissional

---

## Competências Técnicas

---

## Experiência Profissional

---

## Formação Acadêmica

---

## Cursos

---

## Certificações

---

# EXPORTAÇÃO

Botão:

Exportar

Opções:

## PDF

Currículo profissional ATS.

---

## DOCX

Documento editável.

---

# AUTENTICAÇÃO

Supabase Auth.

Métodos:

- Email e senha
- Magic Link

---

# CONFIRMAÇÃO DE EMAIL

Utilizar Resend.

Fluxo:

- Cadastro
- Email automático
- Confirmação
- Login

---

# HISTÓRICO

Criar página de histórico.

Mostrar:

- Data
- Cargo
- Score
- Palavras-chave
- Exportações

Ações:

- Abrir
- Exportar novamente
- Comparar

---

# DASHBOARD

KPIs:

- Total de análises
- Melhor score
- Média geral
- Último score

---

# GRÁFICOS

Usar Recharts.

---

## Evolução ATS

Gráfico de linha.

---

## Histórico Mensal

Gráfico de barras.

---

## Distribuição de Scores

Gráfico de pizza.

---

# BANCO DE DADOS

## users

```sql
id
name
email
avatar_url
created_at
```

---

## analyses

```sql
id
user_id
job_title
job_description
resume_original
resume_optimized
score
keywords_found
keywords_missing
created_at
```

---

## exports

```sql
id
analysis_id
format
created_at
```

---

# PROMPT INTERNO DA IA

Você é um especialista em ATS, recrutamento e otimização de currículos.

Objetivo:

Comparar um currículo com uma vaga.

Regras obrigatórias:

- Nunca invente informações.
- Nunca invente experiências.
- Nunca invente certificações.
- Nunca invente formações.
- Nunca invente idiomas.
- Nunca invente competências.
- Utilize somente os dados presentes no currículo.
- Maximize a compatibilidade ATS.
- Preserve completamente a veracidade profissional.

Retorne obrigatoriamente:

1. Score ATS.
2. Resumo da análise.
3. Palavras-chave encontradas.
4. Palavras-chave ausentes.
5. Palavras-chave críticas.
6. Recomendações.
7. Currículo ATS Friendly completo.

---

# SEO

Criar páginas automaticamente:

- O que é ATS
- Como ATS funciona
- Como aumentar score ATS
- Como melhorar currículo ATS
- ATS para tecnologia
- ATS para marketing
- ATS para vendas
- ATS para estágio
- ATS para primeiro emprego

---

# GEO (GENERATIVE ENGINE OPTIMIZATION)

Preparar a aplicação para mecanismos de IA.

Implementar:

- Schema FAQ
- Schema Article
- Schema SoftwareApplication
- Open Graph
- Twitter Cards
- JSON-LD

---

# RESPONSIVIDADE

Desenvolver Mobile First.

Breakpoints:

- Mobile
- Tablet
- Desktop
- Large Desktop

Toda funcionalidade deve funcionar perfeitamente em qualquer dispositivo.

---

# OBJETIVO FINAL

Construir um SaaS premium chamado FitCV que permita a qualquer profissional analisar currículos, calcular compatibilidade ATS, identificar palavras-chave relevantes, gerar versões ATS Friendly, exportar documentos profissionais, acompanhar sua evolução através de dashboards e maximizar suas chances de aprovação em processos seletivos, sempre preservando a veracidade das informações do candidato.

O prompt definiu:

- Objetivo do produto;
- Regras de negócio;
- Fluxo ATS;
- Telas;
- Dashboard;
- Histórico;
- Exportação;
- Prompt interno da IA;
- Design System;
- Paleta visual.

### Objetivo

Gerar uma primeira versão funcional do FitCV.

---

## 2️⃣ Refino e Melhorias

Após a primeira geração foram realizados refinamentos para melhorar a experiência.

# REFATORAÇÃO PREMIUM DO FITCV

Mantenha toda a lógica atual do FitCV funcionando exatamente como está.

NÃO altere:

- Fluxo principal
- Regras ATS
- Sistema de análise
- Score ATS
- Keywords encontradas
- Keywords ausentes
- Currículo otimizado
- Sistema de autenticação
- Dashboard
- Histórico
- Exportação

O objetivo desta refatoração é elevar a percepção visual do produto para um nível profissional de SaaS moderno.

Inspirar-se fortemente em:

- Linear
- Stripe
- Vercel
- Ramp
- Notion
- Arc Browser

---

# OBJETIVO

Transformar o FitCV de um MVP funcional em um produto premium com aparência de startup de tecnologia pronta para o mercado.

Foco em:

- UX
- UI
- Conversão
- Hierarquia visual
- Credibilidade
- Design SaaS moderno

---

# HERO SECTION

Refatore completamente o Hero.

Manter a proposta atual:

"Seu currículo pronto para passar pelos filtros ATS"

Mas elevar a experiência visual.

## Melhorias

Adicionar:

- Gradientes suaves
- Mais profundidade
- Mais espaçamento
- Melhor hierarquia visual
- Layout mais sofisticado

---

## CARD ATS

Transformar o card atual em um preview premium.

Adicionar:

- Gauge ATS circular
- Indicador visual do score
- Lista expandida de keywords
- Estatísticas visuais
- Microanimações
- Sombras modernas
- Glassmorphism leve

Exemplo de informações:

- Match ATS
- Keywords encontradas
- Keywords ausentes
- Compatibilidade estimada
- Currículo otimizado

Deve parecer uma dashboard real do produto.

---

# MICRO ANIMAÇÕES

Adicionar Framer Motion.

Aplicar em:

- Botões
- Cards
- Hover states
- Navegação
- Dashboard
- Indicadores ATS

Efeitos sutis.

Sem exageros.

Sensação premium.

---

# HIERARQUIA VISUAL

Melhorar:

- Espaçamentos
- Margens
- Agrupamento de informações
- Contraste dos títulos
- Peso visual dos CTAs

Toda seção deve ter respiração visual maior.

---

# BENEFÍCIOS

Transformar os cards atuais em componentes mais sofisticados.

Adicionar:

- Ícones maiores
- Hover elegante
- Pequenas animações
- Melhor alinhamento

Cada card deve parecer um recurso valioso do produto.

---

# SOCIAL PROOF

Adicionar uma seção antes do CTA principal.

Exemplos:

### Estatísticas

+1.000 análises realizadas

+500 currículos otimizados

Score ATS médio aumentado após a otimização

---

### Benefícios rápidos

- Menos rejeições automáticas
- Melhor alinhamento com vagas
- Currículos mais compatíveis com ATS
- Processo mais rápido e eficiente

A seção deve aumentar confiança.

---

# SEÇÃO "O QUE É ATS"

Criar uma nova seção rica em conteúdo.

Perguntas:

### O que é ATS?

Explicação simples.

---

### Como ATS funciona?

Explicação do processo de triagem.

---

### Por que currículos são rejeitados?

Explicar falta de palavras-chave.

---

### Como melhorar seu score ATS?

Explicar como o FitCV ajuda.

Utilizar Accordion do shadcn/ui.

---

# DASHBOARD

Melhorar visualmente o dashboard existente.

Adicionar:

- KPI Cards mais modernos
- Melhor organização
- Gráficos com visual SaaS
- Estados vazios elegantes
- Melhor responsividade

Inspirar-se em:

- Stripe Dashboard
- Linear Analytics
- Ramp

---

# TELA DE RESULTADOS

Transformar na melhor tela do produto.

---

## Score ATS

Criar um componente visual impressionante.

Adicionar:

- Gauge Chart
- Cor dinâmica
- Feedback visual

Faixas:

- Vermelho
- Amarelo
- Verde

---

## Keywords

Separar visualmente:

### Encontradas

Badges verdes.

### Ausentes

Badges amarelas.

### Críticas

Badges vermelhas.

Criar melhor organização visual.

---

## Recomendações

Transformar em cards interativos.

Cada recomendação deve ser fácil de compreender.

---

# CURRÍCULO GERADO

Melhorar muito a apresentação.

O currículo otimizado deve parecer:

- Profissional
- Organizado
- Pronto para exportação

Simular aparência de documento A4.

---

# LOADING STATES

Adicionar estados de carregamento premium.

Durante análise mostrar etapas:

- Extraindo palavras-chave
- Comparando currículo
- Calculando score ATS
- Gerando recomendações
- Criando versão ATS

Utilizar:

- Skeletons
- Progress indicators
- Animações suaves

---

# EMPTY STATES

Adicionar telas vazias elegantes em:

- Histórico
- Dashboard
- Exportações

Mostrar orientações claras do próximo passo.

---

# RESPONSIVIDADE

Melhorar experiência:

- Mobile
- Tablet
- Desktop

Todo o produto deve parecer nativo em qualquer tamanho de tela.

---

# ACESSIBILIDADE

Garantir:

- Contraste AA
- Navegação por teclado
- Estados de foco
- Legibilidade

---

# DESIGN SYSTEM

Continuar utilizando:

- Shadcn/UI
- TailwindCSS
- Lucide Icons

Paleta atual:

Primary:
#8B5CF6

Secondary:
#FDE68A

Background:
#FFFFFF

Surface:
#F8FAFC

Success:
#10B981

Warning:
#F59E0B

Error:
#EF4444

---

# SENSAÇÃO FINAL

O FitCV deve parecer um produto SaaS premium de inteligência artificial focado em carreira e recrutamento.

Quando alguém acessar o site deve ter a sensação de estar utilizando uma ferramenta comparável visualmente a produtos como Linear, Stripe, Ramp ou Vercel.

Priorize:

- Elegância
- Simplicidade
- Clareza
- Profissionalismo
- Conversão
- Credibilidade

Não altere regras de negócio nem funcionalidades existentes.

Refatore exclusivamente UX, UI, Design System, visualização de dados e experiência do usuário.
``
### Melhorias Solicitadas

- Hero mais moderno;
- Melhor hierarquia visual;
- Dashboard mais profissional;
- Cards refinados;
- Melhor uso do espaço;
- Seção explicando ATS;
- Social Proof;
- Microanimações;
- Melhor responsividade;
- Aparência inspirada em Stripe, Linear e Vercel.

### Resultado

Transformação de um MVP funcional em uma experiência próxima de um produto SaaS real.

---

## 📷 Evidências

### Landing Page
<img width="1205" height="454" alt="image" src="https://github.com/user-attachments/assets/bfe5f1f5-8e07-43ad-a6a1-0cd4eea25206" />
<img width="1185" height="341" alt="image" src="https://github.com/user-attachments/assets/6e018314-0bce-4508-9b48-51c1287899a7" />
<img width="1193" height="390" alt="image" src="https://github.com/user-attachments/assets/ef5ccfef-e97a-4b48-9d1b-80fb73295e6f" />
<img width="852" height="406" alt="image" src="https://github.com/user-attachments/assets/5c79d9dd-306e-4e2a-bb05-c0f0d152d6e3" />
<img width="1178" height="319" alt="image" src="https://github.com/user-attachments/assets/f8ecbd59-d77a-415f-8ee5-ac419270d21c" />


### Tela de Análise

<img width="1206" height="301" alt="image" src="https://github.com/user-attachments/assets/4504fecc-aa7c-4883-b1dc-af4e1e15bd1e" />


### Resultado da Análise

<img width="972" height="425" alt="image" src="https://github.com/user-attachments/assets/ecc3f16f-ea93-49b7-afe0-c710d8b92c2b" />
<img width="1010" height="409" alt="image" src="https://github.com/user-attachments/assets/21e482b4-b33f-406a-b549-04718194828a" />
<img width="542" height="470" alt="image" src="https://github.com/user-attachments/assets/3ef466c3-65ae-4457-b826-1a580b6fd335" />
<img width="971" height="334" alt="image" src="https://github.com/user-attachments/assets/6b24b3f7-83a1-4161-a62d-c3e4bdc835a7" />
<img width="965" height="340" alt="image" src="https://github.com/user-attachments/assets/360ba1d8-85d2-4e78-bef5-225f7dab962c" />
<img width="304" height="417" alt="image" src="https://github.com/user-attachments/assets/2f02700b-d6e3-4762-9610-284b86aa1eec" />


---

## 🌍 Aplicação Publicada

**Acesse aqui:**

https://jobfit-whisperer.lovable.app

---

## 💻 Repositório

**GitHub:**

https://github.com/Brena25/FitCV/edit/main/Readme.md

---

## 🚀 Próximas Evoluções

Funcionalidades planejadas para futuras versões:

- Aprimoramento da exportação DOCX;
- Histórico avançado;
- Login com Supabase Auth;
- Confirmação de e-mail com Resend;
- Dashboard analítico completo;
- Especialização por nicho;
- SEO;
- GEO (Generative Engine Optimization);
- Plano Gratuito e Plano Pro.

---

## 👨‍💻 Autor

Projeto desenvolvido como parte de estudos e portfólio para demonstrar conhecimentos em:

- Inteligência Artificial
- Engenharia de Prompt
- Desenvolvimento Front-End
- UX/UI
- Aplicações SaaS
- React
- TypeScript
- Lovable

---

## ✅ Conclusão

O FitCV demonstra como ferramentas de IA e desenvolvimento acelerado podem ser utilizadas para resolver um problema real enfrentado diariamente por profissionais em busca de oportunidades.

Mais do que o resultado final, o projeto evidencia todo o processo de construção: concepção da ideia, criação do mega prompt, geração automática da primeira versão, refinamentos sucessivos e publicação do produto.

Um exemplo prático de como transformar uma necessidade do mercado em uma solução funcional utilizando IA, design e desenvolvimento moderno.

