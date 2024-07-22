---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Травы

Травы являются игровыми элементами, которые игрок может собирать. Эти элементы являются шаблонами сущностей, которые вы можете размещать на уровне.

Все шаблоны трав хранятся в папке **`gameplay\containers\herbs`**. Эти шаблоны реализуют класс [`W3Herb`](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/w3refillablecontainer/w3container/w3herb.md), что делает их контейнерами для лута и позволяет им обладать всеми свойствами классов [`W3Container`](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/w3refillablecontainer/w3container/) и [`W3LockableEntity`](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/).

## Узлы шаблона

`CInteractionComponent`

`CSwitchableFoliageComponent`

`СInventoryComponent`
