# Histórico completo do Engine Pro

Todas as versões, da mais recente à primeira, com cada novidade, melhoria e correção.

## Versão 4.4.1 | Nova página Rede e pastas, separando o mapeamento das pas... | 29/10/2026

- **Melhoria**: Nova página Rede e pastas, separando o mapeamento das pastas do escritório e os reparos de rede dos reparos de limpeza e manutenção.
- **Melhoria**: Aviso Somente no Escritório e verificação automática da conexão com o servidor, com o botão desativado nas Obras.

## Versão 4.4.0 | Mapeamento das pastas do SharePoint do servidor do escrit... | 29/10/2026

- **Novo**: Mapeamento das pastas do SharePoint do servidor do escritório, escolhidas pelo usuário conforme as permissões do AD, com a inicial da pasta como letra da unidade.
- **Novo**: Verificação e correção automática de mapeamentos quebrados ou com defeito.

## Versão 4.3.5 | Reparo de impressoras com limpeza completa da fila (arqui... | 29/10/2026

- **Melhoria**: Reparo de impressoras com limpeza completa da fila (arquivos .SPL e .SHD) em dois ciclos, com o serviço reiniciado duas vezes.
- **Melhoria**: Registro de cada atualização automática instalada.
- **Correção**: Previsão de espaço em disco do Modo IA.

## Versão 4.3.4 | Balão discreto de atualização concluída perto do relógio,... | 29/10/2026

- **Novo**: Balão discreto de atualização concluída perto do relógio, no máximo um a cada 4 horas.
- **Melhoria**: O ícone perto do relógio passa a usar a versão nova sozinho, sem esperar o próximo logon.

## Versão 4.3.3 | Reparo do sistema legível | 29/10/2026

- **Correção**: Saída do reparo dos arquivos do sistema (SFC) legível e com acentos, sem as linhas repetidas de porcentagem.
- **Novo**: Ao pedir uma atualização durante uma tarefa, ela é instalada automaticamente assim que a tarefa terminar.
- **Melhoria**: A tela de execução não repete linhas idênticas em sequência.

## Versão 4.3.2 | Y girando como moeda | 29/10/2026

- **Melhoria**: O Y de espera voltou a girar como uma moeda, sempre de pé, mantendo o tamanho pequeno.

## Versão 4.3.1 | Verificação de atualização sem atraso | 29/10/2026

- **Correção**: A verificação de atualizações passou a enxergar a versão nova logo após a publicação, sem esperar até 10 minutos pela cópia guardada do GitHub.

## Versão 4.3.0 | Modo IA e nova tela de execução | 29/10/2026

- **Novo**: Modo IA: nota de saúde de 0 a 100 e diagnóstico que cruza travamentos de programas, telas azuis, erros de disco e de hardware, saúde do SSD, estabilidade, tempo de inicialização, Windows Update, DNS, drivers e bateria.
- **Novo**: Piloto automático do Modo IA: autocorreção silenciosa (DNS, relógio, WMI, antivírus), manutenção com o computador parado e aprendizado do horário de uso.
- **Novo**: Previsões: quando o disco vai encher, vida útil do SSD, saúde da bateria e índice de estabilidade.
- **Novo**: Nova tela de execução: Y do logotipo girando dentro de um anel e porcentagem subindo em tempo real até 100%.
- **Novo**: 12 novos reparos: diagnóstico da rede, proxy, compartilhamento na rede, Print to PDF, aplicativos do Windows, áudio, senhas salvas do Office, ponto de restauração, WMI, políticas do domínio, energia padrão e relatório de diagnóstico.
- **Melhoria**: Y girando como símbolo de espera em todas as telas que precisam aguardar, sumindo ao terminar.
- **Melhoria**: Instalador: agendamento simplificado em uma única escolha, com "Não agendar" selecionado.
- **Correção**: O serviço do monitor não é mais criado quando a opção do monitor está desmarcada no instalador.

