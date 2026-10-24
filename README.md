# ☕ Serenatto — Café & Bistrô

Site institucional de uma cafeteria e bistrô fictícia, desenvolvido como projeto de estudo a partir de um curso da **Alura**.

🔗 **Demo online:** [serenatto-rosy.vercel.app](https://serenatto-rosy.vercel.app)

---

## 1. Sobre o projeto

O **Serenatto** é uma landing page responsiva para uma cafeteria e bistrô. O objetivo do projeto foi praticar o uso do **Bootstrap** e a **customização de seus componentes**, aplicando identidade visual própria ao site.

> Projeto fictício, sem fins comerciais.

### O que o site apresenta

- **Banner de boas-vindas** e seções de destaque com imagens;
- **Nossos serviços:** Café & Bistrô, Buffet e Delivery, cada um com um painel lateral (offcanvas) de detalhes em formato sanfona (accordion);
- **Nossos produtos:** cafés tradicionais, cafés especiais, smoothies e vitaminas, pães e focaccias, doces e salgados, com modais de detalhes;
- **Formulário de contato** com nome, e-mail, telefone, preferência de contato, nível de satisfação e opt-in de novidades;
- **Modo noturno** (alternância de tema claro/escuro);
- **Menu de navegação** fixo e responsivo, que vira menu lateral em telas menores;
- **Rodapé** com ícones de redes sociais.

---

## 2. Tecnologias utilizadas

### Stack

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura das páginas e semântica |
| **CSS3** | Estilização e customização dos componentes |
| **JavaScript** | Interações, como o modo noturno |
| **Vercel** | Deploy e hospedagem |
| **Git / GitHub** | Versionamento de código |

### Frameworks e bibliotecas

- [**Bootstrap 5.3**](https://getbootstrap.com/) (via CDN): grid, navbar, cards, offcanvas, accordion, modal, formulários e tema claro/escuro (`data-bs-theme`);
- [**Bootstrap Icons 1.10**](https://icons.getbootstrap.com/) (via CDN): ícones de redes sociais e do rodapé.

### APIs e serviços externos

Este projeto **não consome APIs de dados**. Utiliza apenas serviços de CDN:

- [**Google Fonts**](https://fonts.google.com/): fontes *Barlow* e *Barlow Condensed*;
- [**jsDelivr**](https://www.jsdelivr.com/): entrega do CSS/JS do Bootstrap e dos Bootstrap Icons.

### Estrutura de pastas

```
Serenatto/
├── Assets/        # Imagens, logos e favicon
├── index.html     # Página principal
├── estilos.css    # Estilos customizados
├── script.js      # Scripts da página
└── README.md
```

---

## 3. Como baixar e executar o projeto

### Pré-requisitos

- Um navegador moderno (Chrome, Firefox, Edge, Safari);
- [Git](https://git-scm.com/) (opcional, caso prefira clonar);
- Conexão com a internet, pois Bootstrap, ícones e fontes são carregados via CDN.

Não é necessário instalar dependências nem usar Node.js.

### Baixando o projeto

**Opção A: clonando com Git**

```bash
git clone https://github.com/CleverssonHames/Serenatto.git
cd Serenatto
```

**Opção B: download em ZIP**

1. Acesse [github.com/CleverssonHames/Serenatto](https://github.com/CleverssonHames/Serenatto);
2. Clique em **Code → Download ZIP**;
3. Extraia o arquivo na sua máquina.

### Executando

**Opção 1: direto no navegador**

Dê um duplo clique no arquivo `index.html`, ou abra-o pelo navegador (`Ctrl + O`).

**Opção 2: com servidor local (recomendado)**

- **VS Code:** instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer), clique com o botão direito em `index.html` e escolha **Open with Live Server**;
- **Python:**
  ```bash
  python -m http.server 8000
  ```
  Depois acesse `http://localhost:8000`;
- **Node.js:**
  ```bash
  npx serve .
  ```

---

## 🚀 Deploy

O projeto está publicado na **Vercel**. Para fazer o seu próprio deploy, importe o repositório no painel da Vercel. Como é um site estático, não exige configuração de build.

---

## 👨‍💻 Autor

Desenvolvido por **[Cleversson Hames](https://github.com/CleverssonHames)**, com base no curso da Alura.
