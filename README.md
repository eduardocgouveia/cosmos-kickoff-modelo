# KICK-OFF MODELO | COSMOS by Atacama Digital

Template definitivo de apresentacao de kick-off para novos clientes da Atacama Digital, seguindo o Metodo COSMOS e o brand kit oficial.

![Atacama Digital](https://atacama.digital/og-image.jpg)

## Sobre

Apresentacao interativa single-file HTML com 15 slides, projetada para conduzir reunioes de kick-off com novos clientes. Inclui:

- **15 slides** cobrindo: Capa, Quem Somos, Contrato, Squad, Metodo COSMOS, Onboarding, Ongoing, Cadencia, Briefing (3 partes), Metas Compass, Acessos, Proximos Passos e Encerramento
- **Perguntas progressivas** com revelacao por clique (Space / Enter / seta)
- **Campos editaveis** (nome do cliente, datas, tier, plano, squad) com propagacao automatica
- **Carrosseis horizontais** com navegacao por setas e dots
- **Marquee de logos** de clientes com scroll infinito
- **Selos oficiais** Google Partner Premier, Meta Business Partner, RD Station
- **Navegacao por scroll-snap** + barra lateral de dots + contador de slides
- **Estetica COSMOS** com nebula backgrounds, gridlines SVG, grain texture

## Como usar

### 1. Abrir localmente

Basta servir os arquivos com qualquer servidor HTTP local:

```bash
# Com Python
python3 -m http.server 8080

# Com Node.js (npx)
npx serve .

# Com PHP
php -S localhost:8080
```

Abra `http://localhost:8080` no navegador (Chrome recomendado).

### 2. Personalizar para o cliente

1. **Nome do cliente**: Digite no campo "Cliente" na barra superior — o nome se propaga automaticamente para todos os slides
2. **Tier e Plano**: Clique nos badges da capa para editar (ex: "Tier A", "Performance + Social")
3. **Data**: Clique na data da capa para alterar
4. **Squad**: Edite nomes e funcoes nos cards do slide 04
5. **Contrato**: Edite os itens inclusos/nao inclusos no slide 03
6. **Prazos**: Edite datas nos slides de Proximos Passos

Todos os campos editaveis possuem underline pontilhado azul.

### 3. Navegar na apresentacao

- **Scroll** para navegar entre slides (snap automatico)
- **Dots laterais** (direita) para pular para qualquer slide
- **Space / Enter / Seta para baixo** revela perguntas progressivas nos slides de briefing
- **Setas do carrossel** para navegar nos slides de Onboarding e Ongoing

### 4. Publicar online (GitHub Pages)

1. Fork este repositorio
2. Va em Settings > Pages > Source: Deploy from branch > `main` > `/ (root)`
3. Acesse em `https://seu-usuario.github.io/cosmos-kickoff-modelo/`

## Estrutura de arquivos

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

## Stack

- HTML5 + CSS3 (single-file, zero build)
- CSS Scroll Snap para navegacao
- IntersectionObserver para animacoes de entrada
- Google Fonts: Inter Tight + Cormorant Unicase
- Lucide Icons (CDN)
- Google Partner Premier Badge (CDN oficial)

## Brand

- **Fontes**: Inter Tight (UI) + Cormorant Unicase (editorial)
- **Cores institucionais**: Blackout `#000000`, Silver Gray `#DBDCDD`, Pure White `#FFFFFF`
- **Sub-brand COSMOS**: Red/Blue/Purple nebular palette
- **Orange Desert `#E13F07`**: Apenas atmosferico (backgrounds, gradientes)

## Licenca

Propriedade da Atacama Digital. Uso interno e para clientes da agencia.

---

Feito com COSMOS by [Atacama Digital](https://atacama.digital)
