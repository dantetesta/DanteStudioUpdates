# Dante Studio

Gravador e editor de tutoriais gratuito. Versão atual: **0.9.28 para Mac e Windows**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.28/Dante-Studio-0.9.28-macOS-universal.dmg): assinado e notarizado pela Apple.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.28/Dante-Studio-0.9.28-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.28

- **30 estilos de títulos:** galeria com miniaturas, busca e ajustes de fonte, tamanho, contorno, sombra, fundo e transparência. Ajuste automático da caixa ao texto.
- **Biblioteca Motion:** sete movimentos para títulos e mídias, com duração, intensidade e repetição. Inserção de elementos animados por clique ou arraste para a trilha de mídia.
- **Importação de títulos:** SRT/TXT com minutagem cria títulos editáveis; bibliotecas de estilos usam JSON próprio com prévia antes de importar. Não importa projetos After Effects, PSD ou Lottie.
- **Recorte e enquadramento:** Alt/Option nas alças para recortar, duplo clique para mover a imagem dentro da moldura e zoom interno.
- **Só webcam:** novas edições usam os formatos horizontal, vertical ou quadrado sem criar trilha de tela ausente.
- **Modo Sequência:** mova um take e os itens seguintes juntos para abrir espaço na montagem. Colagem prioriza os vãos livres.
- **Cronômetros no Mac:** horas, minutos, segundos e milésimos no cronômetro e na contagem regressiva.

Os recursos da versão anterior continuam disponíveis: narração pelo microfone, preferências de áudio, máscaras de privacidade, consulta aos atalhos, manual do YouTube em texto e vídeo, carrossel de parceiros e contribuição via Pix/PayPal. Máscaras são estáticas por trecho; não acompanham automaticamente objetos em movimento. Para ocultar credenciais, prefira cobertura sólida e confira toda a duração do resultado.

Continuam disponíveis seleção de área livre em qualquer monitor e destaque da janela antes de confirmar, importação unificada de MKV, áudio vinculado, projetos do zero, títulos, gráficos e as 15 fontes de títulos. Recursos MKV preservam faixas compatíveis e reproduzem a principal; não há edição independente de todas as faixas embutidas.

Barra flutuante, desenho e lupa continuam disponíveis somente no Mac. Gravação simultânea de vários monitores em mosaico ainda não foi implementada. A mesma versão não significa paridade de todos os recursos nativos.

## Atualização no Mac

Verifique as atualizações dentro do aplicativo para receber a **0.9.28**. Quem usa o atualizador antigo recebe primeiro a ponte **0.9.16**; após reiniciar, verifique novamente para chegar à versão atual. O DMG acima permite instalar diretamente. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB são preparados com vídeo H.264 SDR e áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MP4/MOV/M4V menores mantêm a importação nativa e os formatos aceitos pela plataforma. MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes desta versão usam Windows Server 2022/2025, mídia sintética, seleção por janelas Win32 e validação do instalador/aplicativo instalado. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.28/Dante-Studio-0.9.28-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
