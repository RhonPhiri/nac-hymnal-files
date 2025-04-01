# nac-hymnal-files
This repo contains hymns, hymnals & audio files used in the New Apostolic Church (NAC) app project
## Issues
If the're any typos, new hymnals or suggestions, create a new issue
## New files
If the're new hymnals that you would like to add, ensure that they are in .json format
- Add the hymnal in the hymnals.json file
- For a hymnal, add its respective hymns, ensure that the following format is followed;
```json
[
    {
        "id": 1,
        "title": "Hymn title",
        "otherDetails": "Hymn number in a common reference book\nHymn title in english",
        "lyrics": {
            "verses": [
                "1. Lorem ipasum\nLorem ipsum",
                "2. Lorem ipsum\nLorem ipsum\nLorem ipsum\nLorem ipsum.",
            ],
            "chorus": "Hymn chorus"
        }
    },  
    {
        "id": 2,
        "title": "Hymn title",
        "otherDetails": "588NEH\nHymn title in english",
        "lyrics": {
            "verses": [
                "1. Lorem ipasum\nLorem ipsum",
                "2. Lorem ipsum\nLorem ipsum\nLorem ipsum\nLorem ipsum.",
            ],
            "chorus": "Hymn chorus"
        }
    }
]
```
- Ensure that permission has been granted by the respective publishing houses before they are uploaded.
## Copyright 
The copyrights for each hymnal belong to the publishing houses responsible
## License
```
   Copyright 2025 Rhon Phiri

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```
