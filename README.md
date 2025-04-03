# GTA: San Andreas - Default Vehicle Statistics Reference

[![GTA:SA](https://img.shields.io/badge/Game-GTA%3A%20San%20Andreas-orange.svg)](https://www.rockstargames.com/sanandreas)
[![DataSource](https://img.shields.io/badge/Data%20Source-handling.cfg-blue.svg)](#)
[![Community](https://img.shields.io/badge/For-Teyra%20Roleplay%20(Baseline)-brightgreen.svg)](#penting-untuk-server-teyra-roleplay)

Repositori ini menyediakan referensi komprehensif untuk statistik kendaraan *default* dalam Grand Theft Auto: San Andreas. Data ini bersumber dari file konfigurasi inti game (`handling.cfg`) dan mencakup ID Model internal, nama kendaraan, kecepatan maksimum teoretis, serta visual kendaraan.

## Pendahuluan

Informasi yang disajikan di sini adalah nilai-nilai dasar (vanilla) dari GTA: San Andreas. Ini dapat sangat berguna sebagai titik awal atau perbandingan, terutama bagi pemain atau pengembang yang bekerja dengan platform modding seperti SA-MP atau open.mp.

### Penting untuk Server Teyra Roleplay

Statistik yang tercantum di bawah ini adalah **nilai dasar game**. Server **Teyra Roleplay** (atau server roleplay lainnya) **sangat mungkin** memiliki penyesuaian, modifikasi, atau *balancing* tersendiri yang dapat **mengubah** performa aktual kendaraan di dalam game secara signifikan.

**Selalu rujuk pada informasi resmi, dokumentasi, atau staf Teyra Roleplay untuk data spesifik yang berlaku di server tersebut.** Gunakan data di sini hanya sebagai referensi *baseline* atau perbandingan dengan nilai *default* game.

### Tentang Kecepatan Maksimal

Nilai "Kecepatan Maks (km/h)" berasal dari parameter `fMaxVelocity` dalam `handling.cfg`. Ini merepresentasikan kecepatan teoretis puncak dalam satuan internal game, yang umumnya diinterpretasikan sebagai km/h. Kecepatan aktual yang dapat dicapai di dalam game akan dipengaruhi oleh banyak faktor lain, termasuk:
* Fisika game
* Medan (jalan rata, off-road, tanjakan)
* Kondisi kendaraan (kerusakan)
* Skill mengemudi pemain
* Potensi modifikasi atau *scripting* di sisi server (seperti pada Teyra Roleplay)

### Sumber Gambar

Tautan gambar disediakan dari [assets.open.mp](https://open.mp/docs/scripting/resources/vehicleid) untuk referensi visual cepat.

---

## 🚗 Cars

### Civilian & General Cars (Sedans, Hatchbacks, SUVs, Station Wagons, etc.)

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `400`           | Landstalker    | 160                   | TransFender   | [`Vehicle_400.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_400.jpg) | - |
| `401`           | Bravura        | 165                   | TransFender   | [`Vehicle_401.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_401.jpg) | - |
| `402`           | Buffalo        | 200                   | TransFender   | [`Vehicle_402.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_402.jpg) | - |
| `404`           | Perennial      | 145                   | TransFender   | [`Vehicle_404.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_404.jpg) | - |
| `405`           | Sentinel       | 185                   | TransFender   | [`Vehicle_405.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_405.jpg) | - |
| `409`           | Stretch        | 160                   | TransFender   | [`Vehicle_409.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_409.jpg) | - |
| `410`           | Manana         | 140                   | TransFender   | [`Vehicle_410.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_410.jpg) | - |
| `412`           | Virgo          | 160                   | Loco Low Co.  | [`Vehicle_412.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_412.jpg) | *Juga Lowrider* |
| `418`           | Esperanto      | 150                   | TransFender   | [`Vehicle_418.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_418.jpg) | - |
| `419`           | Taxi           | 165                   | None          | [`Vehicle_419.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_419.jpg) | *Voodoo base* |
| `420`           | Washington     | 175                   | TransFender   | [`Vehicle_420.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_420.jpg) | - |
| `421`           | Bobcat         | 160                   | TransFender   | [`Vehicle_421.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_421.jpg) | - |
| `426`           | Premier        | 175                   | TransFender   | [`Vehicle_426.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_426.jpg) | - |
| `436`           | Nebula         | 165                   | TransFender   | [`Vehicle_436.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_436.jpg) | - |
| `438`           | Romero         | 155                   | None          | [`Vehicle_438.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_438.jpg) | *Hearse* |
| `439`           | Primo          | 165                   | TransFender   | [`Vehicle_439.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_439.jpg) | - |
| `445`           | Admiral        | 165                   | TransFender   | [`Vehicle_445.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_445.jpg) | - |
| `451`           | Solair         | 160                   | TransFender   | [`Vehicle_451.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_451.jpg) | - |
| `466`           | Glendale       | 150                   | TransFender   | [`Vehicle_466.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_466.jpg) | - |
| `467`           | Oceanic        | 150                   | TransFender   | [`Vehicle_467.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_467.jpg) | - |
| `474`           | Intruder       | 170                   | TransFender   | [`Vehicle_474.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_474.jpg) | - |
| `475`           | Vincent        | 170                   | TransFender   | [`Vehicle_475.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_475.jpg) | - |
| `478`           | Majestic       | 160                   | TransFender   | [`Vehicle_478.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_478.jpg) | - |
| `479`           | Willard        | 160                   | TransFender   | [`Vehicle_479.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_479.jpg) | - |
| `489`           | Regina         | 145                   | TransFender   | [`Vehicle_489.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_489.jpg) | - |
| `491`           | Greenwood      | 165                   | TransFender   | [`Vehicle_491.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_491.jpg) | - |
| `492`           | Tahoma         | 160                   | Loco Low Co.  | [`Vehicle_492.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_492.jpg) | *Juga Lowrider* |
| `496`           | Cadrona        | 170                   | TransFender   | [`Vehicle_496.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_496.jpg) | - |
| `516`           | Elegant        | 175                   | TransFender   | [`Vehicle_516.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_516.jpg) | - |
| `517`           | Journey        | 130                   | None          | [`Vehicle_517.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_517.jpg) | *RV* |
| `518`           | Stafford       | 175                   | TransFender   | [`Vehicle_518.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_518.jpg) | - |
| `526`           | Fortune        | 165                   | TransFender   | [`Vehicle_526.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_526.jpg) | - |
| `527`           | Cadrona (?)    | 165                   | TransFender   | [`Vehicle_496.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_496.jpg) | *ID 527 shares ID 496 model; Unused?* |
| `529`           | Clover         | 170                   | TransFender   | [`Vehicle_529.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_529.jpg) | - |
| `533`           | Sadler         | 150                   | TransFender   | [`Vehicle_533.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_533.jpg) | - |
| `540`           | Previon        | 175                   | TransFender   | [`Vehicle_540.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_540.jpg) | - |
| `542`           | Emperor        | 165                   | TransFender   | [`Vehicle_542.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_542.jpg) | - |
| `545`           | Merit          | 180                   | TransFender   | [`Vehicle_545.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_545.jpg) | - |
| `546`           | Uranus         | 190                   | Wheel Arch Angels | [`Vehicle_546.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_546.jpg) | *Tuner Base* |
| `547`           | Jester         | 200                   | Wheel Arch Angels | [`Vehicle_547.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_547.jpg) | *Tuner Base* |
| `549`           | Stratum        | 180                   | Wheel Arch Angels | [`Vehicle_549.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_549.jpg) | *Tuner Base* |
| `550`           | Elegy          | 200                   | Wheel Arch Angels | [`Vehicle_550.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_550.jpg) | *Tuner Base* |
| `551`           | Sultan         | 200                   | Wheel Arch Angels | [`Vehicle_551.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_551.jpg) | *Tuner Base* |
| `555`           | Windsor        | 180                   | TransFender   | [`Vehicle_555.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_555.jpg) | - |
| `566`           | Feltzer        | 190                   | TransFender   | [`Vehicle_566.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_566.jpg) | - |
| `567`           | Remington      | 160                   | Loco Low Co.  | [`Vehicle_567.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_567.jpg) | *Juga Lowrider* |
| `571`           | Glendale (Dmg) | 150                   | None          | [`Vehicle_571.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_571.jpg) | *Damaged Variant* |
| `572`           | Oceanic (Dmg)  | 150                   | None          | [`Vehicle_572.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_572.jpg) | *Damaged Variant* |
| `575`           | Broadway       | 150                   | Loco Low Co.  | [`Vehicle_575.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_575.jpg) | *Juga Lowrider* |
| `576`           | Tornado        | 150                   | Loco Low Co.  | [`Vehicle_576.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_576.jpg) | *Juga Lowrider* |
| `579`           | Huntley        | 180                   | TransFender   | [`Vehicle_579.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_579.jpg) | - |
| `580`           | Fortune (Tuner)| 185                   | Wheel Arch Angels | [`Vehicle_526.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_526.jpg) | *Tuner Variant, Base 526* |
| `585`           | Euros          | 210                   | TransFender   | [`Vehicle_585.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_585.jpg) | - |
| `589`           | Club           | 170                   | TransFender   | [`Vehicle_589.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_589.jpg) | - |
| `600`           | Rancher        | 160                   | TransFender   | [`Vehicle_490.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_490.jpg) | *Shares model ID 490* |
| `602`           | Alpha          | 200                   | TransFender   | [`Vehicle_602.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_602.jpg) | - |
| `603`           | Phoenix        | 200                   | TransFender   | [`Vehicle_603.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_603.jpg) | - |
| `604`           | Stallion (Dmg) | 180                   | None          | [`Vehicle_439.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_439.jpg) | *Damaged variant of Stallion* |

### Sports & Exotic Cars

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `411`           | Infernus       | 240                   | TransFender   | [`Vehicle_411.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_411.jpg) | - |
| `415`           | Cheetah        | 230                   | TransFender   | [`Vehicle_415.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_415.jpg) | - |
| `429`           | Banshee        | 200                   | TransFender   | [`Vehicle_429.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_429.jpg) | - |
| `434`           | Hotknife       | 180                   | None          | [`Vehicle_434.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_434.jpg) | *Requires Driving School Gold* |
| `451`           | Solair         | 160                   | TransFender   | [`Vehicle_451.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_451.jpg) | *(Listed also in Civilian)* |
| `477`           | Turismo        | 240                   | TransFender   | [`Vehicle_477.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_477.jpg) | - |
| `480`           | Comet          | 200                   | TransFender   | [`Vehicle_480.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_480.jpg) | - |
| `494`           | Hotring Racer  | 220                   | None          | [`Vehicle_494.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_494.jpg) | *Race Variant A* |
| `502`           | Hotring Racer A| 220                   | None          | [`Vehicle_502.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_502.jpg) | *Race Variant B* |
| `503`           | Hotring Racer B| 220                   | None          | [`Vehicle_503.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_503.jpg) | *Race Variant C* |
| `506`           | Super GT       | 230                   | TransFender   | [`Vehicle_506.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_506.jpg) | - |
| `541`           | Bullet         | 230                   | TransFender   | [`Vehicle_541.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_541.jpg) | - |
| `558`           | URanus (Tuner) | 190                   | Wheel Arch Angels | [`Vehicle_546.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_546.jpg) | *Tuner Variant, Base 546* |
| `559`           | Jester (Tuner) | 200                   | Wheel Arch Angels | [`Vehicle_547.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_547.jpg) | *Tuner Variant, Base 547* |
| `560`           | Sultan (Tuner) | 200                   | Wheel Arch Angels | [`Vehicle_551.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_551.jpg) | *Tuner Variant, Base 551* |
| `561`           | Stratum (Tuner)| 180                   | Wheel Arch Angels | [`Vehicle_549.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_549.jpg) | *Tuner Variant, Base 549* |
| `562`           | Elegy (Tuner)  | 200                   | Wheel Arch Angels | [`Vehicle_550.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_550.jpg) | *Tuner Variant, Base 550* |
| `565`           | Flash          | 200                   | Wheel Arch Angels | [`Vehicle_565.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_565.jpg) | *Tuner Base* |

### Lowriders

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `412`           | Virgo          | 160                   | Loco Low Co.  | [`Vehicle_412.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_412.jpg) | - |
| `419`           | Voodoo         | 150                   | Loco Low Co.  | [`Vehicle_419.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_419.jpg) | - |
| `534`           | Blade          | 160                   | Loco Low Co.  | [`Vehicle_534.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_534.jpg) | - |
| `535`           | Remington      | 160                   | Loco Low Co.  | [`Vehicle_567.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_567.jpg) | *Shares model ID 567* |
| `536`           | Slamvan        | 160                   | Loco Low Co.  | [`Vehicle_536.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_536.jpg) | - |
| `567`           | Remington      | 160                   | Loco Low Co.  | [`Vehicle_567.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_567.jpg) | - |
| `575`           | Broadway       | 150                   | Loco Low Co.  | [`Vehicle_575.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_575.jpg) | - |
| `576`           | Tornado        | 150                   | Loco Low Co.  | [`Vehicle_576.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_576.jpg) | - |
| `492`           | Tahoma         | 160                   | Loco Low Co.  | [`Vehicle_492.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_492.jpg) | *(Listed also in Civilian)* |

### Emergency Vehicles

| ID (`Model ID`) | Nama Kendaraan  | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :-------------- | :-------------------- | :------------ | :----- | :---- |
| `407`           | Police (LV)     | 200                   | None          | [`Vehicle_407.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_407.jpg) | - |
| `416`           | Ambulance       | 150                   | None          | [`Vehicle_416.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_416.jpg) | - |
| `423`           | Police Ranger   | 160                   | None          | [`Vehicle_423.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_423.jpg) | - |
| `427`           | Enforcer        | 140                   | None          | [`Vehicle_427.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_427.jpg) | - |
| `432`           | Fire Truck      | 130                   | None          | [`Vehicle_432.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_432.jpg) | - |
| `490`           | FBI Rancher     | 180                   | None          | [`Vehicle_490.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_490.jpg) | - |
| `523`           | HPV-1000 (Motor)| 200                   | None          | [`Vehicle_523.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_523.jpg) | *Police Bike* |
| `528`           | S.W.A.T.        | 140                   | None          | [`Vehicle_528.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_528.jpg) | *SWAT Van* |
| `596`           | Police (LS)     | 200                   | None          | [`Vehicle_596.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_596.jpg) | - |
| `597`           | Police (SF)     | 200                   | None          | [`Vehicle_597.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_597.jpg) | - |
| `598`           | Police Ranger (Alt)| 160                | None          | [`Vehicle_423.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_423.jpg) | *Variant of ID 423* |
| `599`           | Picador (Police)| 160                   | None          | [`Vehicle_600.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_600.jpg) | *Police variant of Picador* |
| `601`           | Rhino (Tank)    | 75                    | None          | [`Vehicle_601.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_601.jpg) | - |

### Commercial & Industrial Vehicles

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `403`           | Linerunner     | 130                   | None          | [`Vehicle_403.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_403.jpg) | *Semi Truck* |
| `406`           | Dumper         | 100                   | None          | [`Vehicle_406.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_406.jpg) | *Dump Truck* |
| `408`           | Trashmaster    | 100                   | None          | [`Vehicle_408.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_408.jpg) | *Garbage Truck* |
| `413`           | Walton         | 140                   | TransFender   | [`Vehicle_413.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_413.jpg) | - |
| `414`           | Benson         | 125                   | None          | [`Vehicle_414.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_414.jpg) | *Box Truck* |
| `422`           | Pony           | 130                   | TransFender   | [`Vehicle_422.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_422.jpg) | *Van* |
| `424`           | Mule           | 120                   | None          | [`Vehicle_424.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_424.jpg) | *Box Truck* |
| `428`           | Securicar      | 140                   | None          | [`Vehicle_428.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_428.jpg) | *Armored Van* |
| `433`           | Packer         | 130                   | None          | [`Vehicle_433.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_433.jpg) | *Car Carrier* |
| `437`           | Moonbeam       | 130                   | TransFender   | [`Vehicle_437.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_437.jpg) | *Van* |
| `440`           | DFT-30         | 120                   | None          | [`Vehicle_440.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_440.jpg) | *Flatbed Truck* |
| `442`           | Burrito        | 150                   | TransFender   | [`Vehicle_442.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_442.jpg) | *Van* |
| `443`           | Tanker         | 130                   | None          | [`Vehicle_443.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_443.jpg) | *Semi Truck* |
| `455`           | Flatbed        | 110                   | None          | [`Vehicle_455.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_455.jpg) | *Truck* |
| `456`           | Yankee         | 110                   | None          | [`Vehicle_456.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_456.jpg) | *Truck* |
| `457`           | Caddy          | 100                   | None          | [`Vehicle_457.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_457.jpg) | *Golf Cart* |
| `470`           | Patriot        | 160                   | TransFender   | [`Vehicle_470.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_470.jpg) | - |
| `482`           | Rumpo          | 130                   | TransFender   | [`Vehicle_482.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_482.jpg) | *Van* |
| `483`           | RC Bandit (?)  | 80                    | None          | [`Vehicle_431.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_431.jpg) | *Shares model ID 431* |
| `498`           | Boxville       | 110                   | None          | [`Vehicle_498.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_498.jpg) | *Box Truck* |
| `499`           | Benson (Var)   | 125                   | None          | [`Vehicle_414.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_414.jpg) | *Variant of ID 414* |
| `500`           | Mesa           | 160                   | TransFender   | [`Vehicle_500.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_500.jpg) | - |
| `504`           | Bloodring Banger| 180                  | None          | [`Vehicle_504.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_504.jpg) | *Demolition Derby Car* |
| `514`           | Barracks       | 120                   | None          | [`Vehicle_514.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_514.jpg) | *Military Truck* |
| `515`           | Hotdog         | 130                   | None          | [`Vehicle_515.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_515.jpg) | *Hotdog Van* |
| `524`           | Cement Truck   | 100                   | None          | [`Vehicle_524.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_524.jpg) | - |
| `525`           | Towtruck       | 140                   | None          | [`Vehicle_525.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_525.jpg) | - |
| `530`           | Sadler (Dmg)   | 150                   | None          | [`Vehicle_533.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_533.jpg) | *Damaged variant of ID 533* |
| `531`           | Boxville (Black)| 110                  | None          | [`Vehicle_498.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_498.jpg) | *Black variant of ID 498* |
| `532`           | Utility Van    | 130                   | None          | [`Vehicle_532.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_532.jpg) | - |
| `543`           | Roadtrain      | 130                   | None          | [`Vehicle_543.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_543.jpg) | *Semi Truck* |
| `544`           | Sweeper        | 90                    | None          | [`Vehicle_544.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_544.jpg) | *Street Sweeper* |
| `552`           | Newsvan        | 140                   | TransFender   | [`Vehicle_552.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_552.jpg) | *Van* |
| `554`           | Tug            | 80                    | None          | [`Vehicle_554.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_554.jpg) | *Airport Tug* |
| `569`           | Sadler (Var)   | 150                   | TransFender   | [`Vehicle_533.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_533.jpg) | *Variant of ID 533* |
| `573`           | Camper         | 130                   | TransFender   | [`Vehicle_573.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_573.jpg) | *VW Bus style* |
| `574`           | Combine Harvester| 80                  | None          | [`Vehicle_574.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_574.jpg) | - |
| `578`           | Yosemite       | 160                   | TransFender   | [`Vehicle_578.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_578.jpg) | *Pickup Truck* |
| `582`           | Dozer          | 70                    | None          | [`Vehicle_582.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_582.jpg) | *Bulldozer* |
| `583`           | Blista Compact | 180                   | TransFender   | [`Vehicle_497.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_497.jpg) | *Shares model ID 497* |
| `588`           | Forklift       | 50                    | None          | [`Vehicle_588.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_588.jpg) | - |
| `591`           | Dune (?)       | 130                   | None          | [`Vehicle_570.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_570.jpg) | *Shares model ID 570* |

---

## 🏍️ Motorcycles

*(Motorcycles cannot be modified at standard tuning shops in vanilla GTA:SA)*

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `448`           | BF-400         | 190                   | None          | [`Vehicle_448.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_448.jpg) | - |
| `461`           | PCJ-600        | 200                   | None          | [`Vehicle_461.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_461.jpg) | - |
| `462`           | Faggio         | 100                   | None          | [`Vehicle_462.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_462.jpg) | *Scooter* |
| `463`           | Freeway        | 180                   | None          | [`Vehicle_463.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_463.jpg) | *Chopper* |
| `468`           | Sanchez        | 160                   | None          | [`Vehicle_468.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_468.jpg) | *Dirtbike* |
| `471`           | Wayfarer       | 160                   | None          | [`Vehicle_471.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_471.jpg) | *Touring Bike* |
| `521`           | FCR-900        | 200                   | None          | [`Vehicle_521.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_521.jpg) | - |
| `522`           | NRG-500        | 220                   | None          | [`Vehicle_522.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_522.jpg) | *Racing Bike* |
| `523`           | HPV-1000       | 200                   | None          | [`Vehicle_523.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_523.jpg) | *Police Bike* |
| `581`           | Pizzaboy       | 100                   | None          | [`Vehicle_449.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_449.jpg) | *Based on Faggio* |
| `586`           | Sanchez (Dirt) | 160                   | None          | [`Vehicle_468.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_468.jpg) | *Variant of ID 468* |

---

## 🚲 Bicycles

*(Bicycles cannot be modified)*
*Catatan: Kecepatan sangat bergantung pada kayuhan pemain (`fMaxVelocity` tidak sepenuhnya relevan).*

| ID (`Model ID`) | Nama Kendaraan  | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :-------------- | :-------------------- | :------------ | :----- | :---- |
| `481`           | BMX             | 45\* | None          | [`Vehicle_481.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_481.jpg) | - |
| `509`           | Bike            | 40\* | None          | [`Vehicle_509.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_509.jpg) | *Cruiser* |
| `510`           | Mountain Bike   | 50\* | None          | [`Vehicle_510.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_510.jpg) | - |

---

## ✈️ Aircraft (Planes & Helicopters)

*(Aircraft cannot be modified at standard tuning shops)*

| ID (`Model ID`) | Nama Kendaraan   | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :--------------- | :-------------------- | :------------ | :----- | :---- |
| `417`           | Maverick         | 200                   | None          | [`Vehicle_417.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_417.jpg) | *Civilian Heli* |
| `425`           | Skimmer          | 170                   | None          | [`Vehicle_425.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_425.jpg) | *Seaplane* |
| `447`           | Sparrow          | 180                   | None          | [`Vehicle_447.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_447.jpg) | *Small Heli* |
| `460`           | Rustler          | 250                   | None          | [`Vehicle_460.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_460.jpg) | *Fighter Plane* |
| `464`           | RC Baron         | 100                   | None          | [`Vehicle_464.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_464.jpg) | *RC Plane* |
| `465`           | RC Raider        | 100                   | None          | [`Vehicle_465.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_465.jpg) | *RC Heli* |
| `469`           | Sea Sparrow      | 180                   | None          | [`Vehicle_469.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_469.jpg) | *Amphibious Heli* |
| `476`           | AT-400           | 200                   | None          | [`Vehicle_476.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_476.jpg) | *Jumbo Jet* |
| `487`           | Police Maverick  | 200                   | None          | [`Vehicle_487.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_487.jpg) | *Police Heli* |
| `488`           | News Chopper     | 200                   | None          | [`Vehicle_488.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_488.jpg) | *News Heli* |
| `497`           | Cargobob (?)     | 180                   | None          | [`Vehicle_548.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_548.jpg) | *Shares model ID 548* |
| `501`           | Beagle           | 200                   | None          | [`Vehicle_501.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_501.jpg) | *Twin Prop Plane* |
| `511`           | Cropduster       | 160                   | None          | [`Vehicle_511.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_511.jpg) | *Biplane* |
| `512`           | Stuntplane       | 220                   | None          | [`Vehicle_512.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_512.jpg) | *Biplane* |
| `513`           | Shamal           | 250                   | None          | [`Vehicle_513.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_513.jpg) | *Private Jet* |
| `519`           | Andromada        | 200                   | None          | [`Vehicle_519.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_519.jpg) | *Cargo Plane* |
| `520`           | Dodo             | 180                   | None          | [`Vehicle_520.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_520.jpg) | *Seaplane* |
| `548`           | Cargobob         | 180                   | None          | [`Vehicle_548.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_548.jpg) | *Transport Heli* |
| `553`           | Nevada           | 250                   | None          | [`Vehicle_553.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_553.jpg) | *Prop Plane* |
| `563`           | Raindance        | 200                   | None          | [`Vehicle_563.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_563.jpg) | *Large Heli* |
| `577`           | Hunter           | 220                   | None          | [`Vehicle_577.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_577.jpg) | *Attack Heli* |
| `592`           | Hydra            | 320+* (Jet Mode)      | None          | [`Vehicle_592.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_592.jpg) | *VTOL Jet* |
| `593`           | Rustler (Var)    | 250                   | None          | [`Vehicle_460.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_460.jpg) | *Variant of ID 460* |

---

## ⚓ Boats

*(Boats cannot be modified at standard tuning shops)*

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `430`           | Predator       | 140                   | None          | [`Vehicle_430.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_430.jpg) | *Police Boat* |
| `446`           | Squalo         | 150                   | None          | [`Vehicle_446.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_446.jpg) | *Speedboat* |
| `452`           | Speeder        | 150                   | None          | [`Vehicle_452.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_452.jpg) | *Speedboat* |
| `453`           | Reefer         | 120                   | None          | [`Vehicle_453.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_453.jpg) | *Fishing Boat* |
| `454`           | Tropic         | 140                   | None          | [`Vehicle_454.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_454.jpg) | *Sailboat* |
| `472`           | Coastguard     | 140                   | None          | [`Vehicle_472.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_472.jpg) | - |
| `473`           | Dinghy         | 130                   | None          | [`Vehicle_473.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_473.jpg) | *Inflatable Boat* |
| `484`           | Marquis        | 130                   | None          | [`Vehicle_484.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_484.jpg) | *Sailboat* |
| `493`           | Jetmax         | 160                   | None          | [`Vehicle_493.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_493.jpg) | *Speedboat* |
| `595`           | Launch         | 140                   | None          | [`Vehicle_595.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_595.jpg) | *Tugboat style* |
| `605`           | Vortex         | 140                   | None          | [`Vehicle_605.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_605.jpg) | *Hovercraft* |

---

## ⚙️ Other & RC Vehicles

*(Generally not modifiable at standard shops)*

| ID (`Model ID`) | Nama Kendaraan | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :------------- | :-------------------- | :------------ | :----- | :---- |
| `431`           | RC Bandit      | 80                    | None          | [`Vehicle_431.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_431.jpg) | *RC Car* |
| `441`           | RC Tiger       | 50                    | None          | [`Vehicle_441.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_441.jpg) | *RC Tank* |
| `444`           | Monster        | 160                   | None          | [`Vehicle_444.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_444.jpg) | *Monster Truck A* |
| `458`           | Kart           | 100                   | None          | [`Vehicle_458.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_458.jpg) | *Go-Kart* |
| `459`           | Mower          | 60                    | None          | [`Vehicle_459.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_459.jpg) | *Lawn Mower* |
| `505`           | RC Goblin      | 100                   | None          | [`Vehicle_505.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_505.jpg) | *RC Heli* |
| `507`           | Bloodring (Alt)| 180                   | None          | [`Vehicle_504.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_504.jpg) | *Variant of ID 504* |
| `508`           | Rancher (Alt)  | 160                   | TransFender   | [`Vehicle_490.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_490.jpg) | *Variant of ID 490* |
| `537`           | Monster A      | 160                   | None          | [`Vehicle_537.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_537.jpg) | *Monster Truck B* |
| `538`           | Monster B      | 160                   | None          | [`Vehicle_538.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_538.jpg) | *Monster Truck C* |
| `556`           | Monster (Tuner)| 160                   | None          | [`Vehicle_444.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_444.jpg) | *Modified Monster?* |
| `557`           | Monster (Tuner)| 160                   | None          | [`Vehicle_444.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_444.jpg) | *Modified Monster?* |
| `564`           | Bandito (?)    | 150                   | None          | [`Vehicle_568.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_568.jpg) | *Shares model ID 568* |
| `568`           | Bandito        | 150                   | None          | [`Vehicle_568.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_568.jpg) | *Dune Buggy* |
| `570`           | Dune           | 130                   | None          | [`Vehicle_570.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_570.jpg) | *Rally Truck* |
| `584`           | Baggage Handler| 80                    | None          | [`Vehicle_584.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_584.jpg) | *Airport Baggage Cart* |
| `587`           | Tractor        | 70                    | None          | [`Vehicle_587.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_587.jpg) | - |
| `590`           | Kart (Variant) | 100                   | None          | [`Vehicle_458.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_458.jpg) | *Variant of ID 458* |
| `594`           | RC Cam         | 30                    | None          | [`Vehicle_594.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_594.jpg) | *Camera Drone* |

---

## 🚛 Trailers

*(Trailers cannot be driven independently or modified)*
*Catatan: Trailer tidak memiliki mesin atau kecepatan maksimum independen (`fMaxVelocity` tidak berlaku).*

| ID (`Model ID`) | Nama Kendaraan        | Kecepatan Maks (km/h) | Modifiable At | Gambar | Notes |
| :-------------- | :-------------------- | :-------------------- | :------------ | :----- | :---- |
| `435`           | Trailer (Articulated) | N/A                   | None          | [`Vehicle_435.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_435.jpg) | *Artic Trailer 1* |
| `450`           | Trailer (Petrol)      | N/A                   | None          | [`Vehicle_450.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_450.jpg) | *Tanker Trailer* |
| `584`           | Baggage Trailer       | N/A                   | None          | [`Vehicle_584.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_584.jpg) | *(Shares model with Baggage Handler)* |
| `591`           | Farm Trailer          | N/A                   | None          | [`Vehicle_591.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_591.jpg) | - |
| `606`           | Trailer (Utility)     | N/A                   | None          | [`Vehicle_606.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_606.jpg) | *Artic Trailer 2* |
| `607`           | Trailer (Stairs)      | N/A                   | None          | [`Vehicle_607.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_607.jpg) | *Airport Stairs* |
| `608`           | Trailer (Box)         | N/A                   | None          | [`Vehicle_608.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_608.jpg) | *Artic Trailer 3* |
| `609`           | Trailer (Farm Plow)   | N/A                   | None          | [`Vehicle_609.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_609.jpg) | - |
| `610`           | Trailer (Log)         | N/A                   | None          | [`Vehicle_610.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_610.jpg) | *Log Trailer* |
| `611`           | Trailer (Car Carrier) | N/A                   | None          | [`Vehicle_611.jpg`](https://assets.open.mp/assets/images/vehiclePictures/Vehicle_611.jpg) | *Empty Car Carrier* |

---

## Lisensi & Kontribusi

Data ini dikompilasi sebagai referensi komunitas. Jika Anda menemukan kesalahan atau memiliki informasi tambahan (terutama mengenai nilai `handling.cfg` yang diverifikasi), jangan ragu untuk membuka *issue* atau *pull request*.

Gambar kendaraan bersumber dari [open.mp](https://open.mp/docs/scripting/resources/vehicleid).

---