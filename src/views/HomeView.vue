<template>
<body>
<div>
  <b-navbar toggleable="lg" class="shadow fixed-top" type="light" variant="light">
    <b-container>
    <b-navbar-brand href="#">
      <img width="51" height="40" src="https://kerjoo.com/wp-content/themes/kerjootheme-v2/assets/img/logo-kerjoo-1.svg" alt="Logo">
      <img class="ml-2" width="109" height="40" src="https://kerjoo.com/wp-content/themes/kerjootheme-v2/assets/img/logo-kerjoo-2.svg" alt="Kerjoo">
      </b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ms-auto">
        <b-nav-item ><strong class="me-3 text-black">Fitur</strong></b-nav-item>
        <b-nav-item class="me-3 "><strong class="text-black">Harga</strong></b-nav-item>
        <b-nav-item class="me-3 "><strong class="text-black">FAQ</strong></b-nav-item>
        <b-nav-item class="me-3 "><strong class="text-black">Blog</strong></b-nav-item>
        <b-nav-item class="me-3 "><b-icon icon="box-arrow-in-right" variant="success" aria-hidden="true"></b-icon><strong class="ms-2 text-black">Masuk</strong></b-nav-item>
        <b-button size="sm" variant="success" pill class="me-3">
          <b-icon icon="person-bounding-box" aria-hidden="true"></b-icon> Daftar Gratis
        </b-button>
      </b-navbar-nav>
    </b-collapse>
    </b-container>
  </b-navbar>
  <b-container class="mt-5">
  <carousel :responsive="{600:{items:1, nav:false,dots:true, autoplay:true}}" class="mt-5">
      <div>
        <div class="card mt-5 border-0">
          <div class="card-body">
            <b-row class="mt-5 mb-5">
              <b-col cols="12" md="5">
                <img class="d-block img-fluid w-100" src="https://i.postimg.cc/zDRjfHH4/Online-world-bro.png" alt="image slot">
              </b-col>
              <b-col cols="12" md="7">
                <h2 class="text-black"><strong>Aplikasi Absensi Online Untuk Karyawan</strong></h2>
                <p class="lead text-justify">Aplikasi absensi online Kerjoo dirancang untuk memberikan kemudahan bagi perusahaan, agar bisa meningkatkan kinerja karyawan yang bekerja di kantor maupun yang bekerja secara remote atau WFH (Work From Home). Dengan Kerjoo, perusahaan bisa lebih fokus kepada hal yang lebih penting. Dalam jangka panjang, perusahaan bisa menghemat sampai ratusan juta.</p>
              </b-col>
            </b-row>
          </div>
        </div>
      </div>
      <div>
        <div class="card mt-5 border-0">
          <div class="card-body">
            <b-row class="mt-5 mb-5">
              <b-col cols="12" md="5">
                <img class="d-block img-fluid w-100" src="https://i.postimg.cc/J0FF1j2P/Digital-transformation-pana.png" alt="image slot">
              </b-col>
              <b-col cols="12" md="7">
                <h2 class="text-black"><strong>Fitur Terbaik Untuk Mengelola Kinerja Karyawan</strong></h2>
                <p class="lead text-justify">Kinerja karyawan yang baik tidak terlepas dari pengelolaan yang optimal dari perusahaan. Fitur-fitur terbaik yang dimiliki aplikasi absensi Kerjoo ini memudahkan perusahaan dalam memaksimalkan kinerja karyawan.</p>
                <div class="mt-3"><svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check-circle text-warning" viewBox="0 0 16 16">
                  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                  <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"/>
                  </svg><a class="text-decoration-none ms-2 text-dark"><Strong>Kemudahan Absensi</Strong></a>
                </div>
                <div class="mt-3"><svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check-circle text-warning" viewBox="0 0 16 16">
                  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                  <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"/>
                  </svg><a class="text-decoration-none ms-2 text-dark"><Strong>Monitor Kehadiran Karyawan</Strong></a>
                </div>
                <div class="mt-3"><svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check-circle text-warning" viewBox="0 0 16 16">
                  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                  <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"/>
                  </svg><a class="text-decoration-none ms-2 text-dark"><Strong>Face Recognition dan Identification</Strong></a>
                </div>
                <div class="mt-3"><svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check-circle text-warning" viewBox="0 0 16 16">
                  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                  <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"/>
                  </svg><a class="text-decoration-none ms-2 text-dark"><Strong>Menghemat Waktu</Strong></a>
                </div>
                <div class="mt-3"><svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check-circle text-warning" viewBox="0 0 16 16">
                  <path d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"/>
                  <path d="M10.97 4.97a.235.235 0 0 0-.02.022L7.477 9.417 5.384 7.323a.75.75 0 0 0-1.06 1.06L6.97 11.03a.75.75 0 0 0 1.079-.02l3.992-4.99a.75.75 0 0 0-1.071-1.05z"/>
                  </svg><a class="text-decoration-none ms-2 text-dark"><Strong>Jumlah Karyawan Unlimited</Strong></a>
                </div>
              </b-col>
            </b-row>
          </div>
        </div>
      </div>
  </carousel>

  <div class="text-center mt-5">
    <button type="button" class="btn btn-success">Daftar Gratis</button>
  </div>

  <div class="text-center mt-5">
    <h4><strong>Fitur Untuk Mengelola Kinerja Karyawan</strong></h4>
    <h6 class="lead"><small>Kami memahami bahwa produktivitas karyawan akan lebih optimal jika dikelola dengan baik. <br> Manfaatkan fitur terbaik aplikasi Kerjoo untuk mengelola kinerja karyawan <br> yang dilengkapi dengan laporan bulanan dalam format excel.</small></h6>
  </div>
    <div class="mt-5 mb-5">
    <b-row>
      <b-col lg="7">
          <b-carousel
            id="carousel-fade"
            fade
            class="rounded shadow mt-2"
            :interval="1600"
            img-width="1024"
            img-height="480"
          >
            <b-carousel-slide
              img-src="https://kerjoo.com/wp-content/uploads/2022/01/main-banner-1-b.jpg"
            ></b-carousel-slide>
            <b-carousel-slide
              img-src="https://kerjoo.com/wp-content/uploads/2022/01/main-banner-2-b.jpg"
            ></b-carousel-slide>
            <b-carousel-slide
              img-src="https://kerjoo.com/wp-content/uploads/2022/01/main-banner-3-b.jpg"
            ></b-carousel-slide>
          </b-carousel>
      </b-col>
      <b-col lg>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Kemudahan Absensi Secara Personal dan Lebih Higienis</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Monitor Kehadiran Karyawan di Lokasi Kerja Secara Akurat</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Face Recognition dan Identification</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Menghemat Waktu Review Kedisiplinan Karyawan</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Jumlah Karyawan Unlimited</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
        <div class="card shadow mb-2 rounded-3" style="max-height: 66px">
          <div class="card-body">
            <b-row>
              <b-col cols="2">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" fill="currentColor" class="bi bi-check2-circle text-warning" viewBox="0 0 16 16">
                    <path d="M2.5 8a5.5 5.5 0 0 1 8.25-4.764.5.5 0 0 0 .5-.866A6.5 6.5 0 1 0 14.5 8a.5.5 0 0 0-1 0 5.5 5.5 0 1 1-11 0z"/>
                    <path d="M15.354 3.354a.5.5 0 0 0-.708-.708L8 9.293 5.354 6.646a.5.5 0 1 0-.708.708l3 3a.5.5 0 0 0 .708 0l7-7z"/>
                  </svg>
                </div>
              </b-col>
              <b-col cols="10">
                <h6><strong>Memudahkan Membuat Jadwal Kerja Harian dan Shift</strong></h6>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
    </b-row>
  </div>
  <div class="text-center mt-5">
    <button type="button" class="btn btn-success">Lihat Semua Fitur</button>
  </div>
  <div class="text-center mt-5">
    <h4><strong>Panduan Penggunaan Kerjoo</strong></h4>
    <h6 class="lead"><small>Ingin tahu cara menggunakan aplikasi absensi online Kerjoo? <br> Pelajari lebih lengkap melalui video panduan di bawah ini</small></h6>
    <div class="container mt-5">
          <div class="embed-responsive embed-responsive-16by9">
            <iframe loading="lazy" title="Panduan Penggunaan Kerjoo" class="shadow" width="800" height="450" 
            src="https://www.youtube.com/embed/cjrkKkQfLIw?autoplay=1" frameborder="0" 
            allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
            </iframe>
          </div>
    </div>
  </div>
  <div class="text-center mt-5">
    <h4><strong>Mengapa Menggunakan Aplikasi Absensi Kerjoo?</strong></h4>
    <h6 class="lead"><small>Sebelum Anda memutuskan berlangganan, pahami sekali lagi manfaat yang akan Anda dapatkan setelah perusahaan menggunakan aplikasi Kerjoo.</small></h6>
  </div>
  <div class="mt-5">
    <b-row>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center"><svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-armchair-2 text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="currentColor" fill-opacity="0.5" stroke-linecap="round" stroke-linejoin="round">
                  <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                  <path d="M5 10v-4a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3v4"></path>
                  <path d="M16 15v-2a3 3 0 1 1 3 3v3h-14v-3a3 3 0 1 1 3 -3v2"></path>
                  <path d="M8 12h8"></path>
                  <path d="M7 19v2"></path>
                  <path d="M17 19v2"></path>
                  </svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Meningkatkan Produktivitas</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-shield-check text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="currentColor" fill-opacity="0.5" stroke-linecap="round" stroke-linejoin="round">
                  <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                  <path d="M9 12l2 2l4 -4"></path>
                  <path d="M12 3a12 12 0 0 0 8.5 3a12 12 0 0 1 -8.5 15a12 12 0 0 1 -8.5 -15a12 12 0 0 0 8.5 -3"></path>
                  </svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Lebih <br> Higienis</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="currentColor" fill-opacity="0.5" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><path d="M19.5 13.572l-7.5 7.428l-7.5 -7.428m0 0a5 5 0 1 1 7.5 -6.566a5 5 0 1 1 7.5 6.572"></path></svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Menghemat Waktu Review Karyawan</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="currentColor" fill-opacity="0.5" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"></path><polyline points="13 3 13 10 19 10 11 21 11 14 5 14 13 3"></polyline></svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Mengetahui Rencana Kerja</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                  <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                  <rect x="4" y="13" rx="2" width="4" fill-opacity="0.5" fill="currentColor" height="6"></rect>
                  <rect x="16" y="13" rx="2" width="4" fill-opacity="0.5" fill="currentColor" height="6"></rect>
                  <path d="M4 15v-3a8 8 0 0 1 16 0v3"></path>
                  <path d="M18 19a6 3 0 0 1 -6 3"></path>
                  </svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Aplikasi yang Fleksibel</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
      <b-col cols="12" md="4">
        <div class="card shadow mb-2 rounded-3">
          <div class="card-body">
            <b-row>
              <b-col cols="4">
                <div class="text-center">
                  <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-clipboard-check text-success" width="50" height="50" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="currentColor" fill-opacity="0.5" stroke-linecap="round" stroke-linejoin="round">
                  <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                  <path d="M9 5h-2a2 2 0 0 0 -2 2v12a2 2 0 0 0 2 2h10a2 2 0 0 0 2 -2v-12a2 2 0 0 0 -2 -2h-2"></path>
                  <rect x="9" y="3" width="6" height="4" rx="2"></rect>
                  <path d="M9 14l2 2l4 -4"></path>
                  </svg>
                </div>
              </b-col>
              <b-col cols="8">
                <h5><strong >Webhook <br> Notifikasi</strong></h5>
              </b-col>
            </b-row>
          </div>
        </div>
      </b-col>
    </b-row>
  </div>
  <div class="text-center mt-5">
    <h4><strong>Telah Diliput Oleh</strong></h4>
  </div>
  <div>
    <carousel :responsive="{0:{items:2,nav:false},600:{items:4,nav:false, dots:false, autoplay:true}}">
      <div class="mb-3 ms-n5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-bantennews.png"  style="max-height: 50px; width: auto">
      </div>
      <div class="mb-3 ms-5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-itworks.png"  style="max-height: 50px; width: auto">
      </div>
      <div class="mb-3 ms-5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-line-today.png"  style="max-height: 50px; width: auto">
      </div>
      <div class="mb-3 ms-5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-itworks.png"  style="max-height: 50px; width: auto">
      </div>
      <div class="mb-3 ms-5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-line-today.png"  style="max-height: 50px; width: auto">
      </div>
      <div class="mb-3 ms-5 me-5 text-center">
        <img src="https://kerjoo.com/wp-content/uploads/2022/01/logo-indotelko.png"  style="max-height: 50px; width: auto">
      </div>
    </carousel>
  </div>
  </b-container>
