# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.17**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.17/Dante-Studio-0.9.17-macOS-universal.dmg): assinado e notarizado.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.17/Dante-Studio-0.9.17-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades

- **Projetos do zero:** abra o Editor, escolha uma gravação ou comece um projeto vazio com os recursos da biblioteca de mídia.
- **MKV do OBS:** importação de vídeo H.264 SDR com seleção de até duas trilhas de áudio para o projeto. Para usar como recurso na biblioteca, escolha uma faixa de áudio. AAC, Opus, FLAC e PCM compatíveis são preparados quando necessário; os originais são preservados.
- **Biblioteca nos dois sistemas:** imagens, GIFs, vídeos, músicas, títulos e gráficos para compor a edição. Áudio dos recursos é opcional.
- **Aulas e lives longas:** duração de até 24 horas, condicionada ao espaço e ao computador. A importação trabalha por partes; a exportação de música aplica volume e fades sem criar um PCM temporário integral de várias horas.
- **Windows:** composição de recursos, música, títulos, gráficos, chroma e enquadramento por take no motor nativo. Corrigido o fundo da câmera em tela cheia quando o vídeo termina.

## Atualização no Mac

Quem usa o atualizador antigo receberá primeiro a **0.9.16**, que prepara a instalação dos novos componentes de mídia. Depois de reiniciar, verifique as atualizações novamente para receber a **0.9.17**. O DMG acima permite instalar diretamente a versão final. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. Fontes e emojis podem variar entre os sistemas. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes automatizados usam mídia sintética e Windows Server; não equivalem a captura física, audição ou teste prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.17/Dante-Studio-0.9.17-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
