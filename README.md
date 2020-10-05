# ugm-fe-07
Project ini diperuntukan untuk pembelajaran Digitalent
Sesi Pertemuan ke 5 Dasar-dasar interaksi Git dan Github Collaboration Project

**Untuk perintah add**

```markdown
git add .
```

**Untuk perintah commit**

```markdown
git commit -m "Pesan commit"
```

**Untuk perintah Push**

```markdown
git push origin master
```


**Untuk perintah Pull**

```markdown
git pull origin master
```

**Untuk perintah fetch**

```markdown
git fetch origin master
```

## Membuat branch baru

### Apa itu Branch

Jika anda melakukan branch maka anda pada dasarnya membuat **suatu cabang dari repository anda**. Jika anda membuat perubahan dan melakukan commit pada cabang ini maka ini hanya terjadi pada cabang tersebut dan tidak akan berdampak pada cabang utama maupun cabang-cabang  lain yang mungkin ada. Disamping itu cabang ini nantinya bisa digabung **(=merge)** dengan cabang-cabang yang lain atau disatukan kembali dengan cabang utama.



### Cara Membuat Branch Baru

Jalan CMD pada directory git anda pada pc dan jalankan perintah berikut ini.

```markdown
git branch "namabranch"
```

```markdown
git checkout "namabranch"
```



**Note : Ubah namabranch sesuai dengan apa yang kamu ingin gunakan dan tanpa tanda petik**

# Pemakaian Git sehari-hari

Kita akan mengulas secara singkat perintah-perintah yang sering kita gunakan dalam Git. Tapi sebelum mulai, perlu kita pahami beberapa istilah sebagai berikut :

- diff : perbedaan antara satu file dengan file lainbiasanya diff dilakukan terhadap satu file yang sudah berubah isinya

- changeset : kumpulan diff

- working folder : folder kerja kita, berisi file yang (mungkin) sudah berubah sejak commit terakhir

- staging : tempat persiapan changeset yang akan dicommit

- commit : snapshot dari posisi folder dan file pada waktu tertentu

- tip : commit paling ujung

- head : nama lain tip

- branch : head yang diberi nama

- HEAD : head yang sedang aktif

- merge : menggabungkan lebih dari satu commit


## Berbagai link pembelajaran git dan github
- https://www.petanikode.com/tutorial/git/ 
- https://www.youtube.com/watch?v=lTMZxWMjXQU - Sandika Galih

  ​