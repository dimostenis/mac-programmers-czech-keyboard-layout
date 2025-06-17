# Programmers' Czech Keyboard Layout for Mac 🇨🇿

Ahoj 👋🏼

This layout modifies the Czech keyboard on macOS so that the top row of keys (`1`, `2`,
`3`, ... `0`) always types numbers without requiring the `⬆Shift` key, while characters
such as `+`, `ě`, `š` ... `é` are accessible by holding `⬆Shift`.

## Key Behavior

This table shows the behavior of the top row keys in this modified layout, compared to
the original Czech keyboard.

| Key Pressed | Output (No `⬆Shift`) | Output (With `⬆Shift`) |
|:------------|:---------------------|:-----------------------|
| `1`         | `1`                  | `+`                    |
| `2`         | `2`                  | `ě`                    |
| `3`         | `3`                  | `š`                    |
| `4`         | `4`                  | `č`                    |
| `5`         | `5`                  | `ř`                    |
| `6`         | `6`                  | `ž`                    |
| `7`         | `7`                  | `ý`                    |
| `8`         | `8`                  | `á`                    |
| `9`         | `9`                  | `í`                    |
| `0`         | `0`                  | `é`                    |

## Why Yet Another Repository?

I could not find any existing layout that worked properly, so I created my own.

## How It Was Created

The layout was created using [Ukelele](https://software.sil.org/ukelele/), based on the
original Czech keyboard layout.

Tested and created on macOS 15.4.1.

## Installation

1. Copy the layout file `Programmers Czech.keylayout` to `~/Library/Keyboard Layouts`.
2. Add it in System Settings:
    - `System Settings` → `Keyboard` → `Input Sources` → `Edit...` → `+` → Select
      "Programmers Czech"

## Maintenance

This layout is considered complete. No further updates are planned unless the Czech
keyboard layout itself changes in future macOS versions.

## Changelog

| Date         | Description  |
|--------------|--------------|
| 2025-06-17   | 🔧 Type numbers with `Caps Lock` enabled instead of `Ě`, `Š`, etc. |
| 2025-04-28   | 🎉 Initial release |