## Versão 4.2.2 | Recursos restritos à equipe de TI (estável) | 29/10/2026

- **Melhoria**: Liberação no canal estável da restrição do Editor do Registro e do BitLocker.

## Versão 4.2.1 | Modo técnico | 29/10/2026

- **Novo**: Modo técnico (Ctrl+Shift+F12) para a equipe de TI.
- **Melhoria**: Editor do Registro e aviso do BitLocker ocultos para os usuários e visíveis só no modo técnico.

## Versão 4.2.0 | Atualização automática pelo GitHub | 29/10/2026

- **Novo**: Atualização automática: o serviço consulta o GitHub a cada 2 horas e instala em silêncio, esperando terminar qualquer tarefa em andamento.
- **Novo**: Assinatura digital das versões: o Engine Pro recusa qualquer instalador sem a assinatura correta, mesmo se a conta do GitHub for invadida.
- **Novo**: Canais Estável e Teste, escolhidos por computador no Sobre.
- **Novo**: Site de download e repositório público no GitHub.
- **Melhoria**: Número da versão escolhido automaticamente na compilação.

## Versão 4.1.0 | Monitor como serviço do Windows | 29/10/2026

- **Novo**: Serviço "Engine Pro Monitor": liga junto com o computador, antes do logon, e roda os sensores com permissão total.
- **Melhoria**: Reinício automático do monitor em caso de falha.
- **Melhoria**: O ícone perto do relógio passa a só exibir os avisos quando o serviço está ativo.

## Versão 4.0.0 | Monitor, sensores e avisos | 29/10/2026

- **Novo**: Monitor em segundo plano com ícone perto do relógio.
- **Novo**: Sensores: antivírus (com reparo automático), memória acima de 95% (no máximo 1 limpeza por hora), disco acima de 90%, programas suspeitos, impressora e spooler travados e sugestões de melhoria.
- **Novo**: Avisos em vermelho na tela inicial, com níveis Tranquilo, Comum, Severo e Crítico, sem janelas pop-up.
- **Novo**: Programas desconhecidos: opções "Conheço" e "Não conheço" (encerra, remove da inicialização e envia para a quarentena).
- **Novo**: Reparos do Office (completo), Outlook, Teams, OneDrive, WebView2 e Antivírus do Windows.

## Versão 3.8.0 | Reparos, Ajustes do sistema e IAs | 29/10/2026

- **Novo**: Página Reparos com 18 reparos de um clique: rede, impressoras, barra de tarefas, Explorador, atalhos quebrados, fontes, relógio, Office e outros.
- **Novo**: Página Ajustes do sistema: programas que iniciam com o Windows, tempos de tela, suspensão e hibernação, plano de energia, proteção de tela e reinício programado.
- **Novo**: Categoria Inteligência artificial: Claude, ChatGPT, Copilot, Perplexity Comet, Ollama, LM Studio, Jan e GPT4All.

## Versão 3.7.0 | Office, Project, Visio e Ferramentas do Windows | 29/10/2026

- **Novo**: Microsoft 365 Apps (empresas e grandes empresas), Project e Visio instalados pela Ferramenta de Implantação do Office.
- **Novo**: Visio Viewer gratuito.
- **Novo**: 26 atalhos para as ferramentas de manutenção do próprio Windows.

## Versão 3.6.0 | Visual profissional | 29/10/2026

- **Melhoria**: Banners em degradê em todas as páginas, cartões com sombra e botões principais em degradê.
- **Novo**: Identidade própria na barra de tarefas, com o ícone do Engine Pro, voltando maximizado ao clicar.
- **Melhoria**: Removidos aplicativos que não são ferramentas de trabalho (Deezer, Telegram, Discord, Spotify, G HUB e Razer Synapse).

## Versão 3.5.1 | Instalação de aplicativos mais robusta | 29/10/2026

