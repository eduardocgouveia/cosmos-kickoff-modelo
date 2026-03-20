# KICK-OFF MODELO | COSMOS by Atacama Digital

Template definitivo de apresentacao de kick-off para novos clientes da Atacama Digital, seguindo o Metodo COSMOS e o brand kit oficial.

---

## GUIA COMPLETO DE USO

Este guia cobre **todas as etapas** do processo de kick-off: desde a preparacao antes da reuniao, passando pela conducao da apresentacao, ate os entregaveis e acoes pos-reuniao. Cada passo e obrigatorio. Nao pule etapas.

---

## FASE 1: ANTES DA REUNIAO (Preparacao)

### 1.1. Receba a passagem de bastao do Comercial

Antes de qualquer acao, o Coordenador do Nucleo audita o contrato e define:

- **Tipo de Contrato e Tier** (A, B ou C)
- **Pacotes de Servico (SLA)**: Performance? Criativos? Social? Tech? Audiovisual?
- **Squad alocada**: CS, Gestor de Performance, Social Media, Coordenador

> Sem essa informacao, nao abra a apresentacao. O kick-off reflete o contrato vendido.

### 1.2. Configure o ambiente do projeto

Antes do kick-off, os Estagios 01 e 02 do Metodo COSMOS ja devem estar concluidos:

- [ ] Ambiente de gestao criado no ClickUp (projeto, listas, automacoes)
- [ ] Grupo de WhatsApp do projeto aberto com cliente + squad
- [ ] Contas de anuncio criadas (Google Ads, Meta Ads)
- [ ] GA4 e GTM configurados
- [ ] Boleto de fee enviado ao cliente
- [ ] Dominio verificado ou apontamento solicitado

### 1.3. Abra e personalize a apresentacao

Sirva os arquivos com qualquer servidor HTTP local:

```bash
# Com Python
python3 -m http.server 8080

# Com Node.js
npx serve .

# Com PHP
php -S localhost:8080
```

Abra `http://localhost:8080` no navegador (Chrome recomendado, tela cheia F11).

### 1.4. Preencha TODOS os campos editaveis

Campos editaveis possuem **underline pontilhado azul**. Clique para editar:

| Slide | Campo | O que preencher |
|-------|-------|-----------------|
| **Header** | Cliente | Nome do cliente (propaga automaticamente para toda a apresentacao) |
| **01 - Capa** | Tier | Classificacao do contrato: Tier A, B ou C |
| **01 - Capa** | Plano | Servicos contratados (ex: "Performance + Social + AV") |
| **01 - Capa** | Data | Data da reuniao de kick-off |
| **03 - Contrato** | Inclusos | Editar cada item conforme o contrato real vendido |
| **03 - Contrato** | Nao inclusos | Ajustar conforme o que NAO esta no escopo |
| **04 - Squad** | Iniciais, nomes e funcoes | Preencher com o squad real alocado para este cliente |
| **14 - Proximos Passos** | Datas | Calcular e preencher as datas de entrega reais (DNA +5d, Calendario +7d, AV +10d) |
| **14 - Proximos Passos** | Data de entrega do DNA | Data especifica em que o DNA Estrategico sera entregue |

> **IMPORTANTE**: Se um item do contrato nao foi vendido (ex: diaria AV), remova-o da lista de "Inclusos". Se um item extra foi vendido, adicione-o. A apresentacao DEVE refletir exatamente o que foi contratado.

---

## FASE 2: DURANTE A REUNIAO (Conducao)

### 2.1. Abertura e contexto (Slides 01-02) — 5 min

**Slide 01 (Capa):** Cumprimente o cliente. Informe que a reuniao sera gravada/transcrita para gerar o DNA Estrategico. Peça permissao.

**Slide 02 (Quem Somos):** Apresente a Atacama brevemente:
- 15+ anos, 250+ clientes, Top 3% Google Partner Premier
- Selos: Google, Meta, RD Station
- Marquee de logos transmite credibilidade — nao precisa comentar cada um

