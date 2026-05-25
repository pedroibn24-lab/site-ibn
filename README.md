# Grupo IBN — Site Institucional

Site institucional do **Grupo IBN (Instituto Brasileiro de Negócios)**, empresa especializada em treinamentos corporativos, consultoria e desenvolvimento organizacional.

## Visão Geral

Site estático de alta performance voltado para geração de leads B2B. Construído com HTML5, CSS3 e JavaScript puro — sem frameworks ou dependências de build — e otimizado para SEO, acessibilidade e segurança.

## Páginas

| Arquivo | Descrição |
|---|---|
| `index.html` | Homepage principal com apresentação da empresa, serviços e formulário de contato |
| `blog.html` | Listagem de artigos com filtro por categoria e leitura via modal |
| `treinamentos-personalizados.html` | Landing page dedicada aos treinamentos in-company |
| `privacidade-e-termos.html` | Política de privacidade e termos de uso |

## Tecnologias

- **HTML5** — Markup semântico com ARIA para acessibilidade
- **CSS3** — 3.000+ linhas de estilo customizado com variáveis CSS, Flexbox e Grid
- **JavaScript (Vanilla)** — Sem frameworks; 530+ linhas cobrindo carrossel, animações, validação de formulário e integração com APIs
- **Apache (.htaccess)** — Configurações de segurança, cache e compressão GZIP
- **Google Fonts** — Libre Baskerville + DM Sans
- **WordPress REST API** — Consumo de posts para o blog
- **Git & GitHub** - Versionamento de código.
- **GitHub Actions** - Automatização de deploy via FTP diretamente para o cPanel.

## Funcionalidades

- Carrossel de serviços com rotação automática a cada 6s
- Animações de scroll reveal via Intersection Observer API
- Efeito parallax em seções de background
- Formulário de contato com validação client-side e envio via WhatsApp
- Modal de leitura de artigos do blog com sanitização de HTML
- Filtro de posts por categoria
- Menu responsivo com hamburger para mobile
- Localização integrada com Google Maps embed

## Segurança

- Headers HTTP configurados no `.htaccess`: CSP, HSTS, X-Frame-Options, X-Content-Type-Options
- Sanitizador de HTML (whitelist) para conteúdo externo do blog
- Redirecionamento forçado para HTTPS
- `rel="noopener noreferrer"` em todos os links externos

## Performance

- Imagens com `loading="lazy"` e `decoding="async"`
- Script carregado com `defer`
- Fontes carregadas de forma não-bloqueante
- Cache de longa duração para assets estáticos via `.htaccess`
- Compressão GZIP habilitada no servidor
- Utilizando imagens comprimidas em .webp

## SEO

- Meta tags Open Graph para compartilhamento em redes sociais
- `sitemap.xml` e `robots.txt` configurados
- URLs canônicas em todas as páginas
- Hierarquia de headings semântica


O site é hospedado via **cPanel** em servidor Apache. 

O conteúdo está sob direitos autorais, a empresa não autoriza a publicação do site de forma indevida.
