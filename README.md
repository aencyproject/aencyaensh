<div align="center">
	<br />
	<p>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://www.aency.xyz/cdn/img/aency_banner_rc.png" width="546" alt="discord.js" /></a>
	</p>
	<br />
	<p>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Versão-1.0-red?labelColor=gray&style=plastic&logoWidth=0" alt="Versão"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Distribuição-Estável-red?labelColor=gray&style=plastic&logoWidth=0" alt="Distribuição"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Licensa-Pública-red?labelColor=gray&style=plastic&logoWidth=0" alt="Licensa"/></a>
		<br>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Desde-2022-orange?labelColor=gray&style=plastic&logoWidth=0" alt="Desde" /></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Criadora-Aency-orange?labelColor=gray&style=plastic&logoWidth=0" alt="Criadora"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Diretor-Gabriel-orange?labelColor=gray&style=plastic&logoWidth=0" alt="Diretor"/></a>
		<br>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Projetos-9-green?labelColor=gray&style=plastic&logoWidth=0" alt="Projetos"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Extenções-0-green?labelColor=gray&style=plastic&logoWidth=0" alt="Extenções"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Pacotes-0-green?labelColor=gray&style=plastic&logoWidth=0" alt="Pacotes"/></a>
		<a href="https://github.com/aencyco/aencyapp/"><img src="https://img.shields.io/badge/Bibliotecas-0-green?labelColor=gray&style=plastic&logoWidth=0" alt="Bibliotecas"/></a>
		<br>
		<a href="https://dsc.gg/aency" ><img src="https://img.shields.io/badge/Discord-Aency-blue?labelColor=gray&style=plastic&logoWidth=0" /></a>
	</p>
</div>

## Sobre
> [!NOTE]
> Esse repositório contém o código fonte do aency.app. O projeto aency.app é uma ferramenta CLI de utilidades para usuários de Linux aproveitarem do sistema de uma maneira simples, antiga e funcional. Sem a necessidade de um monte de espaço ocupado pelo programa, pelo simples fato dele ser super leve. Além de conter o aency.app em si, ele também contem Shanny, que é o terminal padrão do aency.app. Veja sobre as teclas do Shanny e tudo mais sobre abaixo!

## Tabela de Conteúdos
- Básico
  - [Sobre][#sobre]
- Instalação
  - [Time Tracking](#time-tracking)
  - [Note Taking and Lists](#note-taking-and-lists)
- [Utilities](#utilities)
  - [macOS](#macos)
  - [Terminal Sharing Utilities](#terminal-sharing-utilities)
  - [Network Utilities](#network-utilities)
  - [Theming and Customization](#theming-and-customization)
  - [Shell Utilities](#shell-utilities)
  - [System Interaction Utilities](#system-interaction-utilities)
  - [Markdown](#markdown)
  - [Security](#security)
  - [Math](#math)
  - [Weather](#weather)
  - [Browser Replacement](#browser-replacement)
  - [Internet Speedtest](#internet-speedtest)
- [Command Line Learning](#command-line-learning)
- [Data Manipulation](#data-manipulation)
  - [Processors](#processors)
  - [JSON](#json)
  - [YAML](#yaml)
  - [Columns](#columns)
  - [Text](#text)
- [Files and Directories](#files-and-directories)
  - [File Managers](#file-managers)
  - [Deleting, Copying, and Renaming](#deleting-copying-and-renaming)
  - [Files](#files)
  - [File Sync/Sharing](#file-syncsharing)
  - [Directory Listing](#directory-listing)
  - [Directory Navigation](#directory-navigation)
  - [Search](#search)
- [Version Control](#version-control)
  - [Git](#git)
  - [GitHub](#github)
  - [Emoji](#emoji)
- [Images](#images)
  - [Gif Creation](#gif-creation)
  - [Image Conversion](#image-conversion)
- [Screensavers](#screensavers)
- [Graphics](#graphics)
- [Just for Fun](#just-for-fun)
  - [Emoji](#emoji-1)
- [Other Awesome Lists](#other-awesome-lists)
- [License](#license)

## Instalação
> [!WARNING]
> Antes de começar a instalação do aency.app, verifique se seu dispositivo atende aos seguintes requisitos.

- Você instalou a versão mais recente do `Python`
- Você tem uma máquina `Windows ou Linux`. Atualmente, ainda estamos portando o app pra Linux.
- Saber como mexer em um Terminal sem GUI.
- Ler a nossa documentação.

> **Linux**
```
Baixe nossa source pelo botão de download e use o app.
```

> **Windows**
```
Atualmente não foi concluído.
```

## Atalhos do Shanny

| Atalho | Descrição |
| --- | ----------- |
| <kbd>^</kbd>+<kbd>Shift</kdb>+<kbd>C</kdb> | Copia um texto no Shanny. |
| <kbd>^</kbd>+<kbd>Shift</kdb>+<kbd>X</kdb> | Recorta um texto no Shanny. |
| <kbd>^</kbd>+<kbd>Shift</kdb>+<kbd>V</kdb> | Cola um texto no Shanny |
| <kbd>^</kbd>+<kbd>Shift</kdb>+<kbd>A</kdb> | Seleciona todos os textos no Shanny. |
| <kbd>^</kbd>+<kbd>Shfit</kdb>+<kbd>L</kdb> | Limpa a tela do Shanny. |
| <kbd>ALT</kbd>+<kbd>F4</kdb> | Finaliza o processo do Shanny. |

## Pacotes
> [!TIP]
> Os pacotes, sistemas, extenções e bibliotecas são utilidades para o usuário. Elas servem para expandir a customização e aumentar a produtividade do aency.app.
> [!WARNING]
> Só lembrando que por enquanto nenhum está funcionando!
- `@aency.app` - App principal, leia mais no "Sobre".
- `@aency.xyz` - Pacote e coleção de utilidades adicionais externas da comunidade.
- `@aency.net` - Sistema de hospedagem de "Mini Sites CLI" no app.
- `@aency.any` - Pacote inicial utilizado para carregamento do AnyScript.
- `@aency.src` - Um pacote utilizado para hospedar bibliotecas e contribuir no app.
- `@aency.cfg` - Um pacote utilizado para armazenamento e carregamento de arquivos Asson.

## TODO
- [ ] Completar a 1.0
- [ ] Integração com IA
- [ ] Criador Extenções de Extenções da Comunidade
- [ ] Package Manager
- [ ] BASH e ZSH Mode
- [x] Escape Mode
- [x] Github

## Contribuindo
> [!TIP]
> Este é um jeito resumido de como você pode contribuir. Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

> [!IMPORTANT]
> Para contribuir com o desenvolvimento do aency.app, siga as etapas a seguir corretamente.

```
1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.
```
