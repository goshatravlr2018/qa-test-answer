# QA Automation Engineer Test Results

Here is all answer to the test tasks

## As a user, I want to be able to fetch a list of countries, so that I can display them in my own application.

Acceptance Criteria:
```
The endpoint should be publicly available
The countries should be sorted by their population by default
```
Use the endpoint GET /countries.

```bash
Set up the Authorization (Type: Basic Auth)
Username: admin
Password: p@55w07d
```

## Get the list of countries

```python
GET http://localhost:8080/countries

# returns list of countries
[
   {
       "name": "AFGHANISTAN",
       "code": "afg",
       "population": 0
   },
   {
       "name": "ALBANIA",
       "code": "alb",
       "population": 0
   },
   {
       "name": "ALGERIA",
       "code": "alg",
       "population": 0
   },
   {
       "name": "AMERICAN SAMOA",
       "code": "asa",
       "population": 0
   },
   {
       "name": "ANDORRA",
       "code": "and",
       "population": 0
   },
   {
       "name": "ANGOLA",
       "code": "ang",
       "population": 0
   },
   {
       "name": "ANTIGUA AND BARBUDA",
       "code": "ant",
       "population": 0
   },
   {
       "name": "ARGENTINA",
       "code": "arg",
       "population": 0
   },
   {
       "name": "ARMENIA",
       "code": "arm",
       "population": 0
   },
   {
       "name": "ARUBA",
       "code": "aru",
       "population": 0
   },
   {
       "name": "AUSTRALIA",
       "code": "aus",
       "population": 0
   },
   {
       "name": "AUSTRIA",
       "code": "aut",
       "population": 0
   },
   {
       "name": "AZERBAIJAN",
       "code": "aze",
       "population": 0
   },
   {
       "name": "BAHAMAS",
       "code": "bah",
       "population": 0
   },
   {
       "name": "BAHRAIN",
       "code": "brn",
       "population": 0
   },
   {
       "name": "BANGLADESH",
       "code": "ban",
       "population": 0
   },
   {
       "name": "BARBADOS",
       "code": "bar",
       "population": 0
   },
   {
       "name": "BELARUS",
       "code": "blr",
       "population": 0
   },
   {
       "name": "BELGIUM",
       "code": "bel",
       "population": 0
   },
   {
       "name": "BELIZE",
       "code": "biz",
       "population": 0
   },
   {
       "name": "BENIN",
       "code": "ben",
       "population": 0
   },
   {
       "name": "BERMUDA",
       "code": "ber",
       "population": 0
   },
   {
       "name": "BHUTAN",
       "code": "bhu",
       "population": 0
   },
   {
       "name": "BOLIVIA",
       "code": "bol",
       "population": 0
   },
   {
       "name": "BOSNIA AND HERZEGOVINA",
       "code": "bih",
       "population": 0
   },
   {
       "name": "BOTSWANA",
       "code": "bot",
       "population": 0
   },
   {
       "name": "BRAZIL",
       "code": "bra",
       "population": 0
   },
   {
       "name": "BRUNEI DARUSSALAM",
       "code": "bru",
       "population": 0
   },
   {
       "name": "BULGARIA",
       "code": "bul",
       "population": 0
   },
   {
       "name": "BURKINA FASO",
       "code": "bur",
       "population": 0
   },
   {
       "name": "BURUNDI",
       "code": "bdi",
       "population": 0
   },
   {
       "name": "CAMBODIA",
       "code": "cam",
       "population": 0
   },
   {
       "name": "CAMEROON",
       "code": "cmr",
       "population": 0
   },
   {
       "name": "CANADA",
       "code": "can",
       "population": 0
   },
   {
       "name": "CAPE VERDE",
       "code": "cpv",
       "population": 0
   },
   {
       "name": "CAYMAN ISLANDS",
       "code": "cay",
       "population": 0
   },
   {
       "name": "CENTRAL AFRICAN REPUBLIC",
       "code": "caf",
       "population": 0
   },
   {
       "name": "CHAD",
       "code": "cha",
       "population": 0
   },
   {
       "name": "CHILE",
       "code": "chi",
       "population": 0
   },
   {
       "name": "CHINESE TAIPEI",
       "code": "tpe",
       "population": 0
   },
   {
       "name": "COLOMBIA",
       "code": "col",
       "population": 0
   },
   {
       "name": "COMOROS",
       "code": "com",
       "population": 0
   },
   {
       "name": "CONGO",
       "code": "cgo",
       "population": 0
   },
   {
       "name": "COOK ISLANDS",
       "code": "cok",
       "population": 0
   },
   {
       "name": "COSTA RICA",
       "code": "crc",
       "population": 0
   },
   {
       "name": "CÔTE D'IVOIRE",
       "code": "civ",
       "population": 0
   },
   {
       "name": "CROATIA",
       "code": "cro",
       "population": 0
   },
   {
       "name": "CUBA",
       "code": "cub",
       "population": 0
   },
   {
       "name": "CYPRUS",
       "code": "cyp",
       "population": 0
   },
   {
       "name": "CZECH REPUBLIC",
       "code": "cze",
       "population": 0
   },
   {
       "name": "DEMOCRATIC PEOPLE'S REPUBLIC OF KOREA",
       "code": "prk",
       "population": 0
   },
   {
       "name": "DEMOCRATIC REPUBLIC OF THE CONGO",
       "code": "cod",
       "population": 0
   },
   {
       "name": "DENMARK",
       "code": "den",
       "population": 0
   },
   {
       "name": "DJIBOUTI",
       "code": "dji",
       "population": 0
   },
   {
       "name": "DOMINICAN REPUBLIC",
       "code": "dom",
       "population": 0
   },
   {
       "name": "DOMINIQUE",
       "code": "dma",
       "population": 0
   },
   {
       "name": "ECUADOR",
       "code": "ecu",
       "population": 0
   },
   {
       "name": "EGYPT",
       "code": "egy",
       "population": 0
   },
   {
       "name": "EL SALVADOR",
       "code": "esa",
       "population": 0
   },
   {
       "name": "EQUATORIAL GUINEA",
       "code": "geq",
       "population": 0
   },
   {
       "name": "ERITREA",
       "code": "eri",
       "population": 0
   },
   {
       "name": "ESTONIA",
       "code": "est",
       "population": 0
   },
   {
       "name": "ESWATINI",
       "code": "swz",
       "population": 0
   },
   {
       "name": "ETHIOPIA",
       "code": "eth",
       "population": 0
   },
   {
       "name": "FEDERATED STATES OF MICRONESIA",
       "code": "fsm",
       "population": 0
   },
   {
       "name": "FIJI",
       "code": "fij",
       "population": 0
   },
   {
       "name": "FINLAND",
       "code": "fin",
       "population": 0
   },
   {
       "name": "FRANCE",
       "code": "fra",
       "population": 0
   },
   {
       "name": "GABON",
       "code": "gab",
       "population": 0
   },
   {
       "name": "GAMBIA",
       "code": "gam",
       "population": 0
   },
   {
       "name": "GEORGIA",
       "code": "geo",
       "population": 0
   },
   {
       "name": "GERMANY",
       "code": "ger",
       "population": 0
   },
   {
       "name": "GHANA",
       "code": "gha",
       "population": 0
   },
   {
       "name": "GREAT BRITAIN",
       "code": "gbr",
       "population": 0
   },
   {
       "name": "GREECE",
       "code": "gre",
       "population": 0
   },
   {
       "name": "GRENADA",
       "code": "grn",
       "population": 0
   },
   {
       "name": "GUAM",
       "code": "gum",
       "population": 0
   },
   {
       "name": "GUATEMALA",
       "code": "gua",
       "population": 0
   },
   {
       "name": "GUINEA",
       "code": "gui",
       "population": 0
   },
   {
       "name": "GUINEA-BISSAU",
       "code": "gbs",
       "population": 0
   },
   {
       "name": "GUYANA",
       "code": "guy",
       "population": 0
   },
   {
       "name": "HAITI",
       "code": "hai",
       "population": 0
   },
   {
       "name": "HONDURAS",
       "code": "hon",
       "population": 0
   },
   {
       "name": "HONG KONG, CHINA",
       "code": "hkg",
       "population": 0
   },
   {
       "name": "HUNGARY",
       "code": "hun",
       "population": 0
   },
   {
       "name": "ICELAND",
       "code": "isl",
       "population": 0
   },
   {
       "name": "INDIA",
       "code": "ind",
       "population": 0
   },
   {
       "name": "INDONESIA",
       "code": "ina",
       "population": 0
   },
   {
       "name": "IRAQ",
       "code": "irq",
       "population": 0
   },
   {
       "name": "IRELAND",
       "code": "irl",
       "population": 0
   },
   {
       "name": "ISLAMIC REPUBLIC OF IRAN",
       "code": "iri",
       "population": 0
   },
   {
       "name": "ISRAEL",
       "code": "isr",
       "population": 0
   },
   {
       "name": "ITALY",
       "code": "ita",
       "population": 0
   },
   {
       "name": "JAMAICA",
       "code": "jam",
       "population": 0
   },
   {
       "name": "JAPAN",
       "code": "jpn",
       "population": 0
   },
   {
       "name": "JORDAN",
       "code": "jor",
       "population": 0
   },
   {
       "name": "KAZAKHSTAN",
       "code": "kaz",
       "population": 0
   },
   {
       "name": "KENYA",
       "code": "ken",
       "population": 0
   },
   {
       "name": "KIRIBATI",
       "code": "kir",
       "population": 0
   },
   {
       "name": "KOSOVO",
       "code": "kos",
       "population": 0
   },
   {
       "name": "KUWAIT",
       "code": "kuw",
       "population": 0
   },
   {
       "name": "KYRGYZSTAN",
       "code": "kgz",
       "population": 0
   },
   {
       "name": "LAO PEOPLE'S DEMOCRATIC REPUBLIC",
       "code": "lao",
       "population": 0
   },
   {
       "name": "LATVIA",
       "code": "lat",
       "population": 0
   },
   {
       "name": "LEBANON",
       "code": "lbn",
       "population": 0
   },
   {
       "name": "LESOTHO",
       "code": "les",
       "population": 0
   },
   {
       "name": "LIBERIA",
       "code": "lbr",
       "population": 0
   },
   {
       "name": "LIBYA",
       "code": "lba",
       "population": 0
   },
   {
       "name": "LIECHTENSTEIN",
       "code": "lie",
       "population": 0
   },
   {
       "name": "LITHUANIA",
       "code": "ltu",
       "population": 0
   },
   {
       "name": "LUXEMBOURG",
       "code": "lux",
       "population": 0
   },
   {
       "name": "MADAGASCAR",
       "code": "mad",
       "population": 0
   },
   {
       "name": "MALAWI",
       "code": "maw",
       "population": 0
   },
   {
       "name": "MALAYSIA",
       "code": "mas",
       "population": 0
   },
   {
       "name": "MALDIVES",
       "code": "mdv",
       "population": 0
   },
   {
       "name": "MALI",
       "code": "mli",
       "population": 0
   },
   {
       "name": "MALTA",
       "code": "mlt",
       "population": 0
   },
   {
       "name": "MARSHALL ISLANDS",
       "code": "mhl",
       "population": 0
   },
   {
       "name": "MAURITANIA",
       "code": "mtn",
       "population": 0
   },
   {
       "name": "MAURITIUS",
       "code": "mri",
       "population": 0
   },
   {
       "name": "MEXICO",
       "code": "mex",
       "population": 0
   },
   {
       "name": "MONACO",
       "code": "mon",
       "population": 0
   },
   {
       "name": "MONGOLIA",
       "code": "mgl",
       "population": 0
   },
   {
       "name": "MONTENEGRO",
       "code": "mne",
       "population": 0
   },
   {
       "name": "MOROCCO",
       "code": "mar",
       "population": 0
   },
   {
       "name": "MOZAMBIQUE",
       "code": "moz",
       "population": 0
   },
   {
       "name": "MYANMAR",
       "code": "mya",
       "population": 0
   },
   {
       "name": "NAMIBIA",
       "code": "nam",
       "population": 0
   },
   {
       "name": "NAURU",
       "code": "nru",
       "population": 0
   },
   {
       "name": "NEPAL",
       "code": "nep",
       "population": 0
   },
   {
       "name": "NETHERLANDS",
       "code": "ned",
       "population": 0
   },
   {
       "name": "NEW ZEALAND",
       "code": "nzl",
       "population": 0
   },
   {
       "name": "NICARAGUA",
       "code": "nca",
       "population": 0
   },
   {
       "name": "NIGER",
       "code": "nig",
       "population": 0
   },
   {
       "name": "NIGERIA",
       "code": "ngr",
       "population": 0
   },
   {
       "name": "NORWAY",
       "code": "nor",
       "population": 0
   },
   {
       "name": "OMAN",
       "code": "oma",
       "population": 0
   },
   {
       "name": "PAKISTAN",
       "code": "pak",
       "population": 0
   },
   {
       "name": "PALAU",
       "code": "plw",
       "population": 0
   },
   {
       "name": "PALESTINE",
       "code": "ple",
       "population": 0
   },
   {
       "name": "PANAMA",
       "code": "pan",
       "population": 0
   },
   {
       "name": "PAPUA NEW GUINEA",
       "code": "png",
       "population": 0
   },
   {
       "name": "PARAGUAY",
       "code": "par",
       "population": 0
   },
   {
       "name": "PEOPLE'S REPUBLIC OF CHINA",
       "code": "chn",
       "population": 0
   },
   {
       "name": "PERU",
       "code": "per",
       "population": 0
   },
   {
       "name": "PHILIPPINES",
       "code": "phi",
       "population": 0
   },
   {
       "name": "POLAND",
       "code": "pol",
       "population": 0
   },
   {
       "name": "PORTUGAL",
       "code": "por",
       "population": 0
   },
   {
       "name": "PUERTO RICO",
       "code": "pur",
       "population": 0
   },
   {
       "name": "QATAR",
       "code": "qat",
       "population": 0
   },
   {
       "name": "REPUBLIC OF KOREA",
       "code": "kor",
       "population": 0
   },
   {
       "name": "REPUBLIC OF MOLDOVA",
       "code": "mda",
       "population": 0
   },
   {
       "name": "ROMANIA",
       "code": "rou",
       "population": 0
   },
   {
       "name": "RUSSIAN FEDERATION",
       "code": "rus",
       "population": 0
   },
   {
       "name": "RWANDA",
       "code": "rwa",
       "population": 0
   },
   {
       "name": "SAINT KITTS AND NEVIS",
       "code": "skn",
       "population": 0
   },
   {
       "name": "SAINT LUCIA",
       "code": "lca",
       "population": 0
   },
   {
       "name": "SAMOA (UNTIL 1996 WESTERN SAMOA)",
       "code": "sam",
       "population": 0
   },
   {
       "name": "SAN MARINO",
       "code": "smr",
       "population": 0
   },
   {
       "name": "SAO TOME AND PRINCIPE",
       "code": "stp",
       "population": 0
   },
   {
       "name": "SAUDI ARABIA",
       "code": "ksa",
       "population": 0
   },
   {
       "name": "SENEGAL",
       "code": "sen",
       "population": 0
   },
   {
       "name": "SERBIA",
       "code": "srb",
       "population": 0
   },
   {
       "name": "SEYCHELLES",
       "code": "sey",
       "population": 0
   },
   {
       "name": "SIERRA LEONE",
       "code": "sle",
       "population": 0
   },
   {
       "name": "SINGAPORE",
       "code": "sgp",
       "population": 0
   },
   {
       "name": "SLOVAKIA",
       "code": "svk",
       "population": 0
   },
   {
       "name": "SLOVENIA",
       "code": "slo",
       "population": 0
   },
   {
       "name": "SOLOMON ISLANDS",
       "code": "sol",
       "population": 0
   },
   {
       "name": "SOMALIA",
       "code": "som",
       "population": 0
   },
   {
       "name": "SOUTH AFRICA",
       "code": "rsa",
       "population": 0
   },
   {
       "name": "SOUTH SUDAN",
       "code": "ssd",
       "population": 0
   },
   {
       "name": "SPAIN",
       "code": "esp",
       "population": 0
   },
   {
       "name": "SRI LANKA",
       "code": "sri",
       "population": 0
   },
   {
       "name": "ST VINCENT AND THE GRENADINES",
       "code": "vin",
       "population": 0
   },
   {
       "name": "SUDAN",
       "code": "sud",
       "population": 0
   },
   {
       "name": "SURINAME",
       "code": "sur",
       "population": 0
   },
   {
       "name": "SWEDEN",
       "code": "swe",
       "population": 0
   },
   {
       "name": "SWITZERLAND",
       "code": "sui",
       "population": 0
   },
   {
       "name": "SYRIAN ARAB REPUBLIC",
       "code": "syr",
       "population": 0
   },
   {
       "name": "TAJIKISTAN",
       "code": "tjk",
       "population": 0
   },
   {
       "name": "THAILAND",
       "code": "tha",
       "population": 0
   },
   {
       "name": "THE FORMER YUGOSLAV REPUBLIC OF MACEDONIA",
       "code": "mkd",
       "population": 0
   },
   {
       "name": "TIMOR-LESTE",
       "code": "tls",
       "population": 0
   },
   {
       "name": "TOGO",
       "code": "tog",
       "population": 0
   },
   {
       "name": "TONGA",
       "code": "tga",
       "population": 0
   },
   {
       "name": "TRINIDAD AND TOBAGO",
       "code": "tto",
       "population": 0
   },
   {
       "name": "TUNISIA",
       "code": "tun",
       "population": 0
   },
   {
       "name": "TURKEY",
       "code": "tur",
       "population": 0
   },
   {
       "name": "TURKMENISTAN",
       "code": "tkm",
       "population": 0
   },
   {
       "name": "TUVALU",
       "code": "tuv",
       "population": 0
   },
   {
       "name": "UGANDA",
       "code": "uga",
       "population": 0
   },
   {
       "name": "UKRAINE",
       "code": "ukr",
       "population": 0
   },
   {
       "name": "UNITED ARAB EMIRATES",
       "code": "uae",
       "population": 0
   },
   {
       "name": "UNITED REPUBLIC OF TANZANIA",
       "code": "tan",
       "population": 0
   },
   {
       "name": "UNITED STATES OF AMERICA",
       "code": "usa",
       "population": 0
   },
   {
       "name": "URUGUAY",
       "code": "uru",
       "population": 0
   },
   {
       "name": "UZBEKISTAN",
       "code": "uzb",
       "population": 0
   },
   {
       "name": "VANUATU",
       "code": "van",
       "population": 0
   },
   {
       "name": "VENEZUELA",
       "code": "ven",
       "population": 0
   },
   {
       "name": "VIETNAM",
       "code": "vie",
       "population": 0
   },
   {
       "name": "VIRGIN ISLANDS, BRITISH",
       "code": "ivb",
       "population": 0
   },
   {
       "name": "VIRGIN ISLANDS, US",
       "code": "isv",
       "population": 0
   },
   {
       "name": "YEMEN",
       "code": "yem",
       "population": 0
   },
   {
       "name": "ZAMBIA",
       "code": "zam",
       "population": 0
   },
   {
       "name": "ZIMBABWE",
       "code": "zim",
       "population": 0
   }
]
```

