# Dante Studio

Gravador e editor de tutoriais gratuito, com processamento local. Versão **0.9.10**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.10/Dante-Studio-0.9.10-macOS-universal.dmg): assinado e notarizado.
- [Windows x64 de teste — Windows 10 build 19041+ e Windows 11](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.10/Dante-Studio-0.9.10-Windows-x64-setup.exe): instalação e atualização manual por EXE.

## Novidades desde a 0.9.7

- Editor reorganizado: biblioteca à esquerda, player ao centro, propriedades à direita e timeline em toda a largura, com régua fixa durante a rolagem das trilhas.
- Barra superior compacta, painéis recolhíveis e propriedades mais claras para a seleção. Gravações tem identificação por texto; no Mac, Atualizações fecha ao clicar fora; o clique direito deixa de exibir Reload.
- Transições arrastadas com indicador pequeno e seleção ampliada. Arraste outra para substituir; Delete remove e Desfazer restaura. Prévia prepara os dois lados e aplica o efeito na camada escolhida.
- **Mac:** formas, setas desenhadas entre dois pontos, emojis e importação de SVG estático. Posição, tamanho e rotação; cor editável em formas/SVG, mantendo a transparência.
- **Mac:** biblioteca reutilizável entre projetos para imagens, GIFs, vídeos, áudio e gráficos. Busca, filtros, capas e escuta de áudio. Cada projeto recebe sua própria cópia; remover da biblioteca preserva as cópias já usadas e os originais.
- **Mac:** preparação cancelável de vídeos leves compatíveis e de até cinco segundos da transição selecionada. Originais preservados, cache limitado e exportação com a mídia original.
- Navegação rápida mantém o destino mais recente de busca do vídeo; diagnóstico opcional local, sem telemetria.

## Plataformas e limites

**Mac:** universal para Apple Silicon e Intel, com atualização assinada. O canal ARM legado permanece na 0.9.0 como ponte. Vídeos sem metadados completos de cor, HDR, transparentes ou incompatíveis continuam usando o original na prévia. SVG aceito é estático e convertido em imagem: scripts, animações, texto/fontes, filtros, imagens e referências externas não são suportados; não há edição por nós vetoriais.

**Windows:** captura/exportação nativas, versão de teste e atualização manual. Sem certificado Authenticode Dante Studio e sem atualização automática. Recursos visuais importados e suas transições, gráficos/SVG/biblioteca, música, títulos, chroma key, áudio dos recursos, equalização, limpeza de voz, prévias preparadas e desenhos nativos continuam indisponíveis. A mesma versão não significa paridade de funcionalidades.

Testes automatizados e mídia sintética verificam contratos, edição e exportação. Não equivalem a captura física, audição, sincronismo labial observado ou uso prolongado em todo hardware. Esta versão não adiciona remoção neural de ruído nem promete zero quadros perdidos. O diagnóstico de prévia não mede perdas durante a captura. A descoberta de uma atualização não comprova a substituição instalada completa.

Software gratuito. Fontes de desenvolvimento mantidas em repositório privado. Instaladores incluem somente runtime e metadados necessários; materiais de divulgação ficam separados.
