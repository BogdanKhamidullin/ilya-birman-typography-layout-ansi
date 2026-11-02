# Ilya Birman’s Typography Layout adapted for ANSI keyboards on macOS

This repository contains 2 adaptations of [Ilya Birman’s Typography Layout](https://ilyabirman.ru/typography-layout/) for macOS. The English and Russian layouts add typographic characters to your keyboard. For example, Option + comma and Option + period produce « and ». Hold Shift as well to enter other characters. The original page has keyboard diagrams and instructions.

## Choose a bundle

- **Universal** — `Ilya Birman Typography Layout Universal.bundle` uses the original English mapping for ISO keyboard types recognized by macOS and the ANSI mapping for ANSI keyboards.
- **ANSI** — `Ilya Birman Typography Layout ANSI.bundle` uses the ANSI mapping.

In the ANSI English mapping, key code 50 produces a backtick (`` ` ``) instead of the original backslash. On a typical ANSI keyboard, this is the key above Tab. The Russian layout is unchanged. See [ANSI-CHANGE.md](ANSI-CHANGE.md) for details.

The universal mapping depends on how macOS identifies the keyboard. Check the keys on your keyboard after installation; the universal layout has not yet been tested on physical ANSI and ISO keyboards.

## Install

1. Copy the bundle you chose to `~/Library/Keyboard Layouts`. In Finder, choose **Go → Go to Folder** and enter that path.
2. Log out and back in. If the layouts do not appear, restart your Mac.
3. Open **System Settings → Keyboard → Input Sources** and add the English and Russian input sources ending in **Universal** or **ANSI**, matching the bundle you installed.

The original and ANSI bundles share input-source identifiers. Remove an older copy before installing the ANSI bundle. The universal bundle has separate identifiers.

## Remove

Remove the 2 input sources in Keyboard settings, then delete their bundle from `~/Library/Keyboard Layouts`. Log out and back in if the layouts remain available.

---

# Типографская раскладка Ильи Бирмана для клавиатур ANSI на macOS

В репозитории — 2 адаптации [типографской раскладки Ильи Бирмана](https://ilyabirman.ru/typography-layout/) для macOS. Английская и русская раскладки добавляют типографские символы на клавиатуру. Например, Option + запятая и Option + точка вводят « и ». Для других символов удерживайте также Shift. Схемы клавиш и инструкции есть на странице оригинальной раскладки.

## Выбор файла

- **Universal** — `Ilya Birman Typography Layout Universal.bundle` использует оригинальную английскую раскладку для клавиатур, которые macOS определяет как ISO, и версию ANSI для клавиатур ANSI.
- **ANSI** — `Ilya Birman Typography Layout ANSI.bundle` использует версию ANSI.

В английской версии ANSI клавиша с кодом 50 вводит обратный апостроф (`` ` ``) вместо обратной косой черты. На обычной клавиатуре ANSI это клавиша над Tab. Русская раскладка не изменена. Подробности — в [ANSI-CHANGE.md](ANSI-CHANGE.md).

Работа универсальной раскладки зависит от того, как macOS определила клавиатуру. После установки проверьте клавиши на своей клавиатуре: универсальную раскладку ещё не проверяли на физических клавиатурах ANSI и ISO.

## Установка

1. Скопируйте выбранный файл в папку `~/Library/Keyboard Layouts`. Чтобы открыть её в Finder, выберите **Переход → Переход к папке** и введите этот путь.
2. Выйдите из учётной записи и войдите снова. Если раскладки не появились, перезагрузите Мак.
3. Откройте **Системные настройки → Клавиатура → Источники ввода** и добавьте английский и русский источники ввода с окончанием **Universal** или **ANSI** — в зависимости от установленного файла.

У оригинального файла и файла ANSI одинаковые идентификаторы источников ввода. Перед установкой файла ANSI удалите старую копию. У универсального файла отдельные идентификаторы.

## Удаление

Удалите 2 источника ввода в настройках клавиатуры, затем удалите их файл из `~/Library/Keyboard Layouts`. Если раскладки остались в списке, выйдите из учётной записи и войдите снова.
