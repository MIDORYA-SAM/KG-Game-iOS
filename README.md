# KG Adventure — projeto iOS
Jogo 2D HTML5 encapsulado em aplicativo nativo SwiftUI/WKWebView. Compilação na nuvem, via GitHub Actions.

## Arquivos que devem estar no repositório
- `.github/workflows/build.yml` — compila e publica o IPA sem assinatura
- `project.yml` — configura o projeto Xcode (XcodeGen)
- `Game/App.swift` — inicia o aplicativo nativo
- `Game/Web/index.html` — código completo do jogo

## Compilar
1. Crie um repositório **público** no GitHub e envie a estrutura acima.
2. Abra Actions > Compilar IPA > Run workflow.
3. Ao finalizar, abra a execução e baixe `KGGame-IPA` em Artifacts.
4. Abra o ZIP de artifacts no app Arquivos. Dentro estará `KGGame.ipa`.

## Importante
O IPA **não é assinado**. Para instalar num iPhone real, precisa de assinatura/provisionamento, por exemplo pelo AltStore Classic com o AltServer configurado. Não coloque credenciais Apple no GitHub.
