# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.18**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.18/Dante-Studio-0.9.18-macOS-universal.dmg): assinado e notarizado.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.18/Dante-Studio-0.9.18-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.18

- **Importação unificada:** use Imagem e vídeo na Biblioteca de mídia para escolher imagens, GIFs e vídeos compatíveis, incluindo MKV do OBS. O botão exclusivo de MKV foi removido.
- **Preparação automática:** sem seleção manual de trilhas. A janela mostra arquivo, duração, tamanho, progresso e cancelamento quando necessário.
- **Duração completa:** novos vídeos entram inteiros na timeline, corrigindo o limite inicial de três segundos. Trechos antigos podem ser estendidos até o fim da fonte, respeitando vizinhos e o teto de 24 horas.
- **Áudio vinculado:** novos clipes com áudio começam com o som ligado. A faixa Áudio da Mídia acompanha a posição e os cortes do mesmo vídeo, com volume e silêncio por trecho, sem duplicar a reprodução.
- **Várias faixas preservadas:** recursos MKV mantêm os áudios compatíveis no arquivo e reproduzem a faixa principal, sem somar mixes do OBS. Não há edição independente de cada faixa embutida nesta versão. Para arquivos com mais de duas faixas, use a Biblioteca de mídia em vez de importar como projeto.
- **Projetos preservados:** cortes, volume e silenciamento já salvos continuam como estavam; os originais não são alterados.

Projetos do zero, imagens/GIFs/vídeos, música, títulos, gráficos e aulas de até 24 horas continuam disponíveis, conforme a compatibilidade de cada plataforma.

## Atualização no Mac

Quem usa o atualizador antigo receberá primeiro a **0.9.16**, que prepara a instalação dos novos componentes de mídia. Depois de reiniciar, verifique as atualizações novamente para receber a **0.9.18**. O DMG acima permite instalar diretamente a versão final. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB são preparados com vídeo H.264 SDR e áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MP4/MOV/M4V menores mantêm a importação nativa e os formatos aceitos pela plataforma. MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. Fontes e emojis podem variar entre os sistemas. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes automatizados usam mídia sintética e Windows Server; não equivalem a captura física, audição ou teste prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.18/Dante-Studio-0.9.18-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
