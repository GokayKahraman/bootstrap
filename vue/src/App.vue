<template>
  <div>
    <!-- ikonlar(i etiketleri) çalışmıyor nedeni araştıralacak -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-success ">
      <div class="container">
        <a href="#" class="navbar-brand">KURUMSAL BLOG</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#menuac">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="menuac">

          <ul class="navbar-nav ml-auto">

            <li class="nav-item ">
              <a href="#" class="nav-link active">ANASAYFA</a>
            </li>

            <li class="nav-item">
              <a href="#" class="nav-link">UDEMY KURSLARI</a>
            </li>

            <li class="nav-item">
              <a href="#" class="nav-link ">YOUTUBE KANALIM</a>
            </li>

            <li class="nav-item">
              <a href="#" class="nav-link">ÖRNEK SAYFA</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <h1>Öne Çıkan Makaleler</h1>
          <hr class="bg-success">

          <div class="card mb-4">
            <img class="card-img-top" src="http://via.placeholder.com/750x300">
            <div class="card-body">
              <h2 class="card-title">Makale Başlığı</h2>
              <p class="card-text">Lorem ipsu mollit anim id est laborum.</p>
              <a href="#" class="btn btn-success">Devamını Oku</a>
            </div>
            <div class="card-footer text-muted">
              <span>Yayınlandığı Tarih 12.10.2017 22:44</span>
            </div>
          </div>

          <div class="card mb-4">
            <img class="card-img-top" src="http://via.placeholder.com/750x300">
            <div class="card-body">
              <h2 class="card-title">Makale Başlığı</h2>
              <p class="card-text">Lorem iit anim id est laborum.</p>
              <a href="#" class="btn btn-success">Devamını Oku <i class="fa fa-angle-right" aria-hidden="true"></i>
              </a>
            </div>
            <div class="card-footer text-muted">
              <span>Yayınlandığı Tarih 12.10.2017 22:44</span>
            </div>
          </div>

          <div class="card mb-4">
            <img class="card-img-top" src="http://via.placeholder.com/750x300">
            <div class="card-body">
              <h2 class="card-title">Makale Başlığı</h2>
              <p class="card-text">Lorem iit anim id est laborum.</p>
              <a href="#" class="btn btn-success">Devamını Oku <i class="fa fa-angle-right" aria-hidden="true"></i>
              </a>
            </div>
            <div class="card-footer text-muted">
              <span>Yayınlandığı Tarih 12.10.2017 22:44</span>
            </div>
          </div>

          <div class="card mb-4">
            <img class="card-img-top" src="http://via.placeholder.com/750x300">
            <div class="card-body">
              <h2 class="card-title">Makale Başlığı</h2>
              <p class="card-text">Lorem iit anim id est laborum.</p>
              <a href="#" class="btn btn-success">Devamını Oku <i class="fa fa-angle-right" aria-hidden="true"></i>
              </a>
            </div>
            <div class="card-footer text-muted">
              <span>Yayınlandığı Tarih 12.10.2017 22:44</span>
            </div>
          </div>

          <nav>
            <ul class="pagination justify-content-end">
              <li class="page-item "><a href="#" class="page-link bg-success text-white">Geri</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">2</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">3</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">4</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">5</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">6</a></li>
              <li class="page-item"><a href="#" class="page-link bg-success text-white">İleri</a></li>
            </ul>
          </nav>

        </div>

        <div class="col-md-4">

          <div class="card">
            <h6 class="card-header bg-success text-white">Arama Kutusu</h6>
            <div class="card-body">
              <div class="input-group">
                <input type="text" class="form-control" placeholder="Kelime Girin..." name="">
                <button class="btn btn-secondary" type="button">Ara</button>
              </div>
            </div>
          </div>

          <div class="card my-4">
            <h6 class="card-header bg-success text-white">Kategoriler</h6>
            <div class="card-body">
              <div class="row">
                <div class="col-md-6">
                  <ul class="list-unstyled">
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Php Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Java Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> C# Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Python Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Oracle Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Mysql Kursu</a>
                    </li>
                  </ul>
                </div>
                <div class="col-md-6">
                  <ul class="list-unstyled">
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Web Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Program Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Php Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Java Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Oracle Kursu</a>
                    </li>
                    <li>
                      <a href="#"><i class="fa fa-home" aria-hidden="true"></i> Php Kursu</a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>

          <div class="card my-4">
            <h6 class="card-header bg-success text-white">Reklam Alanı</h6>
            <div align="center" class="card-body">
              <img class="img-fluid" src="http://via.placeholder.com/400x400" alt="Reklam Alanı">
            </div>
          </div>

        </div>  

        <footer>
            <nav class="navbar navbar-expand-lg navbar-dark bg-success fixed-bottom">
              <div class="container">
                <a href="index.php" class="navbar-brand" data-toggle="collapse" data-target="#altmenuac">MAİLLİST KAYIT</a>
                <!-- <a href="index.php" class="navbar-brand"><img width="160" src="http://www.emrahyuksel.com.tr/dimg/22374emrahyuksellogo.png"></a>-->
              

                <div class="collapse navbar-collapse" id="altmenuac">

                  <form class="form-inline">

                    <input type="email" class="form-control col-auto mr-2" placeholder="Mail Adresi..." name="">

                    <input type="text" class="form-control col-auto " placeholder="Ad ve Soyad..." name="">

                    <button class="btn btn-secondary my-1 ml-2">Kayıt Ol!</button>

                    
                  </form>

                  <ul class="navbar-nav ml-auto">

                    <li class="nav-item ">
                      <a href="index.html" class="nav-link">Gizlilik</a>
                    </li>

                    <li class="nav-item">
                      <a href="index.html" class="nav-link">Koşullar ve Şartlar</a>
                    </li>

                  </ul>

                </div>

              </div>

            </nav>
          </footer>
      </div>
    </div>
  </div>
</template>

<script></script>

<style scoped>
.card ul a {

	text-decoration: none;
	color:black;
}
</style>
