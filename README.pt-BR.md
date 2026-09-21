# 1stChip

**As especificações e os drivers do seu PC em um relance.**

[English](README.md) · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · Português (Brasil) · [Français](README.fr.md)

> Este documento é uma tradução. Em caso de divergência, prevalece a [versão em coreano](README.ko.md).

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20x64-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-0.9.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/1stchip?lang=pt)

![1stChip screenshot](images/1stchip-ko.webp)

## Visão geral

O 1stChip mostra o que há dentro do seu PC — CPU, placa-mãe, placa de vídeo, multimídia, placa de rede e outros dispositivos — em uma única tela, junto com a versão e a data do driver instalado para cada um.

Funciona até em um Windows recém-instalado: um dispositivo aparece na lista com o fabricante mesmo quando ainda não há driver e o Gerenciador de Dispositivos mostra apenas "Dispositivo desconhecido". Isso é muito útil logo após uma instalação limpa, quando você precisa descobrir quais drivers ainda faltam.

É só descompactar e executar. Sem instalação, sem direitos de administrador, sem nada mais para instalar.

## Recursos

- **Resumo do hardware em uma tela** — CPU, placa-mãe, placa de vídeo, multimídia, placa de rede e outros dispositivos, cada um com o logotipo do fabricante.
- **Versão e data do driver instalado** para cada dispositivo, exibidas abaixo do nome.
- **Funciona sem drivers** — dispositivos sem driver também aparecem com o fabricante e são marcados com `!`.
- **Verificação de atualização de drivers** — a lista é comparada com o servidor do 1stChip; quando um driver mais novo é conhecido, o dispositivo é marcado e uma dica mostra a versão disponível.
- **Um clique até a página do driver** — clique na marca `!` para abrir a página do driver daquele dispositivo.
- **Linha do sistema** na parte inferior: clock da CPU, memória total e edição/versão do Windows.
- **Dispositivos duplicados são agrupados** — dispositivos idênticos aparecem uma só vez como `(×N)`.
- **Portátil** — um único EXE que você pode levar em um pen drive.
- **Não precisa de direitos de administrador.**
- **Segue o Windows** — modo escuro ou claro conforme o tema de aplicativos do Windows; idioma da interface conforme o idioma de exibição do Windows (inglês, coreano).

## Download / Instalação

