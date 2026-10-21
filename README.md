# Site ADMAC

Site estático da Assembleia de Deus Ministério Aliança com Cristo.

## Prévia com GitHub Pages
Em Settings → Pages, selecione Deploy from a branch, branch main, pasta / (root), e Save. Após a conclusão da publicação, o endereço esperado é https://hugomorelli.github.io/admac-site/. Consulte o status no próprio GitHub; a existência dos arquivos não confirma publicação.

## Desenvolvimento
Abra index.html ou execute `python -m http.server 8080` nesta pasta. Sem framework, instalação ou compilação.

## Arquivos
- index.html: página, estilos e comportamento.
- assets/: logo, vídeo original, capa, foto original do casal pastoral e reserva gráfica.

## Estado da prévia
Layout aprovado preservado, vídeo real com controles e foto do casal pastoral incorporados. Validação no Chromium em desktop e celular. Imagens ilustrativas externas mantêm as referências originais e possuem reserva gráfica caso não carreguem. Antes da entrega definitiva, substituir por fotos próprias ou adequadamente licenciadas.

Pendentes: foto individual para a programação, fotos da igreja e galeria, legendas/transcrição do vídeo e confirmação da denominação do bairro. Mapa é ilustrativo; o botão abre busca do endereço no Google Maps. Não há credenciais neste projeto.

## Hostinger
Copie index.html, .nojekyll (opcional na Hostinger) e assets/ para a raiz pública da hospedagem. Preserve um backup de qualquer site existente antes de substituí-lo.
