# ANSI keyboard change

The English layout now outputs a backtick (`) from the unmodified key above
Tab (key code 50). Previously it output a backslash, duplicating the key above
Return and making the backtick require Option.

Shift + the key above Tab still outputs `~`; the key above Return still
outputs `\` and Shift + that key outputs `|`. The Russian layout is unchanged:
the key above Tab outputs `ё` or `Ё` with Shift.

To verify on an ANSI keyboard, select each installed input source and test
these keys, Option combinations, the grave-accent dead key, and shortcuts using
the key above Tab. macOS selects a key map based on its detected keyboard type,
so verify the behavior on the target Mac.
