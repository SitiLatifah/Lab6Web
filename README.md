# Lab6Web
**Nama	 : Siti Latifah** <br>
**NIM	   : 312010321** <br>
**Kelas	 : TI.20.A2** <br>
**Matkul : Pemrograman Web** <br>

# BELAJAR WEB FRAMEWORK
## INTRUKSI PRAKTIKUM
![Screenshot (227)](https://user-images.githubusercontent.com/73010098/163680935-3e82e32b-4294-41dd-9eb6-f6a70ed81eb6.png)

**Buatlah file html dengan nama ```lab6_css_framework```. Berikut adalah syntax html menggunakan framework bootstrap**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous" />

    <style>
      .container {
        width: 980px;
        margin: 0 auto;
        box-shadow: 0 0 1em #ccc;
        padding: 0px;
      }

      .header h1 {
        color: #b5b5b5;
        margin: 20px 10px;
      }

      .divider {
        border: 0;
        border-top: 1px solid #eeeeee;
        margin: 40px 0;
      }

      /* entry */
      .entry {
        margin: 15px 0;
      }
      .entry h2 {
        margin-bottom: 20px;
      }
      .entry p {
        line-height: 25px;
      }
      .entry img {
        float: left;
        border-radius: 5px;
        margin-right: 15px;
      }
      .entry .right-img {
        float: right;
      }

      /* footer */
      footer {
        clear: both;
        background-color: #1d1d1d;
        padding: 20px;
        color: #eee;
      }
    </style>

    <title>FRAMEWORK</title>
  </head>

  <body>
    <div class="container">
      <!-- header -->
      <div class="card-body header">
        <h1 class="card-title display-3">Layout Sederhana</h1>
      </div>
      <!-- ... -->

      <!-- navbar -->
      <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container-fluid">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Konten</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">About</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Kontak</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <!-- ... -->

      <!-- jumbotron -->
      <div class="card-body p-5 bg-secondary bg-opacity-25">
        <h1 class="card-title display-5 fw-bold">Hello World!</h1>
        <p class="card-text text-sm-start">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis innisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium
          nunc pretium ac.
        </p>

        <a href="CSS _ FrameWork.html" class="btn btn-primary"> Learn more </a>
      </div>
      <!-- ... -->

      <!-- element konten -->
      <div class="card-body p-5">
        <div class="row">
          <div class="col-md-8">
            <div class="row m-2">
              <div class="col-md m-md-2">
                <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle" />
                <h3>Heading</h3>
                <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
              </div>
              <div class="col-md m-md-2">
                <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle" />
                <h3>Heading</h3>
                <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
              </div>
              <div class="col-md m-md-2">
                <img src="https://dummyimage.com/120/db7d25/fff.png" alt="" class="rounded-circle" />
                <h3>Heading</h3>
                <p class="text-sm-start">Donec sed odio dui. Etiam porta sem malesuada magna mollis euismod.</p>
                <a href="#" class="btn btn-default">View detail</a>
              </div>
            </div>

            <!-- konten -->

            <hr class="divider" />
            <div class="row">
              <div class="col">
                <article class="entry">
                  <h2>First featurette heading.</h2>
                  <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" />
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc,
                    nec pretium nunc pretium ac.
                  </p>
                </article>
              </div>
            </div>
            <hr class="divider" />
            <div class="row">
              <div class="col">
                <article class="entry">
                  <h2>First featurette heading.</h2>
                  <img src="https://dummyimage.com/150/7b8a70/fff.png" alt="" style="float: right" />
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc,
                    nec pretium nunc pretium ac.
                  </p>
                </article>
              </div>
            </div>

            <!-- akhir konten -->
          </div>
          <div class="col offset-1">
            <h3 class="bg-primary p-1">Widget Header</h3>
            <ul class="nav flex-column">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#">Widget Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Widget Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Widget Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Widget Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Widget Link</a>
              </li>
            </ul>

            <div>
              <h3 class="bg-primary">Widget Text</h3>
              <p class="text-sm-start">Vestibulum lorem elit, iaculis in nisl volutpat, malesuada tincidunt arcu. Proin in leo fringilla, vestibulum mi porta, faucibus felis. Integer pharetra est nunc, nec pretium nunc pretium ac.</p>
            </div>
          </div>
        </div>
      </div>
      <!-- ... -->

      <footer>
        <center><p>&copy; 2021 - Universitas Pelita Bangsa @ Siti Latifah</p></center>
      </footer>
    </div>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
  </body>
</html>
```

## OUTPUT
**Dibawah ini adalah Hasil dari syntax di atas**

![Screenshot (229)](https://user-images.githubusercontent.com/73010098/163681197-0145a333-02d5-4fdd-834b-511dd007dbf5.png)
![Screenshot (228)](https://user-images.githubusercontent.com/73010098/163681209-c6023416-23f0-4ed8-bc26-81cd086b6a8f.png)

