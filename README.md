# BE-PeWorld

<br />
<p align="center">
  <div align="center">
    <img height="150" src="https://github.com/xTats/BE-PeWorld/assets/122331956/c21c1204-f9c1-450a-87d2-c395aa16e945" alt="MyRecipe" border="0"/>
  </div>
  <h3 align="center">PeWorld</h3>
  <p align="center">
    <a href="https://github.com/xTats/BE-PeWorld"><strong>Explore the docs »</strong></a>
    <br />
  <a href="https://peworld-fawn.vercel.app/">View Demo</a>
    ·
    <a href="https://be-pe-world.vercel.app/">Api Demo</a> -->
  </p>
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Built With](#built-with)
- [Installation](#installation)
  - [Documentation](#documentation)
  - [Related Project](#related-project)
- [Contributors](#contributors)
  - [Meet The Team Members](#meet-the-team-members)

# About The Project

Recipe Cooking adalah aplikasi untuk menjelajahi dunia recipe dan juga untuk mencari, dan berbagi banyak resep baru setiap hari, Cari berdasarkan nama resep, Bagikan resep serta bantu orang lain untuk membuat resep sehari-hari yang lezat dan mudah.Berikan like pada recipe yang anda sukai dan save untuk recipe yang ingin anda coba buat di rumah dan juga comment berikan feedback pada pembuat resep

## Built With

These are the libraries and service used for building this backend API

- [Node.js](https://nodejs.org)
- [Express](https://expressjs.com)
- [PostgreSQL](https://www.postgresql.org)
- [Cloudinary](https://cloudinary.com)
- [Json Web Token](https://jwt.io)
- [Multer](https://github.com/expressjs/multer)

# Installation

1. Clone this repository

```sh
git clone https://github.com/xTats/BE-PeWorld.git
```

2. Change directory to BE-PeWorld

```sh
cd BE-PeWorld
```

3. Install all of the required modules

```sh
npm i / npm install
```

4. Create PostgreSQL database, query are provided in [query.sql](./query.sql)

5. Create and configure `.env` file in the root directory, example credentials are provided in [.env.example](./.env.example)

```txt
- Please note that this server requires Google Drive API credentials and Gmail service account
- Otherwise API endpoint with image upload and account register won't work properly
```

6. Run this command to run the server

- Or run this command for running in development environment

```sh
npm start
```


## Documentation

Documentation files are provided in the [docs](./docs) folder

- [Postman API colletion]()
- [PostgreSQL database query](./query.sql)

API endpoint list are also available as published postman documentation

[![Run in Postman](https://run.pstmn.io/button.svg)](https://documenter.getpostman.com/view/29301540/2s9YXb8kR5))

## Related Project

:rocket: [`Backend-PeWorld`](https://github.com/xTats/BE-PeWorld)

:rocket: [`FE-PeWorld`](https://github.com/xTats/FE-PeWorld_Next)

:rocket: [`Demo PeWorld Web`](https://peworld-fawn.vercel.app/)

Project link : [https://github.com/xTats/FE-PeWorld_Next](https://github.com/xTats/FE-PeWorld_Next)]