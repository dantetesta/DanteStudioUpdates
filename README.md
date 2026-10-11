# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.13**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.13/Dante-Studio-0.9.13-macOS-universal.dmg): assinado e notarizado.
- [Windows x64 de teste](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.13/Dante-Studio-0.9.13-Windows-x64-setup.exe): instalação e atualização manual.

## Novidades desde a 0.9.12

- **Mac:** mover, redimensionar e recortar a captura de tela por take, preservando o original.
- **Mac:** propriedades ao selecionar, arraste da biblioteca para a timeline e grade automática ou 2/3/4 colunas.
- **Mac:** 432 emojis em sete categorias, com busca em português.
- Timeline mais compacta e campos sem contornos grossos.
- Só webcam com câmera central e transporte após iniciar a gravação.
- Capas de webcam a partir de 3s e exportações a partir de 5s, com tentativa de evitar quadros pretos.
- **Configurar YouTube** em Exportações: JSON OAuth Desktop do próprio projeto Google e manual. Credenciais/tokens no cofre do sistema; cada usuário autoriza sua própria conta. Testes isolados concluídos; login e envio real ainda precisam de validação com uma conta Google. Não há promessa de quantidade fixa de vídeos, monetização via API ou aprovação de projetos; quotas e restrições do Google se aplicam.
- Créditos com avatar, versão e Pix de apoio voluntário, com exibir/copiar.

## Plataformas e limites

**Mac:** universal para Apple Silicon e Intel, com atualização assinada. O canal ARM legado permanece na 0.9.0 como ponte. Vídeos sem metadados completos de cor, HDR, transparentes ou incompatíveis continuam usando o original na prévia. Composição e recorte da tela por take são exclusivos do Mac. SVG aceito é estático e convertido em imagem: scripts, animações, texto/fontes, filtros, imagens e referências externas não são suportados; não há edição por nós vetoriais.

**Windows:** captura/exportação nativas, versão de teste e atualização manual. Sem certificado Authenticode Dante Studio e sem atualização automática. Recursos visuais importados e suas transições, gráficos/SVG/biblioteca, música, títulos, chroma key, áudio dos recursos, equalização, limpeza de voz, prévias preparadas e desenhos nativos continuam indisponíveis. A mesma versão não significa paridade de funcionalidades.

Testes automatizados e mídia sintética verificam contratos, edição e exportação. Não equivalem a captura física, audição, sincronismo labial observado ou uso prolongado em todo hardware. Esta versão não adiciona remoção neural de ruído nem promete zero quadros perdidos. O diagnóstico de prévia não mede perdas durante a captura. A descoberta de uma atualização não comprova a substituição instalada completa.

Software gratuito. Fontes de desenvolvimento mantidas em repositório privado. Instaladores incluem somente runtime e metadados necessários; materiais de divulgação ficam separados.
