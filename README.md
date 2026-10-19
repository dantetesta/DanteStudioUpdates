# Dante Studio

Gravador e editor de tutoriais gratuito. Versão atual: **0.9.32 para Mac e Windows**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.32/Dante-Studio-0.9.32-macOS-universal.dmg): assinado e notarizado pela Apple.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.32/Dante-Studio-0.9.32-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.32

- **Velocidade no Mac e Windows:** câmera lenta e aceleração de 0,25× a 4× em takes ou blocos selecionados de Tela, Webcam, Microfone e Sistema, com seleção vinculada, Desfazer, salvamento e exportação.
- **Áudio acompanha a velocidade:** o tom também muda. Títulos, mídias adicionais, música e narração mantêm suas durações nesta versão.
- **MOV/HEVC e HDR também no Windows:** MOV/MP4/M4V compatíveis, incluindo HLG/PQ, são preparados automaticamente como cópia H.264 SDR. O Mac mantém seu preparador HDR nativo.
- **Originais preservados:** preparação com progresso e cancelamento, mantendo a orientação e os áudios selecionados. A edição e a exportação são SDR.
- **Sincronização:** correções na leitura temporal de MP4 e no áudio durante a mudança de velocidade.

## Recursos disponíveis

- **Motion graphics:** contador numérico, indicador circular, barra de progresso e destaque com ícone, além dos modelos para tutoriais — 16 opções no total.
- **Seis estilos visuais:** livre, sólido, contorno, elevado, gradiente e translúcido; ajuste cores, cantos, bordas, sombra e opacidade.
- **Contadores personalizáveis:** valor inicial/final, duração, casas decimais, prefixo e sufixo.
- **Edição automática:** textos, fontes e aparência são aplicados sem o botão Aplicar composição, com Desfazer/Refazer.
- **Fontes do computador:** seletor com busca para títulos e motions, incluindo as fontes incorporadas. Fontes locais precisam estar instaladas no computador usado para editar/exportar.
- **Compatibilidade:** composições antigas preservadas; o conteúdo é editado somente no take selecionado.

Continuam disponíveis os 30 estilos de títulos, importação SRT/TXT temporizado e bibliotecas JSON próprias, recorte Alt/Option, enquadramento dentro da moldura, formatos de Só webcam, modo Sequência e cronômetros com milésimos no Mac. Não importa projetos After Effects, PSD ou Lottie.

Os recursos da versão anterior continuam disponíveis: narração pelo microfone, preferências de áudio, máscaras de privacidade, consulta aos atalhos, manual do YouTube em texto e vídeo, carrossel de parceiros e contribuição via Pix/PayPal. Máscaras são estáticas por trecho; não acompanham automaticamente objetos em movimento. Para ocultar credenciais, prefira cobertura sólida e confira toda a duração do resultado.

Continuam disponíveis seleção de área livre em qualquer monitor e destaque da janela antes de confirmar, importação unificada de MKV, áudio vinculado, projetos do zero, títulos, gráficos e as 15 fontes de títulos. Recursos MKV preservam faixas compatíveis e reproduzem a principal; não há edição independente de todas as faixas embutidas.

Barra flutuante, desenho e lupa continuam disponíveis somente no Mac. Gravação simultânea de vários monitores em mosaico ainda não foi implementada. A mesma versão não significa paridade de todos os recursos nativos.

## Atualização no Mac

Verifique as atualizações dentro do aplicativo para receber a **0.9.32**. Quem usa o atualizador antigo recebe primeiro a ponte **0.9.16**; após reiniciar, verifique novamente para chegar à versão atual. O DMG acima permite instalar diretamente. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB passam pelo preparador com áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MOV/MP4/M4V H.264/HEVC HDR compatíveis são preparados em H.264 SDR no Mac e Windows; vídeos HDR menores também são encaminhados automaticamente. No Windows, HEVC SDR também pode ser preparado sem instalar a extensão HEVC da loja. MKV HDR e codecs/áudio fora do contrato podem exigir conversão prévia. A preparação SDR não preserva canal alfa nem entrega um projeto HDR. Recursos nativos de prévia, transições preparadas e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

Projetos com velocidade diferente de 1× precisam de 0.9.32 ou posterior; versões antigas não suportam o novo formato. A importação ainda aguarda a preparação: biblioteca instantânea e edição de recursos pendentes em background não fazem parte desta versão.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes desta versão usam Windows Server 2022/2025, mídia sintética, seleção por janelas Win32 e validação do instalador/aplicativo instalado. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A preparação de mídia utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.32/Dante-Studio-0.9.32-FFmpeg-Source.zip). O conversor Windows inclui zimg para cores HDR. O arquivo separado contém ambos os fontes e a receita atual. Sem componentes GPL/nonfree habilitados.