> Nao se estenda. O cliente ja comprou. 2-3 minutos no maximo.

### 2.2. Alinhamento de escopo (Slide 03) — 5 min

**Slide 03 (Contrato):** Leia em voz alta o que esta INCLUSO e o que NAO esta incluso.

- Isso evita ruidos futuros. Seja direto e transparente.
- Deixe claro: os itens "Nao Inclusos" sao oportunidades de crescimento futuro do projeto.
- Pergunte: "Ficou claro o escopo? Alguma duvida?"

### 2.3. Apresentacao da Squad (Slide 04) — 5 min

**Slide 04 (Squad):** Cada membro da squad se apresenta brevemente:
- CS/Gestora: "Eu sou seu ponto focal. Tudo passa por mim."
- Coordenadora: "Estou no grupo para garantir que tudo flua."
- Social Media: "Cuido do conteudo e da producao criativa."
- CEO/Estrategista: "Entro nas revisoes trimestrais e decisoes estrategicas."

> Deixe o CS se apresentar com mais profundidade — ele e a cara do projeto.

### 2.4. Metodo COSMOS (Slides 05-07) — 10 min

**Slide 05 (Metodo COSMOS):** Explique o metodo em visao macro:
- 6 fases em ciclos de 90 dias (FOs — Fases Operacionais)
- "O que nao e medido nao e gerenciado; o que nao e revisto nao evolui"
- Enfatize: o cliente faz parte do metodo, nao e passivo

**Slide 06 (Onboarding):** Use o carrossel para mostrar os 5 estagios:
1. Abertura & Estruturacao (24h) — ja feito
2. Setup Tecnico (48h) — ja feito ou em andamento
3. Imersao & Diagnostico (72h) — e o que estamos fazendo AGORA
4. Mapeamento de Oportunidades (96h) — resultado do briefing de hoje
5. Planejamento Tatico (7 dias) — entrega do DNA Estrategico

> Diga: "Estamos no Estagio 03 agora. Essa reuniao e o nosso mergulho no negocio de voces."

**Slide 07 (Ongoing):** Explique o ciclo continuo:
- Execucao Criativa + Monitoramento (paralelos)
- Escalonamento baseado em ROI validado
- Cosmos Review a cada 90 dias

### 2.5. Cadencia de comunicacao (Slide 08) — 3 min

**Slide 08 (Cadencia):** Explique a evolucao da cadencia:
- Semanal no inicio (onboarding)
- Quinzenal na maturidade
- Mensal no ongoing (relatorio de performance)
- Trimestral: Cosmos Review (retrospectiva + novo plano)
- WhatsApp: canal direto para o dia a dia

> Diretriz: "No comeco a gente se fala mais. Conforme o projeto ganha maturidade, a cadencia se ajusta."

### 2.6. Briefing — O CORACAO DA REUNIAO (Slides 09-11) — 25-35 min

**ESTA E A PARTE MAIS IMPORTANTE DA REUNIAO. Nao apresse.**

A reuniao deve ser GRAVADA/TRANSCRITA a partir daqui. Informe o cliente.

**Slide 09 (Briefing 1/3 — Sobre o Negocio):**

Use o botao "Proxima pergunta" (ou Space) para revelar uma pergunta de cada vez. Isso cria ritmo e evita que o cliente veja tudo de uma vez e se disperse.

As 5 perguntas sobre o negocio:
1. Conte a historia do negocio. Como tudo comecou?
2. Como era o mundo antes de voce existir?
3. Se voce desistisse amanha, o que seus clientes perderiam?
4. Qual e o diferencial competitivo?
5. Quem sao seus 3 principais concorrentes?

> **Tecnica de conducao:** Deixe o cliente falar. Nao interrompa. Faca perguntas de acompanhamento ("Me conta mais sobre isso", "Como assim?"). O objetivo e extrair o maximo de informacao possivel.

**Slide 10 (Briefing 2/3 — Sobre o Publico):**

