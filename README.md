# BR Imported — landing page

Landing page da BR Imported (Av. Dr. Maurício Cardoso, 1230, sala 1200, Novo Hamburgo/RS). Modelo para apresentação à loja.

- HTML estático, sem build: `index.html` + `img/`
- GSAP (ScrollTrigger, SplitText, Flip), Lenis e Three.js via CDN
- Intro: logo montada em 4 camadas (`img/lg-*.webp`) e animada com GSAP; a cortina preta está no HTML para não haver flash da página
- iPhones 3D procedurais em Three.js (18 Pro Max, 18 Pro, Air, 17 Pro Max, 17, 16e) com seletor de modelo e cor
- Mural de avaliações: conteúdo ilustrativo no array `WALL`; trocar pelas avaliações reais antes de publicar para o cliente
- Deploy automático na Vercel a cada push na `main`

Para rodar local: `npx serve .`
