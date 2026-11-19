# Kelompok 5 - Segmentasi Area Asap dan Api

## Deskripsi Proyek

Proyek ini bertujuan melakukan anotasi segmentasi area sebaran gumpalan asap dan zona api menggunakan metode Polygon.

Anotasi dilakukan menggunakan CVAT (Computer Vision Annotation Tool) dengan format keluaran COCO JSON.

## Tujuan Proyek

- Mengidentifikasi area sebaran asap.
- Mengidentifikasi zona api.
- Membuat anotasi polygon pada setiap objek.
- Menghasilkan dataset segmentasi yang terstruktur.

## Kategori Anotasi

| ID | Nama Label | Keterangan |
|---|---|---|
| 1 | smoke | Area sebaran gumpalan asap |
| 2 | Fire | Area nyala api |


## Sumber Dataset (Link Foto)

Foto yang digunakan dalam proyek ini dikumpulkan dari beberapa sumber internet sebagai bahan anotasi segmentasi asap dan api.

| No | Nama File | Jenis Objek | Sumber Foto |
|---|---|---|---|
| 1 | foto_001.jpg | Smoke dan Fire | [Link Foto 1](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 2 | foto_002.jpg | Smoke | [Link Foto 2](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 3 | foto_003.jpg | Fire | [Link Foto 3](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 4 | foto_004.jpg | Smoke dan Fire | [Link Foto 4](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 5 | foto_005.jpg | Smoke | [Link Foto 5](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 6 | foto_006.jpg | Fire | [Link Foto 6](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 7 | foto_007.jpg | Smoke dan Fire | [Link Foto 7](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 8 | foto_008.jpg | Smoke | [Link Foto 8](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 9 | foto_009.jpg | Fire | [Link Foto 9](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 10 | foto_010.jpg | Smoke dan Fire | [Link Foto 10](https://www.instagram.com/p/Df64MHdFE4m/?utm_source=ig_web_copy_link&dmpr=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 11 | foto_011.jpg | Smoke | [Link Foto 11](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 12 | foto_012.jpg | Fire | [Link Foto 12](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 13 | foto_013.jpg | Smoke dan Fire | [Link Foto 13](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 14 | foto_014.jpg | Smoke | [Link Foto 14](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 15 | foto_015.jpg | Fire | [Link Foto 15](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 16 | foto_016.jpg | Smoke dan Fire | [Link Foto 16](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 17 | foto_017.jpg | Smoke | [Link Foto 17](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 18 | foto_018.jpg | Fire | [Link Foto 18](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 19 | foto_019.jpg | Smoke dan Fire | [Link Foto 19](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 20 | foto_020.jpg | Smoke | [Link Foto 20](https://www.instagram.com/p/Df64Pp7FE0Y/?utm_source=ig_web_copy_link&jplx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 21 | foto_021.jpg | Fire | [Link Foto 21](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 22 | foto_022.jpg | Smoke dan Fire | [Link Foto 22](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 23 | foto_023.jpg | Smoke | [Link Foto 23](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 24 | foto_024.jpg | Fire | [Link Foto 24](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 25 | foto_025.jpg | Smoke dan Fire | [Link Foto 25](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 26 | foto_026.jpg | Smoke | [Link Foto 26](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 27 | foto_027.jpg | Fire | [Link Foto 27](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 28 | foto_028.jpg | Smoke dan Fire | [Link Foto 28](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 29 | foto_029.jpg | Smoke | [Link Foto 29](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 30 | foto_030.jpg | Fire | [Link Foto 30](https://www.instagram.com/p/Df64TEnFNUT/?utm_source=ig_web_copy_link&gwpx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 31 | foto_031.jpg | Smoke dan Fire | [Link Foto 31](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 32 | foto_032.jpg | Smoke | [Link Foto 32](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 33 | foto_033.jpg | Fire | [Link Foto 33](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 34 | foto_034.jpg | Smoke dan Fire | [Link Foto 34](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 35 | foto_035.jpg | Smoke | [Link Foto 35](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 36 | foto_036.jpg | Fire | [Link Foto 36](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 37 | foto_037.jpg | Smoke dan Fire | [Link Foto 37](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 38 | foto_038.jpg | Smoke | [Link Foto 38](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 39 | foto_039.jpg | Fire | [Link Foto 39](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 40 | foto_040.jpg | Smoke dan Fire | [Link Foto 40](https://www.instagram.com/p/Df64W5nlOWZ/?utm_source=ig_web_copy_link&fqnt=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 41 | foto_041.jpg | Smoke | [Link Foto 41](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 42 | foto_042.jpg | Fire | [Link Foto 42](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 43 | foto_043.jpg | Smoke dan Fire | [Link Foto 43](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 44 | foto_044.jpg | Smoke | [Link Foto 44](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 45 | foto_045.jpg | Fire | [Link Foto 45](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 46 | foto_046.jpg | Smoke dan Fire | [Link Foto 46](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 47 | foto_047.jpg | Smoke | [Link Foto 47](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 48 | foto_048.jpg | Fire | [Link Foto 48](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 49 | foto_049.jpg | Smoke dan Fire | [Link Foto 49](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 50 | foto_050.jpg | Smoke | [Link Foto 50](https://www.instagram.com/p/Df64aHSFGTp/?utm_source=ig_web_copy_link&lqvp=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 51 | foto_051.jpg | Fire | [Link Foto 51](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 52 | foto_052.jpg | Smoke dan Fire | [Link Foto 52](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 53 | foto_053.jpg | Smoke | [Link Foto 53](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 54 | foto_054.jpg | Fire | [Link Foto 54](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 55 | foto_055.jpg | Smoke dan Fire | [Link Foto 55](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 56 | foto_056.jpg | Smoke | [Link Foto 56](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 57 | foto_057.jpg | Fire | [Link Foto 57](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 58 | foto_058.jpg | Smoke dan Fire | [Link Foto 58](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 59 | foto_059.jpg | Smoke | [Link Foto 59](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 60 | foto_060.jpg | Fire | [Link Foto 60](https://www.instagram.com/p/Df64d7nlMvx/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 61 | foto_061.jpg | Smoke dan Fire | [Link Foto 61](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 62 | foto_062.jpg | Smoke | [Link Foto 62](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 63 | foto_063.jpg | Fire | [Link Foto 63](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 64 | foto_064.jpg | Smoke dan Fire | [Link Foto 64](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 65 | foto_065.jpg | Smoke | [Link Foto 65](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 66 | foto_066.jpg | Fire | [Link Foto 66](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 67 | foto_067.jpg | Smoke dan Fire | [Link Foto 67](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 68 | foto_068.jpg | Smoke | [Link Foto 68](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 69 | foto_069.jpg | Fire | [Link Foto 69](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 70 | foto_070.jpg | Smoke dan Fire | [Link Foto 70](https://www.instagram.com/p/Df64zLPlM9V/?utm_source=ig_web_copy_link&cnvx=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 71 | foto_071.jpg | Smoke | [Link Foto 71](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 72 | foto_072.jpg | Fire | [Link Foto 72](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 73 | foto_073.jpg | Smoke dan Fire | [Link Foto 73](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 74 | foto_074.jpg | Smoke | [Link Foto 74](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 75 | foto_075.jpg | Fire | [Link Foto 75](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 76 | foto_076.jpg | Smoke dan Fire | [Link Foto 76](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 77 | foto_077.jpg | Smoke | [Link Foto 77](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 78 | foto_078.jpg | Fire | [Link Foto 78](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 79 | foto_079.jpg | Smoke dan Fire | [Link Foto 79](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |
| 80 | foto_080.jpg | Fire | [Link Foto 80](https://www.instagram.com/p/Df643ZPFO3b/?utm_source=ig_web_copy_link&hvrq=MzRlODBiNWFlZA==&avpt=MzRlODBiNWFlZA==) |

**Catatan:** Link sumber diisi menggunakan URL halaman tempat foto diperoleh. Pastikan sumber dan ketentuan penggunaan setiap foto dicatat dengan benar.

## Target Dataset

| Keterangan | Jumlah |
|---|---:|
| Target minimal foto | 80 gambar |
| Kategori anotasi | 2 kelas |
| Metode anotasi | Polygon |
| Format keluaran | COCO JSON |

## Tools yang Digunakan

| Tools | Kegunaan |
|---|---|
| CVAT | Melakukan anotasi polygon |
| Visual Studio Code | Mengelola proyek dan file |
| Git | Mengelola versi proyek |
| GitHub | Menyimpan dan membagikan proyek |

## Format Output

Format hasil anotasi yang digunakan adalah COCO JSON.

File anotasi disimpan pada:

`dataset/annotations/instances_default.json`

File tersebut berisi informasi gambar, kategori objek, serta koordinat polygon hasil anotasi.

## Anggota Kelompok

| No | Nama Anggota |
|---|---|
| 1 | Aditya Hendy Novian |
| 2 | Dede Ridho |
| 3 | Muhammad Nor Azkia Rabbani |
| 4 | Muhammad Syahrul Mukmin |

---

**Kelompok 5 - Segmentasi Area Asap dan Api**  
Proyek anotasi segmentasi citra menggunakan CVAT dan format COCO JSON.