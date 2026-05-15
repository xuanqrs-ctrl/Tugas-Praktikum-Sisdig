# Tugas Praktikum Sistem Digital - Implementasi 3 IC Gerbang Logika

## Deskripsi
Repositori ini berisi hasil pengerjaan simulasi gerbang logika menggunakan platform Tinkercad Circuits. Rangkaian ini dirancang menggunakan 3 komponen IC TTL seri 74HC untuk merepresentasikan persamaan logika kombinasi:
**Y = (A . B) + C'**

IC yang digunakan dalam rangkaian ini adalah:
1. **74HC08 (Quad 2-Input AND Gate):** Mengkalikan input A dan B.
2. **74HC04 (Hex Inverter):** Membalik nilai input C.
3. **74HC32 (Quad 2-Input OR Gate):** Menjumlahkan hasil AND dan NOT untuk disalurkan ke LED.

## Anggota Kelompok
1. Edwin Alfian Barin (H1H025070)
2. Edwin Alfian Barin (H1H025070)
3. Edwin Alfian Barin (H1H025070)

## Tautan Rangkaian Tinkercad
* (https://www.tinkercad.com/things/4fD7eUxRTuV-7-komponen-ic-dengan-masing-masing-gerbang-logika)

## Tabel Kebenaran (Truth Table)
| A | B | C | Output Y |
|:-:|:-:|:-:|:--------:|
| 0 | 0 | 0 |    1     |
| 0 | 0 | 1 |    0     |
| 0 | 1 | 0 |    1     |
| 0 | 1 | 1 |    0     |
| 1 | 0 | 0 |    1     |
| 1 | 0 | 1 |    0     |
| 1 | 1 | 0 |    1     |
| 1 | 1 | 1 |    1     |
