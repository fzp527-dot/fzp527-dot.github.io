---
layout: page
title: Architecture
---

How our architecture changed over the project. The final version is described in Arch1.

## Version 1 (25 October)
From the CRC cards: Player and Goose inherit from Entity, and GameScreen owns almost everything.

![Class diagram v1](assets/images/v1-class.png)

## Version 2 (1 November)
Moved to ECS, moved the rules into GameSession, and added the Listener, Factory and Façade patterns.

![Class diagram C v2](assets/images/v2-classC.png)
![Class diagram D v2](assets/images/v2-classD.png)

## Version 3: implementation (16 November)
Own ECS instead of Ashley, stress bar fills up, GameViewport, Long Boi replaces ProtectiveGeese.

![Component diagram](assets/images/v3-component.png)
![Class diagram A](assets/images/v3-classA.png)
![Class diagram B](assets/images/v3-classB.png)
![Class diagram C](assets/images/v3-classC.png)
![Class diagram D](assets/images/v3-classD.png)
![State machine](assets/images/v3-state.png)
![Bread Van sequence](assets/images/v3-breadvan.png)
![Long Boi sequence](assets/images/v3-longboi.png)
