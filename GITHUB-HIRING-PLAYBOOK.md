# GitHub Hiring Playbook — plano para virar candidato forte

Este documento é um plano prático para transformar o GitHub em um portfólio competitivo para vagas de tecnologia.

Perfil atual analisado: **@mbthenewera**.

Situação atual:

- Existe o repositório especial `mbthenewera/mbthenewera`, usado como README do perfil.
- Existem projetos públicos em áreas variadas: automação Python, ferramentas dev, painel web, C#, C++ e análise.
- O próximo salto é transformar projetos simples em produtos apresentáveis: deploy, screenshots, README forte, testes, CI/CD e narrativa de negócio.

---

## 1. Estrutura do perfil

### Bio ideal

A bio precisa responder em uma linha: **o que você faz, com qual stack e que tipo de problema resolve**.

#### Frontend

```txt
Frontend Developer | React, TypeScript, UX operacional e dashboards responsivos para produtos reais.
```

#### Backend

```txt
Backend Developer | Node.js, APIs REST, PostgreSQL, autenticação e automações para sistemas de negócio.
```

#### Fullstack

```txt
Fullstack Developer | React, Node.js, PostgreSQL e dashboards para vendas, delivery e operações locais.
```

#### Para seu momento atual

```txt
Developer focused on web systems, automation and practical digital products for real business operations.
```

### Foto

Use uma foto:

- rosto visível;
- fundo limpo;
- boa iluminação;
- sem filtro exagerado;
- sem print, anime, logo ou foto escura.

Regra: recrutador precisa reconhecer você em 1 segundo.

### Nome de usuário

Seu usuário atual `mbthenewera` é aceitável: curto, memorável e não parece aleatório. Não recomendo trocar agora.

Evite usernames com:

- muitos números;
- gíria pesada;
- caracteres difíceis;
- nomes que pareçam conta fake.

### Links obrigatórios

Coloque no perfil:

- LinkedIn;
- portfólio pessoal;
- e-mail profissional;
- currículo em PDF, se tiver;
- projeto principal em produção.

### README do perfil: regra dos 10 segundos

O topo do README precisa mostrar:

1. quem você é;
2. stack principal;
3. tipos de projeto;
4. melhores repositórios;
5. contato.

Template copiável:

```md
# Seu Nome

**Fullstack Developer focado em React, Node.js, PostgreSQL e produtos digitais para operações reais.**

Construo sistemas com foco em clareza, performance, documentação e deploy. Meus projetos priorizam problemas reais: vendas, delivery, dashboards, automação e gestão.

## Projetos em destaque

| Projeto | Stack | Resultado |
|---|---|---|
| Nome do projeto | React + Node | Dashboard com autenticação e deploy |
| Nome do projeto | Python | CLI para automação de arquivos |
| Nome do projeto | Node + PostgreSQL | API REST com testes e CI |

## Stack

React • TypeScript • Node.js • PostgreSQL • Python • Git • Docker

## Contato

- LinkedIn: seu link
- Portfólio: seu link
- E-mail: seu email
```

---

## 2. Portfólio de projetos

### Quantidade ideal

- Mínimo: **4 projetos bons**.
- Ideal: **6 projetos públicos fortes**.
- Máximo recomendado: **10 projetos visíveis**.

Mais que isso só se estiver tudo bem organizado. Projeto fraco deve ficar privado ou arquivado.

### O que cada stack precisa ter

#### Frontend

Tenha:

1. Dashboard administrativo realista;
2. Landing/page institucional com performance e responsividade;
3. Clone reinterpretado de app famoso, sem parecer cópia rasa;
4. Projeto com consumo de API, filtro, busca, paginação e estados de erro;
5. Design system pequeno ou biblioteca de componentes.

Projetos sugeridos:

- Dashboard de pedidos para hamburgueria;
- Sistema de estoque para padaria;
- Painel de anúncios para loja de carros;
- Interface de CRM para leads.

#### Backend

Tenha:

1. API REST com autenticação JWT;
2. CRUD com validação, paginação e filtros;
3. Banco relacional com migrations;
4. Testes unitários e integração;
5. Documentação Swagger/OpenAPI;
6. Deploy em Railway, Render ou Fly.io.

