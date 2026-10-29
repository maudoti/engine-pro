# Histórico completo do Engine Pro

Todas as versões, da mais recente à primeira, com cada novidade, melhoria e correção.

## Versão 4.3.4 | Balão discreto de atualização concluída perto do relógio,... | 29/10/2026

- **Novo**: Balão discreto de atualização concluída perto do relógio, no máximo um a cada 4 horas.
- **Melhoria**: O ícone perto do relógio passa a usar a versão nova sozinho, sem esperar o próximo logon.

## Origem | Reparo do sistema legível Y girando como moeda Verificação de atualização sem atraso Modo IA e nova tela de execução Recursos restritos à equipe de TI (estável) Modo técnico Atualização automática pelo GitHub Monitor como serviço do Windows Monitor, sensores e avisos Reparos, Ajustes do sistema e IAs Office, Project, Visio e Ferramentas do Windows Visual profissional Instalação de aplicativos mais robusta Catálogo ampliado Engine Pro Abertura rápida Lista de aplicativos Tela inicial completa Sobre e Ajuda Layout redesenhado Interface gráfica Instalação de aplicativos Manutenção da Estação Primeira versão Origem do projeto | 29/10/2026

- **Correção**: Saída do reparo dos arquivos do sistema (SFC) legível e com acentos, sem as linhas repetidas de porcentagem.
- **Novo**: Ao pedir uma atualização durante uma tarefa, ela é instalada automaticamente assim que a tarefa terminar.
- **Melhoria**: A tela de execução não repete linhas idênticas em sequência.
- **Melhoria**: O Y de espera voltou a girar como uma moeda, sempre de pé, mantendo o tamanho pequeno.
- **Correção**: A verificação de atualizações passou a enxergar a versão nova logo após a publicação, sem esperar até 10 minutos pela cópia guardada do GitHub.
- **Novo**: Modo IA: nota de saúde de 0 a 100 e diagnóstico que cruza travamentos de programas, telas azuis, erros de disco e de hardware, saúde do SSD, estabilidade, tempo de inicialização, Windows Update, DNS, drivers e bateria.
- **Novo**: Piloto automático do Modo IA: autocorreção silenciosa (DNS, relógio, WMI, antivírus), manutenção com o computador parado e aprendizado do horário de uso.
- **Novo**: Previsões: quando o disco vai encher, vida útil do SSD, saúde da bateria e índice de estabilidade.
- **Novo**: Nova tela de execução: Y do logotipo girando dentro de um anel e porcentagem subindo em tempo real até 100%.
- **Novo**: 12 novos reparos: diagnóstico da rede, proxy, compartilhamento na rede, Print to PDF, aplicativos do Windows, áudio, senhas salvas do Office, ponto de restauração, WMI, políticas do domínio, energia padrão e relatório de diagnóstico.
- **Melhoria**: Y girando como símbolo de espera em todas as telas que precisam aguardar, sumindo ao terminar.
- **Melhoria**: Instalador: agendamento simplificado em uma única escolha, com "Não agendar" selecionado.
- **Correção**: O serviço do monitor não é mais criado quando a opção do monitor está desmarcada no instalador.
- **Melhoria**: Liberação no canal estável da restrição do Editor do Registro e do BitLocker.
- **Novo**: Modo técnico (Ctrl+Shift+F12) para a equipe de TI.
- **Melhoria**: Editor do Registro e aviso do BitLocker ocultos para os usuários e visíveis só no modo técnico.
- **Novo**: Atualização automática: o serviço consulta o GitHub a cada 2 horas e instala em silêncio, esperando terminar qualquer tarefa em andamento.
- **Novo**: Assinatura digital das versões: o Engine Pro recusa qualquer instalador sem a assinatura correta, mesmo se a conta do GitHub for invadida.
- **Novo**: Canais Estável e Teste, escolhidos por computador no Sobre.
- **Novo**: Site de download e repositório público no GitHub.
- **Melhoria**: Número da versão escolhido automaticamente na compilação.
- **Novo**: Serviço "Engine Pro Monitor": liga junto com o computador, antes do logon, e roda os sensores com permissão total.
- **Melhoria**: Reinício automático do monitor em caso de falha.
- **Melhoria**: O ícone perto do relógio passa a só exibir os avisos quando o serviço está ativo.
- **Novo**: Monitor em segundo plano com ícone perto do relógio.
- **Novo**: Sensores: antivírus (com reparo automático), memória acima de 95% (no máximo 1 limpeza por hora), disco acima de 90%, programas suspeitos, impressora e spooler travados e sugestões de melhoria.
- **Novo**: Avisos em vermelho na tela inicial, com níveis Tranquilo, Comum, Severo e Crítico, sem janelas pop-up.
- **Novo**: Programas desconhecidos: opções "Conheço" e "Não conheço" (encerra, remove da inicialização e envia para a quarentena).
- **Novo**: Reparos do Office (completo), Outlook, Teams, OneDrive, WebView2 e Antivírus do Windows.
- **Novo**: Página Reparos com 18 reparos de um clique: rede, impressoras, barra de tarefas, Explorador, atalhos quebrados, fontes, relógio, Office e outros.
- **Novo**: Página Ajustes do sistema: programas que iniciam com o Windows, tempos de tela, suspensão e hibernação, plano de energia, proteção de tela e reinício programado.
- **Novo**: Categoria Inteligência artificial: Claude, ChatGPT, Copilot, Perplexity Comet, Ollama, LM Studio, Jan e GPT4All.
- **Novo**: Microsoft 365 Apps (empresas e grandes empresas), Project e Visio instalados pela Ferramenta de Implantação do Office.
- **Novo**: Visio Viewer gratuito.
- **Novo**: 26 atalhos para as ferramentas de manutenção do próprio Windows.
- **Melhoria**: Banners em degradê em todas as páginas, cartões com sombra e botões principais em degradê.
- **Novo**: Identidade própria na barra de tarefas, com o ícone do Engine Pro, voltando maximizado ao clicar.
- **Melhoria**: Removidos aplicativos que não são ferramentas de trabalho (Deezer, Telegram, Discord, Spotify, G HUB e Razer Synapse).
- **Novo**: PDFTools 1.3, com o Java instalado junto automaticamente.
- **Melhoria**: Erros do winget explicados em português e nova tentativa automática em falhas temporárias.
- **Melhoria**: Rotas alternativas de instalação para BIMcollab Zoom e Revo Uninstaller.
- **Melhoria**: Logotipo com a chave de reparo ao lado do Y.
- **Novo**: Catálogo de aplicativos ampliado de 51 para 97, com 38 novos programas.
- **Melhoria**: Office, Teams, OneDrive, Edge, PowerToys e PC Manager também na página Aplicativos.
- **Correção**: Autodesk DWG TrueView passou a instalar pelo site oficial (o pacote do winget instalava em francês).
- **Correção**: Corrigido o identificador do Access Database Engine; todos os identificadores revalidados.
- **Melhoria**: Cabeçalhos com ícone, botões com relevo e conjuntos em pílula.
- **Melhoria**: Novo nome: Manutenção da Estação passou a se chamar Engine Pro, com o slogan "Seu PC Mais Inteligente".
- **Novo**: Nome do usuário na saudação da tela de abertura.
- **Correção**: Abertura que levava cerca de 1 minuto passou a carregar em paralelo, em poucos segundos.
- **Novo**: Tela de abertura "Aguarde... Carregando as informações do seu computador".
- **Correção**: Programa passa a abrir sempre na frente das outras janelas.
- **Correção**: Página Aplicativos que não exibia nenhum programa passou a mostrar o catálogo completo em cartões por categoria, com busca e filtro.
- **Novo**: Confirmação antes de fechar qualquer programa, com reabertura ao final.
- **Novo**: Tela inicial com processador, memória, placa de vídeo, disco e rede, e saudação conforme o horário.
- **Novo**: Logotipo da empresa no ícone do programa.
- **Correção**: Programa passa a abrir maximizado.
- **Novo**: Botão Sobre com versão, desenvolvedor e atualização do aplicativo.
- **Novo**: Ajuda embutida.
- **Melhoria**: Layout mais bonito e moderno.
- **Novo**: Crédito "Desenvolvido por Mau do TI".
- **Novo**: Interface gráfica no estilo do Windows 11, com tema claro e escuro e a cor de destaque do Windows.
- **Novo**: Componentes Microsoft: bibliotecas, runtimes e recursos do Windows.
- **Novo**: Menu de instalação de aplicativos para depois de uma formatação, por winget, Microsoft Store, Chocolatey ou site oficial.
- **Novo**: Programas fechados para limpeza ou atualização são reabertos sozinhos, como estavam.
- **Novo**: Limpeza e manutenção geral do Windows: temporários, navegadores, logs, lixeira, cache do Windows Update, otimização e reparos.
- **Melhoria**: Atualizações e manutenção reunidas em um único programa.
- **Correção**: TeamViewer deixou de causar erro na atualização dos aplicativos.
- **Novo**: Atualização de aplicativos, do Windows e de drivers em um único programa, instalável ou portátil.
- **Novo**: Drivers do fabricante mais novos que os do Windows Update são preservados.
- **Novo**: Comandos do winget para atualizar os aplicativos de uma estação, ponto de partida do Engine Pro.

