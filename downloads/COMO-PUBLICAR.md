# Publicar na Hostinger

1. Baixe ADMAC-Hostinger.zip.
2. No hPanel, abra Sites → Gerenciar → Gerenciador de arquivos.
3. Entre em public_html do domínio correto. Preserve um backup do site anterior, se houver.
4. Envie o ZIP para public_html e extraia ali.
5. Confira que public_html/index.html e public_html/assets/ existem, sem uma pasta intermediária.
6. Caso a página padrão da hospedagem continue aparecendo, verifique se há index.php ou default.php da página inicial padrão; preserve um backup antes de removê-los.
7. Abra o domínio com HTTPS e confira página, fotos e vídeo.

Não precisa instalar Node.js, banco de dados ou executar build. O ZIP contém a página e somente os arquivos de mídia utilizados, incluindo o vídeo e a miniatura dos pastores.

Os metadados de compartilhamento ainda apontam para o endereço da prévia no GitHub Pages. Informe o domínio definitivo para atualizar canonical, og:url e URLs da miniatura antes do compartilhamento definitivo. O site pode ser carregado na Hostinger enquanto esse ajuste é preparado.

O pacote mantém o conteúdo da versão aprovada, incluindo a faixa de prévia para avaliação. O ZIP não publica o site automaticamente.
