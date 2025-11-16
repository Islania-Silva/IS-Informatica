#📱 IS Informática – Assistência Técnica

Site institucional desenvolvido em HTML, CSS e JavaScript, seguindo a abordagem Mobile First.
O objetivo é apresentar serviços, valores, trabalhos realizados e facilitar o contato com clientes via WhatsApp e Instagram.

🚀 Sobre o Projeto

Este projeto foi criado como uma página institucional para uma loja de Assistência Técnica de Computadores, Notebooks e Celulares.
O layout foi planejado inicialmente para dispositivos móveis, garantindo melhor performance, legibilidade e usabilidade em telas pequenas.
Posteriormente, serão implementadas versões específicas para tablet, notebook e desktop.

📌 Funcionalidades
✔️ Mobile First

Todo o layout foi projetado primeiramente para telas pequenas.

O CSS possui media queries vazias preparadas para evolução do projeto:

600px

768px

1024px

1280px

1536px

✔️ Navegação suave

Links âncora usam scrollIntoView() para rolagem suave entre seções.

✔️ Menu moderno

Header com efeito glassmorphism (blur + transparência).

Botão fixo estilo CTA para WhatsApp.

✔️ Seção Hero

Texto destacando os principais serviços.

Vídeo demonstrativo com estilo responsive.

✔️ Galeria de Fotos

Grid responsivo para exibição dos serviços realizados.

✔️ Seção de Vídeos

Carrossel horizontal com vídeos de antes/depois de manutenções.

✔️ Tabela de Valores

Cards com preço, descrição e botão para contratar via WhatsApp.

✔️ Sobre

Missão e visão da empresa apresentadas de forma clara.

✔️ Contato

WhatsApp clicável

Instagram clicável

✔️ Depoimentos

Cards com feedbacks de clientes.

✔️ Footer Automático

O ano atual é inserido dinamicamente via JavaScript.

✔️ Fallback para imagens ausentes

Substitui imagens inexistentes por um placeholder SVG automático.

🛠 Tecnologias Utilizadas
Frontend

HTML5

CSS3

Variáveis CSS (:root)

Flexbox

Grid

Responsividade (Mobile First)

Scroll personalizado

Glassmorphism

JavaScript Vanilla

Atualização dinâmica do ano

Smooth Scroll

Fallback de imagens

Design / UI

Cores modernas baseadas em tema dark

Componentes reutilizáveis (cards, botões, grids)

Layout limpo inspirado em interfaces profissionais

```
📂 Estrutura do Projeto
/
├── index.html
├── style.css
├── global.css
├── assets/
│   ├── img/
│   └── videos/
└── README.md
```
!(assets/img/Captura de tela 2025-11-16 124558.png)

📸 Prévia das Seções

Header com logo + menu

Hero com chamada e vídeo

Galeria de Fotos

Vídeos com scroll horizontal

Tabela de Preços

Sobre (missão e visão)

Contato

Depoimentos

Footer automático

📱 Responsividade

O projeto segue Mobile First e será expandido usando as media queries já preparadas:

@media (min-width: 600px) { }

@media (min-width: 768px) { }

@media (min-width: 1024px) { }

@media (min-width: 1280px) { }

@media (min-width: 1536px) { }

🔧 Como Executar

Baixe ou clone o repositório

Abra o arquivo index.html em qualquer navegador

Para melhor experiência, teste no modo mobile do DevTools (F12)

📝 Licença

Projeto de uso pessoal/estudo.
Você pode modificar livremente para fins.

🙋‍♀️ Autor

IS Informática – Assistência Técnica
Criado com foco em agilidade, transparência e profissionalismo no atendimento.