# Portfólio — Study Hub (GitHub Pages)

> Página pessoal que apresenta quem eu sou, meu Study Hub, meus projetos e documentos.

![Status](https://img.shields.io/badge/status-publicado-22d3a6)
![Versão](https://img.shields.io/badge/vers%C3%A3o-1.0-7c5cff)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**Acesse:** https://matheusluigi.github.io/Meu_Study_Hub_TI/

---

## Sobre o projeto

Projeto da **Etapa Intermediária do Bootcamp I**. O objetivo é transformar o Study Hub
(criado na Fase 1) em uma vitrine pública: um site estático hospedado gratuitamente pelo
**GitHub Pages**, versionado com **Git** e integrado ao meu perfil no **LinkedIn**.

### Seções do site

| Seção | Conteúdo |
|-------|----------|
| Início | Apresentação e chamadas para projetos e repositório |
| Sobre | Biografia e áreas de interesse (Dados e Desenvolvimento Web) |
| Study Hub | Estrutura de pastas do repositório e disciplinas atuais |
| Projetos | Cards com os projetos acadêmicos e pessoais |
| Documentos | Entregas de cada fase do projeto integrado |
| Contato | E-mail, LinkedIn e GitHub |

## Tecnologias

- **HTML5** semântico (`header`, `main`, `section`, `article`, `footer`)
- **CSS3** com *design tokens* (variáveis CSS), Grid, Flexbox e layout responsivo
- **JavaScript** puro para o menu mobile acessível (`aria-expanded`)
- **Git + GitHub** para versionamento e **GitHub Pages** para publicação

Sem frameworks e sem etapa de build: o navegador lê os arquivos exatamente como estão no repositório.

## Onde está o código

O GitHub Pages só publica a partir da raiz do repositório **ou** de uma pasta chamada `docs/`.
Como a raiz é o Study Hub, o código do site fica em [`/docs`](../../../docs/):

```
docs/
├── index.html      # Estrutura e conteúdo
├── css/
│   └── style.css   # Design tokens, componentes e responsividade
└── js/
    └── main.js     # Menu mobile e ano do rodapé
```

## Como executar localmente

```bash
git clone https://github.com/matheusluigi/Meu_Study_Hub_TI.git
cd Meu_Study_Hub_TI
python -m http.server 5500 --directory docs
```

Depois abra `http://localhost:5500` no navegador.

## Publicação (GitHub Pages)

1. No repositório: **Settings → Pages**
2. *Source*: **Deploy from a branch**
3. *Branch*: `main` · pasta `/docs` → **Save**
4. Em ~1 minuto o site fica disponível no link acima. Cada `git push` na `main` atualiza o site.

## Versões

| Versão | O que mudou |
|--------|-------------|
| **v1.0** | Primeira versão: todas as seções, layout responsivo e menu mobile |

O histórico completo está nas [tags](https://github.com/matheusluigi/Meu_Study_Hub_TI/tags) e nos
[commits](https://github.com/matheusluigi/Meu_Study_Hub_TI/commits/main) do repositório.

## Autor

**Matheus Luigi** · [LinkedIn](https://www.linkedin.com/in/matheus-luigi-a7bb22220/) · [GitHub](https://github.com/matheusluigi)
