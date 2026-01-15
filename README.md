# Orayon Docs

Documentação oficial da plataforma Orayon.

🌐 **Live**: [docs.orayon.com.br](https://docs.orayon.com.br)

## Stack

- [Mintlify](https://mintlify.com) - Plataforma de documentação
- MDX - Markdown com componentes React

## Estrutura

```
├── docs.json          # Configuração principal
├── index.mdx          # Página inicial
├── quickstart.mdx     # Guia rápido
├── development.mdx    # Guia de desenvolvimento
├── essentials/        # Guias de customização
├── ai-tools/          # Integrações com IA
├── api-reference/     # Documentação da API
├── logo/              # Logos SVG
└── images/            # Imagens e assets
```

## Desenvolvimento local

```bash
npm i -g mintlify
mintlify dev
```

## Cores da marca

| Cor | Hex |
|-----|-----|
| Primary | `#5636d1` |
| Light | `#7C5CE7` |
| Dark | `#4527A0` |
| Accent | `#e2498a` |

## Deploy

O deploy é automático via GitHub integration com Mintlify.
