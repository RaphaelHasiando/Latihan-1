# Latihan-1
### Daftar Kontak
     # Nama | Nomor Telepon
     # ====================
     # Ari  | 081267888
     # Dina | 087677776
###
      a = {
      "Ari" : 081267888,
      "Dina" : 087677776
      }

### Tampilkan kontaknya Ari
     print(a["Ari"])
![image](https://user-images.githubusercontent.com/61907877/144755432-00ad9e9c-9f48-4f7e-847e-4d08de874f79.png)

### Tambah kontak baru dengan nama Riko, nomor 087654544
     a['Riko'] = '087654544'
     print(a)
![image](https://user-images.githubusercontent.com/61907877/144755566-5bace558-291d-4db6-aeec-82e70f8edc54.png)

### Ubah kontak Dina dengan nomor baru 088999776
     a['Dina'] = '088999776'
     print(a)
![image](https://user-images.githubusercontent.com/61907877/144755677-1f791a43-e91a-4e0c-a2b1-570ca754c891.png)

### Tampilkan semua Nama
     print(list(a.keys()))
![image](https://user-images.githubusercontent.com/61907877/144756135-1ca13323-7101-4e9f-a404-282e710f18c3.png)

#### for loop
     for x in range(len(a)):
      print(list(a.keys())[x])
![image](https://user-images.githubusercontent.com/61907877/144756147-7b6c85d5-bcfe-492e-bf33-2cd3cddb1ed3.png)
### Tampilkan daftar Nama dan nomornya
     for x in range(len(a)):
      print(list(a.keys())[x])
      print(a[list(a.keys())[x]])

### Tampilkan semua nomor
     for x in range(len(a)):
      print(a[list(a.keys())[x]])
![image](https://user-images.githubusercontent.com/61907877/144756322-a54218d4-d898-4530-b1cb-1d40616d8035.png)

### Tampilkan daftar Nama dan nomornya
     for x in range(len(a)):
      print(list(a.keys())[x])
      print(a[list(a.keys())[x]])
![image](https://user-images.githubusercontent.com/61907877/144756405-a091c9ac-7139-4a89-97b6-790031ecf7c9.png)

### Hapus kontak Dina
     del a["Dina"]
     print(a)
 ![image](https://user-images.githubusercontent.com/61907877/144756534-cfa832af-7d11-4f8c-9ae9-555ec23156be.png)
