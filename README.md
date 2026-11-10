# Static site package

Este projeto é uma página estática: não precisa de Node.js, npm ou etapa de build.
O arquivo de entrada é `index.html`; as pastas `css/`, `js/` e `images/` devem permanecer
na raiz do repositório.

## Antes de publicar

1. No `index.html`, procure por `id="cta-button"` e substitua `href="#"` pelo link
   real de destino. Altere também o texto `Access link pending`.
2. O player de vídeo continua hospedado externamente na ConverteAI. Confirme que o
   vídeo é seu/autorizado e que todo o conteúdo e as alegações exibidas nele são
   verdadeiros e comprováveis antes de publicar.
3. Confira se o link de destino, política de privacidade e informações comerciais
   estão corretos para a sua operação.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie o conteúdo desta pasta para a raiz do repositório (não envie uma pasta
   `vsl/` envolvendo os arquivos).
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois salve.

O GitHub Pages publicará o `index.html` automaticamente. Também é possível hospedar
esta pasta em qualquer serviço de hospedagem estática.

## Limpeza aplicada

- Removidos scripts que interceptavam o botão Voltar e redirecionavam o visitante.
- Removidos depoimentos/comentários com resultados financeiros não verificados.
- Removidos inicializadores de pixels/rastreamento e scripts de afiliado antigos.
- Removidos metadados e referências de descoberta do WordPress original.
- Mantidos os estilos, imagens, scripts de interface e a integração externa do player.
