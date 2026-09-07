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

## Fotos das peças

As peças aparecem como ilustrações até existir uma foto real. Basta colocar os
arquivos na pasta [`images/`](images/) seguindo os nomes descritos em
[`images/_LEIA-ME.md`](images/_LEIA-ME.md) — o site troca sozinho.

## Observações

- Contato: WhatsApp (11) 99660-3491 · maisonrivierr@gmail.com · @maisonrivier
- Pagamento on-line não está incluído — a finalização envia o pedido pelo WhatsApp
  (ou e-mail / cópia) para fechar pagamento e frete.
