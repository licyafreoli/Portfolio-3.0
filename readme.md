# Portfólio — Lícya Oliveira

Portfólio estático de desenvolvimento full stack e design, construído com HTML, CSS e JavaScript puro. A experiência combina composição editorial, projetos selecionados, arquivo visual, tradução da interface e interações acessíveis sem dependências de execução.

## Estrutura

- `index.html` — conteúdo e estrutura semântica
- `styles.css` — identidade visual, layout, responsividade e estados de movimento reduzido
- `script.js` — navegação, traduções, filtros, lightbox, animações e formulário
- `imgs/` — imagens e previews dos projetos

## Executar localmente

O site pode ser aberto diretamente pelo `index.html`. Para testar em condições mais próximas da publicação, execute um servidor estático na raiz do projeto:

```bash
python -m http.server 4173
```

Depois acesse `http://localhost:4173`.

## Publicar

### GitHub Pages

1. Envie os arquivos para a branch principal do repositório.
2. Em **Settings → Pages**, selecione **Deploy from a branch**.
3. Escolha a branch principal e a pasta `/root`.

### Vercel ou Netlify

Importe o repositório como site estático. Não é necessário comando de build; o diretório de publicação é a raiz do projeto.

## Recursos

- layout responsivo para desktop, tablet e celular;
- navegação por teclado, link para pular ao conteúdo e estados de foco;
- suporte a `prefers-reduced-motion`;
- idiomas PT, EN, ES, FR e IT;
- filtros para projetos e galeria com lightbox;
- formulário integrado ao endpoint existente do Google Apps Script;
- Instagram pessoal: [@freolitech](https://instagram.com/freolitech).

## Observações

As imagens devem permanecer dentro de `imgs/`, preservando os nomes referenciados no HTML. O projeto não depende do conteúdo de `package.json` para ser executado ou publicado como site estático.
