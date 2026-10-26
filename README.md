# Portfólio · Jacó

Site pessoal de **Rameson Jacó** ([@JacobbV](https://github.com/JacobbV)): projetos, tecnologias, sobre e contato.

No ar em **<https://jacobbv.github.io/>**

## Estrutura

```
JacobbV.github.io/
├── index.html                      ← página inicial do portfólio
├── projetos/
│   └── fiado-do-cartao/
│       ├── index.html              ← apresentação do Fiado do Cartão
│       └── telas/*.webp            ← prints com dados de exemplo
├── .nojekyll
└── README.md
```

Os apps continuam nos repositórios deles e aparecem no mesmo domínio:

| Projeto | Apresentação | App |
|---|---|---|
| Fiado do Cartão | `/projetos/fiado-do-cartao/` | `/fiado-do-cartao/` |
| Expedição Chapada | em breve | `/expedicao-chapada/` |
| Controle de Estoque para Food Service | em breve | uso interno |
| Controle Financeiro | em breve | em repaginação |

## Como colocar seus contatos

No fim do `index.html` tem o bloco `CONTATOS`. Preencha só o que quiser mostrar; o que ficar vazio (`''`) não aparece no site.

```js
const CONTATOS = {
  github:    'JacobbV',
  email:     'seuemail@gmail.com',
  whatsapp:  '5583999999999',   // 55 + DDD + número
  linkedin:  'seu-usuario',     // final de linkedin.com/in/...
  instagram: 'seu_usuario'      // sem @
};
```

## Como adicionar um projeto novo

1. Crie a pasta `projetos/nome-do-projeto/` com um `index.html` e as imagens.
2. Na página inicial, troque o "Apresentação em breve" do card pelo link `projetos/nome-do-projeto/index.html`.
3. `git add .`, `git commit` e `git push`.

## Créditos

| Recurso | Uso | Licença |
|---|---|---|
| [Unbounded](https://fonts.google.com/specimen/Unbounded), [Figtree](https://fonts.google.com/specimen/Figtree), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono), [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) | Tipografia, via Google Fonts | [SIL Open Font License 1.1](https://openfontlicense.org/) |
| Ícone do GitHub | Botões de link | [Diretrizes de marca do GitHub](https://github.com/logos) |
| GitHub Pages | Hospedagem | [Termos do GitHub](https://docs.github.com/pt/site-policy/github-terms/github-terms-of-service) |

Ilustrações dos cards e layout feitos para este site. Os prints usam dados fictícios.

## Histórico de versões

| Versão | Data | Mudanças |
|---|---|---|
| v1.0 | 26/10/2026 | Primeira versão: início, projetos, tecnologias, sobre, contato e apresentação do Fiado do Cartão |

© 2026 Rameson Jacó.
