# 🐆💛 Yellow — Açaí & Sorvetes

Website single-page profissional da sorveteria **Yellow**, construído em um único arquivo HTML.

> **"O melhor açaí e sorvete agora tem Cor! Yellow!"**

## 📁 Versões disponíveis

| Versão | Arquivo | Cor principal | Mascote |
|---|---|---|---|
| **V1** | `index.html` | Amarelo + roxo açaí (50/50) | Tili, a tigresa de óculos |
| **V2** | `v2/index.html` | **Amarelo dominante** (roxo só como acento de açaí; preto das manchas como contraste) | **Yara, a onça-pintada** — sorridente, segurando sorvete de casquinha na pata direita |

A V2 segue o documento oficial da mascote: onça-pintada cartoonizada com pelagem dourada e
rosetas pretas, olhos expressivos, sobrancelhas, bochechas coradas e pose oferecendo o produto.
Inclui também uma seção "Yara, a onça-pintada" explicando o significado da mascote
(identidade brasileira, força, agilidade e conexão com o público familiar).

## 🚀 Como usar

1. Baixe o arquivo da versão escolhida (`index.html` ou `v2/index.html`).
2. Abra direto no navegador (duplo clique) — **precisa de internet** na primeira vez, pois Tailwind CSS, Alpine.js e a fonte Inter são carregados via CDN.
3. Para publicar, envie o arquivo para qualquer hospedagem estática: **Netlify, Vercel, GitHub Pages, Cloudflare Pages** ou o cPanel do seu provedor.

## 🎨 Identidade visual

| Elemento | V1 | V2 |
|---|---|---|
| Amarelo vibrante (letreiro) | `#FFC400` | `#FFC400` (cor principal) |
| Dourado da pelagem | — | `#F0A400` |
| Amarelo-laranja de apoio | `#FFAA00` | `#FFAA00` |
| Roxo açaí | `#6D28D9` (cor de destaque) | `#6D28D9` (apenas acento no card/sorvete de açaí) |
| Contraste escuro | Roxo `#4C1D95` / `#2E1065` | Preto-café `#201500` (manchas da onça) |
| Fundo dark mode | Roxo quase-preto `#2E1065` | Marrom quase-preto `#171104` |
| Branco-creme | `#FFFDF4` | `#FFFDF4` |
| Fonte | Inter (Google Fonts) | Inter (Google Fonts) |
| Mascote | **Tili**, tigresa de óculos (SVG inline) | **Yara**, onça-pintada com casquinha (SVG inline) |

## ✏️ O que personalizar antes de publicar

- **WhatsApp**: troque `https://wa.me/5500000000000` pelo número real (formato: `55` + DDD + número).
- **Endereço e horário**: edite os placeholders no rodapé (seção "Visite a gente").
- **Depoimentos**: substitua os exemplos por avaliações reais dos seus clientes (Google/iFood).
- **Redes sociais**: adicione os links do Instagram/Facebook no rodapé.
- **Fotos reais**: quando tiver fotos profissionais da loja, dos açaís e dos pets, substitua os painéis ilustrativos das seções Buffet e Gelato Pet.

## 🧩 Estrutura do site

1. **Navbar fixa** — logo com a mascote, links com smooth scroll, toggle claro/escuro, menu mobile
2. **Hero** — slogan principal + selo "Melhor Buffet de açaí e sorvetes!!!!" + mascote animada
3. **Faixa marquee** — Açaí · Sorvete Doce · Sorvete Salgado · Fondue · Gelato Pet
4. **Cardápio** — 5 cards de produto
5. **Buffet** — destaque self-service + slogan da casa
6. **Gelato Pet** — "Aqui tem sorvete para o seu pet também"
7. **Espaço Kids** — playground para crianças
8. **Sobre** — história da marca + números
9. **Depoimentos** — espaço para avaliações reais
10. **CTA final** — WhatsApp + como chegar
11. **Footer** — contatos, horários e navegação
12. **Extras** — botão "voltar ao topo", animações ao rolar, SEO completo, dados estruturados (schema.org)

## 🛠️ Tecnologias

- HTML5 semântico
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Alpine.js](https://alpinejs.dev) via CDN (menu mobile, dark mode, voltar ao topo)
- Intersection Observer (animações de entrada)
- Zero dependências de build — um único arquivo
