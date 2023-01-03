  # Tambahan :

  Menambahkan fitur untuk memudahkan user mencari destinasi ter worth it. dengan cara menambahkan harga dari masing2 destinasi ke dalam databse
  berdasar harga sama review.

  ## Backend :
  ### New Tables :
  Hotel, Booking, 

  ### User Role:
  User, Role : admin, destOwner, hotelOwner
  
  ### Endpoint : 
  - Booking, (budget, cityDestination)
  
  Booking --> User input budget and City or Destination 
  Budget = 300k
  if destination price === 50k 
  return Hotel with price < than 250k
  Habis milih cityDestination --> User memilih Destination --> Muncul rekomendasi Hotel yng deket dari destinasi
  if user not choose Destination --> Show destination recommend based on budget, sort by Price and Review

  - Checkout (total price)

  ## Cara user mencari destinasi ter worth it :

  misal budget 1jt, terus di sortir, destinasi mana yang bisa masuk budget

  Paket A : Misal destinasi lombok, gili trawangan, hotel sentosa
  Paket B: Misal destinasi bali, gwk, hotel bunga

  user input kota, balikin dengan halaman destinasi dari kota itu,

  ## Booking

  Halaman Booking (dari manapun bisa akses booking) misal navbar
  Halaman Berisi : Input budget, kota, destinasi (optional) --> outputnya beberapa paket yng sesuai dengan budget dia terus lanjut booking

  # Frontend-Page

  ## Navbar :

  Home, City , Booking, Favorites, Icon People

  ## Page Booking :

  User menginput budget, kota tujuan.
  Tampilkan destinasi berbentuk card kecil.
  User bisa milih destinasi ini, kalo udah milih nanti dikasih recomend paket dari kita.

  Kalo dia udah ada desitnasi tampilkan hotel terdekat yang sesuai budget.

  Kalo misal ngga milih destinasi tampilkan 3 destinasi terbaik (berdasar review dan harga)

  ## Main Page : 
  Landing langsung ke backgroudn,

  ### Search,

  mencari destinasi atau city

  ### Card,

  berisikan city

  ### Card

  berisikan destinasi favorit(top destination), isi berisi nama dan harga aja

  ## City Page,

  Menampikan banyak destinasi dalam bentuk kartu, syling dikit

  ## Destination Page : Information, Review, Covid Status, Price, Weather, Gallery

  ## Halaman Profil :

  Favorites, Transaction history,

  # Admin Page

  ## Destination Page

  yang berisi

  # List User

  ## Admin,
  - Dapat Menambhakan user(Pemilik Hotel&Destinasi)
  - Dapat menghapus review(filter)
  - Dapat notifikasi jika ada user yng mereport

  ## User
  - Book
  - Review
  - Report review
  - Add Favorites

  ## Pemilik Hotel dan Destinasi

  - Hanya dapat melihat Hotel, detail hotel, history booking terus (list booking bertambah) bisa upload gambar.
  - Dapat mengganti status hotel (active/inactive)

