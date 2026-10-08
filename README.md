# Site Rafael Zaccari — versão revisada

Site estático responsivo para publicação no GitHub + Vercel.

## Estrutura
- `index.html`: página principal com hero institucional, nova seção R$600 mil, história (7 capítulos), Dafni, posicionamento, ecossistema, Instagram, palestras, caminhos e formulário.
- `comece/index.html`: URL `/comece/` para link da bio. `comece.html` também incluído para compatibilidade.
- `styles.css`, `script.js`, imagens e `posts.json` (referência de URLs).

## PENDÊNCIAS ANTES DE LANÇAMENTO DEFINITIVO
1. **Diagnóstico Ozare:** o briefing não informa o link final. Por segurança, o botão aponta ao site institucional ozare.com.br e avisa que o destino específico está pendente.
2. **Formulário:** o briefing não informa serviço de recebimento nem e-mail confirmado. O formulário coleta os 4 campos e abre um rascunho de e-mail para envio manual; não grava os dados nem confirma envio automático. `contato@rafaelzaccari.com.br` é um endereço provisório NÃO VALIDADO. Configurar Formspree, Resend, Vercel Function ou outro endpoint aprovado para submissão real.
3. **Palestras:** endereço de contato provisório a confirmar.
4. **Empresas 2 e 3:** informações não fornecidas, aparecem como aguardando definição.
5. **Posts:** 3 links corretos; cards editoriais sem thumbnails porque as capas não foram fornecidas. `posts.json` serve como referência; ainda não existe CMS/integração para editar sem código.
6. **Fotos adicionais:** briefing solicita fotos reais de bastidores e antigas, caso existam. Não foram fornecidas.
7. **Marca Ozare:** logo oficial não fornecido; não foi criado logo fictício.

## Publicação
Descompactar e enviar TODOS os arquivos e a pasta `comece` para a raiz do repositório. Não subir o ZIP como arquivo. O Vercel fará deploy automático se estiver conectado.
