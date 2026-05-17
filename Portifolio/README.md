# Portfólio — Desenvolvedor

Página estática pronta para publicar no **GitHub Pages**.

## Estrutura

```
portfolio/
├── index.html      # Conteúdo da página (edite textos e projetos aqui)
├── styles.css      # Design system completo (cores, fontes, espaçamentos)
└── script.js       # Interações (menu mobile, ano do rodapé)
```

## Como personalizar

### 1. Trocar cores, fontes e espaçamentos
Abra `styles.css` e edite as variáveis no topo (bloco `:root`).
Tudo é centralizado lá — basta mudar `--accent-1`, `--bg`, etc.

### 2. Adicionar / remover projetos
Em `index.html`, procure por `<!-- Card de projeto -->` na seção `#projetos`
e duplique o bloco `<article class="project-card">`.

### 3. Atualizar informações pessoais
- Nome, e-mail e redes: busque por `Seu Nome`, `voce@email.com`, `seu-usuario`.
- Bio e estatísticas: editáveis diretamente no HTML do hero.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `meu-portfolio`).
2. Suba os três arquivos (`index.html`, `styles.css`, `script.js`) na raiz.
3. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.
4. Sua página estará disponível em `https://seu-usuario.github.io/meu-portfolio/`.

Para usar como página pessoal principal (`https://seu-usuario.github.io`),
nomeie o repositório como `seu-usuario.github.io`.