5 perguntas sobre o publico:
6. Quem e seu cliente ideal? (ICP)
7. Qual a principal dor que faz o cliente procurar voce?
8. Qual e a objecao mais comum antes de fechar?
9. De onde vem a maioria dos clientes hoje?
10. Existe sazonalidade?

> **Tecnica de conducao:** Quando o cliente disser a objecao principal, investigue: "E como voce quebra essa objecao hoje?" Isso revela gaps que o marketing pode resolver.

**Slide 11 (Briefing 3/3 — Presenca Digital & Metas):**

5 perguntas sobre presenca digital:
11. Quais redes sociais usa? Frequencia e engajamento?
12. Ja investiu em trafego pago? Quanto? Resultados?
13. Possui site? Satisfeito com ele?
14. Tem referencia visual ou marca que admira? Tom de voz?
15. Ticket medio? Faturamento dos ultimos 12 meses? Meta?

### 2.7. Construcao de Metas — Compass (Slide 12) — 10-15 min

**Slide 12 (Metas):** Este e o momento de tangibilizar os numeros.

5 perguntas de metas:
16. Se tudo der certo em 90 dias, qual resultado voce espera?
17. Meta de vendas/faturamento para o trimestre? Distribuicao entre meses?
18. Taxa de conversao do funil hoje?
19. Evento ou data importante nos proximos 90 dias?
20. O que voce considera sucesso? Como vamos medir juntos?

> **Tecnica de conducao — O Funil Reverso:**
> 1. Pergunte a meta de faturamento trimestral
> 2. Divida pelo ticket medio = numero de vendas necessarias
> 3. Divida pela taxa de conversao = numero de leads necessarios
> 4. Distribua entre os meses (considerar sazonalidade)
> 5. Valide com o cliente: "Esse numero e ambicioso, conservador ou realista?"

> **REGRA ATACAMA:** Sem metas validadas no Compass, nenhuma campanha vai ao ar. A execucao sem meta validada fere o principio da Previsibilidade.

### 2.8. Coleta de acessos (Slide 13) — 5 min

**Slide 13 (Acessos):** Marque junto com o cliente o que ja esta disponivel:

**Acessos obrigatorios:**
- [ ] Instagram (Admin)
- [ ] Facebook / Meta Business (Admin)
- [ ] Google Ads (Administrador)
- [ ] Google Analytics / GA4
- [ ] Google Meu Negocio
- [ ] CRM utilizado
- [ ] WhatsApp comercial (numero)
- [ ] Dominio / acesso ao registro

**Materiais obrigatorios:**
- [ ] Logo em alta (PNG/SVG)
- [ ] Manual de marca
- [ ] Fotos de produto/equipe/espaco
- [ ] Depoimentos / provas sociais
- [ ] Dados de vendas/faturamento

> O que nao for coletado na hora, o CS cobra via WhatsApp nas 24h seguintes.

### 2.9. Proximos passos e encerramento (Slides 14-15) — 5 min

**Slide 14 (Proximos Passos):** Leia cada entregavel com a data preenchida:

1. **Hoje**: Kick-off concluido. Briefing coletado.
2. **+5 dias uteis**: DNA Estrategico (posicionamento, tom de voz, linhas editoriais)
3. **+7 dias uteis**: Calendario editorial do primeiro mes
4. **+10 dias uteis**: Diaria AV realizada + primeiros posts ao ar
5. **Dia 90**: Cosmos Review (retrospectiva + nova FO)

> Repita a data de entrega do DNA em destaque. E o primeiro entregavel tangivel que o cliente recebe.

**Slide 15 (Encerramento):** Finalize com:
- "O plano define o destino. A execucao dita a velocidade."
- Contatos da equipe
- Agradecimento

---

## FASE 3: APOS A REUNIAO (Entregaveis e Acoes)

### 3.1. Nas primeiras 24 horas

