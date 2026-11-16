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
| 1 | foto_001.jpg | Smoke dan Fire | [Link Foto 1](MASUKKAN_LINK) |
| 2 | foto_002.jpg | Smoke | [Link Foto 2](MASUKKAN_LINK) |
| 3 | foto_003.jpg | Fire | [Link Foto 3](MASUKKAN_LINK) |
| 4 | foto_004.jpg | Smoke dan Fire | [Link Foto 4](MASUKKAN_LINK) |
| 5 | foto_005.jpg | Smoke | [Link Foto 5](MASUKKAN_LINK) |
| ... | ... | ... | ... |
| 80 | foto_080.jpg | Fire | [Link Foto 80](MASUKKAN_LINK) |

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