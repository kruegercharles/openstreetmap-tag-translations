In OpenStreetMap every map feature is described by tags, which are key-value-pairs. Usually these tags contain English values, but for localized maps these tags can be translated into the native language.

This repository contains translations of common tags. The format is based on the i18n format for the [Chrome browser](https://developer.chrome.com/extensions/i18n-messages).

Examples:
```json
{
    "tag:barrier": {
        "message": "Barrière",
    },
    "tag:barrier=city_wall": {
        "message": "Mur de la ville",
    },
    "tag:name": {
        "message": "Nom",
        "description": "'name' contains name of map feature"
    },
    "tag:phone": "Numéro de tél."
}
```

Every tag key and every tag key-value-pair has an entry in the JSON file. Every entry is a hash with a `message` (the translation) and optionally a `description`:

* `message`: translation
* `description`: help text

Directories
-----------
* The directory `tags/` contains the tag translations

Contributors
------------
Contributers via Git:
* Shu Higashi
* Stephan Bösch-Plepelits

Alphabetic list of contributors, with the full names from OpenStreetBrowser user names:
* Aivo
* Artur Zgodziński
* Barboska
* bazgal
* ciprian
* HgO
* higa4
* Jens Hyllegaard
* Jochen Kiene
* magnumns
* Michal Pustějovský
* Pascal Dugendre
* pinkpussy
* Remco
* Sven N
* Toni
* Wombalton
* Xuacu Saturio
* Yannis Giftomitros

Additionally the following users contributed via OpenStreetMap Wiki (which was used earlier):
* !i!
* Avila.gas
* Bb-osm
* Derstefan
* Dr&mx
* Driver2
* E-Malte
* Higa4
* Hunsly
* Invisible
* Jezevec
* Luis Latin
* Mage Whopper
* Mar4s
* Pbelas
* PierZen
* Rethna
* Richtest
* Soldier Boy
* Sven Eppler
* Vanchester
* Viw
* Xuacu

I hope I didn't miss any contributors. If you feel missed out or like to change information about you, please contact me.