</div>
<div class="container">
  <footer class="row row-cols-5 py-5 my-5">
    <div class="col-3">
    <a class="navbar-brand" href="#">
      <img width="51" height="40" src="https://kerjoo.com/wp-content/themes/kerjootheme-v2/assets/img/logo-kerjoo-1.svg" alt="Logo">
      <img class="ml-2" width="109" height="40" src="https://kerjoo.com/wp-content/themes/kerjootheme-v2/assets/img/logo-kerjoo-2.svg" alt="Kerjoo">
    </a>
    <div class="row g-0 mt-4">
        <div class="col">
          <p class="text-muted"><small>Kerjoo adalah aplikasi untuk sistem HR yang berbasis Cloud dan SaaS, di mana salah satu fitur yang kami sediakan adalah absensi karyawan yang bisa dilakukan melalui handphone dengan menggunakan teknologi terkini secara real-time melalui sistem GPS dan sistem biometrik face recognition.</small></p>
        </div>
      </div>
    </div>
      <div class="col">
    </div>

    <div class="col-3">
      <h5><strong>Layanan</strong></h5>
      <ul class="nav flex-column">
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Harga Paket</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Cara Registrasi</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Panduan Aplikasi</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Video Tutorial</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Aplikasi Gratis</strong></a></li>
      </ul>
    </div>
    <div class="col-3">
      <h5><strong>Tentang Kami</strong></h5>
      <ul class="nav flex-column">
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Tentang Kami</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Syarat & Ketentuan</strong></a></li>
        <li class="nav-item mb-2"><a href="#" class="nav-link p-0 text-muted"><strong>Kebijakan Privasi</strong></a></li>
      </ul>
    </div>
  </footer>
</div>
</body>
</template>

<script>

import carousel from 'vue-owl-carousel'

export default {
  
  name: 'HomeView',
  components: {
   carousel
  }
}
</script>
