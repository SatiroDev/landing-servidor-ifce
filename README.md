# 🌐 Projeto: Landing Page — IFCE Campus Maranguape

## 📖 Descrição do Projeto
Este projeto consiste na criação de uma **Landing Page** para promover um **servidor do IFCE Campus Maranguape**, aplicando os conceitos de **HTML e CSS** aprendidos na disciplina **Desenvolvimento Web I** (Prof. Thomaz Maia).

O site apresenta informações sobre um servidor escolhido pela dupla, incluindo biografia, formação, disciplinas (quando aplicável) e meios de contato.

---

## 🧩 Estrutura do Projeto

```
landing-servidor-ifce/
│
├── index.html
│
├── html/
│    ├── sobre.html
│    ├── formacao.html
│    ├── disciplinas.html
│    └── contato.html
│
├── css/
│     ├── contato.css
│     ├── disciplinas.css
│     ├── formacao.css
│     ├── index.css 
│     └── sobre.css
│
├── img/
│    └── (imagens utilizadas no site)
│
└── docs/
     └── (currículo em PDF do servidor)

```

---

## 🏠 Página Principal — `index.html`

A página inicial deve conter:
- **Nome completo** do servidor em destaque (`<h1>`);
- **Foto** do servidor (`<img>`);
- **Pequena biografia** (`<p>`);
- **Menu de navegação** (`<nav>`) com links para as demais páginas;
- Uso de **tags semânticas**: `header`, `section`, `article`, `aside` e `footer`;
- **Botão/Link para download** do currículo do servidor (arquivo PDF dentro da pasta `docs/`).

---

## 📄 Subpáginas Obrigatórias

### 🔹 `sobre.html`
Informações adicionais sobre o servidor: fotos, hobbies, curiosidades, etc.

### 🔹 `formacao.html`
Formações acadêmicas e experiências profissionais usando listas ordenadas (`<ol>`) e não ordenadas (`<ul>`).

### 🔹 `disciplinas.html`
Para professores: tabela de horários das disciplinas ministradas (usar `<table>`).

### 🔹 `contato.html`
Formulário de contato contendo:
- Nome (`<input type="text">`)
- E-mail (`<input type="email">`)
- Assunto (`<select>`)
- Mensagem (`<textarea>`)
- Botão de envio (`<input type="submit">`)

---

## 🎨 Estilo — `css/style.css`

Regras de estilização exigidas:
- O CSS deve estar em arquivo externo (`css/style.css`);
- Utilizar **cores personalizadas** (background, texto, links, etc.);
- Estilização de **tipografia** (tamanho, família e cor de fonte);
- Aplicar **box model** com `padding`, `margin` e `border` onde necessário;
- Posicionamento com `position: relative` e `position: absolute` quando pertinente;
- Estilização de **tabelas, listas, links e formulários**.

> Observação: **Não** utilizar `display: flex` nem `display: grid` neste projeto.

---

## ⚙️ Regras Gerais

- O projeto deve ser desenvolvido **em dupla**;
- Cada dupla deve escolher **um servidor diferente** (sem repetição entre as duplas);
- Estrutura de pastas deve ser seguida conforme apresentado;
- O site deve ser semanticamente correto e bem organizado;
- Não utilizar frameworks ou bibliotecas externas (HTML e CSS puros).

---

## 👩‍💻 Autores
Projeto desenvolvido por:  
[José Satiro](https://github.com/SatiroDev) e [Luis Wagner](https://github.com/colarin)  
Curso: Técnico em Informática — IFCE Campus Maranguape  
Disciplina: Desenvolvimento Web I  
Professor: **Thomaz Maia**
