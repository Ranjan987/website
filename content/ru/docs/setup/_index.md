---
reviewers:
- brendandburns
- erictune
- mikedanese
no_issue: true
title: Настройка
main_menu: true
weight: 30
content_template: templates/concept
---

{{% capture overview %}}

Используйте информацию на этой странице, чтобы найти наиболее подходящее для вас решение по установке и настройке.

Решение о том, как запускать Kubernetes, зависит от доступных ресурсов и необходимого уровня гибкости использования. Запуск Kubernetes возможен практически на чём угодно, от вашего ноутбука или виртуальных машины у облачного провайдера и до физических серверов. Решения позволяют как настроить полностью управляемый кластер запуском единственной команды так и создать пользовательский кластер на физических серверах. 

{{% /capture %}}

{{% capture body %}}

## Решения для запуска на локальной машине

Запуск на локальной машине позволяет легко начать работу с Kubernetes. Можно создавать и тестировать кластер Kubernetes не беспокоясь о трате облачных ресурсов и квотах.

Вам следует выбрать запуск на локальной машине, если вы:

* Пробуете или начинаете работу с Kubernetes
* Локально разрабатываете и тестируете кластер

Выбрать [решение для запуска на локальной машине](/docs/setup/pick-right-solution/#local-machine-solutions).

## Управляемые решения

Управляемые решения позволяют надёжно и удобно создавать и поддерживать кластеры Kubernetes. Они настраивают и управляют кластером самостоятельно, не требуя ручного вмешательства.  

Вам следует выбрать управляемое решение, если вы:

* Хотите получить полностью самоуправляемое решение
* Хотите сконцентрироваться на разработке собственных приложений или сервисов  
* Хотите получить высокую доступность, но у вас нет выделенной команды по обеспечению надёжности приложения (SRE).
* Не имеете ресурсов для размещения и мониторинга собственных кластеров

Выбрать [управляемое решение](/docs/setup/pick-right-solution/#hosted-solutions).

## Облачные решения "под ключ"


Такие решения озволяют создавать кластеры Kubernetes с помощью небольшого количества команд. Эти решения имеют большую поддежку сообществом и активно развиваются. Они могут быть размещены на разнообразных IaaS облачных провайдерах, при этом предлагая большую свободу и гибкость в обмен на приложенные усилия.

Вам следует выбрать облачное решение "под ключ", если вы":

* Хотите получить больший контроль над кластерами, чем позволяют размещённые решения
* Хотите получить больше контроля над оперциями Want to take on more operations ownership 

Выбрать [облачное решение "под ключ"](/docs/setup/pick-right-solution/#turnkey-cloud-solutions)

## Местное резервное решение "под ключ"

Такие решения позволяют с помощью небольшого количества команд создавать кластеры Kubernetes в ваших внутренних, защищённых облачных сетях.

Вам следует выбрать местное резервное решение "под ключ", если:

* Вы хотите развернуть кластер в приватной облачной сети
* У вас есть выделенная команда SRE специалистов
* У вас есть ресурсы для размещения и мониторинга собственных кластеров

Выбрать [местное резервное решение "под ключ"](/docs/setup/pick-right-solution/#on-premises-turnkey-cloud-solutions).

## Пользовательские решения

Пользовательские решения позволяют достичь наибольшей свободы в управлении кластерами, но при этом требуют наибольшей экспертизы. Можно найти такие решения как для размещения на физических серверах, так и у облачных провайдеров на разных операционных системах.

Выбрать [пользовательское решение](/docs/setup/pick-right-solution/#custom-solutions).

{{% /capture %}}

{{% capture whatsnext %}}
Перейти к [выбору подходящего решения](/docs/setup/pick-right-solution/), чтобы ознакомить с полным списком доступных решений.
{{% /capture %}}
