# imports by Obtaizen
Import Vehicles

## For Custom Car Sounds (For Cars that need them)

* Drag [car-sounds] into your `resources` folder
* Ensure [car-sounds] in your Server CFG
* Add this to your qb-core/shared/vehicles.lua
Obtaizen
#6969

ɳεω — 12/10/2022
i'm just saying what winrar is telling me
Obtaizen — 12/10/2022
okay well idk what you want me to do if winrar is telling you its corrupted it means it didn't download it correctly
ɳεω — 12/10/2022
I just downloaded the link you put and I'm not saying to do anything, I just might know the reason and help me
Obtaizen — 12/10/2022
what?
ɳεω — 12/10/2022
I just went here (https://github.com/Obtaizen/imports) and downloaded it, but as it's giving me an error I thought you could help me, I didn't tell you to do anything buddy
GitHub
GitHub - Obtaizen/imports: NoPixel Vehicles
NoPixel Vehicles. Contribute to Obtaizen/imports development by creating an account on GitHub.
GitHub - Obtaizen/imports: NoPixel Vehicles
Obtaizen — 12/10/2022
And as I told you winrar is saying its corrupt which means it didn't download it correctly so there's not much I can do bud
ɳεω — 12/10/2022
ok, I didn't say anything to the contrary.
It's Panther | Baby — 12/10/2022
btw, there is no issue for me 🙂
Obtaizen — 12/10/2022
Thought so
It's Panther | Baby — 12/10/2022
gonna edit vehicle lua for this. :hehecat:
Obtaizen — 12/10/2022
why what's up with it?
It's Panther | Baby — 12/10/2022
And Ill send it to you 🙂
ɳεω — 12/10/2022
thanks
AIPaskie — 12/10/2022
Realistic handeling?
Obtaizen — 12/10/2022
It’s with what ever handling came with the cars
Alec — 12/10/2022
This is because you're using V1.2 which uses Dynamic Lights. I used V1.1 without Dynamic Lights and works everytime.
Obtaizen — 12/10/2022
I'll try the older version thank you
Obtaizen — 12/10/2022
Worked a treat
Copofiscool — 12/10/2022
Does anyone want me to make a Shared.lua for this pack?
Obtaizen — 12/10/2022
I can but it takes a while
Obtaizen — 12/10/2022
I've done the shared lua just making sure it works some what
obviously if people could test this as well once I post big love ❤️
SuperJack — 12/10/2022
Legend
Obtaizen — 12/10/2022
Think I nearly got it price is just 9999 atm but everyone can change that how they deem fit
-- 180SX

['nis180'] = {
	['name'] = '180sx',
	['brand'] = 'Nissan',
	['model'] = 'nis180',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `nis180`,
	['shop'] = 'pdm',
	},
	
	-- 1979CamaroZ28
	
	['z2879'] = {
	['name'] = 'z28',
	['brand'] = 'Camaro',
	['model'] = 'z2879',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `z2879`,
	['shop'] = 'pdm',
	},
	
	-- 350Z
	
	['maj350z'] = {
	['name'] = '350z',
	['brand'] = 'Nissan',
	['model'] = 'maj350z',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `maj350z`,
	['shop'] = 'pdm',
	},
	
	-- 675LTSpider
	
	['675ltsp'] = {
	['name'] = '675',
	['brand'] = 'McLaren',
	['model'] = '675ltsp',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `675ltsp`,
	['shop'] = 'pdm',
	},
	
	-- 720s
	
	['m720'] = {
	['name'] = '720s',
	['brand'] = 'McLaren',
	['model'] = 'm720',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `m720`,
	['shop'] = 'pdm',
	},
	
	-- 911GT3
	
	['pgt322'] = {
	['name'] = '911GT3',
	['brand'] = 'Porsche',
	['model'] = 'pgt322',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `pgt322`,
	['shop'] = 'pdm',
	},
	
	-- 911Turbo
	
	['turbo33'] = {
	['name'] = '(911 Turbo)',
	['brand'] = 'Porsche',
	['model'] = 'turbo33',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `turbo33`,
	['shop'] = 'pdm',
	},
	
	-- A45AMG
	
	['a45amg'] = {
	['name'] = 'A45 AMG',
	['brand'] = 'Mercedes',
	['model'] = 'a45amg',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `a45amg`,
	['shop'] = 'pdm',
	},
	
	-- AlfaRomero
	
	['gtam21'] = {
	['name'] = 'Giulia GTA',
... (1,327 lines left)
Collapse
message.txt
26 KB
There you  got people
vLxve — 12/10/2022
Is this the list I gave you? Cause if so imma have to cop this since I've been so busy fixing errors and working on new things I haven't even added all the cars lol 😄
Obtaizen — 12/10/2022
Yes it is
xViperAG — 13/10/2022
@Obtaizen I'm not sure if you're aware, the vehicles that are apart of the Lore list have audio sfx files that are needed for the vehicles, as they have no sounds when loaded into the server. I was trying to figure out how to load all the sounds into a pack to allow for it to work and have found nothing so if you got something then shoot. 🙂
Obtaizen — 13/10/2022
I’m currently at work however I know how to get them working
xViperAG — 13/10/2022
Awesome! I was clueless on how to do the packing of the sounds as I'm used to only doing individual cars with all that stuff.
Obtaizen — 13/10/2022
Nah I will try get it sorted when I’m home or over the weekend
xViperAG — 13/10/2022
You got it.
Mike_EzPz — Yesterday at 04:56
Yo just a suggestion if u wanna do it if you are releasing nopixel vehicles maybe u can add a police.folder and add up all the cars in it the nopixel police then it will be a whole.np.pack
xViperAG — Yesterday at 06:03
ps-liveries is the PD pack for "NP Inspired" This is all the local cars.
@Obtaizen I'm making a PR with sounds.
Obtaizen — Yesterday at 06:35
Cheers
Sorry man I would of done it myself I went to work yesterday with no sleep and I’m in work again today
xViperAG — Yesterday at 07:02
You're good.
Just thought I would make life easier
xViperAG — Yesterday at 07:31
Sooo... I thought it worked...
You may need to rewrite it. (Continuing to test it further...) 
xViperAG — Yesterday at 10:11
Alright. It's all squared away now.
Lbd09 — Yesterday at 22:35
Good day all.
I was just wondering if anyone experienced this error when trying to actually purchase and import?

SCRIPT ERROR: @qb-vehicleshop/server.lua:196: attempt to compare string with number
Lbd09 — Yesterday at 22:51
Cars work from admin spawn so, it must just be some sort of store issue on my end.
Obtaizen — Today at 00:10
Have you added them to your config?
Lbd09 — Today at 00:27
as in the qb-vehicleshop config? I added imports as a shopping option. I also added all them to shared/vehicles.lua.
Obtaizen — Today at 00:39
Odd
What’s on line 196 of qb-vehicleshop?
Obtaizen — Today at 01:19
Is anyone else having an issue with skyline aka the r34 where the wheels aren't spawning? aka you don't see them? 
﻿
-- 180SX

['nis180'] = {
	['name'] = '180sx',
	['brand'] = 'Nissan',
	['model'] = 'nis180',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `nis180`,
	['shop'] = 'pdm',
	},
	
	-- 1979CamaroZ28
	
	['z2879'] = {
	['name'] = 'z28',
	['brand'] = 'Camaro',
	['model'] = 'z2879',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `z2879`,
	['shop'] = 'pdm',
	},
	
	-- 350Z
	
	['maj350z'] = {
	['name'] = '350z',
	['brand'] = 'Nissan',
	['model'] = 'maj350z',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `maj350z`,
	['shop'] = 'pdm',
	},
	
	-- 675LTSpider
	
	['675ltsp'] = {
	['name'] = '675',
	['brand'] = 'McLaren',
	['model'] = '675ltsp',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `675ltsp`,
	['shop'] = 'pdm',
	},
	
	-- 720s
	
	['m720'] = {
	['name'] = '720s',
	['brand'] = 'McLaren',
	['model'] = 'm720',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `m720`,
	['shop'] = 'pdm',
	},
	
	-- 911GT3
	
	['pgt322'] = {
	['name'] = '911GT3',
	['brand'] = 'Porsche',
	['model'] = 'pgt322',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `pgt322`,
	['shop'] = 'pdm',
	},
	
	-- 911Turbo
	
	['turbo33'] = {
	['name'] = '(911 Turbo)',
	['brand'] = 'Porsche',
	['model'] = 'turbo33',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `turbo33`,
	['shop'] = 'pdm',
	},
	
	-- A45AMG
	
	['a45amg'] = {
	['name'] = 'A45 AMG',
	['brand'] = 'Mercedes',
	['model'] = 'a45amg',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `a45amg`,
	['shop'] = 'pdm',
	},
	
	-- AlfaRomero
	
	['gtam21'] = {
	['name'] = 'Giulia GTA',
	['brand'] = 'Alfa Romero',
	['model'] = 'gtam21',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gtam21`,
	['shop'] = 'pdm',
	},
	
	-- AMCJavelin-AMX
	
	['aamx'] = {
	['name'] = 'Javelin',
	['brand'] = 'AMC',
	['model'] = 'aamx',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `aamx`,
	['shop'] = 'pdm',
	},
	
	-- AMGG63
	
	['22g63'] = {
	['name'] = 'G63 AMG',
	['brand'] = 'Mercedes',
	['model'] = '22g63',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `22g63`,
	['shop'] = 'pdm',
	},
	
	-- AMGGT
	
	['amggtbs'] = {
	['name'] = 'GT AMG',
	['brand'] = 'Mercedes',
	['model'] = 'amggtbs',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `amggtbs`,
	['shop'] = 'pdm',
	},
	
	-- AstonMartinVictor
	
	['Victor'] = {
	['name'] = 'Victor',
	['brand'] = 'Aston Martin',
	['model'] = 'Victor',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `Victor`,
	['shop'] = 'pdm',
	},
	
	-- AstonMartinVulcan
	
	['vulcan'] = {
	['name'] = 'Vulcan',
	['brand'] = 'Aston Martin',
	['model'] = 'vulcan',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `vulcan`,
	['shop'] = 'pdm',
	},
	
	-- AudiA6
	
	['a6'] = {
	['name'] = 'A6',
	['brand'] = 'Audi',
	['model'] = 'a6',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `a6`,
	['shop'] = 'pdm',
	},
	
	-- AudiRS6
	
	['audirs6tk'] = {
	['name'] = 'RS6',
	['brand'] = 'Audi',
	['model'] = 'audirs6tk',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `audirs6tk`,
	['shop'] = 'pdm',
	},
	
	-- AventadorLP700-4
	
	['lp700-4'] = {
	['name'] = 'Aventador',
	['brand'] = 'Lamborghini',
	['model'] = 'lp700-4',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `lp700-4`,
	['shop'] = 'pdm',
	},
	
	-- Bearcat
	
	['bcat'] = {
	['name'] = 'Bearcat',
	['brand'] = 'Police',
	['model'] = 'bcat',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `bcat`,
	['shop'] = 'pdm',
	},
	
	-- BentleyGT
	
	['contss18'] = {
	['name'] = 'GT',
	['brand'] = 'Bentley',
	['model'] = 'contss18',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `contss18`,
	['shop'] = 'pdm',
	},
	
	-- Bolide
	
	['bolide'] = {
	['name'] = 'Bolide',
	['brand'] = 'Buggati',
	['model'] = 'bolide',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `bolide`,
	['shop'] = 'pdm',
	},
	
	-- Brabham
	
	['bt62r'] = {
	['name'] = '62R',
	['brand'] = 'Brabham',
	['model'] = 'bt62r',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `bt62r`,
	['shop'] = 'pdm',
	},
	
	-- BugattiChiron
	
	['chiron17'] = {
	['name'] = 'Chiron',
	['brand'] = 'Bugatti',
	['model'] = 'chiron17',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `chiron17`,
	['shop'] = 'pdm',
	},
	
	-- BugattiDivo
	
	['bdivo'] = {
	['name'] = 'Divo',
	['brand'] = 'Bugatti',
	['model'] = 'bdivo',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `bdivo`,
	['shop'] = 'pdm',
	},
	
	-- C63AMG
	
	['mbc63'] = {
	['name'] = 'C63 AMG',
	['brand'] = 'Mercedes',
	['model'] = 'mbc63',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `mbc63`,
	['shop'] = 'pdm',
	},
	
	-- CarreraGT
	
	['cgt'] = {
	['name'] = 'Carrera GT',
	['brand'] = 'Porsche',
	['model'] = 'cgt',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `cgt`,
	['shop'] = 'pdm',
	},
	
	-- CivicEG6
	
	['eg6'] = {
	['name'] = 'Civic EG6',
	['brand'] = 'Honda',
	['model'] = 'eg6',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `eg6`,
	['shop'] = 'pdm',
	},
	
	-- CivicTypeR-FK8
	
	['fk8'] = {
	['name'] = 'Civic TypeR',
	['brand'] = 'Honda',
	['model'] = 'fk8',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `fk8`,
	['shop'] = 'pdm',
	},
	
	-- ClioRS
	
	['cliors'] = {
	['name'] = 'Clio RS',
	['brand'] = 'Renault',
	['model'] = 'cliors',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `cliors`,
	['shop'] = 'pdm',
	},
	
	-- CorvetteC7
	
	['c7'] = {
	['name'] = 'C7',
	['brand'] = 'Corvette',
	['model'] = 'c7',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `c7`,
	['shop'] = 'pdm',
	},
	
	-- CouchCar
	
	['couchcar'] = {
	['name'] = 'Car',
	['brand'] = 'Couch',
	['model'] = 'couchcar',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `couchcar`,
	['shop'] = 'pdm',
	},
	
	-- CountachLPI800-4
	
	['lpi8004'] = {
	['name'] = 'Countach',
	['brand'] = 'Lamborghini',
	['model'] = 'lpi8004',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `lpi8004`,
	['shop'] = 'pdm',
	},
	
	-- CW19
	
	['cw2019'] = {
	['name'] = 'CW 2019',
	['brand'] = 'F1',
	['model'] = 'cw2019',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `cw2019`,
	['shop'] = 'pdm',
	},
	
	-- DB11
	
	['db11'] = {
	['name'] = 'DB11',
	['brand'] = 'Aston Martin',
	['model'] = 'db11',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `db11`,
	['shop'] = 'pdm',
	},
	
	-- DiabloGTR
	
	['500gtrlam'] = {
	['name'] = 'Diablo GTR',
	['brand'] = 'Lamborghini',
	['model'] = '500gtrlam',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `500gtrlam`,
	['shop'] = 'pdm',
	},
	
	-- DodgeCharger1969
	
	['69charger'] = {
	['name'] = 'Charger 1969',
	['brand'] = 'Dodge',
	['model'] = '69charger',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `69charger`,
	['shop'] = 'pdm',
	},
	
	-- DodgeDart
	
	['68dart'] = {
	['name'] = '68 Dart',
	['brand'] = 'Dodge',
	['model'] = '68dart',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `68dart`,
	['shop'] = 'pdm',
	},
	
	-- DodgeDemon
	
	['demon'] = {
	['name'] = 'Demon',
	['brand'] = 'Dodge',
	['model'] = 'demon',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `demon`,
	['shop'] = 'pdm',
	},
	
	-- DrafterWidebody
	
	['draftgpr'] = {
	['name'] = 'Widebody',
	['brand'] = 'Drafter',
	['model'] = 'draftgpr',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `draftgpr`,
	['shop'] = 'pdm',
	},
	
	-- Escalade
	
	['gmt900escalade'] = {
	['name'] = 'GMT',
	['brand'] = 'Escalade',
	['model'] = 'gmt900escalade',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gmt900escalade`,
	['shop'] = 'pdm',
	},
	
	-- FairladyZ
	
	['s30'] = {
	['name'] = 'FairladyZ',
	['brand'] = 'Nissan',
	['model'] = 's30',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `s30`,
	['shop'] = 'pdm',
	},
	
	-- Ferrari488
	
	['488gtb'] = {
	['name'] = '488',
	['brand'] = 'Ferrari',
	['model'] = '488gtb',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `488gtb`,
	['shop'] = 'pdm',
	},
	
	-- FerrariFXX-K
	
	['fxxkevo-K'] = {
	['name'] = 'Fxx-k',
	['brand'] = 'Ferrari',
	['model'] = 'fxxkevo',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `fxxkevo`,
	['shop'] = 'pdm',
	},
	
	-- FocusRS
	
	['ffrs'] = {
	['name'] = 'RS',
	['brand'] = 'Focus',
	['model'] = 'ffrs',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `ffrs`,
	['shop'] = 'pdm',
	},
	
	-- FordF150
	
	['f150'] = {
	['name'] = 'F150',
	['brand'] = 'Ford',
	['model'] = 'f150',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `f150`,
	['shop'] = 'pdm',
	},
	
	-- FordGT
	
	['gt17'] = {
	['name'] = 'GT',
	['brand'] = 'Ford',
	['model'] = 'gt17',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gt17`,
	['shop'] = 'pdm',
	},
	
	-- FordMustang1965
	
	['mustang65'] = {
	['name'] = 'Mustang 1965',
	['brand'] = 'Ford',
	['model'] = 'mustang65',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `mustang65`,
	['shop'] = 'pdm',
	},
	
	-- Futo
	
	['futo2'] = {
	['name'] = 'Futo 2',
	['brand'] = 'Karin',
	['model'] = 'futo2',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `futo2`,
	['shop'] = 'pdm',
	},
	
	-- Gauntlet
	
	['gauntlet6str'] = {
	['name'] = '6STR',
	['brand'] = 'Gauntlet',
	['model'] = 'gauntlet6str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gauntlet6str`,
	['shop'] = 'pdm',
	},
	
	-- GT63AMG
	
	['rmodgt63'] = {
	['name'] = 'GT63 AMG',
	['brand'] = 'Mercedes',
	['model'] = 'rmodgt63',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `rmodgt63`,
	['shop'] = 'pdm',
	},
	
	-- GT86
	
	['gt86'] = {
	['name'] = 'GT86',
	['brand'] = 'Toyota',
	['model'] = 'gt86',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gt86`,
	['shop'] = 'pdm',
	},
	
	-- Holden
	
	['asea'] = {
	['name'] = 'Hodlen',
	['brand'] = 'Vauxhall',
	['model'] = 'asea',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `asea`,
	['shop'] = 'pdm',
	},
	
	-- HondaS200
	
	['s2k'] = {
	['name'] = 'S200',
	['brand'] = 'Honda',
	['model'] = 's2k',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `s2k`,
	['shop'] = 'pdm',
	},
	
	-- HuracanLP-610
	
	['610lb'] = {
	['name'] = 'Huracan',
	['brand'] = 'Lamborghini',
	['model'] = '610lb',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `610lb`,
	['shop'] = 'pdm',
	},
	
	-- ImprezaSTI
	
	['sim22'] = {
	['name'] = 'Impreza STI',
	['brand'] = 'Subaru',
	['model'] = 'sim22',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `sim22`,
	['shop'] = 'pdm',
	},
	
	-- ImprezaWRXSTI
	
	['subwrx'] = {
	['name'] = 'Impreza WRX',
	['brand'] = 'Subaru',
	['model'] = 'subwrx',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `subwrx`,
	['shop'] = 'pdm',
	},
	
	-- IntegraTypeR-DC5
	
	['dc5'] = {
	['name'] = 'Integra TypeR',
	['brand'] = 'Honda',
	['model'] = 'dc5',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `dc5`,
	['shop'] = 'pdm',
	},
	
	-- JeepGrandCherokee
	
	['trhawk'] = {
	['name'] = 'Cherokee',
	['brand'] = 'Jeep',
	['model'] = 'trhawk',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `trhawk`,
	['shop'] = 'pdm',
	},
	
	-- KarinDilettante
	
	['dilettantedx'] = {
	['name'] = 'Dilettante',
	['brand'] = 'Karin',
	['model'] = 'dilettantedx',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `dilettantedx`,
	['shop'] = 'pdm',
	},
	
	-- KoenigseggJesko
	
	['jesko'] = {
	['name'] = 'Jesko',
	['brand'] = 'Koenigsegg',
	['model'] = 'jesko',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `jesko`,
	['shop'] = 'pdm',
	},
	
	-- Ladybird
	
	['ladybird6str'] = {
	['name'] = '6STR',
	['brand'] = 'Ladybird',
	['model'] = 'ladybird6str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `ladybird6str`,
	['shop'] = 'pdm',
	},
	
	-- LandCruiser100
	
	['lc100'] = {
	['name'] = 'Land Cruiser',
	['brand'] = 'Toyata',
	['model'] = 'lc100',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `lc100`,
	['shop'] = 'pdm',
	},
	
	-- LexusGS350
	
	['gs350'] = {
	['name'] = 'GS350',
	['brand'] = 'Lexus',
	['model'] = 'gs350',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gs350`,
	['shop'] = 'pdm',
	},
	
	-- LexusLFA
	
	['lexlfa10'] = {
	['name'] = 'LFA',
	['brand'] = 'Lexus',
	['model'] = 'lexlfa10',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `lexlfa10`,
	['shop'] = 'pdm',
	},
	
	-- LexusRCF
	
	['rcf'] = {
	['name'] = 'RCF',
	['brand'] = 'Lexus',
	['model'] = 'rcf',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `rcf`,
	['shop'] = 'pdm',
	},
	
	-- M2
	
	['m2f22'] = {
	['name'] = 'M2',
	['brand'] = 'BMW',
	['model'] = 'm2f22',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `m2f22`,
	['shop'] = 'pdm',
	},
	
	-- M3E36RocketBunny
	
	['e36prb'] = {
	['name'] = 'M3 E36 Rocket Bunny',
	['brand'] = 'BMW',
	['model'] = 'e36prb',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `e36prb`,
	['shop'] = 'pdm',
	},
	
	-- M3E46
	
	['m3e46'] = {
	['name'] = 'M3 E46',
	['brand'] = 'BMW',
	['model'] = 'm3e46',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `m3e46`,
	['shop'] = 'pdm',
	},
	
	-- M4
	
	['m4comp'] = {
	['name'] = 'M4',
	['brand'] = 'BMW',
	['model'] = 'm4comp',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `m4comp`,
	['shop'] = 'pdm',
	},
	
	-- M5
	
	['22m5'] = {
	['name'] = 'M5',
	['brand'] = 'BMW',
	['model'] = '22m5',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `22m5`,
	['shop'] = 'pdm',
	},
	
	-- M5F10
	
	['f10m5'] = {
	['name'] = 'M5 F10',
	['brand'] = 'BMW',
	['model'] = 'f10m5',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `f10m5`,
	['shop'] = 'pdm',
	},
	
	-- MazdaMX5
	
	['na6'] = {
	['name'] = 'MX5',
	['brand'] = 'Mazda',
	['model'] = 'na6',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `na6`,
	['shop'] = 'pdm',
	},
	
	-- MazdaRX7FC
	
	['mfc'] = {
	['name'] = 'RX7 FC',
	['brand'] = 'Mazda',
	['model'] = 'mfc',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `mfc`,
	['shop'] = 'pdm',
	},
	
	-- MazdaRX7FD
	
	['fd'] = {
	['name'] = 'RX7 FD',
	['brand'] = 'Mazda',
	['model'] = 'fd',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `fd`,
	['shop'] = 'pdm',
	},
	
	-- MazdaRX8
	
	['rx811'] = {
	['name'] = 'RX8',
	['brand'] = 'Mazda',
	['model'] = 'rx811',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `rx811`,
	['shop'] = 'pdm',
	},
	
	-- MitsubishiEvoIX
	
	['evo9'] = {
	['name'] = 'EVO 9',
	['brand'] = 'Mitsubishi',
	['model'] = 'evo9',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `evo9`,
	['shop'] = 'pdm',
	},
	
	-- MitsubishiEvoVI
	
	['cp9a'] = {
	['name'] = 'EVO 10',
	['brand'] = 'Mitsubishi',
	['model'] = 'cp9a',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `cp9a`,
	['shop'] = 'pdm',
	},
	
	-- MotorPotty
	
	['potty'] = {
	['name'] = 'Potty',
	['brand'] = 'Motor',
	['model'] = 'potty',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `potty`,
	['shop'] = 'pdm',
	},
	
	-- Murcielago
	
	['lp670'] = {
	['name'] = 'Murcielago',
	['brand'] = 'Lamborghini',
	['model'] = 'lp670',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `lp670`,
	['shop'] = 'pdm',
	},
	
	-- MustangGT
	
	['mgt'] = {
	['name'] = 'Mustang GT',
	['brand'] = 'Ford',
	['model'] = 'mgt',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `mgt`,
	['shop'] = 'pdm',
	},
	
	-- MustangGTWidebody
	
	['rmodmustang'] = {
	['name'] = 'Mustang GT Widebody',
	['brand'] = 'Ford',
	['model'] = 'rmodmustang',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `rmodmustang`,
	['shop'] = 'pdm',
	},
	
	-- NA1
	
	['na1'] = {
	['name'] = 'NA1',
	['brand'] = 'Honda',
	['model'] = 'na1',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `na1`,
	['shop'] = 'pdm',
	},
	
	-- NC1
	
	['nc1'] = {
	['name'] = 'NC1',
	['brand'] = 'Honda',
	['model'] = 'nc1',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `nc1`,
	['shop'] = 'pdm',
	},
	
	-- Odyssey
	
	['honody'] = {
	['name'] = 'Odyssey',
	['brand'] = 'Honda',
	['model'] = 'honody',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `honody`,
	['shop'] = 'pdm',
	},
	
	-- PaganiHuayra
	
	['bc'] = {
	['name'] = 'Huayra',
	['brand'] = 'Pagani',
	['model'] = 'bc',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `bc`,
	['shop'] = 'pdm',
	},
	
	-- PanameraTurbo
	
	['panamera17turbo'] = {
	['name'] = 'Panamera',
	['brand'] = 'Porsche',
	['model'] = 'panamera17turbo',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `panamera17turbo`,
	['shop'] = 'pdm',
	},
	
	-- Polestar
	
	['starone'] = {
	['name'] = 'Polestar',
	['brand'] = 'Volvo',
	['model'] = 'starone',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `starone`,
	['shop'] = 'pdm',
	},
	
	-- PrimoARD
	
	['primoard'] = {
	['name'] = 'ARD',
	['brand'] = 'Primo',
	['model'] = 'primoard',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `primoard`,
	['shop'] = 'pdm',
	},
	
	-- R32
	
	['r32'] = {
	['name'] = 'R32',
	['brand'] = 'Nissan',
	['model'] = 'r32',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `r32`,
	['shop'] = 'pdm',
	},
	
	-- R33
	
	['r33'] = {
	['name'] = 'R33',
	['brand'] = 'Nissan',
	['model'] = 'r33',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `r33`,
	['shop'] = 'pdm',
	},
	
	-- R34
	
	['skyline'] = {
	['name'] = 'R34',
	['brand'] = 'Nissan',
	['model'] = 'skyline',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `skyline`,
	['shop'] = 'pdm',
	},
	
	-- R35
	
	['r35'] = {
	['name'] = 'R35',
	['brand'] = 'Nissan',
	['model'] = 'r35',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `r35`,
	['shop'] = 'pdm',
	},
	
	-- R35Nismo
	
	['gtr'] = {
	['name'] = 'R35 Nismo',
	['brand'] = 'Nissan',
	['model'] = 'gtr',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `gtr`,
	['shop'] = 'pdm',
	},
	
	-- R8Hycade
	
	['r8hycade'] = {
	['name'] = 'Hycade',
	['brand'] = 'Audi',
	['model'] = 'r8hycade',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `r8hycade`,
	['shop'] = 'pdm',
	},
	
	-- R8V10
	
	['r8v10'] = {
	['name'] = 'R8 V10',
	['brand'] = 'Audi',
	['model'] = 'r8v10',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `r8v10`,
	['shop'] = 'pdm',
	},
	
	-- Raid
	
	['raid'] = {
	['name'] = 'Raid',
	['brand'] = 'Raid',
	['model'] = 'raid',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `raid`,
	['shop'] = 'pdm',
	},
	
	-- RangeRover
	
	['rr14'] = {
	['name'] = 'RR14',
	['brand'] = 'Range Rover',
	['model'] = 'rr14',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `rr14`,
	['shop'] = 'pdm',
	},
	
	-- ReliantRobin
	
	['robin'] = {
	['name'] = 'Robin',
	['brand'] = 'Reliant',
	['model'] = 'robin',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `robin`,
	['shop'] = 'pdm',
	},
	
	-- Ruiner
	
	['ruiner6str'] = {
	['name'] = '6STR',
	['brand'] = 'Ruiner',
	['model'] = 'ruiner6str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `ruiner6str`,
	['shop'] = 'pdm',
	},
	
	-- S15
	
	['s15'] = {
	['name'] = 'S15',
	['brand'] = 'Nissan',
	['model'] = 's15',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `s15`,
	['shop'] = 'pdm',
	},
	
	-- Schwartzer
	
	['schwartzer'] = {
	['name'] = 'Schwartzer',
	['brand'] = 'Schwarzter',
	['model'] = 'schwartzer',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `schwartzer`,
	['shop'] = 'pdm',
	},
	
	-- Senna
	
	['senna'] = {
	['name'] = 'Senna',
	['brand'] = 'McLaren',
	['model'] = 'senna',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `senna`,
	['shop'] = 'pdm',
	},
	
	-- SentinelSG4
	
	['sentinelsg4'] = {
	['name'] = 'SG4',
	['brand'] = 'Sentinel',
	['model'] = 'sentinelsg4',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `sentinelsg4`,
	['shop'] = 'pdm',
	},
	
	-- ShoppingKart
	
	['skart'] = {
	['name'] = 'kart',
	['brand'] = 'Shopping',
	['model'] = 'skart',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `skart`,
	['shop'] = 'pdm',
	},
	
	-- SilviaS14Boss
	
	['s14boss'] = {
	['name'] = 'S14 Boss',
	['brand'] = 'Nissan',
	['model'] = 's14boss',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `s14boss`,
	['shop'] = 'pdm',
	},
	
	-- SilviaS14Kouki
	
	['s14'] = {
	['name'] = 'S14 Kouki',
	['brand'] = 'Nissan',
	['model'] = 's14',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `s14`,
	['shop'] = 'pdm',
	},
	
	-- SRTViper
	
	['viper'] = {
	['name'] = 'Viper SRT',
	['brand'] = 'Dodge',
	['model'] = 'viper',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `viper`,
	['shop'] = 'pdm',
	},
	
	-- StingerGT
	
	['kiagt'] = {
	['name'] = 'kiagt',
	['brand'] = 'StingerGT',
	['model'] = 'kiagt',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `kiagt`,
	['shop'] = 'pdm',
	},
	
	-- Stratum
	
	['stratum'] = {
	['name'] = 'Stratum',
	['brand'] = 'statum',
	['model'] = 'Stratum',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `stratum`,
	['shop'] = 'pdm',
	},
	
	-- SultanRSV8
	
	['sultanrsv8'] = {
	['name'] = 'V8 RS',
	['brand'] = 'Sultan',
	['model'] = 'sultanrsv8',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `sultanrsv8`,
	['shop'] = 'pdm',
	},
	
	-- SupraA80
	
	['a80'] = {
	['name'] = 'Supra A80',
	['brand'] = 'Toyata',
	['model'] = 'a80',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `a80`,
	['shop'] = 'pdm',
	},
	
	-- SupraA90
	
	['tsgr20'] = {
	['name'] = 'Supra A90',
	['brand'] = 'Toyata',
	['model'] = 'tsgr20',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `tsgr20`,
	['shop'] = 'pdm',
	},
	
	-- TeslaTruck
	
	['savanna'] = {
	['name'] = 'Savanna',
	['brand'] = 'Tesla',
	['model'] = 'savanna',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `savanna`,
	['shop'] = 'pdm',
	},
	
	-- V8AstonMartin
	
	['v877'] = {
	['name'] = 'V8',
	['brand'] = 'Aston Martin',
	['model'] = 'v877',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `v877`,
	['shop'] = 'pdm',
	},
	
	-- Valkyrie
	
	['valkyrietp'] = {
	['name'] = 'Valkyrie',
	['brand'] = 'Aston Matin',
	['model'] = 'valkyrietp',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `valkyrietp`,
	['shop'] = 'pdm',
	},
	
	-- Vapid
	
	['ellie6str'] = {
	['name'] = 'Ellie 6STR',
	['brand'] = 'Vapid',
	['model'] = 'ellie6str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `ellie6str`,
	['shop'] = 'pdm',
	},
	
	-- Veloster
	
	['veln'] = {
	['name'] = 'Veloster',
	['brand'] = 'Hyundai',
	['model'] = 'veln',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `veln`,
	['shop'] = 'pdm',
	},
	
	-- Yosemite
	
	['yosemite6str'] = {
	['name'] = 'yosemite6str',
	['brand'] = 'Declasse',
	['model'] = 'yosemite6str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `yosemite6str`,
	['shop'] = 'pdm',
	},
	
	-- ZL1
	
	['exor'] = {
	['name'] = 'ZL1',
	['brand'] = 'Camaro',
	['model'] = 'exor',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `exor`,
	['shop'] = 'pdm',
	},
	
	-- ZR380
	
	['zr3806str'] = {
	['name'] = 'ZR380',
	['brand'] = 'Camaro',
	['model'] = 'zr3806str',
	['price'] = '99999', -- EDIT ME
	['category'] = 'import',
	['hash'] = `zr3806str`,
	['shop'] = 'pdm',
	},
message.txt
26 KB

### A bunch of vehicles that NoPixel use.

### Link to where I got the vehicles from https://pastebin.com/jsvw46cn this includes each GTA 5 Mods link

A Screenshot of some of the cars are below.
![image](https://i.imgur.com/xqbQb7p.jpg)
