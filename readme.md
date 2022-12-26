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

Flow Application :

Entitas Utama :

Province :

Cities :

- Cities punya destinasi masing masing, yang ditambahkan oleh user

Destination :

- Tujuan wisata yang ditambahkan oleh users

Admin :

- Admin bisa menghapus Review,
  edit : destination, city, porovince
  posting : city, province, destination

User :

- Punya fasilitas untuk menjadi premium (membership)
- Menambahkan Comment, Rating (cost, fun, internet, safety)
- Bisa menambahkan destinasi favorit

Fasilitas iklan :
biarkan pemilik penginapan menambah iklan di website kita (mungkin yang terdekat dari destinasi)

Release 0 Backend :

- Bikin test dulu (jest) dengan endpoint masing - masing
- Bikin endpoints

  POST("/register")
  POST("/login")

  PATCH("/users/:id")
  PUT("/users/:id")
  GET("/users/:id")

  POST("/favorites)
  GET("/favorites)

  GET("/destinations")
  GET("/desinations/:id)
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

Release 0 Frontend :

- Bikin template (skeleton dari website)
