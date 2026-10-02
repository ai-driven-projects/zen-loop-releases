# Zen Loop — releases

Instaladores e atualizações do **Zen Loop**: a IA trabalha, você fica zen.

Este repositório existe só para publicar as versões do app. O código-fonte é privado.

## Instalação

Baixe o instalador da [última versão](https://github.com/ai-driven-projects/zen-loop-releases/releases/latest):

| Sistema | Arquivo |
|---|---|
| Windows | `ZenLoop-win-Setup.exe` |
| macOS (Apple Silicon) | `ZenLoop-osx-arm64-Setup.pkg` |
| macOS (Intel) | `ZenLoop-osx-x64-Setup.pkg` |
| Linux | `ZenLoop.AppImage` |

O app se atualiza sozinho a partir das releases daqui (verificação ao abrir, novidades na tela, download e
reinício). Ele **nunca reinicia no meio de uma execução**: oferece instalar quando ela terminar.

> Os binários ainda não são assinados. No macOS, se o Gatekeeper bloquear, use *Abrir* no menu de contexto ou rode
> `xattr -dr com.apple.quarantine "/Applications/Zen Loop.app"`. No Windows, o SmartScreen pode pedir *Mais
> informações → Executar assim mesmo*.

## Problemas e sugestões

Abra uma [issue](https://github.com/ai-driven-projects/zen-loop-releases/issues) com a versão do app
(em *Configurações → Atualizações*), o sistema operacional e o que aconteceu.