| Pacote | Link |
|---|---|
| Instalador | [Baixar](https://down.kilho.net/1stchip?lang=pt) |
| Portátil (ZIP) | [Baixar](https://down.kilho.net/1stchip?lang=pt&nosetup) |

O 1stChip está disponível como aplicativo **portátil**: baixe o ZIP, descompacte em qualquer lugar e execute `1stChip.exe` — não precisa instalar. Também funciona normalmente a partir de um pen drive.

## Como usar

### Fluxo básico

1. Execute `1stChip.exe`. A lista de hardware aparece em poucos segundos.
2. A lista é agrupada assim: **CPU → Placa-mãe → Placa de vídeo → Multimídia → Placa de rede → Outros dispositivos**. A primeira linha de cada categoria é o dispositivo representativo; as demais seguem em cinza.
3. Abaixo do nome de cada dispositivo você vê a **versão e a data do driver instalado**.
4. Uma marca amarela `!` indica que há algo a verificar. Passe o mouse para ver o motivo e **clique** para abrir no navegador a página do driver daquele dispositivo.
5. A parte inferior da janela mostra o clock da CPU, o tamanho da memória e a versão do Windows.

A lista é lida uma vez na inicialização. Depois de instalar um driver, feche e execute o 1stChip novamente para ver o resultado.

### A janela

| Parte | O que mostra |
|---|---|
| Logotipo | Logotipo do fabricante (iniciais para fabricantes sem logotipo) |
| Nome do dispositivo | O nome atribuído pelo Windows. Dispositivos idênticos são agrupados como `(×2)` |
| Segunda linha | Versão · data do driver instalado |
| `!` | Sem driver / com problema / driver mais novo conhecido — passe o mouse para saber qual, clique para a página do driver |
| Painel inferior | Clock da CPU (base) · tamanho da memória · sistema operacional |

### Como…

**Você acabou de instalar o Windows e não sabe quais drivers instalar**
Execute o 1stChip e procure os dispositivos marcados com `!`. Se ao passar o mouse aparecer "Nenhum driver está instalado", aquele dispositivo está sem driver. Clique em `!` para abrir a página do driver, instale e execute o 1stChip de novo para confirmar que o `!` sumiu. Se o PC está sem Internet porque falta o driver de rede, use o 1stChip para ver o fabricante e o modelo da placa de rede e baixe o driver em outro PC.

**O Gerenciador de Dispositivos mostra um "Dispositivo desconhecido"**
O Gerenciador de Dispositivos não consegue nomear um dispositivo sem driver, mas o 1stChip identifica o fabricante e a categoria sem ele. Encontre o dispositivo na categoria e clique em `!`.

**Verificar se os drivers estão atualizados**
Quando um driver mais novo é conhecido, o dispositivo recebe um `!` e, ao passar o mouse, aparece "Você pode atualizar para a versão x.x.x". Sem `!`, ele está atualizado até onde se sabe.

**Ver as especificações do PC rapidamente**
Leia só a primeira linha (dispositivo representativo) de cada categoria e você terá CPU, chipset da placa-mãe, placa de vídeo, som e placa de rede em um relance, com o tamanho da memória e a versão do Windows no painel inferior. Útil para escrever um anúncio de venda ou comparar com os requisitos recomendados de um jogo.

**Vários dispositivos idênticos**
Dispositivos idênticos são agrupados em uma linha com um contador como `(×2)`. Dispositivos estruturais com os quais você nunca precisa se preocupar — hubs USB, pontes internas — ficam fora da lista.

**Verificar muitos PCs**
O 1stChip não precisa de instalação nem de direitos de administrador, então guarde-o em um pen drive e execute em cada PC. Ele não deixa nada no PC em que roda.

**Em um PC sem Internet**
A lista de hardware e os detalhes dos drivers instalados funcionam totalmente offline. Só as marcas de "driver mais novo disponível" e a página do driver aberta ao clicar em `!` precisam de Internet.

**A janela está escura (ou clara), ou em inglês**
O 1stChip segue o Windows. Mude claro/escuro em Windows *Configurações → Personalização → Cores → Modo de aplicativo*, e o idioma da interface pelo idioma de exibição do Windows (coreano → coreano, qualquer outro → inglês).

Apenas uma instância roda por vez; abrir de novo traz a janela já existente para a frente.

## Configuração

Não há janela de configurações. O 1stChip segue o Windows automaticamente:

| Item | Origem |
|---|---|
| Modo claro / escuro | Windows *Configurações → Personalização → Cores → Modo de aplicativo* |
| Idioma da interface | Idioma de exibição do Windows (coreano → coreano, qualquer outro → inglês) |
| Formato de data | Localizado (`yyyy-mm-dd` em coreano, `mm-dd-yyyy` em inglês) |

## Requisitos

- Windows 10 ou Windows 11, **64 bits**
- Não requer direitos de administrador
- Conexão com a Internet é opcional — usada apenas para a verificação de atualização de drivers

## Atualizações

O 1stChip **não** se atualiza sozinho. Novas versões são publicadas manualmente após verificação interna e anunciadas na [página do 1stChip](https://v2.kilho.net/1stchip). Veja o [aviso sobre a política de atualizações](https://en.kilho.net/archives/notice/2940).

**Histórico de versões**

| Versão | Data | Notas |
|---|---|---|
| 0.9.0 | 2026-09-18 | Primeira versão |

## Licença

O 1stChip é **Freeware**.

Você pode usá-lo em qualquer lugar — em casa, no escritório, em escolas e em órgãos públicos — e redistribuí-lo livremente em sua forma não modificada.

## Links

- Site: <https://v2.kilho.net/1stchip>
- Fórum: <https://groups.google.com/g/kilhonet>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
