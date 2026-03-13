# 📝 Blog Pessoal

Uma aplicação web simples de blog pessoal que permite criar e visualizar postagens diretamente no navegador, sem necessidade de backend.

---

## 🖼️ Visão Geral

O projeto consiste em uma página HTML com formulário para criação de posts e uma seção que exibe as postagens em um grid responsivo de cards. As postagens são enviadas para uma API externa (JSONPlaceholder) e renderizadas dinamicamente na tela.

---

## 🚀 Funcionalidades

- Criar postagens com título e conteúdo
- Exibir data de publicação automaticamente (fuso horário pt-BR)
- Grid responsivo de cards com hover animado
- Integração com a API [JSONPlaceholder](https://jsonplaceholder.typicode.com) para simular envio de dados
- Layout limpo e tipografia com **Inter** e **Merriweather** (Google Fonts)

---

## 🗂️ Estrutura do Projeto

```
├── index.html   # Estrutura, lógica JavaScript e integração com a API
└── style.css    # Estilos e layout responsivo
```

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura da página |
| CSS3 | Estilização e responsividade |
| JavaScript (Vanilla) | Lógica de formulário e manipulação do DOM |
| Fetch API | Requisições HTTP para a API |
| Google Fonts | Tipografia (Inter + Merriweather) |
| JSONPlaceholder | API fake para simular publicações |

---

## ▶️ Como Usar

1. Clone ou baixe o repositório
2. Abra o arquivo `index.html` diretamente no navegador — não é necessário servidor

```bash
# Ou, opcionalmente, com o VS Code Live Server:
# Clique com botão direito em index.html → "Open with Live Server"
```

3. Preencha o **título** e o **conteúdo** no formulário
4. Clique em **"Publicar Agora"** para adicionar o post à seção de postagens recentes

> ⚠️ As postagens são apenas renderizadas em memória. Ao recarregar a página, elas serão perdidas (sem persistência local).

---

## 📌 Observações

- A integração com a JSONPlaceholder simula o envio de dados mas **não persiste** as postagens em nenhum servidor real.
- Para adicionar persistência, considere usar `localStorage` ou integrar com um backend próprio.

---

## 📄 Licença

© 2026 Blog Pessoal. Todos os direitos reservados.