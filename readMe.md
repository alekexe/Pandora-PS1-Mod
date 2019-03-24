# Pandora for Sony Playstation 1
```
   ▄███████▄    ▄████████ ███▄▄▄▄   ████████▄   ▄██████▄     ▄████████    ▄████████ 
  ███    ███   ███    ███ ███▀▀▀██▄ ███   ▀███ ███    ███   ███    ███   ███    ███ 
  ███    ███   ███    ███ ███   ███ ███    ███ ███    ███   ███    ███   ███    ███ 
  ███    ███   ███    ███ ███   ███ ███    ███ ███    ███  ▄███▄▄▄▄██▀   ███    ███ 
▀█████████▀  ▀███████████ ███   ███ ███    ███ ███    ███ ▀▀███▀▀▀▀▀   ▀███████████ 
  ███          ███    ███ ███   ███ ███    ███ ███    ███ ▀███████████   ███    ███ 
  ███          ███    ███ ███   ███ ███   ▄███ ███    ███   ███    ███   ███    ███ 
 ▄████▀        ███    █▀   ▀█   █▀  ████████▀   ▀██████▀    ███    ███   ███    █▀  
                                                            ███    ███              
```
Pandora is an open source ESP8266 modchip for the Sony Playstation 1.



## Getting Started

These instructions will get you a Sony Playstation 1 without copy or region protection. Without copy or region protection you can play homebrew games, games from another region or games downloaded from web.

### Installing

Diagrams and step by step guide soon

## How does it work 
Playstation 1 is looking for a 4 letter string which is pressed into the area of the CD which is called "the wobble". You cant burn trough the wobble which prevents you from the copying games.
With the Playstation they actually press the 4 letter string into the wobble from the factory.

There are 3 strings - what they use for copy protection is also used for region protection
  - SCEA(Sony Computer Entertainment America)
  - SCEE(Sony Computer Entertainment Europe)
  - SCEI(Sony Computer Entertainment International) 
Note that International is for Japan. It is named international because Sony is Japanese company.
  
The ESP8266 injects the 4 letter string into the Playstation onto data pin when needed.

## Authors

* **Aleksej Jovanovic ** - *Initial work* - [@alekexe](https://github.com/alekexe)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## Acknowledgments
* [@kalymos]( https://github.com/kalymos ) (Pandora is inspired by kalymos and his PsNee)


## License

This project is licensed under the Attribution 4.0 International (CC BY 4.0) license

![License image](https://i.imgur.com/xwamcYx.png)
