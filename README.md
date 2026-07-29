<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/acervo-logo-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="brand/acervo-logo.svg">
    <img src="brand/acervo-logo.svg" alt="Acervo" width="540">
  </picture>
</p>

<p align="center"><strong>Encontre, organize e controle seus arquivos.</strong></p>

<p align="center">
  <a href="https://github.com/GGuiilhem/Acervo-Releases/releases/latest"><img alt="Última versão" src="https://img.shields.io/github/v/release/GGuiilhem/Acervo-Releases?style=flat-square&color=6d5dfc"></a>
  <a href="https://github.com/GGuiilhem/Acervo-Releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/GGuiilhem/Acervo-Releases/total?style=flat-square&color=1674d1"></a>
  <img alt="Windows" src="https://img.shields.io/badge/Windows-10%20e%2011-1674d1?style=flat-square">
  <img alt="Plataforma" src="https://img.shields.io/badge/plataforma-x64-3f4757?style=flat-square">
</p>

<p align="center">
  <a href="https://github.com/GGuiilhem/Acervo-Releases/releases/latest/download/Acervo-setup.msi"><strong>Baixar o instalador MSI</strong></a>
  ·
  <a href="https://github.com/GGuiilhem/Acervo-Releases/releases/latest/download/Acervo-portable.exe">Baixar a versão portátil</a>
  ·
  <a href="https://github.com/GGuiilhem/Acervo-Releases/releases/latest">Ver a versão mais recente</a>
</p>

## Sobre o Acervo

O **Acervo** é um aplicativo desktop para Windows criado para pesquisar, organizar e transformar grandes conjuntos de arquivos sem bloquear a interface. Todo o processamento principal acontece localmente no computador.

O aplicativo reúne quatro áreas de trabalho:

| Área | O que ela faz |
| --- | --- |
| **Pesquisa de arquivos** | Encontra arquivos por nome ou conteúdo e mostra os resultados enquanto a busca acontece. |
| **Organizar XML** | Extrai ZIPs recursivamente e separa XMLs do eSocial em pastas por evento. |
| **Converter SPED** | Converte arquivos TXT do SPED em XLSX editável, reconstrói os TXT e permite montar consultas visuais. |
| **Utilitários** | Centraliza ferramentas verificadas para manutenção, diagnóstico, aplicativos e drivers do Windows. |

## Principais recursos

### Pesquisa rápida e progressiva

- Pesquisa por **conteúdo** ou **nome do arquivo**, com vários termos separados por linha.
- Resultados apresentados imediatamente, sem esperar o término da varredura.
- Processamento paralelo adaptado à CPU e cache temporário opcional em RAM.
- Expressões regulares, palavra inteira, distinção entre maiúsculas e minúsculas e filtros por extensão, tamanho e data.
- Pesquisa e substituição com confirmação e backup `.bak` opcional.
- Ações em lote para abrir, copiar, mover, recortar e compactar os arquivos selecionados.
- Métricas detalhadas de duração, arquivos por segundo, leitura, comparação, cache e trabalhadores simultâneos.

### Organização de XMLs do eSocial

- Extração nativa e recursiva de ZIPs encontrados dentro de outros ZIPs.
- Identificação de arquivos terminados em `S-0000.xml` e criação automática de uma pasta por evento.
- Preservação do ZIP original e tratamento seguro de nomes repetidos.
- Opção de gerar uma pasta organizada e também um novo ZIP com o resultado.
- Barra de progresso, cronômetro, taxa de XMLs por segundo e cancelamento com limpeza dos resultados parciais.

### Conversor Receitanet/SPED