## As an admin, I want to be able to update a countries population, so that I can ensure the populations are accurate when new consensus data is made available.
Acceptance Criteria:
```
The endpoint should be password protected using admin and p@55w07d
Only the population should be updatable
```

Use the endpoint PATCH /countries{code}.

```bash
Set up the Authorization (Type: Basic Auth)
Username: admin
Password: p@55w07d
```

## Patch the country's population
```python
PATCH http://localhost:8080/countries/afg

#On Body: 
#Write command in JSON type:
{
"name": "AFGANISTAN",
"population": 100
}
#Then Press Send button 
#Response: 202
#Now, the population of country AFGANISTAN is updated
{
   "name": "AFGANISTAN",
   "code": "afg",
   "population": 100
}
```
![Population is updated](update_population.png)
## As an admin, I want to be able to remove a country from the list, so that I can maintain only countries that make it on to my chart.
Acceptance Criteria:

```
The endpoint should be password protected using admin and p@55w07d
Should completely remove the country from the internal list and subsequent calls to the fetch countries endpoint
```
## Delete/Remove Country from the countries list i.e. Afganistan

```bash
Set up the Authorization (Type: Basic Auth)
Username: admin
Password: p@55w07d
# endpoint delete
DELETE http://localhost:8080/countries/afg
# When Running this will get a return response error of 500 
`Unknown error whilst deleting. Cannot DELETE FROM Countrie WHERE code = '${code}'`,
  HttpStatus.INTERNAL_SERVER_ERROR,
# So, to make sure the delete/remove a country from the list success. Need to command a couple of line codes in app.controller.ts file.
```
![Command some line codes](2023-03-23_15-30-07.png)