Projetos sugeridos:

- API de cardápio digital;
- API de pedidos e estoque;
- API de licenças/auth para bots;
- Sistema de pagamentos fake/sandbox.

#### Fullstack

Tenha:

1. App completo com login;
2. Dashboard privado;
3. Banco de dados;
4. Deploy front + back;
5. README com arquitetura;
6. usuário de demonstração.

Projetos sugeridos:

- SaaS simples de cardápio digital;
- sistema de vendas para padaria;
- painel de delivery;
- CRM de veículos.

#### Mobile

Tenha:

- app com login;
- listagem e detalhes;
- armazenamento local;
- consumo de API;
- publicação de APK ou build demonstrável.

Projetos sugeridos:

- app de pedidos para lanchonete;
- app de check-in escolar;
- app de controle financeiro simples.

#### Dados

Tenha:

- notebook limpo;
- dataset documentado;
- análise exploratória;
- gráficos;
- conclusão de negócio;
- dashboard final.

Projetos sugeridos:

- análise de vendas de delivery;
- previsão simples de demanda;
- dashboard de estoque e rupturas.

#### DevOps

Tenha:

- Dockerfile;
- docker-compose;
- GitHub Actions;
- deploy automatizado;
- monitoramento básico;
- documentação de ambiente.

Projetos sugeridos:

- deploy de API Node com PostgreSQL;
- pipeline CI/CD para app React;
- stack local com Nginx + API + banco.

### Como escolher títulos

Título ruim:

```txt
Projeto Final
Sistema Legal
Dashboard IA
Clone Netflix
```

Título bom:

```txt
cardapio-digital-saas
bakery-sales-dashboard
vehicle-leads-crm
delivery-ops-board
node-auth-license-api
```

Regra de keywords:

- inclua domínio: bakery, delivery, crm, auth, sales, dashboard;
- inclua stack quando fizer sentido: node, react, api;
- evite nomes genéricos;
- descrição do repo deve ter palavras buscáveis.

Descrição boa:

```txt
Dashboard responsivo para gestão de pedidos, estoque e vendas de uma hamburgueria, com filtros, métricas e deploy.
```

Em inglês:

```txt
Responsive order management dashboard for a burger shop, including sales metrics, filters, stock alerts and live deployment.
```

### Template de README matador para repositório

```md
# Nome do Projeto

![Preview](./docs/preview.png)

## Visão geral

Explique em 3 linhas o problema que o projeto resolve, para quem ele foi feito e qual o diferencial técnico.

## Deploy

- Produção: link aqui
- Usuário demo: demo@email.com
- Senha demo: 123456

## Tech stack

- Frontend: React, TypeScript, Vite
- Backend: Node.js, Express
- Banco: PostgreSQL
- Testes: Vitest/Jest
- Deploy: Vercel/Railway

## Features

- Autenticação
- CRUD completo
- Busca e filtros
- Paginação
- Validação de formulário
- Dashboard com métricas
- Responsivo

## Arquitetura

```txt
src/
  components/
  pages/
  services/
  hooks/
  utils/
  tests/
```

## Como rodar localmente

```bash
git clone link-do-repo
cd nome-do-repo
npm install
npm run dev
```

## Variáveis de ambiente

```env
DATABASE_URL=
JWT_SECRET=
```

## Testes

```bash
npm run test
npm run lint
```

## Screenshots

| Dashboard | Mobile |
|---|---|
| imagem | imagem |

## Decisões técnicas

- Escolhi X porque...
- Separei Y para facilitar manutenção...
- Usei Z para melhorar performance...

## Próximos passos

- [ ] Melhorar cobertura de testes
- [ ] Adicionar logs estruturados
- [ ] Criar modo escuro
```

---

## 3. Atividade social e networking

### Como conseguir visibilidade sem virar influencer

Ações semanais:

- abrir 1 issue útil em projeto real;
- comentar em 2 discussions técnicas;
- melhorar documentação de 1 projeto open source;
- criar PR pequeno e bem explicado;
- compartilhar um projeto no LinkedIn com texto técnico curto.

### Onde contribuir

Escolha projetos que você usa ou entende minimamente:

