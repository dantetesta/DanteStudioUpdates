# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.15**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.15/Dante-Studio-0.9.15-macOS-universal.dmg): assinado e notarizado.
- [Windows x64 de teste](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.15/Dante-Studio-0.9.15-Windows-x64-setup.exe): instalação e atualização manual.

## Novidades desde a 0.9.13

- **Versão correta no rodapé:** o número acompanha automaticamente a versão do aplicativo. Corrige o rótulo 0.9.12 que aparecia por engano na 0.9.13.
- **Capa para o YouTube:** recorte 16:9, arraste, zoom e centralização; otimização automática para JPEG 1280 × 720 antes do envio.
- **Progresso em destaque:** ao enviar, o formulário dá lugar à porcentagem, dados transferidos, etapas e cancelamento.
- **Selo Enviado ao YouTube:** identifica cada exportação após confirmação do recebimento pelo YouTube e persiste ao reiniciar. Indica envio, não publicação pública. Envios anteriores sem registro não são recuperados retroativamente.
- **Manual ilustrado:** 13 passos para configurar credenciais OAuth Desktop e conectar o próprio canal.

A integração usa autorização individual e cofre do sistema. Quotas, permissões e restrições do Google se aplicam. Monetização e verificações adicionais continuam no YouTube Studio. Os novos fluxos foram validados com testes isolados; não houve novo envio real durante a validação desta versão.

## Plataformas e limites

**Mac:** universal para Apple Silicon e Intel, com atualização assinada. O canal ARM legado permanece na 0.9.0 como ponte. Vídeos sem metadados completos de cor, HDR, transparentes ou incompatíveis continuam usando o original na prévia. Composição e recorte da tela por take são exclusivos do Mac. SVG aceito é estático e convertido em imagem: scripts, animações, texto/fontes, filtros, imagens e referências externas não são suportados; não há edição por nós vetoriais.

**Windows:** captura/exportação nativas, versão de teste e atualização manual. Sem certificado Authenticode Dante Studio e sem atualização automática. Recursos visuais importados e suas transições, gráficos/SVG/biblioteca, música, títulos, chroma key, áudio dos recursos, equalização, limpeza de voz, prévias preparadas e desenhos nativos continuam indisponíveis. A mesma versão não significa paridade de funcionalidades.

Testes automatizados e mídia sintética verificam contratos, edição e exportação. Não equivalem a captura física, audição, sincronismo labial observado ou uso prolongado em todo hardware. Esta versão não adiciona remoção neural de ruído nem promete zero quadros perdidos. O diagnóstico de prévia não mede perdas durante a captura. A descoberta de uma atualização não comprova a substituição instalada completa.

Software gratuito. Fontes de desenvolvimento mantidas em repositório privado. Instaladores incluem somente runtime e metadados necessários; materiais de divulgação ficam separados.
