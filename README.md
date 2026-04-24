# 🌐 LandPage — Projeto de Landing Page

> Projeto desenvolvido por **Caio Henrique Marques Dos Santos** — RA: R982IG7  
> Código CSS e HTML desenvolvido de forma independente, com auxílio de ferramentas como Copilot e Claude para dúvidas, correções, melhorias e responsividade.

---

## 📋 Sobre o Projeto

**LandPage** é uma landing page desenvolvida com foco em conversão, apresentando serviços de desenvolvimento web de forma estratégica e visualmente atrativa. O objetivo é transformar visitantes em clientes por meio de um design profissional, responsivo e orientado a resultados.

---

## 🧱 Estrutura do Projeto

```
landpage/
├── index.html
├── style.css
└── images/
    ├── logo.png
    ├── note-e-cel.png
    ├── tela-codigo.png
    ├── desenvolvimento.png
    ├── implantacao.png
    ├── design.png
    ├── otimização.png
    ├── evolucao.png
    ├── suporte.png
    ├── ball1.png
    ├── ball2.png
    ├── ball3.png
    ├── celular-amarelo.png
    ├── celular-preto.png
    ├── views.png
    └── perfomance.png
```

---

## 🗂️ Seções da Página

### 🏠 Hero — Tela Inicial (`#inicio`)
Apresentação principal com headline de impacto, subtítulo explicativo e dois botões de chamada para ação:
- **Nossos Serviços** — rola para a seção de serviços
- **Fale Conosco** — abre contato

### ⚙️ Serviços (`#service`)
Exibe as soluções tecnológicas oferecidas em um grid de 2 colunas com ícone, título e descrição:

| Serviço | Descrição |
|---|---|
| 💻 Desenvolvimento Web | Landing pages responsivas para todos os dispositivos |
| 🤝 Implantação | Deploy rápido sem impacto na produtividade |
| 🎨 Design UI/UX | Interfaces intuitivas focadas em conversão |
| 🔍 Otimização | SEO para melhor posicionamento nos buscadores |
| 📈 Melhorias | Atualizações com novas funções e relatórios |
| 🎧 Suporte | Atendimento rápido 24/7 |

### 💥 Impacto (`#impacto`)
Seção de CTA que evidencia os riscos de uma landing page mal projetada:
- Prejuízo à credibilidade
- Perda de espaço no mercado digital
- Impacto negativo nas vendas

Inclui mockups fictícios de celulares e gráficos de performance para reforço visual.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica da página
- **CSS3** — Estilização, layout e responsividade
  - Flexbox
  - CSS Grid
  - `position: sticky` na navbar
  - `backdrop-filter: blur` no header
  - Gradientes e `box-shadow` para efeitos visuais
- **Google Fonts**
  - [Montserrat](https://fonts.google.com/specimen/Montserrat)
  - [Playfair Display](https://fonts.google.com/specimen/Playfair+Display)

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|---|---|---|
| Amarelo destaque | `#fec103` | Botões, spans, linha separadora |
| Preto | `#000000` | Textos, botões primários |
| Branco | `#ffffff` | Fundo, textos em contraste |

---

## 🧭 Navegação

A navbar é fixa (`sticky`) no topo da página com links âncora para cada seção:

```
Inicio → #inicio
Serviços → #service
Impacto → #impacto
Contato → (a definir)
```

---

## 🚀 Como Executar

1. Clone ou baixe o repositório
2. Certifique-se de que a pasta `images/` está presente com todos os assets
3. Abra o arquivo `index.html` diretamente no navegador

```bash
# Exemplo com Live Server (VS Code)
# Instale a extensão Live Server e clique em "Go Live"
```

---

## 👨‍💻 Autor

**Caio Henrique Marques Dos Santos**  
RA: R982IG7

---

## 📄 Licença

Este projeto foi desenvolvido para fins acadêmicos.
Ainda não concluido!