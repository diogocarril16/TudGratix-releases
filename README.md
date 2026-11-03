# TudGratix

APP 100% nativa com recursos de monitor de hardware gratuito para Windows 11 e 10 (22H2), com overlay in-game. Autor: **Eu e o mano Cláudio**.

Este repositório só tem os **os exe, ou a versão portátil**: abre **[Releases](https://github.com/diogocarril16/TudGratix-releases/releases)**
e descarrega `TudGratix-Setup-<versão>.exe` (ou o zip portátil - pode ter alguns problemas) e o `SHA256SUMS.txt`.

**Verifica o ficheiro** (recomendado), no PowerShell<img width="243" height="47" alt="image" src="https://github.com/user-attachments/assets/c19008b9-d546-434e-a8c6-611e604bbb41" />
, na pasta das Transferências:

```powershell
Get-FileHash .\TudGratix-Setup-<versão>.exe -Algorithm SHA256
```

O resultado tem de ser igual ao da linha desse ficheiro no `SHA256SUMS.txt`. Se não for, apaga-o, 100% vai explodir o PC

**Requisitos:** Windows 10 22H2 ou Windows 11, x64. 
A app após a verssão de correçao 0.10.6 procura as atualizações aqui via API e instala-as sozinha, com o vosso consentimento.

As licenças das bibliotecas usadas vão dentro da app (`THIRD-PARTY-NOTICES`).

---

**English:** Free Windows hardware monitor with an in-game overlay, by Diogo Carril. This repository only holds
the installers: open **Releases**, download `TudGratix-Setup-<version>.exe` and `SHA256SUMS.txt`, and check the file
with `Get-FileHash` (it must match its line in `SHA256SUMS.txt`). Windows 10 22H2 or Windows 11, x64. The app checks
for updates here and installs them by itself. Third-party licenses ship inside the app (`THIRD-PARTY-NOTICES`).
