## Information 

A fork of pokecrystal designed to restore and localize Mobile Adapter functionality such as online battles and trades to Crystal using disassembled code from the Japanese ROM designed for use with Mobile System recreation projects like the REON Project.

The intention of this project is to create a build of pokecrystal with all of the content that was featured in the Japanese version of the game and was cut from the international release(s).
We've been very strict on ensuring that any decisions made on the localization or presentation of this content match the standards of a hypothetical scenario in which the Mobile Adapter was released outside of Japan and Crystal received a complete English release back in 2001.

This repository is built upon a substantial amount of work done by Sudel-Matze.

A link to Matze’s repository can be found here:
https://github.com/Sudel-Matze/pokecrystal

## Screenshots

![image](https://user-images.githubusercontent.com/110418063/188284868-5d25cf63-ec57-4780-b6d0-8b7ff90e3826.png)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/a1615c31-a83c-4406-ad72-beeb52abe0ad)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/ea64d517-1069-4cdb-a68d-3d657613d16e)
![image](https://user-images.githubusercontent.com/110418063/188298896-8d03b589-8ab1-4d5f-b205-b163e4f616b9.png)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/42c3949c-ad17-4452-981d-5bb19647e022)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/a2753b55-920e-4ed9-bcc4-913655fdc87e)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/6c3f6fe9-9362-4f07-b5bf-f1ae785febf9)
![image](https://user-images.githubusercontent.com/110418063/205540332-b49b9482-e121-4ba0-a2df-3630c04cdc1c.png)
![image](https://user-images.githubusercontent.com/110418063/226153593-93985569-7682-43f9-91d1-e33f9478643d.png)
![image](https://user-images.githubusercontent.com/110418063/188287387-5cd5514c-267c-4fe6-b66f-0a0e36e712e6.png)
![image](https://user-images.githubusercontent.com/110418063/188287421-ff2eedad-1569-4512-8224-d1ee2c5622da.png)
![image](https://github.com/gb-mobile/pokecrystal-mobile-eng/assets/110418063/46af69c9-da9f-4656-90e4-e46cc5aec4b2)
![image](https://user-images.githubusercontent.com/110418063/188331912-d862a3c6-a7d2-4636-b152-8ecd74e5250b.png)
![image](https://user-images.githubusercontent.com/110418063/196129175-eebdad9e-f4a0-44ae-8432-7aa538b3c722.png)
![image](https://user-images.githubusercontent.com/110418063/188289401-f0b79296-f4eb-4463-a8d6-6fb8c605adc1.png)



## Setup [![Build Status][ci-badge]][ci]

For more information, please see [INSTALL.md](INSTALL.md)

After setup has been completed, you can choose which version you wish to build.
To build a specific version, run one of these commands inside the repository directory in cygwin64:

- US Version:   `make`

- EUR Version:	`make crystal_eu` 

- AUS Version:	`make crystal_au`

For a more accurate experience, we advising picking the build version based on where you live as this will make different 'address' options available to you which are selectable for personal information.

The US Version covers the United States and Canada.

The EUR Version covers all countries in Europe (as of 2001).

The AUS Version covers Australia & New Zealand.

Other languages are being worked on, but are not complete and still require a lot of polish.

## Using Mobile Adapter Features

To take advantage of the Mobile Adapter features, we currently recommend the GameBoy Emulator BGB:
https://bgb.bircd.org/

and libmobile-bgb:
https://github.com/REONTeam/libmobile-bgb/releases

Simply open BGB, right click the ‘screen’ and select `Link > Listen`, then accept the port it provides by clicking `OK`.
Once done, run the latest version of libmobile for your operating system (`mobile-windows.exe` or windows and `mobile-linux` for linux).
Now right click the ‘screen’ on BGB again and select `Load ROM…`, then choose the pokecrystal-mobile `.gbc` file you have built.

## Mobile Adapter Features

A full list of Mobile Adapter features for Pokémon Crystal can be found here:
https://github.com/gb-mobile/pokecrystal-mobile-en/wiki/Pok%C3%A9mon-Crystal-Mobile-Features

## Contributors

- Pret           : Initial disassembly
- Matze          : Mobile Restoration & Japanese Code Disassembly
- Damien         : Code
- DS             : GFX & Code
- Nob Ogasawara  : Consultation on minor menu translations
- Ryuzac         : Code & Japanese Translation
- Vulcandth      : Rebasing and keeping the repo up to date
- Zumilsawhat?   : Code (Large amounts of work on the EZ Chat system)
- REON Community : Support and Assistance

[ci]: https://github.com/pret/pokecrystal/actions
[ci-badge]: https://github.com/pret/pokecrystal/actions/workflows/main.yml/badge.svg
