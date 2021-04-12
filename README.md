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
 -   `1`tipe default untuk angka `1`, `2`, `3`, dan seterusnya;
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


