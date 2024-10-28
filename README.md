### Nama : Sovy Aprianti
### Nim : 312410344
### Kelas : TI.24.A4
### Matkul : Bahasa Pemrograman

# Struktur Kondisi


Menggunakan struktur bersyarat dengan kalimat if, Konsep pemrograman yang memungkinkan program untuk menghasilkan respons berdasarkan kondisi atau pernyataan yang diberikan. Struktur untuk seleksi bersyarat yang biasanya digunakan dalam Python

if: Digunakan untuk menilai kondisi tertentu. Jika kondisi yang disebutkan di atas benar (true)
elf : Digunakan untuk menentukan apa yang akan terjadi jika kondisi tersebut bernilai salah.
elif: Digunakan untuk mengevaluasi beberapa kondisi. Python akan mengevaluasi kondisi elif jika kondisi if adalah kondisi yang pertama. Dan Anda dapat memiliki beberapa elif

# Soal Latihan

![Screenshot From 2024-10-24 20-34-23](https://github.com/user-attachments/assets/eb5e67d9-1744-45a6-b247-8375d395d2fd)


# Program Menentukan Nilai Akhir

'''Phyton Code'''
nama = input("Masukkan nama:")
uts = input("Masukkan nilai UTS:")
uas = input("Masukkan nilai UAS:")
tugas = input("Masukkan nilai Tugas:")

akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"
print("\nNama :",nama)
print("Nilai UTS :",uts)
print("Nilai UAS :",uas)
print("Nilai Tugas :",tugas)
print("Nilai Akhir :",akhir)
print("\nNilai Huruf :",huruf)
print("Keterangan :",keterangan)
