---
name: Hymnal request
about: Suggest a hymnal to be added in these files for the hymnal app
title: Hymnal request
labels: ''
assignees: ''

---

**The language of the hymnal**

**Source of the hymnal if available or already in json format**
The hymnal is stored in the hymnal.json file as a list (array) of maps and should be in the following format;
[
    {
        "id": 1,
        "language": "Chichewa",
        "title": "Nyimbo za NAC"
    },
//other hymnals
]

Create a file of hymns in that respective language and should be in the following format
{
        "id": 104,
        "title": "title in local language",
        "otherDetails": "number in a reference book \n title in english",
        "lyrics": {
            "verses": [
                "1. Ndiweramitsa nkhope, ndipereka mphatso,\nNgakhale ndi zochepa, Mfumu ikondwera\nChifuniro changacho, m'njira ya imfayi\nKwaniritsani Mbuye, chifuniro chanu.",
                "2. Sindi..."
            ],
            "chorus": "Chorus lyrics"
        }
    },

**Permission by the respective publishing houses to use the hymnal**