```bash
#After editing the line codes, ensure to stop and delete the container qa-test also delete the images
#Try to run again the project directory by running the script docker-compose up
#Then run again the endpoint DELETE http://localhost:8080/countries/afg
#Response status = 204 No Content
#Check with GET http://localhost:8080/countries
#The country Afganistan is removed from the list
[
   {
       "name": "ALBANIA",
       "code": "alb",
       "population": 0
   },
   {
       "name": "ALGERIA",
       "code": "alg",
       "population": 0
   },
   {
       "name": "AMERICAN SAMOA",
       "code": "asa",
       "population": 0
   },
   {
       "name": "ANDORRA",
       "code": "and",
       "population": 0
   },
   {
       "name": "ANGOLA",
       "code": "ang",
       "population": 0
   },
   {
       "name": "ANTIGUA AND BARBUDA",
       "code": "ant",
       "population": 0
   },
   {
       "name": "ARGENTINA",
       "code": "arg",
       "population": 0
   },
   {
       "name": "ARMENIA",
       "code": "arm",
       "population": 0
   },
   {
       "name": "ARUBA",
       "code": "aru",
       "population": 0
   },
   {
       "name": "AUSTRALIA",
       "code": "aus",
       "population": 0
   },
   {
       "name": "AUSTRIA",
       "code": "aut",
       "population": 0
   },
   {
       "name": "AZERBAIJAN",
       "code": "aze",
       "population": 0
   },
   {
       "name": "BAHAMAS",
       "code": "bah",
       "population": 0
   },
   {
       "name": "BAHRAIN",
       "code": "brn",
       "population": 0
   },
   {
       "name": "BANGLADESH",
       "code": "ban",
       "population": 0
   },
   {
       "name": "BARBADOS",
       "code": "bar",
       "population": 0
   },
   {
       "name": "BELARUS",
       "code": "blr",
       "population": 0
   },
   {
       "name": "BELGIUM",
       "code": "bel",
       "population": 0
   },
   {
       "name": "BELIZE",
       "code": "biz",
       "population": 0
   },
   {
       "name": "BENIN",
       "code": "ben",
       "population": 0
   },
   {
       "name": "BERMUDA",
       "code": "ber",
       "population": 0
   },
   {
       "name": "BHUTAN",
       "code": "bhu",
       "population": 0
   },
   {
       "name": "BOLIVIA",
       "code": "bol",
       "population": 0
   },
   {
       "name": "BOSNIA AND HERZEGOVINA",
       "code": "bih",
       "population": 0
   },
   {
       "name": "BOTSWANA",
       "code": "bot",
       "population": 0
   },
   {
       "name": "BRAZIL",
       "code": "bra",
       "population": 0
   },
   {
       "name": "BRUNEI DARUSSALAM",
       "code": "bru",
       "population": 0
   },
   {
       "name": "BULGARIA",
       "code": "bul",
       "population": 0
   },
   {
       "name": "BURKINA FASO",
       "code": "bur",
       "population": 0
   },
   {
       "name": "BURUNDI",
       "code": "bdi",
       "population": 0
   },
   {
       "name": "CAMBODIA",
       "code": "cam",
       "population": 0
   },
   {
       "name": "CAMEROON",
       "code": "cmr",
       "population": 0
   },
   {
       "name": "CANADA",
       "code": "can",
       "population": 0
   },
   {
       "name": "CAPE VERDE",
       "code": "cpv",
       "population": 0
   },
   {
       "name": "CAYMAN ISLANDS",
       "code": "cay",
       "population": 0
   },
   {
       "name": "CENTRAL AFRICAN REPUBLIC",
       "code": "caf",
       "population": 0
   },
   {
       "name": "CHAD",
       "code": "cha",
       "population": 0
   },
   {
       "name": "CHILE",
       "code": "chi",
       "population": 0
   },
   {
       "name": "CHINESE TAIPEI",
       "code": "tpe",
       "population": 0
   },
   {
       "name": "COLOMBIA",
       "code": "col",
       "population": 0
   },
   {
       "name": "COMOROS",
       "code": "com",
       "population": 0
   },
   {
       "name": "CONGO",
       "code": "cgo",
       "population": 0
   },
   {
       "name": "COOK ISLANDS",
       "code": "cok",
       "population": 0
   },
   {
       "name": "COSTA RICA",
       "code": "crc",
       "population": 0
   },
   {
       "name": "CÔTE D'IVOIRE",
       "code": "civ",
       "population": 0
   },
   {
       "name": "CROATIA",
       "code": "cro",
       "population": 0
   },
   {
       "name": "CUBA",
       "code": "cub",
       "population": 0
   },
   {
       "name": "CYPRUS",
       "code": "cyp",
       "population": 0
   },
   {
       "name": "CZECH REPUBLIC",
       "code": "cze",
       "population": 0
   },
   {
       "name": "DEMOCRATIC PEOPLE'S REPUBLIC OF KOREA",
       "code": "prk",
       "population": 0
   },
   {
       "name": "DEMOCRATIC REPUBLIC OF THE CONGO",
       "code": "cod",
       "population": 0
   },
   {
       "name": "DENMARK",
       "code": "den",
       "population": 0
   },
   {
       "name": "DJIBOUTI",
       "code": "dji",
       "population": 0
   },
   {
       "name": "DOMINICAN REPUBLIC",
       "code": "dom",
       "population": 0
   },
   {
       "name": "DOMINIQUE",
       "code": "dma",
       "population": 0
   },
   {
       "name": "ECUADOR",
       "code": "ecu",
       "population": 0
   },
   {
       "name": "EGYPT",
       "code": "egy",
       "population": 0
   },
   {
       "name": "EL SALVADOR",
       "code": "esa",
       "population": 0
   },
   {
       "name": "EQUATORIAL GUINEA",
       "code": "geq",
       "population": 0
   },
   {
       "name": "ERITREA",
       "code": "eri",
       "population": 0
   },
   {
       "name": "ESTONIA",
       "code": "est",
       "population": 0
   },
   {
       "name": "ESWATINI",
       "code": "swz",
       "population": 0
   },
   {
       "name": "ETHIOPIA",
       "code": "eth",
       "population": 0
   },
   {
       "name": "FEDERATED STATES OF MICRONESIA",
       "code": "fsm",
       "population": 0
   },
   {
       "name": "FIJI",
       "code": "fij",
       "population": 0
   },
   {
       "name": "FINLAND",
       "code": "fin",
       "population": 0
   },
   {
       "name": "FRANCE",
       "code": "fra",
       "population": 0
   },
   {
       "name": "GABON",
       "code": "gab",
       "population": 0
   },
   {
       "name": "GAMBIA",
       "code": "gam",
       "population": 0
   },
   {
       "name": "GEORGIA",
       "code": "geo",
       "population": 0
   },
   {
       "name": "GERMANY",
       "code": "ger",
       "population": 0
   },
   {
       "name": "GHANA",
       "code": "gha",
       "population": 0
   },
   {
       "name": "GREAT BRITAIN",
       "code": "gbr",
       "population": 0
   },
   {
       "name": "GREECE",
       "code": "gre",
       "population": 0
   },
   {
       "name": "GRENADA",
       "code": "grn",
       "population": 0
   },
   {
       "name": "GUAM",
       "code": "gum",
       "population": 0
   },
   {
       "name": "GUATEMALA",
       "code": "gua",
       "population": 0
   },
   {
       "name": "GUINEA",
       "code": "gui",
       "population": 0
   },
   {
       "name": "GUINEA-BISSAU",
       "code": "gbs",
       "population": 0
   },
   {
       "name": "GUYANA",
       "code": "guy",
       "population": 0
   },
   {
       "name": "HAITI",
       "code": "hai",
       "population": 0
   },
   {
       "name": "HONDURAS",
       "code": "hon",
       "population": 0
   },
   {
       "name": "HONG KONG, CHINA",
       "code": "hkg",
       "population": 0
   },
   {
       "name": "HUNGARY",
       "code": "hun",
       "population": 0
   },
   {
       "name": "ICELAND",
       "code": "isl",
       "population": 0
   },
   {
       "name": "INDIA",
       "code": "ind",
       "population": 0
   },
   {
       "name": "INDONESIA",
       "code": "ina",
       "population": 0
   },
   {
       "name": "IRAQ",
       "code": "irq",
       "population": 0
   },
   {
       "name": "IRELAND",
       "code": "irl",
       "population": 0
   },
   {
       "name": "ISLAMIC REPUBLIC OF IRAN",
       "code": "iri",
       "population": 0
   },
   {
       "name": "ISRAEL",
       "code": "isr",
       "population": 0
   },
   {
       "name": "ITALY",
       "code": "ita",
       "population": 0
   },
   {
       "name": "JAMAICA",
       "code": "jam",
       "population": 0
   },
   {
       "name": "JAPAN",
       "code": "jpn",
       "population": 0
   },
   {
       "name": "JORDAN",
       "code": "jor",
       "population": 0
   },
   {
       "name": "KAZAKHSTAN",
       "code": "kaz",
       "population": 0
   },
   {
       "name": "KENYA",
       "code": "ken",
       "population": 0
   },
   {
       "name": "KIRIBATI",
       "code": "kir",
       "population": 0
   },
   {
       "name": "KOSOVO",
       "code": "kos",
       "population": 0
   },
   {
       "name": "KUWAIT",
       "code": "kuw",
       "population": 0
   },
   {
       "name": "KYRGYZSTAN",
       "code": "kgz",
       "population": 0
   },
   {
       "name": "LAO PEOPLE'S DEMOCRATIC REPUBLIC",
       "code": "lao",
       "population": 0
   },
   {
       "name": "LATVIA",
       "code": "lat",
       "population": 0
   },
   {
       "name": "LEBANON",
       "code": "lbn",
       "population": 0
   },
   {
       "name": "LESOTHO",
       "code": "les",
       "population": 0
   },
   {
       "name": "LIBERIA",
       "code": "lbr",
       "population": 0
   },
   {
       "name": "LIBYA",
       "code": "lba",
       "population": 0
   },
   {
       "name": "LIECHTENSTEIN",
       "code": "lie",
       "population": 0
   },
   {
       "name": "LITHUANIA",
       "code": "ltu",
       "population": 0
   },
   {
       "name": "LUXEMBOURG",
       "code": "lux",
       "population": 0
   },
   {
       "name": "MADAGASCAR",
       "code": "mad",
       "population": 0
   },
   {
       "name": "MALAWI",
       "code": "maw",
       "population": 0
   },
   {
       "name": "MALAYSIA",
       "code": "mas",
       "population": 0
   },
   {
       "name": "MALDIVES",
       "code": "mdv",
       "population": 0
   },
   {
       "name": "MALI",
       "code": "mli",
       "population": 0
   },
   {
       "name": "MALTA",
       "code": "mlt",
       "population": 0
   },
   {
       "name": "MARSHALL ISLANDS",
       "code": "mhl",
       "population": 0
   },
   {
       "name": "MAURITANIA",
       "code": "mtn",
       "population": 0
   },
   {
       "name": "MAURITIUS",
       "code": "mri",
       "population": 0
   },
   {
       "name": "MEXICO",
       "code": "mex",
       "population": 0
   },
   {
       "name": "MONACO",
       "code": "mon",
       "population": 0
   },
   {
       "name": "MONGOLIA",
       "code": "mgl",
       "population": 0
   },
   {
       "name": "MONTENEGRO",
       "code": "mne",
       "population": 0
   },
   {
       "name": "MOROCCO",
       "code": "mar",
       "population": 0
   },
   {
       "name": "MOZAMBIQUE",
       "code": "moz",
       "population": 0
   },
   {
       "name": "MYANMAR",
       "code": "mya",
       "population": 0
   },
   {
       "name": "NAMIBIA",
       "code": "nam",
       "population": 0
   },
   {
       "name": "NAURU",
       "code": "nru",
       "population": 0
   },
   {
       "name": "NEPAL",
       "code": "nep",
       "population": 0
   },
   {
       "name": "NETHERLANDS",
       "code": "ned",
       "population": 0
   },
   {
       "name": "NEW ZEALAND",
       "code": "nzl",
       "population": 0
   },
   {
       "name": "NICARAGUA",
       "code": "nca",
       "population": 0
   },
   {
       "name": "NIGER",
       "code": "nig",
       "population": 0
   },
   {
       "name": "NIGERIA",
       "code": "ngr",
       "population": 0
   },
   {
       "name": "NORWAY",
       "code": "nor",
       "population": 0
   },
   {
       "name": "OMAN",
       "code": "oma",
       "population": 0
   },
   {
       "name": "PAKISTAN",
       "code": "pak",
       "population": 0
   },
   {
       "name": "PALAU",
       "code": "plw",
       "population": 0
   },
   {
       "name": "PALESTINE",
       "code": "ple",
       "population": 0
   },
   {
       "name": "PANAMA",
       "code": "pan",
       "population": 0
   },
   {
       "name": "PAPUA NEW GUINEA",
       "code": "png",
       "population": 0
   },
   {
       "name": "PARAGUAY",
       "code": "par",
       "population": 0
   },
   {
       "name": "PEOPLE'S REPUBLIC OF CHINA",
       "code": "chn",
       "population": 0
   },
   {
       "name": "PERU",
       "code": "per",
       "population": 0
   },
   {
       "name": "PHILIPPINES",
       "code": "phi",
       "population": 0
   },
   {
       "name": "POLAND",
       "code": "pol",
       "population": 0
   },
   {
       "name": "PORTUGAL",
       "code": "por",
       "population": 0
   },
   {
       "name": "PUERTO RICO",
       "code": "pur",
       "population": 0
   },
   {
       "name": "QATAR",
       "code": "qat",
       "population": 0
   },
   {
       "name": "REPUBLIC OF KOREA",
       "code": "kor",
       "population": 0
   },
   {
       "name": "REPUBLIC OF MOLDOVA",
       "code": "mda",
       "population": 0
   },
   {
       "name": "ROMANIA",
       "code": "rou",
       "population": 0
   },
   {
       "name": "RUSSIAN FEDERATION",
       "code": "rus",
       "population": 0
   },
   {
       "name": "RWANDA",
       "code": "rwa",
       "population": 0
   },
   {
       "name": "SAINT KITTS AND NEVIS",
       "code": "skn",
       "population": 0
   },
   {
       "name": "SAINT LUCIA",
       "code": "lca",
       "population": 0
   },
   {
       "name": "SAMOA (UNTIL 1996 WESTERN SAMOA)",
       "code": "sam",
       "population": 0
   },
   {
       "name": "SAN MARINO",
       "code": "smr",
       "population": 0
   },
   {
       "name": "SAO TOME AND PRINCIPE",
       "code": "stp",
       "population": 0
   },
   {
       "name": "SAUDI ARABIA",
       "code": "ksa",
       "population": 0
   },
   {
       "name": "SENEGAL",
       "code": "sen",
       "population": 0
   },
   {
       "name": "SERBIA",
       "code": "srb",
       "population": 0
   },
   {
       "name": "SEYCHELLES",
       "code": "sey",
       "population": 0
   },
   {
       "name": "SIERRA LEONE",
       "code": "sle",
       "population": 0
   },
   {
       "name": "SINGAPORE",
       "code": "sgp",
       "population": 0
   },
   {
       "name": "SLOVAKIA",
       "code": "svk",
       "population": 0
   },
   {
       "name": "SLOVENIA",
       "code": "slo",
       "population": 0
   },
   {
       "name": "SOLOMON ISLANDS",
       "code": "sol",
       "population": 0
   },
   {
       "name": "SOMALIA",
       "code": "som",
       "population": 0
   },
   {
       "name": "SOUTH AFRICA",
       "code": "rsa",
       "population": 0
   },
   {
       "name": "SOUTH SUDAN",
       "code": "ssd",
       "population": 0
   },
   {
       "name": "SPAIN",
       "code": "esp",
       "population": 0
   },
   {
       "name": "SRI LANKA",
       "code": "sri",
       "population": 0
   },
   {
       "name": "ST VINCENT AND THE GRENADINES",
       "code": "vin",
       "population": 0
   },
   {
       "name": "SUDAN",
       "code": "sud",
       "population": 0
   },
   {
       "name": "SURINAME",
       "code": "sur",
       "population": 0
   },
   {
       "name": "SWEDEN",
       "code": "swe",
       "population": 0
   },
   {
       "name": "SWITZERLAND",
       "code": "sui",
       "population": 0
   },
   {
       "name": "SYRIAN ARAB REPUBLIC",
       "code": "syr",
       "population": 0
   },
   {
       "name": "TAJIKISTAN",
       "code": "tjk",
       "population": 0
   },
   {
       "name": "THAILAND",
       "code": "tha",
       "population": 0
   },
   {
       "name": "THE FORMER YUGOSLAV REPUBLIC OF MACEDONIA",
       "code": "mkd",
       "population": 0
   },
   {
       "name": "TIMOR-LESTE",
       "code": "tls",
       "population": 0
   },
   {
       "name": "TOGO",
       "code": "tog",
       "population": 0
   },
   {
       "name": "TONGA",
       "code": "tga",
       "population": 0
   },
   {
       "name": "TRINIDAD AND TOBAGO",
       "code": "tto",
       "population": 0
   },
   {
       "name": "TUNISIA",
       "code": "tun",
       "population": 0
   },
   {
       "name": "TURKEY",
       "code": "tur",
       "population": 0
   },
   {
       "name": "TURKMENISTAN",
       "code": "tkm",
       "population": 0
   },
   {
       "name": "TUVALU",
       "code": "tuv",
       "population": 0
   },
   {
       "name": "UGANDA",
       "code": "uga",
       "population": 0
   },
   {
       "name": "UKRAINE",
       "code": "ukr",
       "population": 0
   },
   {
       "name": "UNITED ARAB EMIRATES",
       "code": "uae",
       "population": 0
   },
   {
       "name": "UNITED REPUBLIC OF TANZANIA",
       "code": "tan",
       "population": 0
   },
   {
       "name": "UNITED STATES OF AMERICA",
       "code": "usa",
       "population": 0
   },
   {
       "name": "URUGUAY",
       "code": "uru",
       "population": 0
   },
   {
       "name": "UZBEKISTAN",
       "code": "uzb",
       "population": 0
   },
   {
       "name": "VANUATU",
       "code": "van",
       "population": 0
   },
   {
       "name": "VENEZUELA",
       "code": "ven",
       "population": 0
   },
   {
       "name": "VIETNAM",
       "code": "vie",
       "population": 0
   },
   {
       "name": "VIRGIN ISLANDS, BRITISH",
       "code": "ivb",
       "population": 0
   },
   {
       "name": "VIRGIN ISLANDS, US",
       "code": "isv",
       "population": 0
   },
   {
       "name": "YEMEN",
       "code": "yem",
       "population": 0
   },
   {
       "name": "ZAMBIA",
       "code": "zam",
       "population": 0
   },
   {
       "name": "ZIMBABWE",
       "code": "zim",
       "population": 0
   }
]
```

## As an admin, I want to be able to reset the database back to it's original state, so that I can quickly recover from any problems that might be introduced when editing.

Acceptance Criteria:

The endpoint should be password protected using admin and p@55w07d

## Reset Back to original state

```python
Set up the Authorization (Type: Basic Auth)
Username: admin
Password: p@55w07d
```
```python
GET http://localhost:8080/countries/reset 
# Response code = 204 No Content
GET http://localhost:8080/countries
# Now, the Afganistan country is back again on the country list
```
