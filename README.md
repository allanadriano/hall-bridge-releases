# Hall Bridge: releases

Versões publicadas do app Android **Hall Bridge**. Este repositório não tem código-fonte, só os arquivos de cada versão.

Cada release traz:
- `app.apk`: o instalador;
- `update.json`: lido pelo app para saber se há versão nova (`versionCode`, `versionName`, `apkUrl`, `sha256`, `notes`, `minVersionCode`).

O app consulta `releases/latest/download/update.json`. As releases são criadas pelo servidor quando alguém clica em "Publicar versão"; não crie releases à mão aqui.
