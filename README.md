# Rafael Zaccari — site reconstruído

Projeto HTML/CSS/JS estático. A **home** é `index.html` na raiz. A página de bio é `comece/index.html`. Não há `comece.html` duplicado nem regras de reescrita do Vercel.

## Publicar corretamente

1. Crie um **repositório GitHub novo e vazio** (recomendado para isolar versões antigas).
2. **Extraia o ZIP** no computador. No GitHub, envie **o conteúdo da pasta extraída** (não a pasta-mãe e não o arquivo ZIP).
3. Confira que `index.html`, `styles.css`, `script.js` e a pasta `comece/` aparecem **na raiz** do repositório.
4. No Vercel: New Project → Import repositório novo → Framework Preset **Other** → Root Directory **./** → Deploy. Não defina Output Directory ou Build Command.
5. Teste `/`, `/#historia` e `/comece/`.

## Pendências do cliente

- Link específico do diagnóstico Ozare: atualmente o botão leva ao site institucional `https://ozare.com.br`.
- E-mail de palestras e lista de interesse: `contato@rafaelzaccari.com.br` é provisório. O formulário abre o aplicativo de e-mail, **não grava cadastros**. Para captação real, conectar um serviço de formulários ou backend.
- Empresas 2 e 3 do ecossistema ainda não informadas.
- Links de Instagram são clicáveis, mas sem capas originais dos posts.

## Arquivos

`index.html` home; `comece/index.html` página de bio; `styles.css` layout; `script.js` menu e formulário; quatro JPGs de fundo; `favicon.svg`.
