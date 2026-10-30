# Dante Studio

Gravador e editor de tutoriais gratuito. Versão atual: **0.9.42 para Mac e Windows**.


## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.42/Dante-Studio-0.9.42-macOS-universal.dmg): assinado e notarizado pela Apple.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.42/Dante-Studio-0.9.42-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.42

- **Área livre entre monitores:** comece o arraste em uma tela e termine em outra para gravar a região em um único vídeo.
- **Todos os monitores:** um novo botão prepara o desktop inteiro, respeitando a disposição das telas e deixando pretos os espaços sem monitor.
- **Seleção ligada ao layout:** mudanças de posição, resolução ou monitores exigem uma nova seleção; não há troca silenciosa para outra tela.
- **Créditos reorganizados:** perfil do autor, site, comunidade e apoio voluntário por Pix/PayPal em um painel adaptável aos temas claro e escuro.
- **Converse com Dante Testa:** o botão de WhatsApp nos créditos permite conversar sobre o desenvolvimento do seu próximo software. O Dante Studio continua gratuito.

A saída preserva as opções de qualidade/FPS sob o limite existente de **3840 pixels no maior lado**. Conjuntos muito largos podem reduzir a legibilidade; a versão não promete gravar todas as telas em resolução nativa simultânea. Os testes usam composições e monitores sintéticos, contratos do helper e CI; não homologam todas as GPUs, escalas ou quatro monitores físicos. Windows continua com instalação e atualização manual.

## Histórico preservado — novidades da 0.9.41

- **Anotações no Windows:** preparação de cada quadro fora da tela para evitar o apagamento intermediário dos desenhos, especialmente durante o uso da lupa.
- **Paleta de escrita:** ícones vetoriais, ferramentas reorganizadas em linhas e campo de texto com aparência consistente.
- **Retorno após a seleção:** o Studio reaparece quando o seletor termina, inclusive ao cancelar ou ocorrer um erro. Só fica oculto após a confirmação dos controles flutuantes.
- **Uma instância do aplicativo:** abrir novamente traz a janela existente para frente, inclusive quando ela estava oculta.
- **Seleção de janela no Windows:** superfícies internas de anotações, controles e seleção são excluídas dos alvos.
- **Saída durante a gravação:** o X orienta a usar **Parar e salvar**, mantendo os controles acessíveis e preservando a gravação em andamento.

A validação inclui fixtures nativas, interface e instalação no CI. Os relatos originais não tiveram uma causa única de encerramento confirmada; isso não equivale a homologação de todo monitor, GPU ou escala de DPI.

## Histórico preservado — novidades da 0.9.40

- **Tela inteira com confirmação:** a janela principal permanece visível enquanto a barra flutuante é preparada; ela só é ocultada após a confirmação de abertura dos controles.
- **Recuperação em caso de falha:** erros na seleção ou na abertura da barra restauram a janela principal para uma nova tentativa.
- **Barra flutuante no Windows:** verifica o monitor, posicionamento e visibilidade antes de confirmar a abertura. Ao selecionar outra fonte, reposiciona os controles; atualizações da mesma fonte preservam a posição arrastada.
- **Dispositivos no Windows:** tratamento de falhas na identificação de câmeras e microfones, com liberação dos recursos também em caso de erro.

O encerramento relatado em um computador com monitor 2 ainda não foi reproduzido fisicamente. Esta versão corrige as falhas encontradas no fluxo de seleção e reforça o tratamento de erros. Testes automatizados e runners Windows Server não equivalem à homologação de todos os monitores, drivers ou configurações de escala. Windows continua com instalação e atualização manuais.

## Histórico preservado — novidades da 0.9.39

