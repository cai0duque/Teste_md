---
title: "LearnConnect – Biblioteca Social de Conhecimentos"
draft: false
language: pt-br
featured_image: images/featured/learnconnect-featured.png
summary: "LearnConnect é uma plataforma web que conecta quem aprende e quem ensina, organizando materiais, comentários e feedbacks em um só lugar."
author: UniFil
categories: Projeto de Extensão
tags: ["CC", "ES", "ADS", "Educação", "Tecnologia", "Cultura"]
linkandroid: ""
linkios: ""
linkweb: "http://168.75.74.153:3001/"
linkblog: ""
linkvideo: ""
---

## Sobre o LearnConnect

O **LearnConnect** nasceu na disciplina / projeto de Extensão Curricular da Universidade UniFil com o objetivo de **centralizar, organizar e democratizar** materiais de estudo. A plataforma permite que qualquer pessoa:

* publique **materiais** (artigos, links, road‑maps);
* **reaja** (likes) e discuta em um **sistema de comentários**;
* descubra conteúdos por **tags** e categorias;
* acompanhe o **perfil** de autores e comentadores.

Tudo isso em uma interface escura (_dark‑mode_) inspirada em comunidades tech, com realce em **<#5c64f4>** (roxo) para ações e destaques.

![Screenshot – lista de materiais](images/featured/learnconnect-screenshot-list.png)
![Screenshot – material detalhado](images/featured/learnconnect-screenshot-post.png)

## Motivação

Nem sempre é fácil encontrar **conteúdos de qualidade em um único lugar**. Professores, alunos e entusiastas acabam espalhando links por grupos de WhatsApp ou planilhas. O LearnConnect propõe:

> “Transformar a bagunça de links em uma **biblioteca social**.”

Benefícios:

| Público        | Ganho principal                               |
| -------------- | --------------------------------------------- |
| Estudante      | Encontrar rapidamente roteiros de estudo      |
| Docente        | Divulgar leituras e acompanhar feedback       |
| Comunidade     | Valorizar autores locais e criar networking   |

## Tecnologias Utilizadas

```text
Frontend  → Next.js 15 + React + TailwindCSS
Backend   → Node.js 18 + Express + Prisma (PostgreSQL)
Infra     → Docker Compose (postgres, backend, frontend)
Auth      → JWT
CI/CD     → GitHub Actions
```

### Paleta de Cores

| Cor              | Hex      | Uso principal          |
| ---------------- | -------- | ---------------------- |
| Midnight Black   | `#121212`| Fundo (dark‑mode)      |
| Iron Gray        | `#1a1a1a`| Cartões, side‑bar      |
| Neon Purple      | `#5c64f4`| Botões, links ativos   |
| Glow Border      | `#5c64f4/70`| Borda luminosa nos cards |

## Como acessar

O projeto está rodando publicamente em:

➡️ **[http://168.75.74.153:3001/](http://168.75.74.153:3001/)**  ← clique e teste!

## Próximos Passos

- [ ] Implementar **upload** de PDFs/imagens
- [ ] Notificações por e‑mail
- [ ] Theme claro/escuro
- [ ] Integração com OAuth (Google / GitHub)

---

> _“Compartilhar conhecimento é multiplicar oportunidades.”_ – Equipe LearnConnect
