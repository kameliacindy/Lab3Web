# Praktikum 3 : HTML Lanjutan
## A. Membuat List

### **1. Ordered List**
 
 **_Ordered list_** merupakan list yang terurut dengan menggunakan penomoran angka, secara default. 
 
 _Ordered list_ dibuat dengan tag `<ol>`. Lalu di dalamnya diisi dengan item-item yang akan dimasukkan ke dalam list. Item dibuat dengan tag `<li>`  _(list item)_.
 
 **Contoh:**
 
 Persiapan membuat dokumen HTML, seperti berikut.
 
 ![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/html_list.PNG)

Kemudian membuat kode _ordered list_ seperti berikut.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ordered_list.PNG)
 
 **Dan hasilnya:**
 
 ![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_ol.PNG)

List diatas diurutkan secara default yaitu berdasarkan angka dari `1` sampai  `3`.

_Ordered List_ dapat dikonfigurasi lebih lanjut menggunakan atribut `type` dan `start`. Terdapat lima macam `type`:
 -   `1`  tipe default untuk angka `1`, `2`, `3`, dan seterusnya;
 -   `a`  untuk alfabet  `a`,  `b`,  `c`, dan seterusnya;
 -   `A`  untuk alfabet  `A`,  `B`,  `C`, dan seterusnya;
 -   `i`  untuk angka romawi `i`,  `ii`,  `iii`, dan seterusnya;
 -   `I`  untuk angka romawi `I`,  `II`,  `III`, dan seterusnya.
 
 ### **2. Unordered List**
 
 **_Unordered list_**  adalah list yang tak terurut yang menggunakan simbol-simbol pada item-nya.  _Unordered list_  dibuat dengan tag  `<ul>`  dan untuk item-nya dibuat juga dengan tag  `<li>`.
 
**Contoh:**

Tambahkan kode untuk membuat _Unordered list_, setelah deklarasi  ordered list pada section `unordered-list`, seperti berikut ini.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/unorderd_list.PNG)
 
**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_ul.PNG)

Simbol yang digunakan pada list di atas adalah menggunakan atribut`type` `square`.
Kita juga dapat menggantinya dengan atribut  `type`. Berikut ini nilai yang bisa diberikan untuk atribut  `type`:

-   `square`  untuk simbol persegi;
-   `disc`  (default) untuk simbol lingkaran disc;
-   `none`  tidak memakai simbol;
-   `circle`  untuk simbol lingkaran.

### **3. Description List**

**_Description List_**  adalah list yang berisi deksripsi atau penjelasan dari sesuatu.

Ada tiga tag yang digunakan untuk membuat description list:

-   `<dl>`  (description list) tag untuk memulai description list;
-   `<dt>`  (description term) tag untuk membuat kata yang akan dideskripsikan;
-   `<dd>`  (description description) tag untuk membuat penjelasan dari kata.

**Contoh:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/description_list.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_dl.PNG)


## B. Membuat Table
### Tag untuk Membuat Tabel di HTML

Ada beberapa tag yang untuk membuat tabel di HTML:

1.  Tag  `<table>`  untuk membungkus tabelnya
2.  Tag  `<thead>`  untuk membungkus bagian kepala tabel
3.  Tag  `<tbody>`  untuk membungkus bagian body dari tabel
4.  Tag  `<tr>`  (tabel row) untuk membuat baris
5.  Tag  `<td>`  (table data) untuk membuat sel
6.  Tag  `<th>`  (table head) untuk membuat judul pada header

**Contoh:**

Persiapan untuk membuat dokumen HTML terlebih dahulu.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/html_table.PNG)

Selanjutnya, tambahkan kode untuk membuat tabel sederhana, seperti berikut ini.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/table.PNG)

 - Nilai  `"1"`  pada atribut  `border`  adalah ukuran garisnya. Semakin besar ukurannya, maka akan semakin besar pula ukuran garisnya. 
 - Nilai  `"1"`  adalah ukuran garis yang paling kecil.

**Dan hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_table.PNG)

### Mengatur Margin dan Padding

 - **Cellspacing** untuk menentukan jarak spasi antar cell
 - **Cellpadding** untuk menentukan jarak antara garis cell dengan isi cell (padding)
 - **Height** untuk menentukan tinggi tabel
 - **Width** untuk menentukan lebar tabel
 
 Atribut-atribut di atas diletakkan di dalam tag `<table>`, seperti contoh di bawah ini:
 
![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/margin_padding.PNG)
 
 **Hasilnya:**
 
![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_padding.PNG)
 
### Menggabungkan Sel Data
Untuk menggabungkan sel data, menggunakan atribut `rowspan` dan `colspan`. 

 - **Rowspan** untuk menggabungkan baris (secara vertikal)
 - **Colspan** untuk menggabungkan kolom (secara horizontal)
 
 ![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/rowspan.PNG)

**Hasilnya:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_rowspan.PNG)


## Membuat Form

**Form** biasanya digunakan untuk mengumpulkan data dari pengunjung web kita. Mulai dari form untuk login, form kontak, form untuk pendaftaran user, bahkan untuk mengirimkan data antar halaman web.

Tag dasar yang akan kita gunakan untuk membuat form di HTML adalah sebagai berikut.

 1. Form di HTML dapat kita buat dengan tag  `<form>`.
Tag ini memiliki beberapa atribut yang harus diberikan, seperti:

