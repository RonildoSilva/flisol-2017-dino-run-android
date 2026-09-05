# Dino Run (FliSoL 2017)

> Módulo Android de um jogo endless runner em LibGDX, desenvolvido durante o Festival Latino-americano de Instalação de Software Livre de 2017.

![status](https://img.shields.io/badge/status-concluído-success) ![libgdx](https://img.shields.io/badge/LibGDX-Android-red) ![java](https://img.shields.io/badge/Java-7-blue)

## Sobre
Atividade prática da oficina de jogos do FliSoL 2017, baseada no tutorial de William Mora. Este repositório contém o módulo Android (lançador, manifesto, recursos e a spritesheet empacotada com TexturePacker) e o APK gerado (`android-release.apk`). O módulo `core` com a lógica do jogo (`GameRun`) não foi versionado.

## Stack
- LibGDX, Android SDK 25 (mínimo 8), Gradle, Android Studio
- TexturePacker para a spritesheet

## Estrutura de pastas
```text
AndroidManifest.xml
src/com/flisol2017/dino/AndroidLauncher.java   inicializa a aplicação LibGDX
assets/spritesheet.pack                        atlas de sprites
res/                                           strings e tema
build.gradle                                   configuração Android e cópia das bibliotecas nativas
android-release.apk                            build final
```

## Como executar
Instale `android-release.apk` em um dispositivo Android ou emulador.

## Status
Concluído para o evento. Não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
