<p align="center"><img src="docs/icone.png" width="96" alt="Engine Pro"></p>
<h1 align="center">Engine Pro</h1>
<p align="center"><b>Seu PC Mais Inteligente</b><br>Manutenção, atualização, reparo e monitoramento de estações Windows.</p>

---

## Download

A versão mais recente fica na página **[Releases](../../releases/latest)** e no site do projeto.

| Canal | Para quem | Arquivo de versão |
|---|---|---|
| **Estável** | Todas as estações | [`docs/canais/estavel.json`](docs/canais/estavel.json) |
| **Teste** | Estações de homologação | [`docs/canais/teste.json`](docs/canais/teste.json) |

### Instalação silenciosa (implantação em massa)

```
EnginePro_Setup_X.Y.Z.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

## Atualização automática

O serviço **Engine Pro Monitor**, presente em cada estação, consulta o canal configurado **a cada 2 horas**.
Quando encontra uma versão nova, ele:

1. confere a **assinatura digital** da versão com a chave pública embutida no programa;
2. baixa o instalador do release e confere o **SHA256**;
3. espera não haver nenhuma tarefa do Engine Pro em andamento;
4. instala em silêncio e registra um aviso na tela inicial.

Versões sem assinatura válida são recusadas, mesmo que sejam publicadas aqui. Por isso,
a chave privada de assinatura **nunca** é enviada a este repositório.

## Estrutura

```
docs/                 site do projeto (GitHub Pages)
  index.html          página de download
  canais/estavel.json versão liberada para todas as estações
  canais/teste.json   versão em homologação
  versoes.json        histórico exibido no site
  chave-publica.xml   chave pública que confere as assinaturas
CHANGELOG.md          histórico de versões
```

---
<sub>Desenvolvido por Mau do TI.</sub>
