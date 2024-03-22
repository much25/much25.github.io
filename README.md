<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Profil - Muchdor Bafaqih</title>
 
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">

  
  <style>
   

 
    .navbar {
      padding: 1rem 0;
    }

    .navbar-brand {
      font-size: 1.5rem;
    }

    .nav-link {
      font-size: 1.1rem;
    }

  
    section {
      padding: 4rem 0;
    }

    
    #home {
      background-color: #f8f9fa;
    }

   
    #about {
      background-color: #e9ecef;
    }

   
    #experience {
      background-color: #dee2e6;
    }

  
    #education {
      background-color: #ced4da;
    }

    #contact {
      background-color: #adb5bd;
    }

 
    h1, h2, h3, h4, h5, h6 {
      margin-bottom: 1.5rem;
    }

    p {
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .container {
      max-width: 960px;
      margin: 0 auto;
      padding: 0 15px;
    }

   
    @media (max-width: 768px) {
      .navbar-brand {
        font-size: 1.3rem;
      }
      .nav-link {
        font-size: 1rem;
      }
    }
  </style>
  
</head>
<style>
  .contact-icon {
      font-size: 34px;
  }
</style>

<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container">
      <a class="navbar-brand" href="#">Profil</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Beranda</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">Profil</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#experience">Pengalaman</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#education">Pendidikan</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Kontak</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Home Section -->
  <section id="home" class="py-5" style="background-image: url('keren.avif');">
    <div class="container">
        <h1 id="welcome" style="color: blue;">Selamat Datang di Profil Saya</h1>


   <div class="profile-pic-container">
            <img src="cipung.jpeg" alt="Foto Profil" class="img-fluid rounded profile-pic">
        </div>
    </div>

  <style>
        /* Animasi teks */
        @keyframes moveText {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(100%);
            }
        }

        
        #welcome {
            position: relative;
            animation: moveText 10s linear infinite; 
        }


        .profile-pic-container {
            width: 220px;
            height: 220px;
            overflow: hidden;
            border: 2px solid transparent;
            border-radius: 50%;
            transition: all 0.3s ease;
        }

        .profile-pic-container:hover {
            border-color: white;
        }

        .profile-pic {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
        }
    </style>
</section>

  </section>


  <section id="about" class="py-5">
    <div class="container">
      <h2>Tentang Saya</h2>
      <div class="row">
        <div class="col-md-4">
         
          
 </div>
        <div class="col-md-8">
          <p>
            Nama saya Muchdor Bafaqih. Saya lahir di Jombang pada 25 Mei 2004. Saat ini, saya sedang menempuh kuliah di Universitas Hasyim Asy'ari dengan fokus pada keahlian dalam coding. Saya memiliki minat yang besar dalam bidang pengembangan perangkat lunak dan senang mempelajari hal-hal baru seputar teknologi. Selain itu, saya aktif mengikuti berbagai
             kursus online untuk meningkatkan keterampilan saya dalam pemrograman dan pengembangan web.</p>
        </div>
      </div>
    </div>
  </section>


  <section id="experience" class="py-5">
    <div class="container">
      <h2>Pengalaman</h2>
      <p class="section-text">software engineer</p>
    </div>
  </section>

  <section id="education" class="py-5">
    <div class="container">
      <h2>Pendidikan</h2>
      <p class="section-text">Universitas Hasyim Asy'ari
        Bachelor of Science in Computer Science
    </p>
    </div>
  </section>


  <section id="contact" class="py-5">
    <div class="container">
        <h2>Kontak</h2>
        <div class="contact-item">
            <i class="fab fa-whatsapp contact-icon"></i>
            <a href="https://wa.me/6285812016289" target="_blank">WhatsApp</a>
        </div>
        <div class="contact-item">
            <i class="fab fa-instagram contact-icon"></i>
            <a href="https://www.instagram.com/muchdorbfq/" target="_blank">Instagram</a>
        </div>
        <div class="contact-item">
            <i class="fab fa-tiktok contact-icon"></i>
            <a href="https://www.tiktok.com/@zeeta000" target="_blank">TikTok</a>
        </div>
        <div class="contact-item">
            <i class="far fa-envelope contact-icon"></i>
            <a href="mailto:muchdorbfq@gmail.com">muchdorbfq@gmail.com</a>
        </div>
    </div>
</section>

</section>


 
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
