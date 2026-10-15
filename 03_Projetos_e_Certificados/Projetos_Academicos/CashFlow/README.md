# 💰 CashFlow — Controle Financeiro Pessoal

> Aplicação web para organizar as finanças pessoais, desenvolvida em equipe como Projeto Integrador.

![Tipo](https://img.shields.io/badge/projeto-integrador-7c5cff)
![Equipe](https://img.shields.io/badge/equipe-5%20alunos-22d3a6)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)

🔒 **Código:** repositório privado da equipe (acesso restrito aos integrantes).

---

## 📖 Sobre o projeto

O CashFlow nasceu como Projeto Integrador do curso de Ciências da Computação (CEUB). O objetivo
é incentivar o hábito de organização financeira com uma ferramenta simples, modular e didática,
que sirva de base para evoluir com backend e banco de dados.

## ✨ Funcionalidades

- **Login** com validação de e-mail e senha
- **Cadastro em três etapas**: dados pessoais, endereço e confirmação
- **Dashboard** com resumo financeiro e **gráfico por categoria**
- **Limite de gastos** configurável no perfil
- **Relatório em PDF** para download
- Telas de **perfil** e **configurações**

## 🛠️ Tecnologias

| Camada | Tecnologia | Uso |
|--------|------------|-----|
| Estrutura | HTML5 | Interfaces de cada tela |
| Estilo | CSS3 | Visual e responsividade |
| Lógica de interface | JavaScript | Validações, navegação entre telas e gráficos |
| Servidor | PHP | Conexão com o banco e rotinas do backend |

## 🏗️ Arquitetura

Cada tela é um módulo independente, com seus próprios arquivos de estrutura, estilo e lógica
(separação de responsabilidades):

```
CashFlow/
├── CashFlow_Tela_de_Login/
├── CashFlow_Tela_de_Cadastro/
├── CashFlow_Tela_HomePage/
├── CashFlow_Tela_Perfil/
├── CashFlow_Tela_Config/
└── conexao.php
```

## 👥 Equipe e minha participação

Projeto desenvolvido por uma equipe de 5 alunos, com versionamento colaborativo em um
repositório compartilhado no GitHub. Sou um dos autores do sistema e da sua documentação oficial.

## 🔭 Próximos passos

- Ampliar a responsividade para dispositivos móveis
- Evoluir o controle financeiro (lançamentos, categorias e saldo)
