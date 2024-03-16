# Uzi2.1

This repo contains unpacked browser files.

![Uzi Logo](https://raw.githubusercontent.com/KomboAmina/Uzi2.1/main/assets/img/Uzi%20Logo%20large.jpg)

## Intro

A string is a sequence of characters such as letters, numbers and symbols.
_Uzi_ is a free chrome extension to generate random strings, such as passwords. Its name means _“thread”_ in Kiswahili.

## How To Install

- Clone this repo
- Open your browser (ie Google Chrome)
- Go to //chrome://extensions/
- Turn on "Developer mode"
- Choose "Load unpacked"
- Select the folder where this repo has been cloned
- (Optional: pin Uzi to your browser)
- Click the icon to run the extension.

## How to Use

The extension loads with "uzi" as the default string and a length of 3.
String generation mostly happens automatically when the extension is loaded or one of the generating values is called.

![Screenshot of the expanded view](https://raw.githubusercontent.com/KomboAmina/Uzi2.1/main/assets/img/Popup-5.png)

## Features

1. Editable output field.
2. Random string generation.
3. Automatic string encryption.
4. String reversal.
5. String length calculator.
6. Copy to clipboard.
7. Generate QR Code.

### Characters

String length can only be whole numbers from 1 to 2048.
Character content can be:

- alphanumeric
- unambiguous
- letters
- lowercase letters
- uppercase letters
- numerical
- only symbols
- binary
- hexadecimal
- octal

### Encrypted Strings

Encrypted strings are read-only and can be:

- MD5
- SHA1
- Base64

### QR Codes

A QR code of the random generated string. Maximum length is 1270 characters.

![Screenshot of the expanded qr code view](https://raw.githubusercontent.com/KomboAmina/Uzi2.1/main/assets/img/Popup-6.png)

### Special Mentions

- This extension was built on the UIkit framework (https://getuikit.com).
- With icons by Line Awesome (https://icons8.com/line-awesome).
- With QR Generator by David Shim (https://github.com/davidshimjs)
