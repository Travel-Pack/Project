# Travel Pack

### Ide:

- Navigasi ke tempat tujuan
- review kota untuk travelling
- data-data terkait kota
- Tenant tempat wisata

### Third Party API :

- Chart.js (optional)
- WeatherAPI
- Disqus

## Flow Application :

### Entitas Utama :

### Cities :

- Cities punya destinasi masing masing, yang ditambahkan oleh user

### Destination :

- Tujuan wisata yang ditambahkan oleh users

### Admin :

- Admin bisa menghapus Review,
  edit : destination, city, porovince
  posting : city, province, destination

### User :

- Punya fasilitas untuk menjadi premium (membership)
- Menambahkan Comment, Rating (cost, fun, internet, safety)
- Bisa menambahkan destinasi favorit

Fasilitas iklan :
biarkan pemilik penginapan menambah iklan di website kita (mungkin yang terdekat dari destinasi)

## Release 0 Backend :

- Bikin test dulu (jest) dengan endpoint masing - masing
- Bikin endpoints

  ```json
  POST("/register")
  POST("/login")

  PATCH("/users/:id")
  PUT("/users/:id")
  GET("/users/:id")

  POST("/favorites")
  GET("/favorites")

  GET("/destinations")
  GET("/desinations/:id")
  POST("/destinations")
  PUT("/destinations")

  GET("/cities")
  GET("/cities/:id")
  PUT("/cities")
  POST("/cities")

  POST("/reviews")
  DELETE("/reviews/:id")

  POST("/province")
  PUT("/province")
  ```

## Release 1 Backend :

- Bikin MVC

## Release 0 Frontend :

- Bikin mockup (skeleton dari website)

## Release 1 Frontend :

- Bikin template

## Release 2 Frontend

- Intiate React app

## Release 3 Frontend

Pages :

- Login & Register
- Home (berisikan Kota yang berbentuk cards, masing masing card memiliki weather)
- Profile (Berisikan Favorites dan detail User) User dapat mengedit detail di halaman ini
- Kota (berisikan detail dari destinasi tersebut dan review dari user, user dapat menambahkan comment di halaman ini)

- Home untuk admin yang berisikan daftar Kota yang tersedia
- Destinasi, bisa diakses melalui click pada list kota

## Fitur tambahan menyusul ! masing masing anggota kelompok dapat menambahkan langsung di bawah sini :

1.
2.
3.
