# Dante Studio

Gravador e editor de tutoriais gratuito. Versão **0.9.22**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.22/Dante-Studio-0.9.22-macOS-universal.dmg): assinado e notarizado.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.22/Dante-Studio-0.9.22-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.22

- **Parada com estado correto no Windows:** falhas de captura congelam o cronômetro e iniciam a finalização com aviso, sem apresentar uma captura interrompida como ainda ativa.
- **Finalização com opção de cancelar:** a preparação dos arquivos pode ser cancelada para preservar os originais e tentar a recuperação pela biblioteca. Uma verificação em andamento pode demorar a responder.
- **Recuperação mais consistente:** sessões cuja finalização falhou continuam identificadas como interrompidas. Faixas opcionais vazias deixam de bloquear o vídeo, mantendo a validação dos demais arquivos.
- **Áudio e processos auxiliares:** criação da faixa somente quando há amostras, liberação dos buffers antes da codificação e encerramento dos conversores junto ao aplicativo.
- **Instalação Windows protegida:** verificação dos conversores em uso antes de substituir arquivos, com nova tentativa após liberar o bloqueio.

O Mac recebe a versão 0.9.22 com sua captura nativa preservada. As correções acima são específicas do Windows.

A versão mantém as **15 fontes para títulos**, com nove famílias incorporadas para uso offline, a preparação do próximo clipe na prévia e a correção do limite final da exportação no Mac, entregues na 0.9.20.

Continuam disponíveis a importação unificada de MKV, a duração completa e o áudio vinculado introduzidos na 0.9.18. Recursos MKV preservam áudios compatíveis e reproduzem a faixa principal; não há edição independente de todas as faixas embutidas. Projetos e cortes já salvos são preservados.

Projetos do zero, imagens/GIFs/vídeos, música, títulos, gráficos e aulas de até 24 horas continuam disponíveis, conforme a compatibilidade de cada plataforma.

## Atualização no Mac

Quem usa o atualizador antigo receberá primeiro a **0.9.16**, que prepara a instalação dos novos componentes de mídia. Depois de reiniciar, verifique as atualizações novamente para receber a **0.9.22**. O DMG acima permite instalar diretamente a versão final. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB são preparados com vídeo H.264 SDR e áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MP4/MOV/M4V menores mantêm a importação nativa e os formatos aceitos pela plataforma. MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes usam Windows Server 2022/2025, mídia sintética e captura GDI real de janela/região com pausa, retomada e parada. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.22/Dante-Studio-0.9.22-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
