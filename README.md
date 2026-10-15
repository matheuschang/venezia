# POPUP MAIL ♡ — GitHub Pages

Publique `index.html` na raiz do repositório e ative Settings > Pages > Deploy from a branch (main / root).

## Mensagens
No `index.html`, edite `const MENSAGENS = [...]`.
A lista está da janela mais funda até a mais sobreposta: texto 10 no fundo; texto 1 no topo.
Todas as barras de título mostram **Nova Mensagem**. As 15 janelas incluem 9 mensagens de texto, 1 janela com player e 5 com imagens (33,3% do total).

## Imagens
Crie a pasta `imagens/` e adicione `foto1.jpg`, `foto2.jpg`, `foto3.jpg`, `foto4.jpg`, `foto5.jpg`, ou mude os caminhos na lista `MENSAGENS`. Enquanto não forem adicionadas, aparecem ilustrações provisórias.

## Música / vídeo
Crie a pasta `midia/` e coloque um arquivo `musica.mp4` (áudio contido em MP4/AAC) ou, mais recomendado, `musica.mp3`, e altere `arquivo:'midia/musica.mp4'` para `arquivo:'midia/musica.mp3'`.
O player usa a trilha sonora do arquivo, mesmo quando é um vídeo; não mostra o vídeo. A reprodução depende de clique, conforme exigência de navegadores móveis. Não envie mídia sem autorização de uso.

## Nota de experiência
A janela do texto 10 é criada primeiro e fica na camada mais funda. O usuário pode arrastar janelas, então a ordem efetiva de leitura depende das interações. Para um efeito de descoberta mais previsível, evite arrastar a janela do fundo para frente.