- **Novo**: PDFTools 1.3, com o Java instalado junto automaticamente.
- **Melhoria**: Erros do winget explicados em português e nova tentativa automática em falhas temporárias.
- **Melhoria**: Rotas alternativas de instalação para BIMcollab Zoom e Revo Uninstaller.
- **Melhoria**: Logotipo com a chave de reparo ao lado do Y.

## Versão 3.5.0 | Catálogo ampliado | 29/10/2026

- **Novo**: Catálogo de aplicativos ampliado de 51 para 97, com 38 novos programas.
- **Melhoria**: Office, Teams, OneDrive, Edge, PowerToys e PC Manager também na página Aplicativos.
- **Correção**: Autodesk DWG TrueView passou a instalar pelo site oficial (o pacote do winget instalava em francês).
- **Correção**: Corrigido o identificador do Access Database Engine; todos os identificadores revalidados.
- **Melhoria**: Cabeçalhos com ícone, botões com relevo e conjuntos em pílula.

## Versão 3.4.0 | Engine Pro | 28/10/2026

- **Melhoria**: Novo nome: Manutenção da Estação passou a se chamar Engine Pro, com o slogan "Seu PC Mais Inteligente".
- **Novo**: Nome do usuário na saudação da tela de abertura.

## Versão 3.3.2 | Abertura rápida | 28/10/2026

- **Correção**: Abertura que levava cerca de 1 minuto passou a carregar em paralelo, em poucos segundos.
- **Novo**: Tela de abertura "Aguarde... Carregando as informações do seu computador".
- **Correção**: Programa passa a abrir sempre na frente das outras janelas.

## Versão 3.3.1 | Lista de aplicativos | 28/10/2026

- **Correção**: Página Aplicativos que não exibia nenhum programa passou a mostrar o catálogo completo em cartões por categoria, com busca e filtro.

## Versão 3.3.0 | Tela inicial completa | 28/10/2026

- **Novo**: Confirmação antes de fechar qualquer programa, com reabertura ao final.
- **Novo**: Tela inicial com processador, memória, placa de vídeo, disco e rede, e saudação conforme o horário.
- **Novo**: Logotipo da empresa no ícone do programa.
- **Correção**: Programa passa a abrir maximizado.

## Versão 3.2.0 | Sobre e Ajuda | 28/10/2026

- **Novo**: Botão Sobre com versão, desenvolvedor e atualização do aplicativo.
- **Novo**: Ajuda embutida.

## Versão 3.1.0 | Layout redesenhado | 28/10/2026

- **Melhoria**: Layout mais bonito e moderno.
- **Novo**: Crédito "Desenvolvido por Mau do TI".

## Versão 3.0.0 | Interface gráfica | 28/10/2026

- **Novo**: Interface gráfica no estilo do Windows 11, com tema claro e escuro e a cor de destaque do Windows.
- **Novo**: Componentes Microsoft: bibliotecas, runtimes e recursos do Windows.

## Versão 2.1.0 | Instalação de aplicativos | 28/10/2026

- **Novo**: Menu de instalação de aplicativos para depois de uma formatação, por winget, Microsoft Store, Chocolatey ou site oficial.
- **Novo**: Programas fechados para limpeza ou atualização são reabertos sozinhos, como estavam.

## Versão 2.0.0 | Manutenção da Estação | 28/10/2026

- **Novo**: Limpeza e manutenção geral do Windows: temporários, navegadores, logs, lixeira, cache do Windows Update, otimização e reparos.
- **Melhoria**: Atualizações e manutenção reunidas em um único programa.
- **Correção**: TeamViewer deixou de causar erro na atualização dos aplicativos.

## Versão 1.0.0 | Primeira versão | 28/10/2026

- **Novo**: Atualização de aplicativos, do Windows e de drivers em um único programa, instalável ou portátil.
- **Novo**: Drivers do fabricante mais novos que os do Windows Update são preservados.

## Origem | Origem do projeto | 26/10/2026

- **Novo**: Comandos do winget para atualizar os aplicativos de uma estação, ponto de partida do Engine Pro.

