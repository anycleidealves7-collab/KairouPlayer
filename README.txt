Kairou Player — projeto Android com compilação automática

O app abre https://kairou.space/ dentro de uma WebView. Este ZIP ainda NÃO contém o APK.

COMO GERAR O APK PELO CELULAR (usando GitHub Actions):
1. Entre em https://github.com/ e crie/acesse sua conta.
2. Crie um repositório novo (pode ser privado).
3. Envie os arquivos e pastas deste ZIP para a raiz do repositório, incluindo a pasta oculta .github/workflows.
4. Abra a aba Actions do repositório.
5. Se aparecer a confirmação para permitir workflows, confirme.
6. Abra “Build Kairou Player APK” e toque em “Run workflow” (ou aguarde a compilação automática após enviar os arquivos).
7. Quando terminar com sucesso, abra a execução e baixe “KairouPlayer-APK” na seção Artifacts.
8. Extraia o arquivo baixado e instale app-debug.apk no Android.

Observações:
- O build depende dos serviços do GitHub e de compatibilidade atual das ferramentas Android.
- A reprodução depende do site, de seus servidores e da compatibilidade do Android System WebView.
- O projeto não inclui rastreamento, contas próprias ou coleta adicional de dados.
