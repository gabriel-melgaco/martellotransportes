# Martello Guinchos e Transportes — Landing Page

Landing page institucional da **Martello Guinchos e Transportes**, empresa especializada em transporte veicular, reboque 24 horas e logística automotiva com cobertura em todo o Brasil, sediada em Cascavel – PR.

## Sobre o Projeto

Site desenvolvido para apresentar os serviços e valores da empresa, facilitar o contato via WhatsApp e reforçar a presença digital nos mecanismos de busca (SEO local).

## Funcionalidades

- **Hero section** com chamada para orçamento via WhatsApp
- **Sobre a empresa** com lista de serviços oferecidos
- **Nossos Valores** — missão e diferenciais da empresa
- **Galeria** com carrossel de 9 imagens da frota
- **Rodapé** com endereço, mapa integrado do Google Maps e links para redes sociais
- **Botão flutuante** de WhatsApp em todas as páginas
- **Botão "Voltar ao topo"** com scroll suave
- **SEO** com Schema.org (LocalBusiness), Open Graph, sitemap e Google Site Verification

## Tecnologias Utilizadas

- HTML5 e CSS3 (sem frameworks)
- JavaScript (jQuery 3.6)
- [Ionicons](https://ionic.io/ionicons) para ícones
- [Font Awesome](https://fontawesome.com/) para ícones de redes sociais e WhatsApp
- Google Fonts (Oswald + Rubik)
- Google Maps Embed API
- Deploy via [Render](https://render.com)

## Estrutura de Arquivos

```
landing_page/
├── index.html
├── favicon.svg
├── sitemap.xml
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── script.js
    └── images/
        ├── logo-removebg-preview.png
        ├── hero-banner.png
        ├── about-banner.jpg
        └── ... (imagens da galeria)
```

## Como Rodar Localmente

Não há dependências de build. Basta abrir o arquivo `index.html` em qualquer navegador:

```bash
# Opção 1 — abrir diretamente
xdg-open index.html

# Opção 2 — servidor local com Python
python3 -m http.server 8000
# acesse http://localhost:8000
```

## Deploy

O site está hospedado no Render e pode ser acessado em:
**https://martellotransportes.onrender.com**

## Contato

- **WhatsApp:** (45) 99940-1870
- **Instagram:** [@martello_transportes](https://www.instagram.com/martello_transportes)
- **Facebook:** [Martello Transportes Cascavel](https://www.facebook.com/martellotransportescvel/)
- **Endereço:** Rua Guaraniaçu, 1008 – São Cristóvão, Cascavel – PR, CEP 85816-260

---

Desenvolvido por [MEG DEV](https://github.com/gabriel-melgaco)
