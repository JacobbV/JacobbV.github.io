# Portfólio · Jacó

Site pessoal de **Rameson Jacó** ([@JacobbV](https://github.com/JacobbV)): projetos, tecnologias, sobre e contato.

No ar em **<https://jacobbv.github.io/>**

## Estrutura

```
JacobbV.github.io/
├── index.html                      ← página inicial do portfólio
├── projetos/
│   ├── fiado-do-cartao/            ← apresentação do Fiado do Cartão
│   ├── expedicao-chapada/          ← apresentação da Expedição Chapada
│   └── controle-de-estoque/        ← apresentação do Controle de Estoque
│       (cada uma com index.html e telas/*.webp, prints com dados de exemplo)
├── og/                           ← cards de compartilhamento (1200×630) de cada página
├── .nojekyll
└── README.md
```

Os apps continuam nos repositórios deles e aparecem no mesmo domínio:

| Projeto | Apresentação | App |
|---|---|---|
| Fiado do Cartão | `/projetos/fiado-do-cartao/` | `/fiado-do-cartao/` |
| Expedição Chapada | `/projetos/expedicao-chapada/` | `/expedicao-chapada/` (com login) |
| Controle de Estoque para Food Service | `/projetos/controle-de-estoque/` | uso interno |
| Controle Financeiro | em breve | em repaginação |

## Como colocar seus contatos

No fim do `index.html` tem o bloco `CONTATOS`. Preencha só o que quiser mostrar; o que ficar vazio (`''`) não aparece no site.

```js
const CONTATOS = {
  github:    'JacobbV',
  email:     'seuemail@gmail.com',
  whatsapp:  '5583999999999',   // 55 + DDD + número
  linkedin:  'seu-usuario',     // final de linkedin.com/in/...
  instagram: 'seu_usuario',     // sem @
  facebook:  'seu.usuario'      // final de facebook.com/...
};
```

## Como adicionar um projeto novo

1. Crie a pasta `projetos/nome-do-projeto/` com um `index.html` e as imagens.
2. Na página inicial, troque o "Apresentação em breve" do card pelo link `projetos/nome-do-projeto/index.html`.
3. `git add .`, `git commit` e `git push`.

## Card de compartilhamento

Cada página tem uma imagem `og/*.jpg` (1200×630) e as tags `og:` e `twitter:` no `<head>`. É isso que faz aparecer o card bonito ao colar o link no WhatsApp, Telegram, LinkedIn ou Facebook.

Se trocar uma imagem e o WhatsApp continuar mostrando a antiga, mande o link com `?v=2` no final (ex.: `https://jacobbv.github.io/?v=2`): ele guarda a prévia em cache.

## Créditos

| Recurso | Uso | Licença |
|---|---|---|
| Unbounded, Figtree, JetBrains Mono, Bricolage Grotesque, Big Shoulders Display, Public Sans, Playfair Display e Plus Jakarta Sans | Tipografia, via Google Fonts | [SIL Open Font License 1.1](https://openfontlicense.org/) |
| [Inter](https://rsms.me/inter/), [Lora](https://fonts.google.com/specimen/Lora), DejaVu Sans Mono | Texto dos cards de compartilhamento (`og/`) | SIL OFL 1.1 / [licença DejaVu](https://dejavu-fonts.github.io/License.html) |
| Ícone do GitHub | Botões de link | [Diretrizes de marca do GitHub](https://github.com/logos) |
| GitHub Pages | Hospedagem | [Termos do GitHub](https://docs.github.com/pt/site-policy/github-terms/github-terms-of-service) |

Ilustrações dos cards e layout feitos para este site. Os prints usam dados fictícios.

## Histórico de versões

| Versão | Data | Mudanças |
|---|---|---|
| v1.2 | 26/10/2026 | LinkedIn no contato e cards de compartilhamento (WhatsApp, Telegram, LinkedIn) |
| v1.1 | 26/10/2026 | Apresentações da Expedição Chapada e do Controle de Estoque |
| v1.0 | 26/10/2026 | Primeira versão: início, projetos, tecnologias, sobre, contato e apresentação do Fiado do Cartão |

© 2026 Rameson Jacó.