- docs de frameworks;
- bibliotecas menores de React/Node;
- projetos brasileiros;
- templates, CLIs e ferramentas dev;
- issues marcadas como `good first issue`, `documentation`, `bug`, `help wanted`.

### Como fazer PR que soma

PR ruim:

```txt
fix
```

PR bom:

```txt
docs: clarify setup instructions for local development
```

Descrição boa:

```md
## O que foi feito

Corrigi a seção de instalação local, adicionando o comando de cópia do `.env.example` e a ordem correta de execução.

## Por quê

A documentação anterior pulava uma etapa e podia causar erro de variável de ambiente ausente.

## Como testei

- Rodei `npm install`
- Copiei `.env.example`
- Executei `npm run dev`
```

### Como ser notado por hiring managers

- Responda issues com solução técnica clara;
- publique PRs pequenos e frequentes;
- evite discussão emocional;
- mostre investigação: logs, reprodução, causa e correção;
- mantenha perfil limpo e README bom.

---

## 4. Qualidade técnica do código

### Checklist do recrutador técnico

Ele olha:

- nomes de variáveis claros;
- funções pequenas;
- estrutura de pastas previsível;
- separação de responsabilidades;
- tratamento de erro;
- validação de entrada;
- testes;
- README;
- commits;
- segurança básica;
- deploy funcionando.

### Estrutura recomendada para front-end

```txt
src/
  components/
  pages/
  services/
  hooks/
  utils/
  styles/
  tests/
```

### Estrutura recomendada para back-end

```txt
src/
  controllers/
  services/
  repositories/
  routes/
  middlewares/
  validators/
  config/
  tests/
```

### Commits profissionais

Use Conventional Commits:

```txt
feat: add order status filter
fix: handle empty product image
refactor: split dashboard metrics component
docs: improve setup instructions
test: add auth service tests
chore: configure eslint and prettier
```

Evite:

```txt
update
arrumei
final
agora vai
coisas
```

### CI/CD mínimo

Crie `.github/workflows/ci.yml`:

```yaml
name: CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  checks:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v4
      - uses: actions/setup-node@v4
        with:
          node-version: 20
      - run: npm ci
      - run: npm run lint
      - run: npm run test -- --run
      - run: npm run build
```

### Ferramentas profissionais

Use quando fizer sentido:

- Vercel: deploy de front-end;
- Railway/Render/Fly.io: deploy de APIs;
- Supabase/Neon: banco PostgreSQL;
- GitHub Actions: CI;
- Dependabot: atualização automática;
- Codecov: cobertura de testes;
- SonarCloud: qualidade e bugs;
- ESLint + Prettier: padronização;
- Husky + lint-staged: validação antes do commit;
- Docker: ambiente previsível.

---

## 5. Estratégias de fundo

### O que não colocar no GitHub

Não deixe público:

- projeto de curso sem modificação;
- código copiado sem autoria clara;
- repo vazio;
- fork sem contribuição;
- código com senha/token;
- projeto quebrado sem aviso;
- README genérico;
- 20 clones iguais;
- arquivos `node_modules`, `.env`, builds pesados.

### Deploy de todos os projetos

Todo projeto web importante precisa ter link vivo.

Sugestão:

- Front-end: Vercel;
- API Node: Railway ou Render;
- Banco: Supabase ou Neon;
- Documentação: README + screenshots;
- Demo: usuário e senha de teste.

### Adaptar GitHub para vagas específicas

#### Nubank / fintech

Destaque:

- back-end limpo;
- testes;
- APIs;
- segurança;
- idempotência;
- logs;
- tratamento de erro;
- arquitetura.

Projeto ideal:

```txt
mini-finance-ledger-api
```

#### iFood / delivery

Destaque:

- pedidos;
- cardápio;
- logística;
- tempo real;
- dashboard;
- status de entrega.

Projeto ideal:

```txt
delivery-ops-dashboard
```

#### Uber / mobilidade

Destaque:

- geolocalização;
- rotas;
- status;
- matching;
- eventos;
- escalabilidade.

Projeto ideal:

```txt
route-dispatch-simulator
```

#### Startups SaaS

Destaque:

- autenticação;
- multiusuário;
- plano/free/pro;
- billing sandbox;
- dashboard;
- métricas.

Projeto ideal:

```txt
restaurant-menu-saas
```

### Manutenção

Rotina ideal:

- 1 commit útil por dia ou a cada 2 dias;
- 1 README melhorado por semana;
- 1 deploy revisado por semana;
- 1 issue/PR open source por semana;
- revisar repositórios pinados a cada 15 dias.

Repos para pinar:

1. melhor fullstack;
2. melhor front-end;
3. melhor back-end/API;
4. ferramenta/CLI;
5. contribuição open source ou lib;
6. projeto de domínio real: delivery, vendas, financeiro ou automação.

---

# Roteiro de 4 semanas — 1h por dia

## Semana 1 — Arrumar vitrine

Objetivo: fazer o perfil parecer profissional rápido.

Dia 1:

- atualizar bio;
- adicionar LinkedIn, portfólio e e-mail;
- revisar foto.

Dia 2:

- finalizar README do perfil;
- colocar stack;
- listar projetos em destaque.

Dia 3:

- escolher 6 repositórios públicos para manter;
- arquivar ou privatizar os fracos.

Dia 4:

- melhorar README do melhor projeto;
- adicionar descrição clara.

Dia 5:

- adicionar screenshot ou SVG preview.

Dia 6:

- criar deploy do projeto web mais forte.

Dia 7:

- revisar tudo como se fosse recrutador por 10 segundos.

## Semana 2 — Criar projeto principal

Objetivo: ter 1 projeto forte para vaga.

Projeto recomendado para você:

```txt
cardapio-digital-saas
```

Features mínimas:

- login admin;
- CRUD de categorias;
- CRUD de produtos;
- imagem do produto;
- cardápio público por link;
- dashboard simples;
- deploy.

Dia 1: planejar telas e banco.
Dia 2: montar front-end.
Dia 3: montar back-end/API.
Dia 4: integrar CRUD.
Dia 5: criar tela pública do cardápio.
Dia 6: deploy.
Dia 7: README completo.

## Semana 3 — Qualidade técnica

Objetivo: parecer projeto de empresa.

Dia 1:

- ESLint + Prettier.

Dia 2:

- testes básicos.

Dia 3:

- GitHub Actions.

Dia 4:

- badges no README.

Dia 5:

- tratamento de erros e validações.

Dia 6:

- documentação da arquitetura.

Dia 7:

- abrir issues internas com próximos passos.

## Semana 4 — Visibilidade e candidatura

Objetivo: GitHub pronto para recrutador.

Dia 1:

- pinar os 6 melhores repositórios.

Dia 2:

- criar post curto no LinkedIn com projeto principal.

Dia 3:

- contribuir com documentação em projeto open source.

Dia 4:

- abrir PR pequeno.

Dia 5:

- adaptar README para vaga alvo.

Dia 6:

- revisar currículo/linkedin com os projetos.

Dia 7:

- aplicar para vagas usando links diretos dos projetos.

---

# Caminho se o perfil estiver zerado

Faça nesta ordem:

1. criar repo especial do perfil;
2. criar README profissional;
3. criar 3 projetos pequenos e bem acabados;
4. criar 1 projeto fullstack maior;
5. colocar deploy em todos os web;
6. adicionar screenshots;
7. criar testes e CI em pelo menos 1 projeto;
8. pinar os melhores.

# Caminho se já tem projetos medianos

Faça upgrade:

1. renomear projetos ruins;
2. trocar README genérico por README forte;
3. adicionar screenshots;
4. adicionar deploy;
5. melhorar estrutura de pastas;
6. criar issues com roadmap;
7. adicionar testes;
8. pinar apenas os melhores.

---

## Prioridade máxima para @mbthenewera

1. Atualizar links reais no README do perfil.
2. Criar ou melhorar um projeto principal fullstack.
3. Fazer deploy do melhor projeto web.
4. Adicionar screenshots/GIFs nos repositórios.
5. Melhorar README dos 6 projetos públicos atuais.
6. Pinar os projetos certos.
7. Fazer commits com mensagens profissionais.
8. Criar CI/CD em pelo menos um projeto.
