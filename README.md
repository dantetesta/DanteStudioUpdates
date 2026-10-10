# Dante Studio

Gravador e editor de tutoriais gratuito, com processamento local. Versão **0.9.7**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.7/Dante-Studio-0.9.7-macOS-universal.dmg): assinado e notarizado.
- [Windows x64 de teste — Windows 10 build 19041+ e Windows 11](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.7/Dante-Studio-0.9.7-Windows-x64-setup.exe): atualização manual por EXE.

## Novidades da 0.9.7

- Divisões simples preservam reprodução contínua de áudio na prévia, sem reiniciar as fontes.
- Transições com miniatura pequena ao arrastar e alvos maiores nas divisões. Substituição e remoção continuam disponíveis.
- Opções da webcam afastadas da borda do take e abertura direta da aba Configurações.
- **Mac:** barra de desenho compacta, transporte acima, ferramentas em uma linha e cores abaixo. Clique repetido ou Esc desativa; sem OK/Cancelar/banner. Limpar apaga os traços e desativa.
- **Mac:** opção de incluir os controles na gravação abrange painel e bolinha; desligada, ambos ficam fora do vídeo. Os desenhos continuam gravados.
- **Mac:** fila limitada de captura absorve picos curtos e aguarda brevemente o encoder, reduzindo descartes evitáveis. Perdas reais continuam sendo informadas.

## Plataformas e validação

Mac universal com atualização assinada. O canal ARM legado permanece na 0.9.0 como ponte. A checagem de update não comprova uma troca instalada completa.

Windows usa captura/exportação nativas e instalador de teste, sem Authenticode Dante Studio e sem atualização automática. Recursos visuais importados, transições entre recursos, música, títulos, chroma key, áudio dos recursos, equalização e desenhos nativos continuam indisponíveis no backend Windows. A mesma versão não significa paridade de funcionalidades.

Testes automatizados e mídia sintética cobrem áudio, transições, captura, exportação, instalação e integridade. O encaixe das transições passou em hit-tests e eventos sintéticos do editor; a automação adicional do gesto nativo ficou inconclusiva. Esses testes não equivalem a captura física em Windows 10/11, audição ou uso contínuo em todo hardware. Sem promessa de zero quadros perdidos sob qualquer carga.

Software gratuito. Fontes de desenvolvimento mantidas em repositório privado. Instaladores incluem somente runtime e metadados necessários; materiais de divulgação ficam separados.
