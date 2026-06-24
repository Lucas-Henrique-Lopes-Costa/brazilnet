# BrazilNet Coworking — Website

Landing page institucional premium para a **BrazilNet Coworking · Escritório Virtual**, na Aldeota, Fortaleza – CE.

Site de página única (single-page), 100% estático, focado em branding, autoridade e geração de leads.

## Stack

- **HTML semântico** + **Tailwind CSS** (CDN)
- **GSAP + ScrollTrigger** — animações de entrada e parallax do hero
- **Lenis** — scroll suave
- **AOS** — scroll reveal das seções
- **Swiper** — carrossel de depoimentos
- **GLightbox** — galeria com lightbox e zoom
- **Vanilla-Tilt** — microinterações nos cards de vidro
- Contadores numéricos animados (implementação própria, leve)

## Identidade visual

Extraída do briefing e da identidade da marca:

- **Cor primária:** Teal `#3DA8A8` (logo BrazilNet)
- **Fundo:** dark teal `#0C1716`
- **Tipografia:** Sora (display) + Manrope (texto)

## Conteúdo

Todo o conteúdo (serviços, vantagens, história, contato) vem do briefing em `briefing/`.
As fotos são reais dos espaços, em `assets/img/`.

### Contato
- WhatsApp: (85) 98956-8807
- Telefone: (85) 98180-5678
- Instagram: [@escritoriovirtualbrazilnet](https://instagram.com/escritoriovirtualbrazilnet)
- Endereço: Av. Santos Dumont, 2789 · 10º andar — Aldeota, Fortaleza – CE · 60150-161

## SEO

HTML semântico, hierarquia de headings, Open Graph, Twitter Cards, Schema.org
(`ProfessionalService`), `robots.txt` e `sitemap.xml`.

## Como rodar

É um site estático. Basta servir a pasta:

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## Estrutura

```
index.html              # página completa (estrutura, estilos e scripts)
robots.txt / sitemap.xml
assets/
  brand/                # favicon e logo
  img/                  # fotos reais dos espaços
briefing/               # material de origem (briefing, identidade, fotos)
ref/                    # referências de design e copywriting
```
