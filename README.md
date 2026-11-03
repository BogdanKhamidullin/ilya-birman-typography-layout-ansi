# Ilya Birman Typography Layout for ANSI keyboards

[Ilya Birman’s Typography Layout](https://ilyabirman.net/typography-layout/) for macOS, adapted for ANSI keyboards. Its Russian and English layouts let you type typographic characters using Option: for example, Option + comma and Option + period produce « and ». Hold Shift as well for other characters. The [original page](https://ilyabirman.net/typography-layout/) has a complete keyboard diagram and instructions.

## Install

1. Copy `Ilya Birman Typography Layout ANSI.bundle` to `~/Library/Keyboard Layouts`. In Finder, choose **Go → Go to Folder** and enter that path.
2. Log out and back in. If the layouts do not appear, restart your Mac.
3. Open **System Settings → Keyboard → Input Sources**, add **English – Ilya Birman Typography ANSI** and **Russian – Ilya Birman Typography ANSI**, then select the layout you want to use.

If an older copy is installed, remove it before installing this bundle. The original and ANSI versions use the same input-source identifiers, so they are not set up to coexist independently.

## ANSI change

In the English layout, the key above Tab produces a backtick (`` ` ``); Shift + that key produces `~`. The key above Return produces `\`, or `|` with Shift. In the Russian layout, the key above Tab produces `ё`, or `Ё` with Shift.

The change applies to the primary keyboard map. If the keys behave differently, check the active input source and your keyboard’s identification in macOS. See [ANSI-CHANGE.md](ANSI-CHANGE.md) for the mapping details and checks.

## Remove

Remove the ANSI input sources in Keyboard settings, then delete the bundle from `~/Library/Keyboard Layouts`. Log out and back in if the layouts remain available.

---

# Типографская раскладка Ильи Бирмана для клавиатур ANSI

[Типографская раскладка Ильи Бирмана](https://ilyabirman.ru/typography-layout/) для macOS, адаптированная для клавиатур ANSI. Русская и английская раскладки позволяют вводить типографские символы с помощью Option: например, Option + запятая и Option + точка дают « и ». Чтобы ввести другие символы, удерживайте также Shift. Полная схема клавиш и инструкции есть на [странице оригинальной раскладки](https://ilyabirman.ru/typography-layout/).

## Установка

1. Скопируйте `Ilya Birman Typography Layout ANSI.bundle` в папку `~/Library/Keyboard Layouts`. Чтобы открыть её в Finder, выберите **Переход → Переход к папке** и введите этот путь.
2. Выйдите из учётной записи и войдите снова. Если раскладки не появились, перезагрузите Мак.
3. Откройте **Системные настройки → Клавиатура → Источники ввода**, добавьте **English – Ilya Birman Typography ANSI** и **Russian – Ilya Birman Typography ANSI**, затем выберите нужную раскладку.

Если установлена старая копия, удалите её перед установкой. У оригинальной версии и версии ANSI одинаковые идентификаторы источников ввода, поэтому они не настроены для независимой работы друг от друга.

## Изменение для ANSI

В английской раскладке клавиша над Tab вводит обратный апостроф (`` ` ``), а с Shift — `~`. Клавиша над Return вводит `\`, а с Shift — `|`. В русской раскладке клавиша над Tab вводит `ё`, а с Shift — `Ё`.

Изменение внесено в основную карту клавиатуры. Если клавиши работают иначе, проверьте выбранный источник ввода и то, как macOS определила клавиатуру. Подробности и способы проверки — в [ANSI-CHANGE.md](ANSI-CHANGE.md).

## Удаление

Удалите 2 источника ввода ANSI в настройках клавиатуры, затем удалите файл раскладки из `~/Library/Keyboard Layouts`. Если раскладки остались в списке, выйдите из учётной записи и войдите снова.
