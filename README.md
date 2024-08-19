# Program sederhana untuk penambahan dan pengurangan dua angka

# Fungsi untuk penambahan
def penambahan(a, b):
    return a + b

# Fungsi untuk pengurangan
def pengurangan(a, b):
    return a - b

# Meminta input dari pengguna
angka1 = float(input("Masukkan angka pertama: "))
angka2 = float(input("Masukkan angka kedua: "))

# Melakukan operasi penambahan dan pengurangan
hasil_tambah = penambahan(angka1, angka2)
hasil_kurang = pengurangan(angka1, angka2)

# Menampilkan hasil
print(f"Hasil penambahan {angka1} + {angka2} = {hasil_tambah}")
print(f"Hasil pengurangan {angka1} - {angka2} = {hasil_kurang}")
