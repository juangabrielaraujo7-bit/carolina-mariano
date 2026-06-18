# Estética Carolina Mariano — Landing Page

Landing page premium em **HTML, CSS e JavaScript puro**, focada em conversão via
WhatsApp para a Estética Carolina Mariano, na Freguesia do Ó, São Paulo.

## ✨ Destaques

- Design feminino, premium e sofisticado — base branca, **verde pastel** e **rosa claro**, com **dourado** em detalhes discretos.
- Cards modernos com efeito **glassmorphism** e micro-animações suaves (reveal on scroll).
- **Hero** com headline original, destaques da primeira dobra (Limpeza de Pele Coreana, Drenagem Linfática, Atendimento Personalizado, Bem-estar) e CTA de WhatsApp visível sem rolar.
- Seções: Hero · Credibilidade/Prova social · Benefícios · Procedimentos · Sobre · Depoimentos · Localização (mapa) · CTA final.
- **Botão flutuante de WhatsApp** e CTAs distribuídos pela página.
- **SEO completo**: meta tags, Open Graph, Twitter Card e **Schema.org `HealthAndBeautyBusiness`** (LocalBusiness) com avaliações reais.
- SEO local com referências naturais à **Freguesia do Ó** e região.
- Responsividade impecável (desktop, tablet e mobile) e alta performance (sem frameworks).

## 📁 Estrutura

```
.
├── index.html
├── styles.css
├── script.js
└── assets/
    └── images/
        ├── carolina-hero.png    (foto da Hero)
        ├── carolina-about.png   (foto da seção Sobre)
        ├── carolina-hero.svg    (placeholder de fallback)
        └── carolina-about.svg   (placeholder de fallback)
```

## 🖼️ Fotos da Carolina

As fotos reais da Carolina foram otimizadas para web (WebP + JPEG de fallback,
via `<picture>`), reduzindo de ~3,4MB para ~200KB no total:

- `carolina-hero.webp` / `carolina-hero.jpg` — foto da Hero
- `carolina-about.webp` / `carolina-about.jpg` — foto da seção Sobre

Caso algum desses arquivos esteja ausente, a página exibe automaticamente um
**placeholder elegante em SVG** (`carolina-hero.svg` / `carolina-about.svg`).

## 🚀 Como visualizar

Abra o `index.html` no navegador, ou rode um servidor local:

```bash
python3 -m http.server 8000
# acesse http://localhost:8000
```

## 📞 Contato configurado

- **WhatsApp:** (11) 99547-9683 → `https://wa.me/5511995479683`
- **Instagram:** [@mariano_stetic](https://instagram.com/mariano_stetic)
- **Endereço:** R. da Bica, 305 — Freguesia do Ó, São Paulo · SP · 02925-000
