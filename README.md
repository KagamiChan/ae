# AE

AE - VN Tools is a multipurpose utility for working with common Visual Novel
and game archive, image and misc data formats.

AE is written in Delphi 7 from scratch.

It includes:

* Archiver tool
* EDGE - image manipulation/conversion tool
* GrapS - RAW image data reader
* Data processing tool

Win32 binaries: http://wks.arai-kibou.ru/ae.php?p=dl

Online manual: http://wks.arai-kibou.ru/ae.php?p=docu

Donation info: http://wks.arai-kibou.ru/donate.php


## Depencence

- `JCL/JVCL - TJVArrowButton` Project JEDI (will be deleted entirely in 0.7.0)
- `JISKit` unicode/shift-jis components developed by Proger_XP
- `TCredits` by Saturn Laboratories
- `PercentCube` displays WinRAR-alike 3D-ish percentage bar. Written by dsp2003 with fixes from Proger_XP

## How to compile:

1) Install the following visual design components:

    src/lib/_jiskit/Unicode components/jiskit_tlabelw.dpk
    src/lib/_jiskit/Unicode dialogs/jiskit_udialogs.dpk
    src/lib/credits/credits.pas
    src/lib/PercentCube.pas

2) Next, open /src/AnimEd.dpr.