- **Motion com curvas:** escolha movimento linear, aceleração, desaceleração ou curva suave; entrada e saída podem usar curvas diferentes. Novas fases Descer, Afastar e Inclinar.
- **Animação por pontos:** trajetórias com 2 a 32 pontos para posição, escala, rotação e opacidade, com interpolação configurável e persistência no projeto.
- **22 modelos Motion:** seis novas composições editáveis, sem adicionar bibliotecas de animação ao aplicativo.
- **15 transições:** novas opções de empurrar para cima, empurrar para baixo e leque radial. Curvas de progresso e suavidade de bordas ajustáveis nas máscaras compatíveis.
- **Sem vãos aprimorado:** compacta os espaços existentes considerando o conteúdo de todas as faixas, com desfazer/refazer da mudança completa; quando não há espaços, alterna o modo automático.
- **Prévia pausada de transições corrigida:** evita ficar presa no primeiro quadro enquanto os decoders de borda terminam o seek. Reutiliza os decoders existentes e renova o cache quando o quadro é apresentado.
- **Dispositivos acompanhados por eventos:** atualiza o inventário de câmeras, microfones e monitores pelas notificações nativas. Adia a atualização durante operações ocupadas e não troca silenciosamente uma tela desconectada por outra.

Projetos antigos preservam o comportamento quando as novas opções estão ausentes. Projetos que usam as novas animações e transições precisam da 0.9.39 nos demais computadores. Estas melhorias não incluem transcrição automática ou revelação de títulos por palavra. O custo de processamento depende da composição e do equipamento.

A validação desta versão inclui exportações sintéticas decodificadas com as novas curvas, pontos e transições nos helpers empacotados, Mac ARM/Rosetta/Intel e Windows Server 2022/2025, além de instalação e IPC no Windows. Hotplug físico, captura física, audição e substituição instalada pelo atualizador não foram homologados nesta entrega. Windows continua com instalação e atualização manuais.

## Histórico preservado — novidades da 0.9.38

- **Prévia leve automática:** quando o editor está pausado, prepara uma cópia por vez conforme a capacidade do dispositivo. Use **Original** para inspecionar os detalhes ou **Cancelar** para pausar o preparo. Fontes sem cópia segura continuam no original; a exportação usa os originais.
- **HEVC opcional na gravação do Mac:** disponível apenas quando a cadeia de hardware é compatível. H.264 continua padrão e a escolha não muda resolução ou quadros por segundo. HEVC pode economizar espaço, mas o resultado depende do conteúdo e há casos maiores; alguns aplicativos não o abrem. Windows continua gravando em H.264.
- **Análise opcional de exportação:** **Equilibrada** preserva o perfil padrão. **Máxima eficiência**, quando disponível, compara uma alternativa à referência e mantém a referência se a alternativa não ficar menor ou falhar nos limites numéricos de qualidade. Pode exigir mais tempo e espaço temporário. **Até agora, a matriz de exportações testada conservou a referência: não houve ganho de tamanho comprovado desse modo.** Não é compressão sem perdas nem promessa de economia.
- **Aviso sonoro ao concluir:** jingle original de quatro segundos somente depois de uma exportação nova concluída com sucesso. Falhas, cancelamentos e prévias não disparam o aviso.
- **Lixeira por vídeo exportado:** confirme o arquivo escolhido para remover somente aquela exportação. As gravações e os demais vídeos ficam preservados.
- **Manutenção dos cortes e da reprodução:** continuidade das emendas, recuperação do decoder e regras de sincronismo/privacidade preservadas. Ajustes de desempenho não alteram os cortes salvos ou os originais.
- **Preparador de mídia atualizado:** FFmpeg 9.0.2 sob LGPL, com ferramentas offline separadas dos encoders nativos de captura/exportação. Sem componentes GPL/nonfree habilitados.

A validação usa mídia sintética, helpers nativos, WebKit e runners de CI, conforme o recibo final de cada plataforma. O Mac universal foi validado em ARM, Rosetta e Intel. No Windows, a instalação e a preservação de arquivos passaram em Server 2022/2025; o EXE canônico também passou pela prova de prévias com IPC e pixels reais no WebView2. Não equivale a captura física de tela/câmera/microfone, audição ou homologação de todo hardware consumidor. Economia medida na captura HEVC não é ganho demonstrado na exportação.

