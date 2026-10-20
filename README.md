# Dante Studio

Gravador e editor de tutoriais gratuito. Versão atual: **0.9.35 para Mac e Windows**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.35/Dante-Studio-0.9.35-macOS-universal.dmg): assinado e notarizado pela Apple.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.35/Dante-Studio-0.9.35-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.35

- **Ferramentas de desenho no Windows:** setas, retângulos, elipses, caneta, textos e passos numerados, com seis cores, Desfazer e Limpar. As anotações aparecem no vídeo gravado.
- **Barra flutuante no Windows:** gravar, pausar, continuar e finalizar; arraste ou recolha os controles. Escolha se a barra deve aparecer no vídeo.
- **Lupa no Windows:** lente circular que acompanha o cursor e permite clicar no programa apresentado.
- **Cronômetro e contagem regressiva no Windows:** horas, minutos, segundos e milésimos; regressivo padrão de um minuto, duração digitável e botões +1, +5 e +10 minutos. A barra permite um de cada por vez; ative uma ferramenta de desenho para arrastar os relógios.
- **Retorno após erro:** a janela principal reaparece com a mensagem quando o início da gravação pela barra falha, permitindo revisar a configuração e tentar novamente.

As novas ferramentas Windows atendem à captura de tela, janela e área. O modo Só webcam permanece sem sobreposições. Os recursos já existentes no Mac são preservados; a lupa do Mac usa seu próprio modo de zoom.

Continuam disponíveis velocidade de 0,25× a 50×, importação em segundo plano, Ajustar ao canvas e barra compacta do editor. Acima de 4×, a prévia usa quadros amostrados e suspende o áudio dos takes rápidos; a exportação inclui esse áudio, com alteração de tom.

## Recursos disponíveis

- **Motion graphics:** contador numérico, indicador circular, barra de progresso e destaque com ícone, além dos modelos para tutoriais — 16 opções no total.
- **Seis estilos visuais:** livre, sólido, contorno, elevado, gradiente e translúcido; ajuste cores, cantos, bordas, sombra e opacidade.
- **Contadores personalizáveis:** valor inicial/final, duração, casas decimais, prefixo e sufixo.
- **Edição automática:** textos, fontes e aparência são aplicados sem o botão Aplicar composição, com Desfazer/Refazer.
- **Fontes do computador:** seletor com busca para títulos e motions, incluindo as fontes incorporadas. Fontes locais precisam estar instaladas no computador usado para editar/exportar.
- **Compatibilidade:** composições antigas preservadas; o conteúdo é editado somente no take selecionado.

Continuam disponíveis os 30 estilos de títulos, importação SRT/TXT temporizado e bibliotecas JSON próprias, recorte Alt/Option, enquadramento dentro da moldura, formatos de Só webcam, modo Sequência e cronômetros com milésimos. Não importa projetos After Effects, PSD ou Lottie.

Os recursos da versão anterior continuam disponíveis: narração pelo microfone, preferências de áudio, máscaras de privacidade, consulta aos atalhos, manual do YouTube em texto e vídeo, carrossel de parceiros e contribuição via Pix/PayPal. Máscaras são estáticas por trecho; não acompanham automaticamente objetos em movimento. Para ocultar credenciais, prefira cobertura sólida e confira toda a duração do resultado.

Continuam disponíveis seleção de área livre em qualquer monitor e destaque da janela antes de confirmar, importação unificada de MKV, áudio vinculado, projetos do zero, títulos, gráficos e as 15 fontes de títulos. Recursos MKV preservam faixas compatíveis e reproduzem a principal; não há edição independente de todas as faixas embutidas.

Barra flutuante, desenho, lupa e temporizadores estão disponíveis no Mac e no Windows, com interfaces e comportamentos específicos de cada plataforma. No Windows, dependem da composição da área de trabalho e da exclusão de janelas da captura. Gravação simultânea de vários monitores em mosaico ainda não foi implementada.

## Atualização no Mac

Verifique as atualizações dentro do aplicativo para receber a **0.9.35**. Quem usa o atualizador antigo recebe primeiro a ponte **0.9.16**; após reiniciar, verifique novamente para chegar à versão atual. O DMG acima permite instalar diretamente. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB passam pelo preparador com áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MOV/MP4/M4V H.264/HEVC HDR compatíveis são preparados em H.264 SDR no Mac e Windows; vídeos HDR menores também são encaminhados automaticamente. No Windows, HEVC SDR também pode ser preparado sem instalar a extensão HEVC da loja. MKV HDR e codecs/áudio fora do contrato podem exigir conversão prévia. A preparação SDR não preserva canal alfa nem entrega um projeto HDR. Recursos nativos de prévia, transições preparadas e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

Projetos com velocidade em takes capturados precisam de 0.9.32 ou posterior; velocidade em mídias importadas, músicas e narrações requer 0.9.33. Velocidades acima de 4× requerem 0.9.34 ou posterior compatível. Imagens estáticas, títulos e Motion usam controles próprios de duração e animação.

A fila prepara uma mídia por vez. Os próximos arquivos aparecem imediatamente e podem ser arrastados depois da análise de metadados. Prévia e som ficam disponíveis ao concluir a preparação; vídeos incompatíveis não são reproduzidos parcialmente. A exportação pede aguardar os recursos pendentes utilizados na timeline. O original permanece preservado.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes desta versão usam Windows Server 2022/2025, mídia sintética, seleção por janelas Win32 e validação do instalador/aplicativo instalado. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A preparação de mídia utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.35/Dante-Studio-0.9.35-FFmpeg-Source.zip). O conversor Windows inclui zimg para cores HDR. O arquivo separado contém ambos os fontes e a receita atual. Sem componentes GPL/nonfree habilitados.
