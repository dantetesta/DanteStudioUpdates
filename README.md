# Dante Studio

Gravador e editor de tutoriais gratuito. Versão atual: **0.9.25 para Mac e Windows**.

## Downloads

- [Mac universal — Intel e Apple Silicon, macOS 13+](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.25/Dante-Studio-0.9.25-macOS-universal.dmg): assinado e notarizado pela Apple.
- [Windows x64](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.25/Dante-Studio-0.9.25-Windows-x64-setup.exe): Windows 10 build 19041+ / Windows 11, instalação e atualização manual.

## Novidades da 0.9.25

- **Timeline que acompanha a edição:** a reprodução termina no último conteúdo e a área visível acompanha a agulha perto da borda.
- **Encaixe controlável:** snap curto entre bordas, inclusive em outras trilhas, com Posicionamento livre no menu de cada take/recurso.
- **Montagem mais prática:** camadas extras vazias são removidas. Reordene, recorte, copie e cole takes com desfazer. Com Fechar espaços ativo, colagens mistas abrem espaço apenas nas trilhas envolvidas.
- **Novos movimentos de zoom:** Aproximar, Afastar e Aproximar e voltar; os dois pontos centrais compartilham o enquadramento. Duplique pontos conservando posição e escala.
- **Chroma com ajuste de reflexos:** alcance opcional da neutralização da cor de fundo em áreas opacas, preservando a aparência de projetos anteriores. Cores legítimas semelhantes ao fundo podem perder saturação; ajuste conforme o conteúdo.
- **Correções de prévia e interface:** carregamento de transições sem o SecurityError relatado, contador do gravador ocioso zerado e prévia do halo Windows coerente com o desenho gravado.
- **Mac atualizado:** inclui as correções de timestamps/finalização e orientação de permissões posteriores à 0.9.22. A notarização da Apple foi concluída.

Continuam disponíveis seleção de área livre em qualquer monitor e destaque da janela antes de confirmar, importação unificada de MKV, áudio vinculado, projetos do zero, títulos, gráficos e as 15 fontes de títulos. Recursos MKV preservam faixas compatíveis e reproduzem a principal; não há edição independente de todas as faixas embutidas.

Barra flutuante, desenho e lupa continuam disponíveis somente no Mac. Gravação simultânea de vários monitores em mosaico ainda não foi implementada. A mesma versão não significa paridade de todos os recursos nativos.

## Atualização no Mac

Verifique as atualizações dentro do aplicativo para receber a **0.9.25**. Quem usa o atualizador antigo recebe primeiro a ponte **0.9.16**; após reiniciar, verifique novamente para chegar à versão atual. O DMG acima permite instalar diretamente. O canal ARM legado permanece na ponte 0.9.0.

## Compatibilidade

MKV e vídeos acima de 512 MiB são preparados com vídeo H.264 SDR e áudio compatível AAC, Opus, FLAC ou PCM mono/estéreo. MP4/MOV/M4V menores mantêm a importação nativa e os formatos aceitos pela plataforma. MKV é um contêiner; outros codecs, HDR e formatos de áudio fora da lista podem exigir conversão prévia. Recursos como proxies de prévia, transições preparadas, HEVC e processamento avançado de voz continuam específicos do Mac. As seis fontes legadas e os emojis podem variar entre os sistemas; as nove novas famílias de títulos estão incorporadas ao aplicativo. SVG é estático, sanitizado e rasterizado, sem scripts ou referências externas.

No Windows e no macOS 14+, gravações fragmentadas reduzem o risco de perda após interrupções. A recuperação preserva os originais e depende dos fragmentos efetivamente gravados; não substitui backup. A finalização Windows verifica as trilhas para preservar também a cauda do áudio.

O instalador Windows ainda não possui certificado Authenticode próprio e não oferece atualização automática. Os testes desta versão usam Windows Server 2022/2025, mídia sintética, seleção por janelas Win32 e validação do instalador/aplicativo instalado. Não equivalem a testes de microfones ou câmeras físicos, audição ou uso prolongado em todo hardware. Não há promessa de ausência de perda em falhas ou de desempenho idêntico entre computadores.

## Software e licenças

Fontes do aplicativo mantidas em repositório privado. Instaladores contêm somente runtime, licenças e metadados necessários. Materiais de divulgação ficam separados.

A importação MKV utiliza programas FFmpeg 8.0.3 sob LGPL 2.1 ou posterior. [Código-fonte correspondente, licença e receita de compilação](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.25/Dante-Studio-0.9.25-FFmpeg-Source.zip). Sem componentes GPL/nonfree habilitados.
