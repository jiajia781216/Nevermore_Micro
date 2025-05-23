[![Support Nevermore3D - Buy me a coffee](https://img.shields.io/badge/Support%20Nevermore3D%20-Buy%20me%20a%20coffee-orange.svg)](https://www.buymeacoffee.com/nevermore3d)

# Nevermore Activated Carbon Filters - Micro Edition

<div align="center">Nevermore Micro V5 Duo (dual fan)</div>

![Nevermore Activated Carbon Filter Micro V5 Duo](images/DUO_COMBINED_render.png "Nevermore Activated Carbon Filter Micro V5 Duo")

<div align="center">Nevermore Micro V4 (single fan)</div>

![Nevermore Activated Carbon Filter Micro V4](images/logo.png "Nevermore Activated Carbon Filter Micro V4")

Originally intended as a carbon fume filter for Voron V2, it has found its way into a multitude of other machines. Let yours be the next! Bad smells or fumes, or complaints thereof, should not keep you from being a maker!

- [Nevermore Activated Carbon Filters - Micro Edition](#nevermore-activated-carbon-filters---micro-edition)
- [About The Nevermore Micro](#about-the-nevermore-micro)
  - [Why The Nevermore?](#why-the-nevermore)
  - [Nevermore Background](#nevermore-background)
  - [Nevermore V4, First Release](#nevermore-v4-first-release)
  - [Nevermore V5 Duo](#nevermore-v5-duo)
- [FAQs](#faqs)
  - [What are differences between V4 and V5 Duo?](#what-are-differences-between-v4-and-v5-duo)
  - [Why use a single fan version, if dual is better?](#why-use-a-single-fan-version-if-dual-is-better)
  - [What other changes does V5 bring?](#what-other-changes-does-v5-bring)
  - [What fans should I use?](#what-fans-should-i-use)
  - [How do I make a suggestion/report a bug/find out more?](#how-do-i-make-a-suggestionreport-a-bugfind-out-more)
- [Getting Started](#getting-started)
  - [SOURCING THE PROPER ACID-FREE CARBON](#sourcing-the-proper-acid-free-carbon)
  - [NEVERMORE 3D PRINTER CARBON](#nevermore-3d-printer-carbon)
  - [BOM (V5)](#bom-v5)
  - [BOM (V4)](#bom-v4)
  - [Assembly](#assembly)
    - [Instructions for V5](#instructions-for-v5)
    - [Instructions for V4](#instructions-for-v4)
  - [Final Thoughts on Usage](#final-thoughts-on-usage)
- [Credits](#credits)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)
  - [Special Thanks](#special-thanks)

# About The Nevermore Micro

[VOCs (Volatile Organic Compounds)](https://en.wikipedia.org/wiki/Volatile_organic_compound) are common in daily life but VOCs generated from 3D printing are known to cause severe health issues and even cause cancer in some cases.

![Emitted VOCs](images/emitted-voc.jpg "Emitted VOCs")

A study from 2013 of [ultrafine particle emissions from desktop 3D printers (2013)](https://www.sciencedirect.com/science/article/pii/S1352231013005086) is a good start to understand the importance of your filament choices and the printer's environment.

![Characterization of volatile organic compound emissions from consumer level material extrusion 3D printers (2019)](images/emitted-voc2.jpg "Characterization of volatile organic compound emissions from consumer level material extrusion 3D printers (2019)")
_(credit: [Characterization of volatile organic compound emissions from consumer level material extrusion 3D printers (2019)](https://www.sciencedirect.com/science/article/pii/S0360132319304196))_

![Characterization of particulate and gaseous pollutants emitted during operation of a desktop 3D printer (2019)](images/emitted-voc3.jpg "Characterization of particulate and gaseous pollutants emitted during operation of a desktop 3D printer (2019)")
_(credit: [Characterization of particulate and gaseous pollutants emitted during operation of a desktop 3D printer (2019)](https://www.sciencedirect.com/science/article/pii/S0160412018323663))_

## Why The Nevermore?

At the end of the day, a fresh single-pass filtered exhaust (at brand new) has perhaps 70% VOC removal efficiency while still exhausting 30% of the nasty. A worn-in 50% efficiency recirculation filter achieving four passes would still remove 94% of the bad stuff. Or 99% at six passes!

The number of passes you get all depends on how well you can seal your build chamber.

Some will have a hard time achieving a good chamber seal, which creates the biggest drawback of recirculation filters - _they're air flow neutral_. Meaning, as nothing pulls air into the chamber, air can diffuse freely to the outside through any remaining gaps. And that air could be _zero-per-cent_ cleaned...

If you plan on using only a Nevermore - be sure to seal your chamber as good as possible to prevent diffusing.

## Nevermore Background

There are many options for 3d printing air filters. Here’s a short list, and why I eventually settled on creating Nevermore:

**1. Home air purifiers**

**PRO:** Plug and play! High air flow (mostly). Will filter most particles a 3d printer produces.

**CON:** ABS headaches are not from particles, but Volatile Organic Compounds (VOCs), that are two orders of magnitude smaller than any particles a HEPA or ULPA could trap - they’re essentially gasses.

While home purifiers typically also contains carbon filtration and/or photocatlytic UV filtration stages, they will still not be suitable for 3d printing. Why? Efficient carbon adsorption in sufficient amount and stages is an absolute airflow killer, so most purifiers contain only a thin layer of carbon mesh/pellets that will be fully adsorbed within days or weeks at full power. And even if the filter is not used, contact with air saturates the carbon in 1-2 months. Yet they’re advertised as lasting for 6 months – that's only true for the HEPA component, not the VOC adsorbant carbon we're after.

And replacement filters typically run 20-60 USD a pop. Quite a lot for changing every few weeks when the carbon component depletes.

UV photocatalyst activity can last though; however, breakdown is slow and inefficient with voc halflives of several hours. The TiO2 layer reacting to the UV will also easily get irreversibly blocked by silicates (of which there are a lot in peoples homes, in everything from sink and bathroom sealants to plaster walls). And breakdown will many times be incomplete. Styrene passing a PCO filter might get turned to even more dangerous benzene, for instance.

**2. Carbon/HEPA filter combinations like the Zortrax M Series HEPA Filters**

Same as above. The HEPA component will keep working, but the carbon is just a few pebbles per hex. It could provide partial VOC clearance when fresh, but will quickly deplete with air flow. Then you need to replace it for 36 USD after a week of printing.

**3. Wet scrubber**

Awesome for both particles and VOCs, but its an industrial solution with any smaller home versions plagued by loud noise, water leakage and mechanical issues. It's not a solution for the masses.

**So, how about Nevermore?**

Well, the carbon in those filters mentioned above, costing a lot for little duration is actually dirt cheap. Whereas you get 20 grams for 36 USD with a zortax filter, **you can get 5000 grams for 36 USD in bulk**.

And with an enclosed chamber, you don't need the air flow of a room-size air purifier. Even a 350mm V2 Voron only holds about 5cf, meaning even a partial flow from a 5015 fan of 0.5-2cfm is enough to filter the fumes efficiently at the source.

So what are we waiting for? We got lots of cheap carbon. We can replace it easily. We don't need high airflow to clean a small chamber. We deal with poor efficiency of one-pass carbon filters by multiplying the amount and recirculate the air.

Enter, _The Nevermore_.

## Nevermore V4, First Release

Nevermore V4 is a refinement of the V3. V4 adds a air guides, as the previous versions had the majority of air flow on just one side of the filter (most recent version has all supports removed yet again!). The cartridge lid also mounts a bit sturdier, and V4 now has separate base pieces for use with Vorons other than 2.4.

![Nevermore Micro V2 Prototype](images/print_example2.png "Nevermore Micro V2 Prototype")

The V4 was the first official release of the Nevermore Micro to the public.

## Nevermore V5 Duo

Following the V4, the V5 Duo was released that changes the direction of air flow, better suited for when the Nevermore Micro would be placed flat on the bottom or top of the printer. Though there are other "outlet" options, like for the V1.8/Trident style that blows outwards and not up.

The V5 Duo also adds a 2nd additional 5015.

![Nevermore Micro V5 Duo](images/nevermore-micro-duo.jpg "Nevermore Micro V5 Duo")

![Nevermore Micro V5 Duo](images/nevermore-micro-duo-opened.jpg "Nevermore Micro V5 Duo")

_(Nevermore V5 Duo. used with permission from Tightwad(JT)#6055)_

This repository hosts both versions, as they are the same in design and function.

# FAQs

## What are differences between V4 and V5 Duo?

The current NM Micro versions are V4 and V5 Duo.

V4 utilizes a single dissected 5015 fan that is glued in place to spread the airflow over the entire filter surface (something impossible to do with an intact scroll, which focuses the air too much). The intake is on the top, and exhausts out the front.

V5 Duo uses two blowers in parallel to achieve a more even spread of airflow while keeping the pressure-generating scrolls intact; however, it still needs some slight modifications to the scroll exhaust. The intake is on the top, and exhausts upwards.

## Why use a single fan version, if dual is better?

_Dual is not better._ The area per blower is halved, so what is gained in air flow is lost in increased restriction per blower. There should be some improvements though, from linear air flow and intact scroll.

Also, the V4 single fan version may be better suited for printers where the Micro has to be mounted vertically, like on the side of a Voron V0.

![Voron V0.1 with Nevermore V4](images/voron-v0.jpg "Voron V0.1 with Nevermore V4")

_(Voron V0.1 w/Nevermore V4. used with permission from DoubleT#0448)_

The single fan version of the V4 design in the Voron V0 above would draw the air from under the build plate, and exhaust it upwards, creating a circulation flow within the printer.

Air circulation is critical to filter as much of the VOCs within the build chamber as possible. Not only that, but it would help heat the chamber faster and achieve higher chamber temps.

However, on a Voron V2 or similar printer, the V5 Duo version would be better suited when placed under the bed as the upward exhaust venting creates a good circulation effect.

![](images/voron-v2-nevermore.jpg)

_(Voron V2 w/Nevermore V5. used with permission from Laserbeak43#2729)_

## What other changes does V5 bring?

- Exhausts air upwards
  - Better heat spread in the Voron V2 chamber
  - Less air leaks through Voron V2 split doors
- BOM 6x3 magnets are standard
- Blower fans are seated by bolts again, with less modifications needed

## What fans should I use?

Aim for any 5015 blower with a rating above 200Pa / 20mmH2O / 1 inH2O.

Since the fan (probably) cant be reused for other projects and will function in a high temp environment affecting its lifetime, go for budget. The Sunon Maglev MF50151VX (12V) / MF50152VX (24V) (high speed version, 6000 rpm) is good but unfortunately almost impossible to find as most are fakes. The GDStime 6000rpm Dual Ball bearing is another good option, but quality may vary. The Delta BFB0524HH is a gucci option, as is the special micro versions made for the papst rlf-35 which is an equally awesome and expensive fan. Any fan that works well for stealthburner should be a good option for nevermore micro as well.

See the BOM below for more details.

## How do I make a suggestion/report a bug/find out more?

- [The Nevermore Micro](https://github.com/nevermore3d/Nevermore_Micro)
  - [Report a Bug](https://github.com/nevermore3d/Nevermore_Micro/issues)
  - [Request a Feature](https://github.com/nevermore3d/Nevermore_Micro/issues)
- [Explore all Nevermore Activated Carbon Filters](https://github.com/nevermore3d)

# Getting Started

You're ready to build a Nevermore Micro? Cool!

> [!NOTE]  
> MADE FOR ABS/PC/PETG - USE A DECENTLY HEAT RESISTANT FILAMENT !!

> [!NOTE]  
>  Since you are committing to fan dissection, be aware a 5015 used for a NM Micro will most likely never find a different purpose!

## SOURCING THE PROPER ACID-FREE CARBON

**IMPORTANT!** Since first release the varying quality carbon out there has become increasingly evident. Users has both gotten bad carbon as well as outright dangerous stuff (in one case oxidizing most metal surfaces in a new voron in minutes. Be sure to vet your carbon supplier! You do not want your printer to look like this.

![Acid residue on end-stop switch oxidizing](images/endstop-switch-acid-residue.jpg "Acid residue on end-stop switch oxidizing")

_(z end-stop switch after using acid residue carbon for 30 minutes, oxidizing)_

![Acid residue on rails and screws oxidizing](images/voron2-oxidation1.png "Acid residue on rails and screws oxidizing")

_(oxidation on rails and screws after using acid residue carbon. used with permission from Zeptron#8880)_

![Acid residue on filament tension spring oxidizing](images/voron2-oxidation2.png "Acid residue on filament tension spring oxidizing")

_(oxidation on filament tension spring after using acid residue carbon. used with permission from Zeptron#8880)_

![Acid residue on bolts and washers oxidizing](images/voron2-oxidation3.png "Acid residue on bolts and washers oxidizing")

_(oxidation on bolts and washers after using acid residue carbon. used with permission from Zeptron#8880)_

**Picking the Right Carbon for Your 3D Printer**

Choosing the optimal activated carbon for a specific task requires careful
consideration of several key factors, including surface area, CTC/benzene
efficiency, porosity, and pH. These properties play a crucial role in determining the
effectiveness and efficiency of the activated carbon in adsorbing target
contaminants!

**Surface area** is perhaps the most critical factor, as it directly influences the
adsorption capacity of the activated carbon. A higher surface area allows for more
adsorption sites, enabling the activated carbon to capture and retain a greater
amount of contaminants. Activated carbons typically range from 500 to 1250 m²/g,
and a carbon of 1200 m²/g would have twice the capture capacity compared to a
600 m²/g carbon. A good carbon usually has at least 1000 m²/g.
Be sure you're not getting scammed by buying 25% cheaper carbon that lasts half
as long!

**CTC** (Carbon Tetrachloride) **efficiency** - or even better for 3D printing applications,
aromatic hydrocarbon efficiency - is another important consideration, as it
measures the activated carbon's ability to adsorb volatile organic compounds
created from 3D printing. A higher CTC efficiency indicates a greater proportion of
micro-pores, which are essential for capturing - and holding on to - small
contaminants like airstream VOCs. Choosing an activated carbon with a CTC
efficiency that matches the size of the target contaminants ensures optimal
adsorption performance. A good carbon usually has at least 60% CTC.
Be sure you're not getting scammed by buying 25% cheaper carbon that captures
half as much!

**Porosity** , which refers to the distribution of pore sizes within the activated carbon,
also plays a significant role. Activated carbons, depending on quality and carbon
source, will have different ratios of micro-pores (<2 nm), meso-pores (2-50 nm),
and macro-pores (>50 nm). For general use, an even mix might be preferred, as
they can effectively capture a broad spectrum of contaminants while allowing for
efficient mass transfer and regeneration. However, for 3D printing use, a high
micro- and mesoporosity is ideal to both capture VOCs (<2 nm) and VOC-
agglomerates (ultra-fine particles, <50 nm), whereas macropores will struggle to
hold on to VOCs in a hot application like a 3D printer's heated chamber. Good
carbon types for our application are usually sourced from coconut or anthracite, as
they are highly microporous, whereas other common carbons, such as bamboo or
bituminous, usually have a larger percentage of macropores.
Be sure you're not getting scammed by buying 25% cheaper carbon that releases
half the VOCs again!

**The pH of your activated carbon** should be considered, especially when dealing
with pH-sensitive applications or contaminants. Activated carbons with a neutral or


slightly alkaline pH are suitable for most applications, while acidic or basic activated
carbons may be required for specific tasks. In order to capture any VOC type
generated from any filament, a neutral carbon (capable of binding to both neutral,
acidic, and alkaline VOCs) is preferred. Some users have also experienced severe
printer corrosion from using acid-contaminated/treated carbon that, for some
reason, got released with the heating cycles.
Be sure to buy a 3D printer-safe carbon that is steam-activated and not acid-
treated/coated!

**Compare carbons in a jiffy**

As a general comparison number for neutral carbons, try multiplying surface area
and CTC efficiency (available space * capturing efficiency):

**Carbon A** : 1250 m²/g * 80% CTC would be 1250 * 0.8 = 1000 ( _yes, this is
Nevermore specs_ )

**Carbon B** : 1000 m²/g * 50% CTC would be 1000 * 0.5 = 500

This means that Carbon A can be expected to be 2x the performance, capturing
more VOCs for longer.

Be sure to buy Carbon A unless it's twice the price (or if you wish to refill your
cartridges twice as often - it gets tedious quickly!).


## NEVERMORE 3D PRINTER CARBON
**Nevermore offers its own premium carbon of unmatched specifications through selected voron resellers.** Its the best activated carbon for 3D printer use we have found after speaking to most major, vetted suppliers, offering benzene adsorbtion of up to 48 wt%, **surface area of 1250** and **CTC value of 80**. It doesn't come cheap compared to bulk carbon from amazon, but its safe, has unbeatable performance, and every purchase supports the nevermore project by at least a dollar.  

[All Nevermore resellers here](https://github.com/nevermore3d/Reseller)

## BOM (V5)

- 2x 5015 blowers (rating above 200Pa / 20mmH2O / 1 inH2O)
  - Sunon Maglev MF5015VX (high speed version, 6000 rpm. NOTE: There are A LOT of fake sunons out there, even from usually reputable sources. Blantant examples include 24V versions. Also, Sunon does not officially reecommend PWM:ing this fan, so while its still perfectly doable it can have unintended consequences later on) (There is no 24V version for this fan only comes in 12 V)
  - GDStime 6000rpm Dual Ball bearing on Aliexpress (This is 12V rated fans)
  - Delta BFB0524HH (This is 24V rated fans)
  - Avoid mechatronics fans for this purpose.
- 6x M3, 5 mm OD, 4 mm height heatset inserts (standard voron issue)
  - 1 in plenum base to secure plenum lid
  - 1 in cartridge base to secure cartridge lide
  - 4 in fans (2 in each fan × 2 fans)
- 8x ⌀6x3 mm round magnets
- 1x 2 pin JST header
- 4x M3x16 BHCS
  - for heat inserts that go into the four fan tabs
- 1x M3x18 BHCS
  - ONLY for delta and v1.8 variants
- 1x M3x6 BHCS
- 1x M3x4 BHCS
  - for the extra hole in the plenum@lid for symmetry (it doesn’t attach to anything and is totally optional)

Acid-free Activated Carbon

- 4mm Active Carbon Air Filter Pellets

Optional for the cartridge closure

- 1x M3x0.5mm Heatset inserts
- 1x M3x6 BHCS

Optional for Vorons or any printer with 2020 extrusions

- 2x M3x12 SHCS
- 2x M3 2020 T-Nuts

Optional for Vorons or any printer using 24PSU
- 24 to 12 buck converter

## BOM (V4)

- 1x 5015 blowers (rating above 200Pa / 20mmH2O / 1 inH2O)
  - Sunon Maglev MF5015VX (high speed version, 6000 rpm. The 5000 rpm might be okay also)
  - or, the $4-6 GDStime 6000rpm Dual Ball bearing on Aliexpress
- 4x M3, 5mm OD, 4mm height Heatset inserts (standard voron issue)
  - 2 for seating plenum to base
  - 2 for seating plenum lid to plenum
- 8x ⌀4x6 mm or ⌀6x3 mm magnets
  - Make sure to print correct parts (4x6 or 6x3 files)
- 1x 2 pin JST header
- 2x M3x10 SHCS
  - for seating plenum to base
- 2x M3x6 BHCS (any size, fits up to 20mm)
  - for seating plenum lid to plenum

Acid-free Activated Carbon

- 4mm Active Carbon Air Filter Pellets

Optional for Vorons or any printer with 2020 extrusions

- 2x M3x12 SHCS
- 2x M3 2020 T-Nuts

## Assembly

Check out assembly images (**take note at how the fans are cut!**) here: [Nevermore V5 Plenum Assembly Album](https://ibb.co/album/0BN405?sort=name_asc&page=1&params_hidden%5Blist%5D=images&params_hidden%5Bfrom%5D=album&params_hidden%5Balbumid%5D=0BN405)

### Instructions for V5

Print pieces without supports. This goes for all Nevermore parts. Do note that there as **built-in support** below the cartridge insert. This is meant to be easily removed by pushing or crushing (it's a single line wall). 

### Instructions for V4

Start by cutting up the 5015 so just the center remains. Take off the top half, cut the bottom piece circular along the fan blades. We aim for removing the focused air stream and instead achieve an even pressure across all of the filter medium.

The Nevermore Micro has three main parts: **Base**, **Plenum**, and **Cartridge** (plus lids for the plenum/cartridge).

- **Base** is mounted in the 130mm space between the bottom extrusions found on many vorons (designed for v2 originally). It’s seated with one m3 on each side, that screws into to a receiving 2020 M3 T-nut.

- **Plenum** holds the cut up 5015 fan, and is seated with two m3 screws into the base (base has two recieving m3 4mm heat inserts) on each side.

- **Cartridge** holds the filter medium of your choice (made for 4mm air filter active carbon pellets, but feel free to filter with what you think works best!). It snaps onto the Plenum piece for easy and quick removal.

For wiring, you are free to connect however works with your printer. If you do not have any direct controls on your MCU (controller board), then directly wiring may be your only option (with an inline switch).

However, if your MCU does have an additional fan output, then it is recommended to connect to it. If you are using Klipper on a Raspberry Pi, you have the option of using PWM fans and connecting the control wire to one of your PWM outputs on the RPi 40-pin header.

## Final Thoughts on Usage

**PID tune AGAIN if a Nevermore Micro is installed right beneath a heated bed, or draws/exhausts air over the bed thermistor. This is important, as worst case it could cause the bed to overheat, and/or make the heater adhesive burn (this will smell worse than any ABS printing!), and/or possibly even damage the bed heater.**

The Nevermore Micro's activated carbon will not filter Ultra-Fine Particulates (UFP). This is what the HEPA filter does in the Nevermore Mini (not released yet) and [Nevermore Max](https://github.com/nevermore3d/Nevermore_Max) variants. Those also have built-in negative-pressure fans.

However, you can achieve the same results with the Nevermore Micro by using a HEPA filter of your own and creating slightly negative air-pressure within your build chamber, exhausting air outwards at a slow pace. Since you are filtering with the Nevermore, the vast majority of VOCs will be filters by the active carbon filtration, leaving the HEPA filter to capture the remaining UFPs. This also greatly extends the live of your HEPA filter as the Nevermore Micro will be accumulating the larger particulates.

To create a negative pressure within your build chamber, simply install a fan to slowly draw air out of your build chamber and our through a HEPA filter. Voron machines already have such a design with their rear exhaust housing for HEPA filters.

The negative pressure will also eliminate diffusion, especially if your build chamber is not completely sealed.

# Credits

The Nevermore Activated Carbon Filter was modelled in [Fusion 360](http://autodesk.com).

## Contributing

Please contribute! I'd like to incorporate VOC sensors, making the filter smart (running on low-noise mode at an acceptable VOC level, then ramp up at the end to clean more thoroughly before doors open).

## License

Distributed under GNU General Public License version 3.0 (GPLv3)

## Contact

- Discord: 0ndsk4 - (<https://discord.com/user/0ndsk4>)
- Nevermore: [https://github.com/nevermore3d](https://github.com/nevermore3d)

## Acknowledgements

- [The Voron Dev Team](https://vorondesign.com/)

## Special Thanks

- [eduncan911#4852](https://github.com/eduncan911) as the Git Guru to publish all of this
