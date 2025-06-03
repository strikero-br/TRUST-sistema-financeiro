<p align="right">
  <a href="https://github.com/strikero-br/TRUST-sistema-financeiro">
    <img src="https://img.icons8.com/win10/200/228BE6/github.png" alt="GitHub" width="90" height="90">
  </a>
</p>

# TRUST

> Sistema de Controle Financeiro Pessoal com Simulador de Trades na Bolsa de Valores

---

## 🎯 Sobre o Projeto

**TRUST** é uma aplicação web desenvolvida em React com o objetivo de ajudar o usuário a organizar suas finanças pessoais e, como funcionalidade extra, simular operações de trade com ações da bolsa de valores. O sistema é simples, direto e feito para ser usado em qualquer dispositivo.

Funcionalidades principais:

- 💰 Cadastro de receitas e despesas  
- 📊 Dashboard financeiro com saldo e totais  
- 📈 Simulador de operações de trade (funcionalidade extra)  
- 🔐 Autenticação de usuários  
- 🖥️ Interface responsiva e moderna  

---

## 🚀 Funcionalidades

### 1. Autenticação de Usuário
- Tela de login com validação nativa (`email`, `required`)
- Redirecionamento automático para o dashboard se estiver logado

### 2. Dashboard Financeiro
- Exibição de:
  - Nome do usuário
  - Saldo atual
  - Total de receitas
  - Total de despesas
- Área futura para gráficos e movimentações

### 3. TRUST Trading Desk (Funcionalidade Extra)
- Cadastro de operações de trade:
  - Código do ativo
  - Tipo de operação (compra ou venda)
  - Preço de entrada e saída
  - Quantidade
  - Data e observações
- Histórico de operações com cálculo automático de lucro/prejuízo
- Estatísticas:
  - Número total de trades
  - Taxa de acerto
  - Resultado acumulado

> Obs.: Esta seção está em protótipo.
---

## 🖼️ Layout e Rotas

- Interface responsiva para desktop e mobile (ainda em desenvolvimento)
- Componentes reutilizáveis
- Rotas:
  - `/` - Tela de login
  - `/dashboard` - Painel financeiro
  - `/trading` - Simulador de bolsa (ainda em desenvolvimento)
  - `*` - Página 404

---

## 🛠️ Tecnologias Utilizadas

- [React 18](https://reactjs.org/)
- [Vite](https://vitejs.dev/)
- [React Router DOM](https://reactrouter.com/)
- Context API (autenticação e dados financeiros)
- CSS Puro (global, reset e variáveis)

---

## 🌐 **Apresentação do Projeto**
### 👉 [Acesse a apresentação oficial do projeto: Trust - Controle Financeiro](https://.my.canva.site/)

> Conheça mais sobre o projeto, seu funcionamento de gerenciamento financeiro.

---

## 📁 Estrutura do Projeto

```txt
TRUST/
 ├── public/
 │   └── favicon.svg
src/
 ├── assets/
 │   └── logotrust.png
 ├── components/
 │   ├── Button.jsx
 │   ├── Button.css
 │   ├── Header.jsx
 │   ├── Header.css
 │   ├── Footer.jsx
 │   └── Footer.css
 ├── contexts/
 │   ├── AuthContext.jsx
 │   ├── FinanceContext.jsx
 │   └── TradeContext.jsx
 ├── pages/
 │   ├── DashboardPage.jsx
 │   ├── DashboardPage.css
 │   ├── LoginPage.jsx
 │   ├── LoginPage.css
 │   ├── NotFoundPage.jsx
 │   ├── NotFoundPage.css
 │   ├── TradePage.jsx          ← Implementação Futura!
 │   └── TradePage.css          ← Implementação Futura!
 ├── routes/
 │   └── Routes.jsx
 ├── services/
 │   └── (vazio)
 ├── styles/
 │   └── global.css
 ├── App.jsx
 └── main.jsx
├── index.html
├── .gitignore
├── package.json
└── README.md
```

---

## ▶️ Como Executar

> ### Clone o repositório
> ```bash
> git clone https://github.com/strikero-br/TRUST-sistema-financeiro
> ```
>
> ### Navegue até o diretório do projeto
> ```bash
> cd TRUST-sistema-financeiro
> ```
> 
> ### Instale as dependências
> ```bash
> npm install
> ```
>
> ### Inicie o servidor de desenvolvimento
> ```bash
> npm run dev
> ```
>
> Abra no navegador: [http://localhost:5173](http://localhost:5173)

---

## 👤 Desenvolvedor

**Jonathan Pereira Delmonte**  
Responsável pelo projeto.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📬 Contato

Caso tenha dúvidas, sugestões ou feedbacks:  
✉️ jonathanpdelmon@gmail.com

---

**Projeto criado para a disciplina de Desenvolvimento Web Front-End – Centro Universitário Uniacademia**
