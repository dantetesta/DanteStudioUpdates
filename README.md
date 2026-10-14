# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.20**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.20/Dante-Studio-0.9.20-macOS-universal.dmg): assinado e notarizado.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.20/Dante-Studio-0.9.20-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.20

- **15 fontes para títulos:** nove famílias incorporadas ao aplicativo — Lato, Anton, Bebas Neue, Pacifico, Lobster, Righteous, Cinzel Decorative, Abril Fatface e Architects Daughter. Funcionam offline no Mac e Windows, com os mesmos arquivos na prévia e na exportação. As seis opções anteriores continuam disponíveis.
- **Cortes sem flash preto na prévia:** o próximo trecho é preparado antes da junção e a imagem é mantida até o novo quadro ficar pronto. Espaços intencionais continuam preservados.
- **Exportação no Mac:** corrigido um arredondamento que podia rejeitar o último clipe ao terminar exatamente no limite da timeline, inclusive em projetos criados do zero.

Continuam disponíveis a importação unificada de MKV, a duração completa e o áudio vinculado introduzidos na 0.9.18. Recursos MKV preservam áudios compatíveis e reproduzem a faixa principal; não há edição independente de todas as faixas embutidas. Projetos e cortes já salvos são preservados.

Projetos do zero, imagens/GIFs/vídeos, música, títulos, gráficos e aulas de até 24 horas continuam disponíveis, conforme a compatibilidade de cada plataforma.

## Atualização no Mac

Quem usa o atualizador antigo receberá primeiro a **0.9.16**, que prepara a instalação dos novos componentes de mídia. Depois de reiniciar, verifique as atualizações novamente para receber a **0.9.20**. O DMG acima permite instalar diretamente a versão final. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB são preparados com vídeo H.264 SDR e áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MP4/MOV/M4V menores mantêm a importação nativa e os formatos aceitos pela plataforma. MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes automatizados usam mídia sintética e Windows Server; não equivalem a captura física, audição ou teste prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.20/Dante-Studio-0.9.20-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
