
![StealthMax](.../../assets/renders/sm_300.png)

# Nevermore StealthMax
The Nevermore StealthMax is an air filter developed for 3D printers.
With its activated carbon and HEPA filtration, it aims to capture harmful fumes and unpleasant odors generated when melting plastics, creating a safer and more pleasant environment for makers.

[![Buy Me a Coffee](https://img.shields.io/badge/Support_Nevermore3D-grey?style=flat-square&logo=buymeacoffee&logoColor=black&label=Buy%20Me%20a%20Coffee&labelColor=FFDD00)](https://www.buymeacoffee.com/nevermore3d) [![Discord](https://img.shields.io/discord/1017933489779245137?style=flat-square&logo=discord&logoColor=white&label=Discord&labelColor=%237785cc&color=grey&link=https%3A%2F%2Fdiscord.gg%2FH8tZ9fZVQ4)](https://discord.gg/H8tZ9fZVQ4)

# Table of Contents
1. [About](#1-about)<br>
   .1 [Nevermore3D](#11-nevermore3d)<br>
   .2 [StealthMax](#12-stealthmax)<br>
   .3 [Volatile Organic Compounds (VOCs) and Ultra-Fine Particles (UFPs)](#13-volatile-organic-compounds-vocs)
   
2. [Getting Started](#2-getting-started)<br>
   .1 [Overview](#21-overview)<br>
   .2 [Documentation](#22-documentation)

3. [Bill of Materials (BOM) and Sourcing Guide](#3-bill-of-materials-and-sourcing-guide)<br>
   .1 [StealthMax Kits](#31-stealthmax-kits)<br>
   .2 [Self Sourcing (BOM)](#32-self-sourcing-bom)

4. [Contributing](#4-contributing)<br>
5. [Acknowledgements](#5-acknowledgments)<br>
6. [Showroom](#6-showroom)

# (1) About

##  (1.1) Nevermore3D
Nevermore3D empower the 3D printing community with resources to create their own air filtration systems, promoting a safer and healthier printing environment.

 - ### History
   The project began in 2019 with the [Nevermore Micro](https://github.com/nevermore3d/Nevermore_Micro), a filtration system that has become widely adopted within the Voron community.<br>
   Since then, multiple filtration systems have been developed - with more to come!

   [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/Nevermore_Micro?style=flat-square&logo=github&label=Micro)](https://github.com/nevermore3d/Nevermore_Micro)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=)](https://github.com/nevermore3d/Nevermore_Micro/stargazers) [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/StealthMax?style=flat-square&logo=github&label=StealthMax)](#stealthmax)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=)](https://github.com/nevermore3d/StealthMax/stargazers)<br>
   [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/Nevermore_FLEX?style=flat-square&logo=github&label=Flex&color=lightgrey)](https://github.com/nevermore3d/Nevermore_FLEX)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=&color=lightgrey)](https://github.com/nevermore3d/Nevermore_FLEX/stargazers) [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/Nevermore_Mini?style=flat-square&logo=github&label=Mini&color=lightgrey)](https://github.com/nevermore3d/Nevermore_Mini)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=&color=lightgrey)](https://github.com/nevermore3d/Nevermore_Mini/stargazers) [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/Resin_Filtration?style=flat-square&logo=github&label=Parapet%20Filter%20Tower&color=lightgrey)](https://github.com/nevermore3d/Resin_Filtration/tree/main/Parapet_Filter_Tower)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=&color=lightgrey)](https://github.com/nevermore3d/Resin_Filtration/stargazers) [![GitHub Repo stars](https://img.shields.io/github/stars/nevermore3d/RatPack?style=flat-square&logo=github&label=RatPack&color=lightgrey)](https://github.com/nevermore3d/RatPack)[![](https://img.shields.io/badge/-blue.svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=&color=lightgrey)](https://github.com/nevermore3d/RatPack/stargazers)

 - ### Nevermore Carbon and other Filtration Media
   When users reported issues of oxidizing and damaging their printers due to bad carbon, we set out to find the most suitable carbon for 3D printing. After consulting leading suppliers, Nevermore3D now offers its own premium carbon of unmatched specifications through selected [resellers](https://github.com/nevermore3d/Reseller).<br>
   Its usally one of the cheapest options in carbon performance/gram as it captures up to 2x its competition, though it might cost more per kilo compared to bulk options; Nevermore Carbon is safe to use in 3D printing environments, offers unbeatable effectiveness targeted at 3D printing VOCs specifically, and every purchase directly contributes to the ongoing development of the Nevermore3D project. Read more on how to evaluate carbon for 3D printing on our [reseller](https://github.com/nevermore3d/Reseller) page!

    - #### Nevermore Carbon
      -   Highly micro-porous and laboratory tested premium activated carbon, from a major European manufacturer
      -   Market-leading VOC adsorption fine tuned for _aromatic hydrocarbons emitted during 3D printing_ such as styrene, benzaldehyde, toluene, benzene, etc. [**CTC >=80**, benzene adsorption capacity up to **0.48g/g**]
      -   Market-leading surface area (storage capacity) of **1250m2/g**!
      -   Vacuum packed for minimal dust generation during shipping.
      -   Vacuum dedusted during the packaging process for immediate use in 3d printers
      -   Available in Regular (750ml, 0.33kg) and XL (2300ml, 1kg)

    - #### Nevermore Scorch
      -   Zeolite-based, highly microporous adsorption medium, enhanced with potassium permanganate (KMnO4).
      -   Chemically transform printer VOC toxins like styrene – a major VOC in ABS and ASA filaments – into harmless potassium benzoate (food additive).
      -   The process is not harmed by high chamber temps, but accelerated, making Nevermore Scorch ideal for heated 3D printer chambers!
      -   Colour changes from bright purple to a dullish gray as it is being spent, giving a visual indication of when it is time to swap filter media!
      -   Available in Regular (750ml, 0.66kg) and XL (2300ml, 2kg)

    - #### Nevermore Boost
      -   Pre-prepared 50/50 mix of Nevermore Carbon and Nevermore Scorch; a less-hassle, best-of-both-worlds printer filtration
      -   Combining the long-life och stellar adsorption capacity of activated carbon with Nevermore Scorch performance in hot surroundings.
      -   Ideal for most users with enclosed 3d printers printing ABS/ASA/PETG/PC in chamber temps of 50C +-10C.

    - #### Nevermore HEPA
      -   Nevermore HEPA Filters

## (1.2) StealthMax
The Nevermore StealthMax improves upon the [Nevermore Max](https://github.com/nevermore3d/Nevermore_Max) with a more warp-resistant frame, smaller size, optional exhaust for cooler printing, and easier assembly.

With its 2-liter carbon basket, it can hold 20 times as much carbon as the Nevermore Micro, and thanks to its innovative dual filtration design, the StealthMax allows for recirculation of filtered air within an enclosed printer to both maintain chamber temperature and further improve filtration efficiency and longevity.

 - #### Dual Filtration
   The StealthMax does not make any compromises and utilizes activated carbon and HEPA filtration:
      
   -   **Activated carbon filter:** This type of filter is designed to absorb volatile organic compounds (VOCs). VOCs are gases emitted during 3D printing, and they can cause irritation to the eyes, nose, and throat. An activated carbon filter can help to reduce odors and improve air quality.

   -   **HEPA (High Efficiency Particulate Air) filter:** This type of filter is effective at capturing tiny particles 2.5um in diameter and below (in 3D printing often _much_ smaller). These particles can - compared to larger PM2.5  particles - have direct toxic effects if inhaled, so a HEPA filter goes a long way to capture both small particles as well as any carbon dust, improving air quality furter in your printing space.

 - #### Recirculation
   The StealthMax and your printer's enclosure function as a closed-loop system, enabling air to recirculate through the filter multiple times. 
   This results in a significantly higher capture rate of harmful particles compared to a single-pass exhaust filter.<br>
   The effectiveness of this process is diminished if the enclosure has leaks, however, opening the exhaust slider creates a slight negative pressure inside the enclosure, thus drawing air in through leaks and maximizing the StealthMax's filtration potential.

 - #### StealthMax S (250)
   Making safer printing more accessible, the StealthMax S was designed for printing on a 250x250mm bed.<br>
   Despite its compact size, the StealthMax S retains impressive filtering capacity thanks to its 1.4-liter carbon basket as well as the benefits of dual filtration.
   [Read more](.../../assets/_unsorted/Stealthmax_S)

## (1.3) Volatile Organic Compounds (VOCs) and Ultra-Fine Particles (UFPs)
When 3D printing, especially with certain types of materials like plastics, various [volatile organic compounds (VOCs)](https://en.wikipedia.org/wiki/Volatile_organic_compound) can be emitted. The specific VOCs produced can vary depending on the type of filament or resin used and the printing conditions. Some common VOCs emitted during 3D printing include:

-  **Styrene**: Commonly emitted when printing with ABS (Acrylonitrile Butadiene Styrene) filament. Styrene exposure has been linked to respiratory issues, irritation of the eyes, nose, and throat, and in some cases, long-term exposure may increase the risk of cancer.
    
-  **Formaldehyde**: Often produced during the thermal decomposition of certain plastics, such as PLA (Polylactic Acid). Formaldehyde exposure can cause irritation of the eyes, nose, and throat, as well as respiratory issues. Prolonged exposure to high levels of formaldehyde has been linked to an increased risk of cancer.
    
-  **Acetaldehyde**: Another byproduct of thermal decomposition, commonly found in emissions from ABS and PLA printing. Acetaldehyde exposure can cause irritation of the eyes, nose, and throat, and may also affect the central nervous system.
    
-  **Acrylonitrile**: Present in emissions from ABS filament, acrylonitrile exposure has been associated with respiratory issues and may increase the risk of certain cancers.
    
-  **Ethylene glycol**: Found in emissions from certain types of resins used in stereolithography (SLA) printing, ethylene glycol exposure can cause irritation of the eyes, skin, and respiratory system.

-  **Butadiene**: Present in ABS-type filaments, as well as rubber additives, long exposures to Butadiene is a known accellerator or cardiovascular disease (heart attacks and strokes), increases the risk of certain cancers, and is suspected to impact fetal development (teratogen).
    
Volatile Organic Compounds (VOCs) can have a range of health effects that vary based on factors such as concentration, duration of exposure, and individual susceptibility. Short-term exposure to high levels of VOCs can cause respiratory tract irritation, headaches, dizziness, and nausea. Prolonged exposure to certain VOCs is associated with more severe health issues, including respiratory problems, an increased risk of cancer, and vascular diseases such as stroke and heart attacks.

Just as individual VOCs can be released into the air, clusters of VOCs, known as **Ultra-Fine Particles (UFPs)**, are also emitted. These particles begin their existence extremely small, with diameters of only 10-15 nm — for comparison, a single VOC molecule is typically about 1 nm, and the grid of a HEPA filter is 20 times larger than a newborn UFP.

If not addressed, these Ultra-Fine Particles gradually coalesce into larger droplets, eventually reaching sizes of about 50-100 nm. At this size, they can be captured by HEPA filters, unless they have already dispersed into the surrounding air. UFPs droplet agglomerates often consist of mixed, room-temperature-viscous VOC oils such as styrene, with some solid components (such as stearic acid, if your chamber is cooler than 70C or so). Unlike larger particles that may accumulate in the airways, breathed UFPs are absorbed by the body—VOC by VOC—similar to inhaled medication, and can exert the same toxic effects as the individual VOCs they contain.

Moreover, carbon porosity is not limited to micropores (carbon pores smaller than 2 nm) but also extends to mesopores (carbon pores 2-50 nm), which can adsorb UFPs before they agglomerate or soak the HEPA. Finally, any carbon dust or larger UFPs bypassing carbon filtering, can be safely collected by the dual integrated HEPA filters of the Stealthmax.

# (2) Getting Started

## (2.1) Overview
Different printers and use cases require different solutions - choose the StealthMax that fits your needs!
 - ### Regular StealthMax (300) or StealthMax S (250)?
   The StealthMax comes in two sizes:
   | | Regular StealthMax (300) | StealthMax S (250) |
   | ---| --- | --- |
   | Min. Req. Bed Size | 300x300mm | 250x250mm|
   | Carbon Capacity | 2.0 liters | 1.4 liters |
   | HEPA Filter | HEPA Filter for Xiaomi Mijia G1 | Nevermore HEPA Filter |
   | Fan | Delta BFB0712HF | Delta KFB0612HAFDB |

 - ### Back Panel Mount or Direct On Panel Mount?
   The are two options for mounting a StealthMax to your printer:
    - #### Back Panel Mount (BPM)
      The Back Panel Mount is designed to be used with Voron printers (in particular Voron 2 and Trident) by utilizing the back panel's cutout and mounting the StealthMax to the top 2020 extrusion.
    - #### Direct On Panel Mount (DOPM)
      Alternatively, the Direct On Panel Mount can be used to mount a StealthMax on pretty much any panel.
	  [Read more](.../../assets/_unsorted/Direct-On-Panel_Mount)

 - ### Basic or Smart?
    - #### Basic
      Simpler to set up, a sensorless StealthMax only requires the appropriate fan, a 12VDC power source (s. [Power Source](#power-source)) and PWM control (e.g. by using your printer's electronics or a Pico).
    - #### Smart
      Thanks to the [Nevermore Controller](#nevermore-controller), a smart StealthMax utilizes VOC, temperature and humidity sensors to monitor air quality and automatically adjust fan speed.

 - ### Add-ons
   Increase the capability of your StealthMax further and explore our range of add-ons:

    - #### CPAP
      Moves the intake closer to the hotend by attaching it directly to the gantry, maximizing VOC capture potential.

    - #### Displays
      [WORK IN PROGRESS / EARLY DEVELOPMENT]<br>
      Upgrade your StealthMax with a GC9A01 or CST816S display to monitor it's effectiveness at a glance.

    - #### Photocatalytic Oxidation (PCO) Filtration
      [WORK IN PROGRESS / EARLY DEVELOPMENT]<br>
      PCO Filtration mimics the sun's natural breakdown of VOCs. Utilizing UVC lights and a TiO2 mesh, it generates hydroxyl radicals to dismantle VOCs into harmless compounds. This method enhances efficiency by addressing stubborn VOCs, maintains cleanliness between prints, and adapts to heat conditions for optimal performance.
      [Read more](.../../assets/_unsorted/PCO)

 - ### User Mods
   Find clever solutions and unique customizations with our collection of [User Mods](/UserMods) contributed by fellow community members.

## (2.2) Documentation
 - ### Manual
   soon<sup>tm</sup><br>
   In the meantime, you may find the [DOPM focused installation documentation](https://github.com/nevermore3d/StealthMax/blob/main/Docs/DOPM_Preparation.md) useful.

 - ### Print Guide
   Our interactive [Print Guide](https://bit.ly/NevermoreStealthMaxPrintGuide) helps you find the parts you need to print and lets you download all the required STL files at once.

 - ### Nevermore Controller
   A Raspberry Pi Pico W based controller for the Nevermore3D family of 3D printer filters created and maintained by [@SanaaHamel](https://github.com/SanaaHamel). Compatible with Klipper, it offers automatic fan control and leverages Bluetooth LE technology to reduce wiring needs and allow for multiple device connections.
   [Read more](https://github.com/SanaaHamel/nevermore-controller)

# (3) Bill of Materials and Sourcing Guide

#### Power Source
The StealthMax Kits and Bill of Materials (BOM) do not include a power source.<br>
You will need to choose between one of the following options:
-   A 12V power supply unit (PSU) with a minimum rating of 1.5 Amps.
-   Utilize a voltage-selectable fan port on your printer's electronics (if available).

## (3.1) StealthMax Kits
For those who value convenience and simplicity, kits eliminate the guesswork and ensure you have everything you need.

| Kit           | StealthMax Size | Sources                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |  |  |  |
|---------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|---|---|
| Basic         | 300 (Regular)    | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-filter-kit-basic/?wpam_id=2)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) |  |  |  |
| Basic S       | 250 (S)          | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-filter-s-kit-basic/?wpam_id=2)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) |  |  |  |
| Smart         | 300 (Regular)    | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-filter-kit/?wpam_id=2)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | ![US](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "US") [FYSETC](https://s.click.aliexpress.com/e/_msl6FbE)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | ![US](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "US") [Central 3D Printing](https://central3dprinting.com/products/nevermore-stealthmax-kit?ref=NEVERMORE3D)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | ![US](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "US") [Mandala Rose Works](https://mandalaroseworks.com/products/nevermore-stealthmax-hardware-kit?_pos=2&_sid=01b5d81dd&_ss=r&variant=44508025979133) | ![Sweden](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/se.png "Sweden") [3DKATTEN](https://3dkatten.se/en/products/stealthmax-kit?_pos=2&_sid=fafe2628b&_ss=r) |
| Smart S       | 250 (S)          | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-s-filter-kit-advanced/?wpam_id=2)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | ![US](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "US") [Central 3D Printing](https://central3dprinting.com/products/nevermore-stealthmax-s-hardware-kit?ref=NEVERMORE3D)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | ![US](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/us.png "US") [Mandala Rose Works](https://mandalaroseworks.com/products/nevermore-stealthmax-s-small-hardware-kit?_pos=1&_sid=01b5d81dd&_ss=r&variant=44520877785341) |  |
| Fasteners     | _both_           | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [OneTwo3D](https://www.onetwo3d.co.uk/product/nevermore-stealthmax-fastener-kit/?wpam_id=2)![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=) | | | |
| Printed Parts | 300 (Regular)    | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [JB3D](https://jb3d.uk/product/nevermore-stealthmax/) |  |  |  |
| Printed Parts | 250 (S)          | ![UK](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "UK") [JB3D](https://jb3d.uk/product/nevermore-stealthmax-s-printed-parts-kit/) |  |  |  |

![](https://img.shields.io/badge/-rgba(0%2C%200%2C%200%2C%20%200).svg?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuNTkwODc4IDAuMjUgMTQuODIgMTQuMTYiPgoJPHBhdGggZD0iTSA4IDAuMjUgYSAwLjc1IDAuNzUgMCAwIDEgMC42NzMgMC40MTggbCAxLjg4MiAzLjgxNSBsIDQuMjEgMC42MTIgYSAwLjc1IDAuNzUgMCAwIDEgMC40MTYgMS4yNzkgbCAtMy4wNDYgMi45NyBsIDAuNzE5IDQuMTkyIGEgMC43NTEgMC43NTEgMCAwIDEgLTEuMDg4IDAuNzkxIEwgOCAxMi4zNDcgbCAtMy43NjYgMS45OCBhIDAuNzUgMC43NSAwIDAgMSAtMS4wODggLTAuNzkgbCAwLjcyIC00LjE5NCBMIDAuODE4IDYuMzc0IGEgMC43NSAwLjc1IDAgMCAxIDAuNDE2IC0xLjI4IGwgNC4yMSAtMC42MTEgTCA3LjMyNyAwLjY2OCBBIDAuNzUgMC43NSAwIDAgMSA4IDAuMjUgWiIgZmlsbD0iI2UzYjM0MSIvPgo8L3N2Zz4=)Affiliate links: may earn the Nevermore3D project a small commission (at no extra cost to you).

## (3.2) Self Sourcing (BOM)
For those who find satisfaction in the journey, each meticulously sourced component adds to the story of their creation.

See our interactive [Bill of Materials / Sourcing Guide](https://bit.ly/NevermoreStealthMaxBOM) for a complete list of components.


# (4) Contributing
**We welcome your contributions!** <br>
Report any difficulties, suggest ideas, propose solutions, and create new designs or enhance existing ones.
Whether on GitHub or the [Nevermore Discord](https://discord.gg/H8tZ9fZVQ4), your input is valued and appreciated!

[![Discord](https://img.shields.io/discord/1017933489779245137?style=flat-square&logo=discord&logoColor=white&label=Discord&labelColor=%237785cc&color=grey&link=https%3A%2F%2Fdiscord.gg%2FH8tZ9fZVQ4)](https://discord.gg/H8tZ9fZVQ4)


# (5) Acknowledgments
Special thanks for all the help, nudges, support and additions to the project, goes to:
- [@SanaaHamel](https://github.com/SanaaHamel)
- [@FatalBulletHit](https://github.com/FatalBulletHit)
- @TubaToothpasties
- [@Blamm](https://github.com/bartlammers)
- [@Backslash](https://github.com/UnPure)
- [@Exerqtor](https://github.com/Exerqtor)
- [@AdamV3D](https://github.com/AdamV3D)
- [@rajenki](https://github.com/rajenki)

# (6) Showroom
![StealthMax Showroom](.../../assets/showroom/showroom_small.png)
![StealthMax Promo](.../../assets/showroom/showroom_promo.png)
