# DOCUMENTAÇÃO MESTRE: PADRÃO OURO - FLAG PAGE (V.2026)
> **STATUS:** DOCUMENTO DEFINITIVO E ÚNICO (FONTE DA VERDADE)
> **REFERÊNCIA DE ESTRUTURA:** `c:\Users\Vinicius\.gemini\antigravity\scratch\optiplax-na\index.html`

Este documento consolida e substitui todas as documentações anteriores. Ele define a estrutura rígida "Padrão Ouro" para a criação de **Flag Pages de Alta Conversão**.

---

## 🚨 REGRAS INVIOLÁVEIS DE CONTEÚDO E ESTRUTURA

### 1. Regra da Relevância e Filtragem (O Filtro de Ouro)
Independente da quantidade de texto, estudos científicos ou informações detalhadas fornecidas sobre o produto:
*   **FILTRO:** Você deve extrair apenas o que se encaixa na estrutura de 10 seções abaixo.
*   **DESCARTE:** Informações redundantes ou que não tenham lugar nas seções pré-definidas (ex: história da empresa, missões complexas, blogs) devem ser ignoradas.

### 2. Regra de Expansão Zero (Proibição de Novas Seções)
*   **ESTRUTURA FIXA:** É estritamente proibido criar novas seções (ex: "Como Funciona", "Estudos Clínicos", "Equipe Médica").
*   **ADAPTAÇÃO:** Se houver uma informação vital que não se encaixe diretamente, ela deve ser integrada como um **benefício** (na Benefits Grid), uma **pergunta** (no FAQ) ou um **parágrafo** (na Hero/Final CTA).

---

## 🔟 ESTRUTURA DAS 10 SEÇÕES (ORDEM OBRIGATÓRIA)

1.  **HEADER (Fixo):** Fundo branco, **APENAS** a Logo centralizada. Altura ~25px. Sem menus.
2.  **HERO SECTION:** 
    *   *Fundo:* Azul Claro Suave (`#EBF2FF`).
    *   *Hierarquia:* Imagem Hero (images/hero.webp) -> Headline H1 -> Texto de Apoio.
3.  **TRUST BAR:** Faixa Navy Blue com Ícones Brancos/Azuis (Benefícios rápidos tipo "Vision Support").
4.  **FLAG SECTION (Geolocalização):** 
    *   *Posição:* SEMPRE a segunda seção de conteúdo (logo após o Trust Bar).
    *   *Conteúdo:* Grid de 4 Cards (USA, CA, NZ, AU) com link direto para o checkout/oferta.
5.  **INGREDIENTS / BENEFITS:** Grid 3x2 (ou similar) mostrando os diferenciais do produto.
6.  **BONUSES:** Cards de bônus gratuitos (empilhamento vertical ou grid harmônico).
7.  **REVIEWS:** Prova social real com estrelas verdes, badge "Verified" e autor com avatar.
8.  **FAQ:** Acordeão interativo para eliminar objeções (Envio, Garantia, Segurança).
9.  **FINAL CTA:** Chamada de urgência centralizada antes do rodapé.
10. **FOOTER (Compliance):**
    *   Rodapé cinza com links legais obrigatórios.
    *   **MODAIS:** Todos os links (Privacy, Terms, Shipping) devem abrir em Modais internos (Overlay), nunca em nova página ou recarregando o site.

---

## 🎨 DESIGN SYSTEM & TIPOGRAFIA

*   **Fonte:** **Inter** (Google Fonts) para TUDO. Sans-serif puro. Títulos em Bold (700-800).
*   **Paleta de Cores Premium:**
    *   `Navy (#34436E)` - Títulos e Botões Premium.
    *   `Navy Dark (#1E2D50)` - Trust Bar e Hovers.
    *   `Green (#2EAD6B)` - Badges de Estoque e Estrelas.
    *   `Background (#FFFFFF / #EBF2FF)` - Alternância de seções.
*   **Botão Premium:** Arredondado (Pill), cor Navy, ícone de seta, efeito Hover com elevação.

---

## 🛠️ REGRAS TÉCNICAS E PASTA DE IMAGENS

1.  **PASTA IMAGES (Regra de Ouro):**
    *   TODAS as fotos/logos devem estar dentro da pasta `images/`.
    *   FORMATO OBRIGATÓRIO: **.webp**.
    *   ARQUIVOS PADRÃO: `images/logo.webp`, `images/hero.webp`, `images/product.webp`.
2.  **SEO & SERP:**
    *   Título de página com foco em benefício principal + nome do produto.
    *   Meta Description orientada a conversão.
    *   Open Graph (OG Tags) completo para Facebook/WhatsApp.
    *   Schema.org JSON-LD (Product & Organization) incluído e validado.
3.  **BOTÕES DE CHECKOUT:**
    *   Todos os botões da página devem levar ao mesmo link de oferta fornecido, exceto os links do rodapé que abrem modais.

---

## 📋 CHECKLIST DE CRIAÇÃO (PROCESSO)
1.  Ignorar textos não-relevantes.
2.  Extrair Benefícios, FAQ e Prova Social do texto bruto.
3.  Gerar HTML/CSS em um único arquivo `index.html`.
4.  Garantir que o rodapé abra modais via JS simples (sem dependências externas).
5.  Validar tipografia Inter e formato WebP das imagens.

**Este documento revoga qualquer instrução anterior e serve como o guia definitivo para todas as Landing Pages solicitadas.**
