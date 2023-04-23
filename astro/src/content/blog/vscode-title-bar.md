---
author: Sat Naing
pubDatetime: 2023-04-23T14:25:00Z
title: How to custom the title bar in Visual Studio Code on Linux

postSlug: vscode-title-bar-linux
featured: true
draft: false
tags:
  - linux
  - vscode
  - vscode-title-bar
ogImage: ""
description: In this article, I will show you how to get rid of the big title bar in VSCode on Linux. This is especially useful if you're using a small screen or just want to save some space.
---

<details>
<summary>Version française</summary>

# Reduire la barre de titre de VS Code sur Linux

Si vous utilisez VS Code sur Linux, vous avez peut-être remarqué que la barre de titre prend beaucoup de place et que cela peut être gênant, surtout si vous utilisez un petit écran. Heureusement, il est possible de la reduire.

Pour cela, il faut ajouter la ligne suivante dans le fichier `settings.json` de VS Code :

`"window.titleBarStyle": "custom"`

Ensuite, il faut redémarrer VS Code pour que les changements prennent effet.

Voici un avant/après pour illustrer la différence :

Avant :

<img src="/assets/vscode-title-bar-before.png" alt="vscode title bar before">

Après :

<img src="/assets/vscode-title-bar-after.png" alt="vscode title bar after">

</details>

## English version

If you are using VS Code on Linux, you may have noticed that the title bar takes up a lot of space and can be annoying, especially if you have a small screen. Fortunately, it is possible to remove it.

To do this, you need to add the following line to the `settings.json` file of VS Code:

`"window.titleBarStyle": "custom"`

Then, you need to restart VS Code for the changes to take effect.

Here is a before/after to illustrate the difference:

Before:

<img src="/assets/vscode-title-bar-before.png" alt="vscode title bar before">
After:

![After](vscode-title-bar-after.png)