-   `action`  untuk menentukan aksi yang akan dilakukan saat data dikirim
- `enctype`  untuk mendefinsikan cara encoding data sebelum dikirimkan. Biasanya digunakan jika ingin meng-upload file.
-   `method`  metode pengiriman data.
**GET**: Data dikirimkan bersama URL. 
**POST**: Data dikirimkan terpisah dari URL.

2. Tag `<fieldset>` untuk membuat sebuah garis.
3. Di dalam tag `<fieldset>`, kita membuat tag `<legend>` untuk memberikan teks pada _fieldset_.
4. Setiap field kita bungkus dalam tag `<p>` agar terlihat rapi dan juga kita berikan sebuah label dengan tag `<label>`.
5. Tag `input` merupakan tag paling banyak digunakan di dalam **form** dan memiliki banyak bentuk berdasarkan atribut type di bawah ini:

 -   `<input type="text">` adalah _textbox_ inputan biasa yang menerima input berupa text, contohnya digunakan untuk inputan _nama_, _username_, dll.
 - `<input type="password">`  tampilannya sama dengan _textbox_, namun teks yang diinput tidak akan terlihat, akan berupa bintang atau bulatan. Biasanya hanya digunakan untuk inputan yang sensitif seperti _password_.
 - `<input type="checkbox">` adalah inputan berupa _checkbox_ yang dapat diceklist atau di centang oleh user. User dapat memilih atau tidak memilih checkbox ini. Contoh inputan **checkbox** berupa hobi.
 - `<input type="radio">` mirip dengan **checkbox**, namun user hanya bisa memilih satu diantara pilihan group radio. Contoh inputan type radio adalah jenis kelamin.
 - `<input type="submit">` adalah tombol untuk memproses form. Biasanya diletakkan pada baris terakhir dari form. **Atribut value** jika diisi akan membuat text tombol submit berubah sesuai inputan nilai **value**.
 
 **Contoh:**
 
 ![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/form.PNG)

**Kemudian tambahkan style CSS:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/form_css.PNG)

**Hasilnya (tanpa CSS):**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_form.PNG)

**Dengan CSS:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_form_css.PNG)

## Membuat Form yang Menampilkan *Dropdown* menu dan *Listbox* dengan *Multiple Selection*
Tag `<select>` di dalam HTML digunakan untuk membuat **objek form** yang berupa list pilihan yang dapat dipilih oleh user. Kita juga membutuhkan tag `<option>` sebagai “_isi_” dari tag `<select>`.
Atribut-atribut yang digunakan pada tag `<select>` adalah seperti di bawah ini:

 - **Atribut name** untuk digunakan sebagai identitas dari tag `select` tersebut. Identitas ini diperlukan pada saat pemrosesan di sisi **server** (misalnya menggunakan **PHP**).
 - **Atribut id** dibutuhkan untuk pemograman HTML menggunakan **Javascript** dan **CSS**.
 - **Atribut value** digunakan di dalam tag `option`. Nilai dari atribut inilah yang akan dikirimkan kedalam web server, sehingga disarankan menggunakan nilai yang mencerminkan pilihan user.
 - **Atribut size**  digunakan untuk menentukan besar dari tampilan  tag `select`. Jika tidak ditulis,  tag `select`  memiliki nilai  _default_  _size_=”1″, sehingga hanya 1 pilihan yang “_terlihat_” ketika user memilih pilihan yang ada.
Namun jika anda menambahkan atribut  **size=”3″,**  maka pada saat form ditampilkan,  tag `select`  akan ditampilkan sebanyak 3 baris. **Atribut size** biasanya di kombinasikan dengan **atribut multiple**.
 - **Atribut multiple** digunakan untuk memungkinkan user untuk dapat memilih lebih dari 1 nilai. Namun untuk dapat memilih lebih dari 1 nilai, user harus menekan tombol **ctrl** pada **keyboard**.

Berikut ini form yang menampilkan ***dropdown*** menu dan ***listbox*** dengan *multiple selection*.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/ss_dropdown_listbox.PNG)

### 1. *Dropdown* menu
Select Box digunakan untuk membuat inputan berupa pilihan dengan tampilan dropdown, secara default tag ini mengharuskan user untuk memilih 1 pilihan yang ada.

**Contoh:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/kode_dropdown.PNG)

Kode di atas menggunakan tag `<select>` dengan atribut id + name + value.

**Dan hasilnya seperti berikut:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/dropdown.png)

Terlihat ketika diklik akan ada 4 pilihan, yaitu SMA/SMK, D3, S1, dan S2. Menu pilihan tersebut dinamakan ***dropdown*** menu.

### 2. *Listbox* dengan *Multiple Selection*
Perhatikan contoh di bawah ini.

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/kode_listbox.PNG)

Kode di atas menggunakan tag `<select>` dengan atribut id + name + size + multiple + value.

**Dan hasilnya seperti di bawah ini:**

![enter image description here](https://github.com/kameliacindy/Lab3Web/blob/main/img/listbox.png)

Terlihat bahwa yang tampil adalah 3 pilihan karena kita menambahkan **atribute size=’3′**, selain itu kita dapat memilih lebih dari 1 karena menambahkan **atribut multiple**.

Terimakasih, semoga bermanfaat...

Nama: Kamelia Cindy Astuti

NIM: 311910104

Kelas: TI. 19. A. 1





