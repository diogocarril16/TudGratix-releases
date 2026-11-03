# TudGratix

Monitor de hardware gratuito para Windows, com overlay in-game. Autor: **Diogo Carril**.

Este repositório só tem os **instaladores**: abre **[Releases](https://github.com/diogocarril16/TudGratix-releases/releases)**
e descarrega `TudGratix-Setup-<versão>.exe` (ou o zip portátil) e o `SHA256SUMS.txt`.

**Verifica o ficheiro** (recomendado), no PowerShell, na pasta das Transferências:

```powershell
Get-FileHash .\TudGratix-Setup-<versão>.exe -Algorithm SHA256
```

O resultado tem de ser igual ao da linha desse ficheiro no `SHA256SUMS.txt`. Se não for, apaga-o.

**Requisitos:** Windows 10 22H2 ou Windows 11, x64. A app procura atualizações aqui e instala-as sozinha.

As licenças das bibliotecas usadas vão dentro da app (`THIRD-PARTY-NOTICES`).

---

**English:** free Windows hardware monitor with an in-game overlay, by Diogo Carril. This repository only holds
the installers: open **Releases**, download `TudGratix-Setup-<version>.exe` and `SHA256SUMS.txt`, and check the file
with `Get-FileHash` (it must match its line in `SHA256SUMS.txt`). Windows 10 22H2 or Windows 11, x64. The app checks
for updates here and installs them by itself. Third-party licenses ship inside the app (`THIRD-PARTY-NOTICES`).
