# ✉️ E-mail Marketing Compatível com Outlook e Clientes de E-mail

> Projeto de template de e-mail desenvolvido com foco em compatibilidade total com leitores de e-mail como **Outlook, Gmail, Apple Mail, Yahoo**, entre outros. Criado com técnicas específicas para garantir a renderização correta do layout em ambientes limitados de leitura de HTML/CSS.

---

## 🎯 Objetivo

Desenvolver um layout de e-mail responsivo e profissional, utilizando **HTML básico, CSS inline e estrutura em tabelas**, garantindo compatibilidade com os principais clientes de e-mail — especialmente o Outlook, que possui diversas limitações na renderização moderna de CSS.

---

## 🛠️ Tecnologias e Técnicas Utilizadas

- **HTML4/HTML5 básico** (sem uso de JavaScript)
- **Tabelas aninhadas** para estruturar o conteúdo
- **CSS embutido (inline styles)** para garantir leitura
- **Fontes padrões (web-safe)** — sem fontes externas como Google Fonts
- **Layout fixo ou fluido (em porcentagem)**
- **Cores e botões estilizados com `<table>` e `<td>`**
- **Uso de `<!--[if mso]>` para correções específicas no Outlook**
- **Imagens com `alt` e dimensões definidas**

---

## 🔧 Técnicas Específicas de Compatibilidade

- ❗ **Evita** Flexbox, Grid, pseudo-classes (`:hover`), e JavaScript
- ✅ Utiliza `align`, `valign`, `cellpadding`, `cellspacing`
- ✅ Usa `<table>` com larguras fixas ou em `%` para controle de layout
- ✅ Todo CSS é aplicado **inline**: `style="font-size:14px; color:#000;"`

---

## 🧱 Estrutura do Template

https://project-email-io.vercel.app/

