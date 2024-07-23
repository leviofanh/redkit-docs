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

Все шаблоны трав хранятся в папке `gameplay\containers\herbs`. Эти шаблоны реализуют класс [W3Herb](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/w3refillablecontainer/w3container/w3herb.md), что делает их контейнерами для лута и позволяет им обладать всеми свойствами классов [W3Container](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/w3refillablecontainer/w3container/) и [W3LockableEntity](../../scripting/classes/centity/cperistententity/cgameplayentity/w3lockableentity/).

Для удобного размещения трав по уровню используйте инструмент [Gardener](../../level-design/gardener.md).&#x20;

{% hint style="warning" %}
При использовании Gardener травы могут не отображаться сразу, а только после сохранения уровня. Чтобы увидеть травы до сохранения, включите опцию **Containers** в настройках дебага редактора.
{% endhint %}

## Узлы шаблона

* CInteractionComponent
* CSwitchableFoliageComponent
* СInventoryComponent
