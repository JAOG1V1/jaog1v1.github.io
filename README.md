<div align="center">
# 🎮 João Gabriel — Portfólio Pessoal
 
**Meu cantinho na internet: quem eu sou, o que eu curto e pra onde eu tô indo.**
 
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-no%20ar-2EC4B6?style=for-the-badge)
![Arquivo único](https://img.shields.io/badge/arquivo-%C3%BAnico-FF9F1C?style=for-the-badge)
 
### 🌐 Acesse o site publicado
 
**🗒️ [jaog1v1.github.io](https://jaog1v1.github.io)**
 
> *"Às vezes você cai, mas sempre tem um próximo round."*
 
</div>
---
 
## 📋 Sumário
 
- [👤 Sobre o Projeto](#-sobre-o-projeto)
- [🎨 Conceito de Design](#-conceito-de-design)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias Utilizadas](#%EF%B8%8F-tecnologias-utilizadas)
- [📁 Estrutura do Projeto](#-estrutura-do-projeto)
- [🚀 Como Executar](#-como-executar)
- [🗺️ Próximos Passos](#%EF%B8%8F-próximos-passos)
- [✍️ Autor](#%EF%B8%8F-autor)
- [🤖 Transparência e Ferramentas](#-transparência-e-ferramentas)
- [📜 Licença](#-licença)
---
 
## 👤 Sobre o Projeto
 
Este é o meu **site pessoal**. Tenho 15 anos e ainda estou descobrindo o que quero ser — então, em vez de fingir que já escolhi uma área, fiz um site sobre isso mesmo: **um caderno aberto, em constante rascunho**.
 
O site registra quem eu sou *agora*: meus hobbies (basquete, games, música, mangás), o que estou aprendendo, os projetos que já fiz e os sonhos que estão "colados na parede do futuro".
 
A ideia é que ele **cresça junto comigo**: cada curso concluído, medalha ou projeto novo vira uma atualização aqui.
 
---
 
## 🎨 Conceito de Design
 
O visual simula um **caderno escolar cheio de adesivos**:
 
| Elemento | Como aparece no site |
|---|---|
| 📓 Papel quadriculado | Fundo com grade desenhada em CSS puro |
| 🏷️ Adesivos | Cards com borda grossa, sombra colorida e leve rotação |
| 📸 Polaroid | Moldura de foto com fita adesiva no topo |
| 🗒️ Post-its | Sonhos, metas e o card "no momento…" em notinhas coloridas |
| 🖊️ Anotações à mão | Fonte manuscrita (Caveat) nas legendas e setas |
| 🖍️ Marca-texto | Destaques nos títulos, estilo caneta marcadora |
 
**Dois temas completos**, alternáveis pelo botão ☀️/🌙 no topo:
 
- 🌙 **Escuro (padrão)** — "caderno de papel preto com caneta gel"
- ☀️ **Claro** — caderno tradicional de papel branco
**Tipografias:** Bricolage Grotesque (títulos) · Instrument Sans (texto) · Caveat (manuscrita)
 
---
 
## ✨ Funcionalidades
 
- 🔄 **Palavra giratória** no título — "gamer 🎮", "nerd assumido 🤓", "dev front-end em formação 💻"... porque eu sou um pouco de tudo
- 🌙 **Tema claro/escuro** com transição suave e cores adaptadas
- 📌 **Card "no momento…"** — o que estou jogando, lendo e ouvindo agora, com data de atualização
- 🎧 **Player do Spotify** embutido, tocando a playlist oficial *This Is Skillet*
- 🥚 **Easter egg secreto** — existe. É só isso que eu vou falar. Boa sorte. 😏
- 🌪️ **Página 404 própria** — "essa página caiu fora da zona", com botão de voltar pro lobby
- 🏷️ **Logos oficiais das redes** ([Simple Icons](https://simpleicons.org)) em SVG embutido, adaptando-se ao tema
- 🔗 **Open Graph** — prévia bonita do link ao compartilhar no WhatsApp, Discord e redes
- 🎬 **Animações ao rolar** a página (Intersection Observer)
- 📦 **Arquivo único** — HTML, CSS, JS e até a imagem de perfil (em base64) num só `index.html`
- 📱 **Design responsivo** — funciona do celular ao desktop
- ♿ **Acessibilidade** — foco visível por teclado, `aria-label` nos controles e suporte a `prefers-reduced-motion`
- 🎮 **Favicon personalizado** em SVG
---
 
## 🛠️ Tecnologias Utilizadas
 
| Tecnologia | Uso no projeto |
|---|---|
| **HTML5** | Estrutura semântica (`<header>`, `<section>`, `<nav>`, `<footer>`) |
| **CSS3** | Variáveis customizadas (temas), Grid, Flexbox, animações, gradientes |
| **JavaScript (ES6+)** | Troca de tema, palavra giratória, animações de scroll, confete do easter egg |
| **SVG inline** | Rabiscos, favicon e logos oficiais das marcas (Simple Icons) |
| **Spotify Embed** | Player oficial com a playlist *This Is Skillet* |
| **Open Graph** | Meta tags de prévia do link para redes sociais |
| **Google Fonts** | Bricolage Grotesque, Instrument Sans e Caveat |
 
> ⚠️ **Sem frameworks** — só HTML, CSS e JavaScript puros.
 
---
 
## 📁 Estrutura do Projeto
 
```
jaog1v1.github.io/
├── 📄 index.html   # O site inteiro: HTML + CSS + JS + imagem, tudo num arquivo só
├── 🌪️ 404.html     # Página de erro personalizada (levada pela tempestade)
├── 🖼️ avatar.jpg   # (opcional) imagem usada na prévia do link
└── 📖 README.md    # Este arquivo
```
 
Simples assim. 😄
 
---
 
## 🚀 Como Executar
 
**Online (recomendado):** acesse **[jaog1v1.github.io](https://jaog1v1.github.io)**
 
**Localmente:**
 
```bash
git clone https://github.com/JAOG1V1/jaog1v1.github.io.git
```
 
Depois é só abrir o `index.html` em qualquer navegador moderno. Sem instalação, sem build, sem servidor.
 
💡 *Dica: pra conhecer a página 404, tenta acessar qualquer endereço que não existe, tipo `jaog1v1.github.io/banana`.* 🍌
 
---
 
## 🗺️ Próximos Passos
 
Como todo caderno aberto, sempre tem página em branco esperando:
 
- [ ] Trocar o avatar por uma foto de verdade 📸
- [ ] Adicionar novos certificados do Codifica Jovem conforme eu concluir os módulos
- [ ] Criar uma seção de mangás favoritos 📖
- [ ] Trocar o player pela minha própria playlist 🎧
- [ ] Registrar os próximos projetos e concursos
---
 
## ✍️ Autor
 
**João Gabriel Sabedra Vieira** — estudante, 15 anos, Douradina‑PR 🇧🇷
 
Em jornada pra virar dev. Construindo, errando e aprendendo. 🚀
 
| | |
|---|---|
| 💻 GitHub | [@JAOG1V1](https://github.com/JAOG1V1) |
| 📷 Instagram | [@joaogabrielsv2010](https://www.instagram.com/joaogabrielsv2010) |
| 🐦 X (Twitter) | [@Joaogabrielsv10](https://x.com/Joaogabrielsv10) |
| 🎬 TikTok | [@joaogabrielsv2010](https://www.tiktok.com/@joaogabrielsv2010) |
| 🎮 Steam | [Meu perfil](https://steamcommunity.com/profiles/76561199080371319/) |
| ✉️ E-mail | joaogabrielsabedra@gmail.com |
| 🌱 Projeto em destaque | [Agro Forte — Agrinho 2026](https://github.com/JAOG1V1/agrinho-2026) |
 
---
 
## 🤖 Transparência e Ferramentas
 
Acredito que a transparência faz parte de um desenvolvimento responsável — a mesma prática que adotei no [Agro Forte](https://github.com/JAOG1V1/agrinho-2026).
 
Este site foi desenvolvido por mim com auxílio de uma ferramenta de Inteligência Artificial (**Claude**, da Anthropic) como apoio ao aprendizado e à implementação.
 
**✍️ Da minha autoria:**
- Todo o conteúdo pessoal (quem eu sou, hobbies, projetos, sonhos)
- As decisões de estilo, tema e direção do site
- As respostas e ideias que moldaram cada seção
- A publicação e manutenção do projeto
**🤝 Onde utilizei IA como apoio:**
- Escrita e organização do código (HTML, CSS, JavaScript)
- Sugestões de design, acessibilidade e boas práticas
- Estruturação desta documentação
**🛠️ Outras ferramentas:** GitHub Pages (hospedagem), Git/GitHub (versionamento) e [Simple Icons](https://simpleicons.org) (logos oficiais das marcas).
 
---
 
## 📜 Licença
 
Projeto pessoal e educacional. O **código** é livre para estudo e inspiração. Os **textos e imagens pessoais** pertencem ao autor. 😉
 
---
 
<div align="center">
🗒️ *"Às vezes você cai, mas sempre tem um próximo round."*
 
**Rabiscado com carinho por João Gabriel ✦ Douradina‑PR ✦ 2026**
 
🥚 *psiu... o segredo tá em algum lugar do site.*
 
</div>
 
