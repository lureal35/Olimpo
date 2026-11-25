# Relatório e Planejamento de SEO — Projeto Olimpo

**URL Publicada:** `https://lureal35.github.io/Olimpo/`  
**Repositório / Escopo:** 5 páginas estáticas (`index.html`, `titans.html`, `deuses.html`, `historia.html`, `livros.html`)

---

## 1. Palavras-Chave Estratégicas (3 Principais do Tema)

1. **Mitologia Grega** *(Palavra-chave cabeça / principal — trabalhada na Home e como âncora temática em todas as páginas)*
2. **Deuses do Olimpo** *(Palavra-chave secundária de alta busca — focada em `deuses.html` e interligada nas demais)*
3. **Titãs da Mitologia Grega** *(Palavra-chave de cauda média — focada em `titans.html` e contextualizada em `historia.html`)*

---

## 2. Decisões Técnicas e Otimizações Tomadas

### On-Page SEO e Meta Tags
* **Titles e Meta Descriptions únicos:** Cada uma das 5 páginas recebeu `<title>` (entre 55 e 60 caracteres) e `<meta name="description">` (entre 145 e 160 caracteres) exclusivos, corrigindo falhas de preenchimento e erros ortográficos anteriores.
* **Canonical e Favicon:** Adicionada `<link rel="canonical">` com a URL absoluta do GitHub Pages em todas as páginas para evitar duplicidade de indexação, além de `<link rel="icon">`.
* **Open Graph Completo:** Implementadas as propriedades `og:locale`, `og:type`, `og:site_name`, `og:title`, `og:description`, `og:url` e `og:image` apontando para banner em formato `1200×630` (`og-banner.webp`).

### Dados Estruturados (Schema.org / JSON-LD)
* Inserido bloco `<script type="application/ld+json">` em todas as páginas (`WebSite` na `index.html`, `CollectionPage` em `livros.html` e `Article` nas páginas internas), devidamente validado no **Schema Markup Validator** (`validator.schema.org`).

### Arquitetura, Crawling e Links Internos
* **`robots.txt` e `sitemap.xml`:** Limpeza de regras residuais no `robots.txt`, mantendo a liberação total aos crawlers e o apontamento direto para o `sitemap.xml` atualizado na raiz.
* **Linkagem Interna Descritiva:** Substituição de textos âncora genéricos por links contextuais entre `index.html`, `titans.html`, `deuses.html`, `historia.html` e `livros.html`.

### Performance, Acessibilidade e Imagens
* **Formato e Dimensões:** Padronização das imagens para `.webp`, definição explícita dos atributos `width` e `height` (evitando *Cumulative Layout Shift* - CLS) e carregamento tardio com `loading="lazy"` nas imagens abaixo da primeira dobra.
* **Semântica e Acessibilidade:** Correção da estrutura HTML inválida (movendo tags `<img>` para dentro de `<li>`), adição de `aria-label` na navegação e preenchimento de textos alternativos (`alt`) descritivos em 100% das imagens.

---

## 3. Resultados Lighthouse (Dispositivo Móvel — Antes vs. Depois)

| Página | SEO (Antes) | SEO (Depois) | Acessibilidade (Antes) | Acessibilidade (Depois) |
| :--- | :---: | :---: | :---: | :---: |
| `index.html` | [XX] | [XX] (Meta: ≥ 95) | [XX] | [XX] (Meta: ≥ 90) |
| `titans.html` | [XX] | [XX] (Meta: ≥ 95) | [XX] | [XX] (Meta: ≥ 90) |
| `deuses.html` | [XX] | [XX] (Meta: ≥ 95) | [XX] | [XX] (Meta: ≥ 90) |
| `historia.html` | [XX] | [XX] (Meta: ≥ 95) | [XX] | [XX] (Meta: ≥ 90) |
| `livros.html` | [XX] | [XX] (Meta: ≥ 95) | [XX] | [XX] (Meta: ≥ 90) |