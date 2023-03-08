---
id: writing-style
title: Общие правила написания текстов
sidebar_label: General writing guidelines
description: При написании текстов следуйте приведенным ниже указаниям.
keywords:
  - docs
  - matic
  - polygon
  - documentation
  - writing
  - contribute
  - style
image: https://wiki.polygon.technology/img/polygon-wiki.png
slug: writing-style
---

Это руководство посвящено лучшим рекомендациям по написанию технической документации и
стилистическим нормам, которых следует придерживаться при разработке документации для вики Polygon.
Цель этого руководства — помочь соавторам писать четкие, краткие и последовательные
тексты. Команда Polygon рассматривает вики Polygon как официальный продукт в составе документации.

## Основные правила {#primary-guidelines}

Мы считаем, что согласованный дизайн делает Polygon особенным, и мы
стремимся сохранить эту определяющую характеристику. Команда Polygon рассматривает вики Polygon
как продукт в составе официальной документации. Мы с самого начала установили ряд правил, благодаря которым новые
вклады будут только улучшать весь проект в целом:

- **Качество**: код в проекте Polygon должен соответствовать правилам стиля, иметь
достаточно тестовых примеров, описательных сообщений и доказательств того, что вклад не нарушает никаких обязательств по совместимости, не вызывает некорректного использования функций и
прошел качественную проверку коллегами.
- **Размер**: культура проекта Polygon основана на небольших запросах на извлечение, которые отправляются регулярно. Чем больше будет запрос на извлечение, тем более вероятно, что вас попросят
отправить его повторно как серию самодостаточных и доступных для индивидуальной проверки запросов на извлечение.
- **Удобство обслуживания**: если функция требует постоянного обслуживания (например, поддержка определенной базы данных), мы можем попросить вас взять на себя ответственность за
обслуживание этой функции.

Руководство по стилю основано на следующих общих руководствах по стилю:

> Если вы не найдете ответ на вопрос по стилю, тону или терминологии
> в этом руководстве, используйте следующие ресурсы.