| Acao | Responsavel | SLA |
|------|-------------|-----|
| Enviar gravacao/transcricao para o squad | CS | 2h |
| Cobrar acessos pendentes via WhatsApp | CS | 24h |
| Criar tasks no ClickUp com base no briefing | CS + Coordenador | 24h |
| Configurar contas de anuncio com acessos recebidos | Gestor de Trafego | 24h |
| Instalar/testar pixels e tags de rastreamento | Gestor de Trafego | 24h |
| Iniciar integracao de API de conversao | Gestor de Trafego | 24h |

### 3.2. Ate 5 dias uteis — DNA Estrategico

Produzir e entregar ao cliente o **DNA Estrategico** contendo:

1. **Posicionamento**: Quem e o cliente, o que ele faz, por que ele e diferente
2. **Tom de voz**: Como a marca fala (formal/informal, tecnico/acessivel, direto/narrativo)
3. **Personas/ICP**: Perfis de publico-alvo com dores, desejos, objecoes
4. **Linhas editoriais**: Territorios de conteudo definidos (educativo, institucional, conversao, bastidores, etc.)
5. **Analise de concorrencia**: O que os concorrentes fazem bem e onde ha gaps
6. **Metas validadas no Compass**: KPIs numericos para o trimestre (FO1)

> Esse documento e construido com base na transcricao do kick-off. Por isso a gravacao e obrigatoria.

### 3.3. Ate 7 dias uteis — Calendario Editorial

Produzir o calendario editorial do primeiro mes:

- Datas de publicacao
- Temas por linha editorial
- Formatos (Reels, carrossel, estatico, stories)
- Copys aprovadas
- Briefing de criativos para o time de design

> Enviar para aprovacao do cliente via WhatsApp ou ClickUp.

### 3.4. Ate 10 dias uteis — Producao e Lancamento

- [ ] Diaria audiovisual realizada (se inclusa no contrato)
- [ ] Primeiros criativos produzidos e aprovados
- [ ] Primeiros posts publicados
- [ ] Campanhas de trafego pago configuradas e no ar
- [ ] Dashboard de acompanhamento (Compass + Atacama Performance) compartilhado com o cliente

> **REGRA:** Nenhuma campanha vai ao ar sem meta validada no Compass (definida no kick-off).

### 3.5. Ongoing — Ciclo Continuo (Pos-Lancamento)

Apos o lancamento, o projeto entra na **Etapa 2: Ongoing** com a seguinte cadencia:

**Semanas 1-4 (Semanal):**
- Alinhamento rapido com o cliente (15-20 min)
- Ajustes de rota, aprovacao de criativos
- Otimizacao diaria de campanhas

**Mes 2 em diante (Quinzenal):**
- Reuniao de acompanhamento tatico
- Revisao de metricas e KPIs
- Aprovacao do proximo ciclo de conteudo

**Mensal:**
- Relatorio de performance completo
- Comparativo real vs. meta (Compass)
- Recomendacoes de otimizacao

### 3.6. Dia 90 — Cosmos Review

A **Cosmos Review** e obrigatoria a cada 90 dias. Roteiro:

1. **Analise de Performance (Retro)**: Real vs. Meta do trimestre
2. **Vitorias e Aprendizados**: Testes A/B, criativos vencedores, canais que performaram
3. **Gargalos Identificados**: Honestidade tecnica sobre o que impediu resultados maiores
4. **Nova Tatica (Next)**: Plano para a proxima FO com metas ajustadas
5. **Oportunidades de Escala**: Novos canais ou aumento de investimento baseado em ROI

**Participantes obrigatorios:** CS, Gestor de Performance, Decisor do Cliente (C-Level/Dono)

**Entregavel:** PDF com resumo dos resultados e novo Plano Tatico.

> Diretriz: "Nao mostramos apenas cliques. Mostramos impacto no negocio e visao de futuro."

Apos a Cosmos Review, o ciclo reinicia: novo planejamento tatico, novas metas no Compass, nova FO comeca.

---

## NAVEGACAO DA APRESENTACAO

