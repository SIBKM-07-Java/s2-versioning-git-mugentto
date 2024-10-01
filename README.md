FAST FORWARD
1. Inisialisai Direktori
![](image/1.png)
Melakukan pemindahan direktori ke folder yang ingin kita tuju. Melakukan pengenalan direktori dengan git (git init) 
2. Penambahan README.md
![](image/2.png)
Setelah file readme berhasil kita buat maka status file Untracked file, hal itu terjadi jika ada file yang ditambah atau dihapus selanjutnya kita melakukan add dan commit untuk memakukan ke git lokal
HASIL
![](image/2a.png)
3. Pembuatan Branch Parent dan Child
![](image/3.png)
Pada kasus ini master dan Parent memenuhi peran yang sama maka hanya perlu di rename saja, sedangkan Child perlu membuat dari awal
4. Perubahan file pada child
![](image/4.png)
Setelah terjadi perubahan pada file dilakukan add dan commit kedalam ChildAgus
5. Merge
![](image/5.png)
Berpindah branch ke Parent dan melakukan pengabungan atau merge dengan branch Child serta hasil FAST FORWARD sudah nampak.

REMOTE SERTA PUSH KE ORGANISASI
1. Push ParentAgus
![](image/1r.png)
inisialisai repositori organisasi dengan remote. Melakukan push pada branch parent
2. Push ChildAgus
![](image/2r.png)
Melakukan push pada branch child

THREE WAY MERGE
1. git clone
![](image/21.png)
Melakukan clone dan menyiapkan direktori hasil clone
2. Menampilkan branch tersembunyi
![](image/22.png)
Menampilkan kembali branch parent dan child
3. Three Way Merge pada child
![](image/23.png)
Setelah melakukan perubahan maka dilakukan add,commit, dan push
4. Three Way Merge pada parent
![](image/24.png)
Setelah melakukan perubahan maka dilakukan add,commit, dan push
5. Melakukan pull seolah olah conflict
![](image/25.png)
![](image/20.png)
pilih tindakan yang diminati dan di merge di visual studio
6. Commit hasil penanganan conflict
![](image/26.png)
hasil penanganan conflict di vs code di commit 
7. Push ke git remote
![](image/27.png)
8. melakukan pull pada parent dan melihat log
![](image/28.png)
9. hasil pull request
![](image/29.png)