- [Руководство по стилю Google](https://github.com/google/styleguide/blob/gh-pages/docguide/style.md)
- [Оксфордское руководство по стилю](https://global.oup.com/academic/product/new-oxford-style-manual-9780198767251?cc=nl&lang=en&)
- [Общее руководство по стилю Microsoft](https://docs.microsoft.com/en-us/style-guide/welcome/)

### Генератор статичных сайтов {#static-site-generator}

Вики-ресурс построен на основе [Docusaurus](https://docusaurus.io/), генератора статичных сайтов для
построения сайтов документации в разметке. Вики использует следующий шаблон метаданных для своих файлов разметки и требует адаптации каждого нового документа:

```
---
id: wiki-maintainers
title: Wiki Maintainers
sidebar_label: Maintainers
description: A list of Polygon Wiki maintainers
keywords:
  - docs
  - matic
  - polygon
  - wiki
  - docs
  - maintainers
  - contributors
image: https://matic.network/banners/matic-network-16x9.png
slug: community-maintainers
---
```

При написании метаданных для файла разметки необходимо учитывать ряд важных аспектов:
- Мы просим вкладчиков использовать **уникальный идентификатор** и избегать использовать **только** общие слова и предложения, такие как «Введение» или «Обзор».
- **Заголовок** — это предложение, используемое в начале статьи. Для этой статьи заголовок выглядит так: «Общие правила написания текстов». Поэтому не нужно добавлять заголовки H1/H2 для представления каждой статьи. Вместо этого следует использовать этот **заголовок** из метаданных.
- **Описание** не должно быть слишком длинным, поскольку оно используется на плитках указателя, имеющих ограничение по количеству символов. Например, определение «Блокчейн — это неизменяемый журнал для записи транзакций» для *basics-blockchain.md* выглядит на плитке указателя так:
![img](/img/contribute/index-tile.png)

  Поэтому **описание** должно содержать **не более 60 символов** с учетом пробелов между ними.
- Ключевые слова важны для поисковой оптимизации и описания статьи. Старайтесь выбирать не менее пяти ключевых слов.

:::note

См. [официальную документацию по метаданным](https://docusaurus.io/docs/next/api/plugins/@docusaurus/plugin-content-docs#markdown-front-matter) для получения дополнительной информации.

:::

### Поделитесь опытом с читателем {#share-the-experience-with-the-reader}

- Первое лицо: не используйте местоимение «я». Используйте высказывания от первого лица редко и
целенаправленно. При чрезмерном использовании речь от первого лица перегружает ощущение
общего опыта и запутывает читателя.
- Второе лицо: в большинстве случаев следует обращаться к читателю напрямую. В руководствах используйте множественное число первого лица (мы, нас, наш) или второе лицо. Поскольку руководства дают
конкретные указания по теме, использование множественного числа первого лица в них более естественно и
распространено по сравнению с другими типами документации.
- Третье лицо: не используйте местоимение «мы», когда говорите о Polygon или Polygon Technology.
- Активный залог: по возможности используйте настоящее время. Иногда целесообразнее использовать страдательный залог, прибегайте к нему, когда говорите об агенте.
- Не забывайте о факторе человеческого присутствия: динамичный тон при описании технических концепций помогает читателю лучше усвоить материал, чем простое описание программного обеспечения или кода
и того, что они делают.
- Местоимения: по возможности используйте гендерно-нейтральные местоимения, такие как «они». Обычно вы можете поставить любое существительное во множественное число для согласования с глаголом и избежать
использования гендерных местоимений («он», «она», «ее», «его» и т. д.)
  - Обращайте внимание на безличные и потенциально многозначные местоимения. Если вы используйте любые из следующих безличных местоимений, убедитесь, что они отвечают на вопросы «чего?», «какого?» или «в качестве чего?» в составе предложения.
    - все, другие, любые
    - каждый, любой
    - немногие, многие, ни один, никакие,
    - один, другой
    - такой же, несколько, некоторые, такие
    - то, их, эти, те

### Краткость и четкость {#being-swift-and-concise}

- Документация имеет смысл и полезна, только если в ней используются необходимые слова и правильные фразы.
  - По возможности используйте распространенные и широко известные слова.
  - Избегайте цветистого языка и чрезмерных литературных оборотов.
  - Избегайте жаргона, просторечий и идиоматических фраз.
  - Избегайте наречий и субъективных заявлений. Например, не используйте слова и фразы, включающие слова «легко», «быстро», «просто», «скоро». Если это требуется, лучше преуменьшить, чем
  преувеличить.
  - Не используйте фразы, которые могут быть интерпретированы неоднозначно. Например, вместо «Когда этот релиз выйдет...» пишите «После того, как этот релиз выйдет...»
  - Обращайте особое внимание на выбор слов. Лучше используйте «начиная с» (период времени) вместо
  «потому что» (подразумевается причина и результат) или «как только» (одиночное событие) вместо «после того, как»
  (каждый раз).
  - Избегайте восклицательных знаков.
- Избегайте ненужных фраз или слов. Примеры:
  - Вместо «и тогда» используйте «тогда».
  - Вместо «для того, чтобы» используйте «чтобы».
  - Вместо «а также» используйте «и».
  - Вместо «посредством» используйте «используя», «с помощью» и т. п.
- Используйте разговорный тон, который не будет слишком формальным, но будет при этом профессиональным.
- Ясность: придавайте жизнь словам и фразам, когда это будет возможно. Например:
  - Вместо «см.» используйте «для получения дополнительной информации»
  - Вместо «т. е.» используйте «то есть» или перепишите предложение так, чтобы оно было ясным без дополнительных уточнений.
  - Вместо «и т. д.» используйте «и так далее» или перепишите текст, чтобы сделать это добавление ненужным. Вместо того
  чтобы заканчивать перечень примеров «и т. д.», оставьте один или два примера и начните перечисление с «такие как» или «например».
  - Вместо оговорок используйте соответствующие заменяющие слова, такие как «внимание», «предупреждение» или «осторожно».
  - Сокращения придают документации более естественный тон, по крайней мере, на английском языке.
  Используйте сокращения сознательно и обоснованно.

## Структура {#structure}

Документы должны быть разделены на разделы. Каждый раздел должен быть посвящен определенной теме или вопросу. Каждый раздел должен содержать один или несколько абзацев. Каждый абзац должен передавать только одну мысль. Избегайте повторения одних и тех же мыслей в разных разделах и разбивайте абзацы, в которых говорится о разных вещах.
Читатель должен с первого предложения понять, о чем говорится в абзаце.

## Документация по продукту {#product-documentation}

Если вы пишете о конкретном продукте, убедитесь, что документ напоминает этот
продукт. Ранее документация по Polygon была обобщенной и основанной на Polygon PoS.
Сейчас существуют разные продукты на базе Polygon, и соавторам следует обращать внимание на их дополнения.

Например «Развертывание смарт-контракта в Polygon с помощью ####» звучит неоднозначно. Если бы это руководство относилось к Polygon PoS, его название должно было бы быть точным, например
«Развертывание смарт-контракта в Polygon PoS с помощью ####». Если использовать тот же пример с Polygon Rollup, например Polygon Hermez, оно будет выглядеть так: «Развертывание смарт-контракта в Polygon Hermez с помощью ####».

Убедитесь, что документация по продукту, будь то общее руководство или обучающее руководство, добавлена
в соответствующее хранилище документации по продукту. Для большинства документов ссылка должна присутствовать в одном из общих хранилищ (например, «Разработка» или «Документация»), но сам документ
должен находиться в составе документации по продукту. Вам нужно будет разместить ссылку на документ в хранилище, добавив ее в `sidebars.js`.
Однако сам документ будет существовать в соответствующем хранилище документации продукта и перенаправит пользователя после нажатия. Это же правила относится к большинству
документов. Их ссылки должны находиться в одном из общих хранилищ, но сами документы должны находиться в составе документации по продукту.

Большая часть документации на базе API в вики Polygon имеет форму справочной документации за исключением упоминаемых в руководствах API.
Например, документация по API в Matic.js предоставляет информацию о структуре, параметрах и возвращаемых значениях для каждой функции или метода в API.

## Документация API {#api-documentation}

При документировании API следует учитывать следующее:

* Хорошее введение, дающее отправную точку.
* Четкое описание вызова или запроса. Опишите, что делает конечная точка.
* Полный список параметров:
  * Типы параметров
  * Синтаксические выражения с замещающими символами, показывающие доступные параметры
  * Специальное форматирование
* Примеры кода для нескольких языков.
* Образец вызова с ожидаемым выводом.
* Коды ошибок. Граничные примеры.
* Инструкции по получению ключей API в случае необходимости.
* Всегда полезно указывать ответы на часто задаваемые вопросы и приводить сценарии использования.
* Ссылки на дополнительные ресурсы, такие как посты в социальных сетях, блоги и видеоконтент.