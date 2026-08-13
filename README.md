# Boss Library — Página de Vendas

Página de vendas estática do produto **Boss Library** da Comunidade Boss.

## Deploy via Vercel (recomendado)

1. Faça o clone deste repositório no GitHub
2. Acesse [vercel.com](https://vercel.com) e conecte sua conta GitHub
3. Clique em **Add New Project** → selecione este repositório
4. Clique em **Deploy** — nenhuma configuração adicional é necessária

O `vercel.json` já está configurado para roteamento correto.

## Personalização antes de publicar

- **Depoimentos**: Substitua os blocos `placeholder` na seção `#depoimentos` com prints ou textos reais de alunas
- **CTA Button**: Verifique se o link `https://pay.kiwify.com.br/LmE8ovC` é o link correto de afiliação para o aluno que vai usar
- **Imagens dos módulos**: As imagens de capa são carregadas da CDN da Kiwify — nenhuma ação necessária

## Estrutura

```
boss-library/
├── index.html    ← página completa (CSS e JS embutidos)
├── vercel.json   ← config de roteamento Vercel
└── README.md
```

## Identidade

- Paleta: cosmic dark (`#06000E`, `#7C3AED`, `#A855F7`, `#D8B4FE`, `#C9A84C`)
- Tipografia: Playfair Display (display) + Inter (corpo)
- Fonte: Google Fonts (CDN)
