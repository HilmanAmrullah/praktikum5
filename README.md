Nama: Hilman Ihza Amrullah <br>
NIM: 312210310 <br>
Kelas: TI.22.A.3

---

## Latihan

- Buat sebuah list yang berisi 5 elemen

```python
warna = ["Merah", "Hijau", "Hitam", "Abu-abu", "Biru"]
```

- Untuk menampilkan semua elemen didalam list, gunakan fungsi `print(warna)`
- Untuk menampilkan elemen ke-3, gunakan fungsi `print(warna[2])` *( index dimulai dari 0 )*
- Untuk menampilkan elemen ke 2 sampai elemen ke-4, gunakan fungsi `print(warna[1:4])`
- Untuk menampilkan elemen terakhir, gunakan fungsi `print(warna[-1])`

```python
print(warna)
print(warna[2])
print(warna[1:4])
print(warna[-1])
```

Output:

```
["Merah", "Hijau", "Hitam", "Abu-abu", "Biru"]
Hitam
["Hijau", "Hitam", "Abu-abu"]
Biru
```

---

- Untuk mengubah elemen ke-4 dengan nilai lainnya, `warna[3] = "nilai baru"`
- Untuk mengubah elemen ke-4 sampai elemen terakhir, `warna[3:] = "nilai baru", "nilai baru", ...`

```python
warna[3] = "Ungu"

# Isi list menjadi: ["Merah", "Hijau", "Hitam", "Ungu", "Biru"]

warna[3:] = "Putih", "Kuning"

# Isi list menjadi: ["Merah", "Hijau", "Hitam", "Putih", "Kuning"]
```

---

- Untuk mengambil 2 bagian dari **list A** ke **list B**

```python
warna2 = [warna[0], warna[1]]

# Isi list menjadi: ["Merah", "Hijau"]
```

- Untuk menambah elemen list, gunakan `append()` untuk menambahkan elemen ke akhir daftar

```python
warna2.append("Coklat")

# Isi list menjadi: ["Merah", "Hijau", "Coklat"]
```

- Untuk menambah lebih banyak elemen list, gunakan `extend()`

```python
warna2.extend(["Biru Muda", "Violet", "Oren"])

# Isi list menjadi: ["Merah", "Hijau", "Coklat", "Biru Muda", "Violet", "Oren"]
```

- Untuk menggabungkan **list A** dan **list B**, gunakan operasi pertambahan (+)

```python
warna3 = warna + warna2
```

- Jika ditampilkan, maka outputnya:

```
['Merah', 'Hijau', 'Hitam', 'Abu-abu', 'Biru', 'Merah', 'Hijau', 'Biru Muda', 'Violet', 'Oren']
```
