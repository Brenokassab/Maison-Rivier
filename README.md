# Maison Rivier — Paris

Site institucional e loja da **Maison Rivier**, marca de moda masculina premium.
_Élégance. Discrétion. Intemporel._

Página única, sem build e sem dependências — todo o site está em [`index.html`](index.html).

## Recursos

- Identidade completa: brasão em SVG, tipografia Cinzel + Montserrat, tema claro e escuro
- **Coleção Heritage I** — 8 categorias (polos, camisetas, moletons, camisas Oxford, calças chino, bermudas, bonés, acessórios)
- **Loja funcional** — seleção de cor e tamanho, ilustração da peça que muda com a cor
- **Sacola** com persistência (`localStorage`), quantidade, subtotal e resumo de pedido
- História da marca, lookbook, selos de garantia
- Formulários de contato e newsletter com validação
- Responsivo, acessível (foco de teclado, `prefers-reduced-motion`)

## Ver localmente

Abra `index.html` no navegador — ou sirva a pasta:

```bash
python -m http.server
```

## Publicar (GitHub Pages)

Com o repositório no GitHub: **Settings → Pages → Branch: `main` / root**.
O site fica em `https://<usuario>.github.io/maison-rivier/`.

## Observações

- Pagamento on-line não está incluído — a finalização gera um resumo de pedido por e-mail/cópia.
- `atelier@maisonrivier.com` e `@maisonrivier` são placeholders.
