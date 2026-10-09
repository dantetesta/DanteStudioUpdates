<div align="center">

# Dante Studio

### Grave, edite e compartilhe suas ideias.

**100% gratuito. Sem assinatura. Sem cobrança.**

Um estúdio para gravar tutoriais, aulas e apresentações com tela, webcam e áudio.

<a href="https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.4/Dante-Studio-0.9.4-macOS-universal.dmg"><img alt="Baixar grátis para Mac Intel e Apple Silicon — versão 0.9.4" height="48" src="https://img.shields.io/badge/BAIXAR_PARA_MAC-0.9.4-4158F5?style=for-the-badge&amp;logo=apple&amp;logoColor=white"></a>

<a href="https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.4/Dante-Studio-0.9.4-Windows-x64-setup.exe"><img alt="Baixar grátis para Windows — versão 0.9.4" height="48" src="https://img.shields.io/badge/BAIXAR_PARA_WINDOWS-0.9.4-1676D2?style=for-the-badge"></a>

[Site oficial](https://dantetesta.com.br/dante-studio/) · [Todas as versões](https://github.com/dantetesta/DanteStudioUpdates/releases) · [Comunidade no WhatsApp](https://chat.whatsapp.com/IaXqPAlW1sNEALIoRktDrM?mode=gi_t)

</div>

---

## Seu conteúdo, do começo ao vídeo final

- Grave uma área da tela, uma janela ou a tela inteira.
- No Mac, desenhe durante a gravação com caneta, setas, formas, texto, Steps, seis cores e lupa; o painel abre ao iniciar a gravação.
- Use webcam, microfone e áudio do sistema em trilhas separadas.
- Monte seus vídeos com cortes, zoom e ajustes de enquadramento.
- Personalize a webcam e o áudio em um painel lateral com abertura suave.
- Ajuste a altura do player arrastando o divisor acima da timeline.
- Exporte em MP4 com o nome que você escolher.
- Organize gravações e exportações separadamente, reproduza a prévia dos vídeos exportados e abra suas pastas pelo aplicativo.

Seus vídeos e projetos ficam no seu computador. Os recursos disponíveis variam entre Mac e Windows; anotações durante a captura e controles flutuantes estão disponíveis no Mac.

## Novidades da versão 0.9.4

- **Modo claro e escuro:** escolha a aparência em Preferências ou no botão do topo.
- **Gravador mais direto:** monitores em cards de seleção única, controles mais legíveis e prévia da câmera em modal, sem rolar a página.
- **Avisos flutuantes:** notificações temporárias e menos texto ocupando o espaço de trabalho.
- **Remover exportações:** exclusão permanente dos MP4 listados, com quantidade, pastas e confirmação antes de apagar do disco. As gravações originais são protegidas.
- **Timeline:** trilhas com altura uniforme, seleção por arraste e cortes que respeitam os elementos selecionados. Sem seleção, o corte divide os elementos atravessados pelo marcador.
- **Volumes de áudio de 0% a 200%:** controle por trilha ou trecho, mantendo as opções de silenciar. Volumes de recursos acima de200% salvos em versões anteriores são preservados até nova edição.
- **Microfone no Mac:** equalização opcional de graves, médios e agudos, com presets; sem ajustes, a voz original é mantida.
- **Recursos no Mac:** filtros em uma linha, cards compactos responsivos e ajustes de áudio/chroma key mais organizados.
- **Desenhos no Mac:** ferramentas maiores, nomes e indicação clara da ferramenta ativa.
- **Pastas no Windows:** correção dos caminhos canônicos, Unicode e caminhos longos, incluindo o acesso do seletor de pastas e a leitura de mídia.
- **Inicialização no Windows:** aviso nativo e relatório local para falhas ao abrir; instalação do WebView2 ausente também durante atualizações.
- **Créditos:** autor Dante Testa, site e comunidade no menu do aplicativo.

Música, títulos, recursos visuais importados, chroma key, áudio desses recursos, equalização do microfone e ferramentas de desenho estão disponíveis no Mac. A versão Windows mantém os recursos nativos descritos nos controles do aplicativo e continua como versão de teste. Ambos os instaladores têm a mesma versão; suas capacidades nativas ainda diferem. Os arquivos e projetos ficam no computador, com edição não destrutiva.

## Download e instalação

| Sistema | Versão | Requisitos | Download |
| --- | --- | --- | --- |
| **Mac** | **0.9.4** | macOS 13 ou posterior · Intel e Apple Silicon | [Baixar DMG gratuito](https://github.com/dantetesta/DanteStudioUpdates/releases/download/macos-universal-v0.9.4/Dante-Studio-0.9.4-macOS-universal.dmg) |
| **Windows** | **0.9.4 — versão de teste** | Windows 10 versão 2004/build 19041 ou posterior · Windows 11 · x64 | [Baixar EXE gratuito](https://github.com/dantetesta/DanteStudioUpdates/releases/download/windows-x64-v0.9.4/Dante-Studio-0.9.4-Windows-x64-setup.exe) |

**Mac:** abra o DMG e arraste o Dante Studio para Aplicativos. O instalador tem assinatura Developer ID e notarização Apple. Ao usar tela, câmera ou microfone, conceda as permissões solicitadas pelo macOS.

**Windows:** execute o instalador EXE e siga as etapas. A instalação solicita autorização de administrador. O WebView2 Runtime é necessário: quando ausente, o instalador baixa o componente oficial da Microsoft e precisa de internet. Edições Windows N precisam também do Media Feature Pack para os recursos de mídia. Esta versão de teste ainda não possui assinatura Authenticode do Dante Studio e pode exibir um aviso de segurança do Windows.

Os testes automatizados verificam instalação, abertura com usuário padrão, IPC, falhas de WebView2 e preservação de dados em Windows Server 2022/2025. Captura física e o funcionamento em computadores Windows 10/11 específicos ainda requerem validação nesses sistemas.

Os arquivos `.sha256` para conferência estão nas [releases](https://github.com/dantetesta/DanteStudioUpdates/releases).

### Atualizações

No **Mac**, abra **Atualizações** para consultar o repositório oficial. As versões Apple Silicon anteriores recebem a 0.9.0 por um pacote de transição; as próximas atualizações usam o canal universal. Se sua versão ainda aponta para o endereço antigo, instale o DMG 0.9.4 manualmente uma vez. A detecção e os pacotes assinados são verificados; a instalação automática completa no aplicativo instalado ainda precisa de teste do usuário.

No **Windows**, as atualizações são instaladas manualmente pelo EXE. O auto-update dessa plataforma ainda não está disponível.

## Participe da comunidade

Tem uma ideia para melhorar o Dante Studio? Encontrou um bug? Entre no grupo para sugerir recursos e ajudar a melhorar o programa.

<div align="center">
<a href="https://chat.whatsapp.com/IaXqPAlW1sNEALIoRktDrM?mode=gi_t"><img alt="Entrar no grupo do Dante Studio no WhatsApp" height="44" src="https://img.shields.io/badge/ENTRAR_NO_GRUPO-WhatsApp-25D366?style=for-the-badge&amp;logo=whatsapp&amp;logoColor=white"></a>
</div>

Ao relatar um problema, informe a versão do Dante Studio, o sistema operacional e os passos para reproduzir o erro.

## Apoie o desenvolvimento

O Dante Studio é e continuará sendo **gratuito**. Se quiser ajudar a manter o desenvolvimento, **doe qualquer valor via Pix**. A contribuição é livre e espontânea; todos podem usar o programa sem doar.

<div align="center">
<strong>Obrigado por apoiar as próximas melhorias do Dante Studio ❤️</strong>
</div>
