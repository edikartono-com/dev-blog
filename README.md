# dev-blog

# Alhamdulillah

Akhirnya saya memutuskan untuk membagikan <em>source code</em> blog saya, namun teman-teman jangan berharap banyak dari project ini. Sebab ini hanyalah project kecil, berupa web blog biasa saja, yang membedakan hanyalah bahasa dan framework yang digunakan. Sungguh tidak ada yang istimewa di dalamnya.</p>

Front end template:
=======================================================
* Template Name: DevFolio - v2.3.0
* Template URL: https://bootstrapmade.com/devfolio-bootstrap-portfolio-html-template/
* Author: BootstrapMade.com
* License: https://bootstrapmade.com/license/
========================================================

Admin templte: django-jazzmin (LTE)

# fitur

1. Blog
2. sitemap.xml dan yandex.xml
3. dioptimasi untuk SEO
4. multi user dengan group
5. sidebar (static) pencarian artikel, kategori, artikel terbaru, random related artikel
6. admin (django-jazzmin) https://github.com/farridav/django-jazzmin
7. user social login (django-allauth) caranya : https://django-allauth.readthedocs.io/en/latest/providers.html

# Lisensi 

Meski devblog yang saya hasilkan ini masih jelek, namun tetap dirasa perlu menyematkan lisensi dalam penggunaannya. Bukanlah sebuah lisensi yang aneh-aneh, project ini saya beri lisensi <strong>GNU General Public License v3.0</strong>, agar siapa saja bisa memanfaatkan project ini untuk kepentingannya masing-masing.Silahkan kalian pelajari tentang lisensi GNU V3.0. https://github.com/edikartono-com/dev-blog/blob/main/LICENSE

Namun karena project ini tidak murni 100% karya saya, maka bisa saja terdapat perbedaan lisensi diantaranya: 

Template (backend dan frontend) juga module yang digunakan. Masing-masing memiliki lisensinya sendiri.

# Cara Menggunakannya
Sebenarnya tidak sulit menggunakan devblog, 

siapkan sebuah virtual environment, clone https://github.com/edikartono-com/dev-blog.git

isntall module python yang dibutuhkan   

<pre><code>pip install -r requirements.txt

python manage.py migrate

python manage.py runserver</code></pre>

# masih ada error
Beberapa masih belum sempurna, seperti yandex.xml yang belum bisa diakses.

# to do
1. email marketing (subscribe dan newsletter)
2. dashboard user
3. Product dan shopping cart