- Combina vários arquivos TXT em um único XLSX e mantém a identificação e a ordem de cada arquivo original.
- Cria uma planilha por código de registro, com cabeçalhos baseados nos manuais oficiais.
- Reconhece **ECD**, **ECF**, **EFD ICMS/IPI** e **EFD-Contribuições**.
- Rastreia relações entre registros pais e filhos por IDs explícitos.
- Reconstrói um TXT para cada arquivo original e recalcula registros totalizadores quando linhas são adicionadas ou removidas.
- Inclui um **Query Builder visual** para arrastar registros, ligar campos, escolher `INNER` ou manutenção de linhas sem correspondência, aplicar condições e exportar o resultado para outro XLSX.

### Utilitários e integração com o Windows

- Integração com WinUtil, PowerToys, UniGetUI, Sysinternals Suite, Bulk Crap Uninstaller, Winhance e Sophia Script.
- Instalação e atualização por identificadores verificados do WinGet.
- Detecção dos aplicativos já instalados para oferecer a ação **Abrir**.
- Identificação local do fabricante, modelo e adaptadores gráficos, com consulta de drivers pelo Windows Update e suporte oficial.
- Menu de contexto do Explorer para iniciar o Acervo diretamente em uma pasta.
- Notificações do Windows ao concluir pesquisas, organizações e conversões.

## Interface e personalização

- **124 idiomas** disponíveis localmente, incluindo português do Brasil e inglês.
- Oito temas predefinidos: Light, Dark, Slate, Nous, MidNight, Ember, Mono e CyberPunk.
- Temas personalizados com escolha de três cores, nome e armazenamento local.
- Layout adaptável para janelas menores e uso em tela cheia.
- Colunas redimensionáveis e ordenação crescente, decrescente ou desativada.
- Uma única instância do aplicativo aberta por vez.

## Download e instalação

| Opção | Arquivo | Indicação |
| --- | --- | --- |
| **Instalador** | [`Acervo-setup.msi`](https://github.com/GGuiilhem/Acervo-Releases/releases/latest/download/Acervo-setup.msi) | Recomendado. Registra o aplicativo no Windows e habilita notificações, atualização e integração com o Explorer. |
| **Portátil** | [`Acervo-portable.exe`](https://github.com/GGuiilhem/Acervo-Releases/releases/latest/download/Acervo-portable.exe) | Executa sem instalação. Algumas integrações do Windows dependem da instalação pelo MSI. |

### Requisitos

- Windows 10 ou Windows 11 de 64 bits.
- Microsoft Edge WebView2 Runtime, normalmente já instalado no Windows atual.
- Permissão de administrador somente para ações que alteram o sistema ou exigem confirmação do Windows.

## Atualizações automáticas

O Acervo verifica novas versões quando houver conexão com a internet. Ao aceitar uma atualização, o aplicativo baixa o MSI deste repositório, valida sua assinatura e instala a nova versão sem encaminhar o usuário para outra página.

O fluxo de publicação testa, compila e assina cada versão antes de disponibilizar:

- `Acervo-setup.msi` — instalador recomendado;
- `Acervo-setup.msi.sig` — assinatura usada pelo atualizador;
- `Acervo-portable.exe` — executável portátil;
- `latest.json` — manifesto da versão mais recente.

## Segurança e privacidade

- Pesquisas, conversões e organizações são processadas localmente.
- O conteúdo dos arquivos não é enviado ao GitHub nem a outro serviço externo.
- Atualizações são assinadas e os arquivos publicados recebem um resumo SHA-256 verificável na release.
- Operações destrutivas exigem confirmação e os arquivos originais são preservados sempre que aplicável.
- Utilitários externos usam uma lista fechada, origem identificada e autorização explícita do usuário.
- Este repositório público contém somente os arquivos necessários para apresentação, instalação e atualização; o código-fonte não é distribuído aqui.

> Baixe o Acervo somente pelos links desta página ou pelas [releases oficiais](https://github.com/GGuiilhem/Acervo-Releases/releases).

## Sobre o autor

Desenvolvido por [Gabriel Guilhem](https://www.linkedin.com/in/gabriel-guilhem-18140a19b).

© 2026 Gabriel Guilhem · Acervo
