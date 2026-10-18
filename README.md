# Contatos do Grupo

Pagina estatica (HTML + CSS) com os LinkedIns do grupo, feita para ser aberta via QR Code.

## Estrutura

```
contatos-grupo/
├── index.html          # conteudo da pagina (nomes, links)
├── css/
│   └── style.css       # visual (cores, layout)
├── assets/
│   └── img/            # fotos e logo
└── README.md
```

## Como editar
- Nomes, cargos e links do LinkedIn: `index.html`
- Cores: variaveis no topo de `css/style.css`
- Fotos: salve em `assets/img/` com o mesmo nome usado no `index.html`

## Como publicar
- **GitHub Pages:** suba a pasta para um repositorio, va em Settings > Pages e escolha a branch `main`.
- **Vercel:** importe o repositorio (ou arraste a pasta). Nao precisa de configuracao.