## Histórico preservado — novidades da 0.9.37

- **Prévia mais resistente:** recuperação do decoder quando uma busca não apresenta o quadro esperado, com preservação do destino mais recente após cortes. O botão “Recarregar imagem da prévia” refaz a imagem sem alterar os cortes ou o marcador.
- **Motions favoritos:** guarde textos, cores, fonte, aparência e movimento na seção “Modelos salvos”. Remover um modelo mantém os demais favoritos. Títulos também têm uma estrela para salvar estilos.
- **Área livre no Mac:** encaixar a seleção numa janela mantém a captura da região da tela. Para isolar uma janela, use a opção explícita “Janela exclusiva”. No Windows, “Área da janela” captura os pixels visíveis e informa essa diferença.
- **Exportação protegida:** clique fora ou Esc preservam as configurações; use o X para fechar.
- **Dependências de compilação atualizadas:** Vite 8.3.3 e Tokio 1.53.3, com correções de segurança e de segurança de I/O.

Continuam disponíveis as melhorias de importação, exportação de áudio e anotações das versões anteriores. As validações automatizadas usam mídia sintética e runners Windows Server. O teste longo de prévia verifica offsets acima de 4 GiB e falhas simuladas no WebKit do Mac; não equivale à reprodução da corrupção verde em toda GPU. Captura, câmera, microfone e audição físicos em computadores de usuários ainda precisam de teste próprio.

## Recursos disponíveis

- **Motion graphics:** contador numérico, indicador circular, barra de progresso e destaque com ícone, além dos modelos para tutoriais — 22 opções no total.
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

Verifique as atualizações dentro do aplicativo para receber a **0.9.41**. Quem usa o atualizador antigo recebe primeiro a ponte **0.9.16**; após reiniciar, verifique novamente para chegar à versão atual. O DMG acima permite instalar diretamente. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB passam pelo preparador com áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MOV/MP4/M4V H.264/HEVC HDR compatíveis são preparados em H.264 SDR no Mac e Windows; vídeos HDR menores também são encaminhados automaticamente. No Windows, HEVC SDR também pode ser preparado sem instalar a extensão HEVC da loja. MKV HDR e codecs/áudio fora do contrato podem exigir conversão prévia. A preparação SDR não preserva canal alfa nem entrega um projeto HDR. Cópias leves são oferecidas conforme a capacidade validada: Mac admite fontes opacas SDR compatíveis e Windows usa um caminho conservador H.264 SDR com cor declarada segura. Fontes sem interpretação segura, inclusive casos de início não zero fora do contrato Windows, continuam no original; isso não é anúncio de suporte a todos os timestamps ou formatos. Transições preparadas e processamento avançado de voz mantêm suas capacidades específicas do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

Projetos com velocidade em takes capturados precisam de 0.9.32 ou posterior; velocidade em mídias importadas, músicas e narrações requer 0.9.33. Velocidades acima de 4× requerem 0.9.34 ou posterior compatível. Imagens estáticas, títulos e Motion usam controles próprios de duração e animação.

A fila prepara uma mídia por vez. Os próximos arquivos aparecem imediatamente e podem ser arrastados depois da análise de metadados. Prévia e som ficam disponíveis ao concluir a preparação; vídeos incompatíveis não são reproduzidos parcialmente. A exportação pede aguardar os recursos pendentes utilizados na timeline. O original permanece preservado.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes desta versão usam Windows Server 2022/2025, mídia sintética, seleção por janelas Win32 e validação do instalador/aplicativo instalado. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A preparação de mídia utiliza programas FFmpeg 9.0.2 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.41/Dante-Studio-0.9.41-FFmpeg-Source.zip). O conversor Windows inclui zimg para cores HDR. O arquivo separado contém ambos os fontes e a receita atual. Sem componentes GPL/nonfree habilitados.
