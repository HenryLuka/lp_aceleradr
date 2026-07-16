# Acelera Dr — Landing Page

Landing page estática do **Acelera Dr**, ecossistema de marketing e atendimento com IA para médicos e dentistas.

## Stack

- HTML/CSS/JS único (`index.html`), sem build
- Animações: [GSAP 3](https://gsap.com) + ScrollTrigger (CDN)
- Smooth scroll: [Lenis](https://lenis.darkroom.engineering) (CDN)
- Fontes: Google Fonts (Sora + Inter)

## Deploy no Coolify

O projeto inclui `Dockerfile` (nginx:alpine) e `nginx.conf` prontos:

1. No Coolify, crie um novo recurso **Application** apontando para este repositório
2. Build Pack: **Dockerfile**
3. Porta exposta: **80**
4. Deploy 🚀

## Desenvolvimento local

```bash
python -m http.server 8777
# abra http://localhost:8777
```

---
Desenvolvido por [Henry Developer](https://henrydeveloper.space)
