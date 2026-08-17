# Contech — landing page

Landing page da **Contech**, empresa de software sob medida. Mostra o
[Convito](https://convito-nine.vercel.app/) (produto próprio, já usado em
50+ festas) como prova de execução e capta clientes para consultoria de
sistemas sob medida.

## Stack

Página estática, um único arquivo (`index.html`), sem build nem
dependências:

- HTML + CSS + JavaScript puro (vanilla)
- Fontes ([Unbounded](https://fonts.google.com/specimen/Unbounded),
  [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans),
  [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono)) e o
  ícone do Convito embutidos como `data:` URI — a página funciona offline,
  sem chamadas externas
- Calculadora de excedente interativa, reproduzindo ao vivo a mesma regra
  de negócio do [Convito](https://github.com/maiconqatech/Convito)
  (`excedente = max(0, confirmados − incluídos)`)
- Tema claro/escuro automático (`prefers-color-scheme`)
- Anima confete no hero via `<canvas>`, respeitando
  `prefers-reduced-motion`

## Rodando localmente

Não precisa de servidor nem instalação — é um único HTML autocontido:

```bash
# Windows
start index.html

# ou simplesmente abra o arquivo no navegador
```

## Deploy

Como é um HTML estático único, pode ser publicado em qualquer hospedagem
estática sem configuração:

- **GitHub Pages**: Settings → Pages → Deploy from branch (`main`, pasta
  raiz)
- **Vercel / Netlify**: importe o repositório, sem build command

## Contato

WhatsApp: [(15) 99734-1422](https://wa.me/5515997341422)