| Acao | Como fazer |
|------|-----------|
| Navegar entre slides | Scroll (snap automatico) |
| Pular para um slide | Dots laterais (direita) |
| Revelar perguntas | Space, Enter, seta para baixo, ou botao "Proxima pergunta" |
| Navegar carrosseis | Setas < > nos slides de Onboarding e Ongoing |
| Nome do cliente | Campo "Cliente" no header — propaga automaticamente |
| Editar campos | Clique em qualquer texto com underline pontilhado azul |
| Tela cheia | F11 (recomendado para apresentacao) |

---

## ESTRUTURA DE ARQUIVOS

```
cosmos-kickoff-modelo/
├── index.html                    # Apresentacao completa (single-file)
├── atacama-digital-canyons.webp  # Background da capa (canyon)
├── assets/
│   ├── clients/                  # Logos de clientes (WebP) para o marquee
│   │   ├── grautecnico.webp
│   │   ├── ecopostos.webp
│   │   ├── mfmo.webp
│   │   └── ... (20 logos)
│   └── seals/                    # Selos de parceiros
│       ├── meta-partner.png
│       └── rd-station-partner.png
└── README.md
```

---

## PUBLICAR ONLINE (GitHub Pages)

1. Fork este repositorio
2. Va em Settings > Pages > Source: Deploy from branch > `main` > `/ (root)`
3. Acesse em `https://seu-usuario.github.io/cosmos-kickoff-modelo/`

---

## STACK

- HTML5 + CSS3 (single-file, zero build)
- CSS Scroll Snap para navegacao
- IntersectionObserver para animacoes de entrada
- Google Fonts: Inter Tight + Cormorant Unicase
- Lucide Icons (CDN)
- Google Partner Premier Badge (CDN oficial)

## BRAND

- **Fontes**: Inter Tight (UI) + Cormorant Unicase (editorial)
- **Cores institucionais**: Blackout `#000000`, Silver Gray `#DBDCDD`, Pure White `#FFFFFF`
- **Sub-brand COSMOS**: Red/Blue/Purple nebular palette
- **Orange Desert `#E13F07`**: Apenas atmosferico (backgrounds, gradientes)

---

## CHECKLIST RAPIDO

### Antes da reuniao
- [ ] Contrato auditado (Tier, SLA, servicos)
- [ ] Squad alocada e informada
- [ ] ClickUp configurado
- [ ] WhatsApp do projeto aberto
- [ ] Contas de anuncio criadas
- [ ] Apresentacao personalizada (nome, tier, plano, squad, datas, escopo)
- [ ] Link da reuniao enviado ao cliente

### Durante a reuniao
- [ ] Gravacao/transcricao ativada
- [ ] Quem Somos apresentado (breve)
- [ ] Contrato lido em voz alta (incluso + nao incluso)
- [ ] Squad apresentada
- [ ] Metodo COSMOS explicado
- [ ] Onboarding e Ongoing apresentados
- [ ] Cadencia de comunicacao alinhada
- [ ] 20 perguntas do briefing respondidas
- [ ] Metas tangibilizadas no Compass (funil reverso)
- [ ] Acessos coletados ou pendencias anotadas
- [ ] Proximos passos com datas confirmados
- [ ] Data do DNA Estrategico confirmada

### Apos a reuniao
- [ ] Gravacao enviada ao squad (2h)
- [ ] Acessos pendentes cobrados (24h)
- [ ] Tasks criadas no ClickUp (24h)
- [ ] Pixels e tags instalados (24h)
- [ ] DNA Estrategico entregue (5 dias uteis)
- [ ] Calendario editorial entregue (7 dias uteis)
- [ ] Diaria AV realizada (10 dias uteis)
- [ ] Campanhas no ar (10 dias uteis)
- [ ] Dashboard Compass compartilhado
- [ ] Cosmos Review agendada (dia 90)

---

Propriedade da Atacama Digital. Uso interno e para clientes da agencia.

Feito com COSMOS by [Atacama Digital](https://atacama.digital)
