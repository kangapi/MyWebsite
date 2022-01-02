---
author: "Kangapi"
title: "Memo plugin minecraft"
date: "2021-12-29"
description: "Guide to create a website with Hugo and hosting with Github Pages"
tags: ["Minecraft", "Java"]
ShowToc: true
ShowBreadCrumbs: false
---

## Requirement

* [IntelliJ IDEA](https://www.jetbrains.com/fr-fr/idea/), The Community edition is sufficient
* The plugin [Minecraft Developement](https://plugins.jetbrains.com/plugin/8327-minecraft-development) for IntelliJ IDEA

## Create a new project

1. Click on **new project**
    ![new-project](images/IntelliJ-main.png)
2. Select **Minecraft** and **Spigot Plugin**
    ![choose-plugin](images/choose-plugin.png)
3. Enter `me.kangapi` in the field **GroupId** and a `PluginName` in **ArtifactId** and click **Next**
    ![build-settings](images/build-settings.png)
4. You can change the **Minecraft Version** and set a **Description**
    ![spigot-settings](images/spigot-settings.png)
5. Enter the same **Plugin Name** as in step 4 and click **Finish**
    ![finish](images/finish.png)

## Run a Project

Click on the **green play button**
    ![run-project](images/run-project.png)