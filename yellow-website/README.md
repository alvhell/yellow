# 🐯💛 Yellow — Açaí & Sorvetes

Website single-page profissional da sorveteria **Yellow**, construído em um único arquivo HTML.

> **"O melhor açaí e sorvete agora tem Cor! Yellow!"**

## 🚀 Como usar

1. Baixe o arquivo `index.html`.
2. Abra direto no navegador (duplo clique) — **precisa de internet** na primeira vez, pois Tailwind CSS, Alpine.js e a fonte Inter são carregados via CDN.
3. Para publicar, envie o arquivo para qualquer hospedagem estática: **Netlify, Vercel, GitHub Pages, Cloudflare Pages** ou o cPanel do seu provedor.

## 🎨 Identidade visual

| Elemento | Valor |
|---|---|
| Amarelo vibrante (letreiro) | `#FFC400` |
| Amarelo-laranja de apoio | `#FFAA00` |
| Roxo açaí | `#6D28D9` |
| Roxo profundo | `#4C1D95` |
| Roxo quase-preto (dark mode) | `#2E1065` |
| Branco-creme | `#FFFDF4` |
| Fonte | Inter (Google Fonts) |
| Mascote | **Tili**, a tigresa de óculos (SVG inline — sem imagem externa) |

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
