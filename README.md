## STRING

# LATIHAN 1 
```python
txt = 'Hello World'

# Hitung jumlah karakternya
jumlah_karakter = len(txt)
print("Jumlah karakter:", jumlah_karakter)

# Ambil karakter terakhir
karakter_terakhir = txt[-1]
print("Karakter terakhir:", karakter_terakhir)

# Ambil karakter index ke-2 sampai index ke-4 (llo)
substring = txt[2:5]
print("Karakter index ke-2 sampai index ke-4:", substring)

# Hilangkan spasi pada teks tersebut (HelloWorld)
tanpa_spasi = txt.replace(" ", "")
print("Teks tanpa spasi:", tanpa_spasi)

# Ubah teks menjadi huruf besar
huruf_besar = txt.upper()
print("Teks dalam huruf besar:", huruf_besar)

# Ubah teks menjadi huruf kecil
huruf_kecil = txt.lower()
print("Teks dalam huruf kecil:", huruf_kecil)

# Ganti karakter H dengan karakter J
ganti_h = txt.replace("H", "K")
print("Teks setelah mengganti H dengan k:", ganti_h)
```
## Output
````markdown
Jumlah karakter: 11
Karakter terakhir: d
Karakter index ke-2 sampai index ke-4: llo
Teks tanpa spasi: HelloWorld
Teks dalam huruf besar: HELLO WORLD
Teks dalam huruf kecil: hello world
Teks setelah mengganti H dengan k: Kello World
````
## LATIHAN 2 
```python
umur = 20
txt = 'Hello, nama saya jui, dan umur saya adalah {} tahun'

print(txt.format(umur))
```
## Output
````markdwon
Teks dalam huruf kecil: hello world
Teks setelah mengganti H dengan k: Kello World
PS D:\kuliah\B.PEMROGRAMAN> & C:/Python312/python.exe "d:/kuliah/B.PEMROGRAMAN/latihan string pert 15/latihan2.py"
Hello, nama saya jui, dan umur saya adalah 20 tahun
````
