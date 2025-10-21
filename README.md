[students.html](https://github.com/user-attachments/files/23019478/students.html)
[gallery.html](https://github.com/user-attachments/files/23019482/gallery.html)[index.html](https://github.com/user-attachments/files/23019485/index.html)
[achievements.html](https://github.com/user-attachments/files/23019484/achievements.html)
[news.html](https://github.com/user-attachments/files/23019483/news.html)
[style.css](https://github.com/user-attachments/files/23019500/style.css)
/* ===== GENERAL STYLES ===== */
body {
  font-family: "Poppins", sans-serif;
  margin: 0;
  background-color: #fafafa;
  color: #333;
  line-height: 1.6;
}

/* ===== HEADER ===== */
header {
  background-color: #fff8e1;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 60px;
  border-bottom: 1px solid #ddd;
  flex-wrap: wrap;
}

.logo {
  font-weight: bold;
  font-size: 1.3em;
  color: #002366;
}

nav a {
  text-decoration: none;
  color: #002366;
  margin: 0 15px;
  font-weight: 500;
}

nav a.active,
nav a:hover {
  color: #f57c00;
}

/* ===== HERO SECTION ===== */
.hero {
  height: 60vh;

  /* 🔹 PLACE YOUR HERO BACKGROUND IMAGE BELOW */
  background-image: url("images/hero-bg.jpg"); /* Example: a school campus or group of students */
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  color: white;
  text-shadow: 0 2px 6px rgba(0,0,0,0.5);
  text-align: center;
  padding: 0 20px;
}

.hero h1 {
  font-size: 2.5em;
  margin: 0;
}

.hero p {
  font-size: 1.2em;
}

.btn {
  background-color: #002366;
  color: white;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  margin-top: 15px;
  display: inline-block;
}

.btn:hover {
  background-color: #f57c00;
}

/* ===== CONTENT SECTION ===== */
.content {
  text-align: center;
  padding: 50px 20px;
  max-width: 1000px;
  margin: auto;

  /* 🔹 OPTIONAL BACKGROUND IMAGE for this section */
  /* background-image: url("images/content-bg.jpg"); */
  /* background-size: cover;
  background-position: center;
  background-repeat: no-repeat; */
}

.image-slot {
  margin-top: 30px;
}

.image-slot img {
  width: 100%;
  max-width: 700px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

/* ===== GRID SECTION (Achievements, Students, Gallery, News) ===== */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
  padding: 40px 60px;
  justify-items: center;

  /* 🔹 OPTIONAL BACKGROUND IMAGE for cards section */
  /* background-image: url("images/achievements-bg.jpg"); */
  /* background-size: cover;
  background-position: center;
  background-repeat: no-repeat; */
}

.card {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  overflow: hidden;
  max-width: 320px;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card img,
.card video {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.card h3 {
  margin: 15px 0 5px;
  color: #002366;
}

.card p {
  padding: 0 15px 20px;
  font-size: 0.95em;
}

.card:hover {
  transform: translateY(-5px);
  box-shadow: 0 6px 14px rgba(0,0,0,0.15);
}

/* ===== NEWS SECTION ===== */
.news-item {
  background-color: white;
  margin: 20px auto;
  padding: 20px;
  max-width: 900px;
  border-radius: 10px;
  box-shadow: 0 3px 8px rgba(0,0,0,0.1);
  text-align: left;
  display: flex;
  flex-wrap: wrap;
  gap: 20px;

  /* 🔹 OPTIONAL BACKGROUND IMAGE for the news area */
  /* background-image: url("images/news-bg.jpg"); */
  /* background-size: cover;
  background-position: center;
  background-repeat: no-repeat; */
}

.news-item img {
  width: 250px;
  height: 180px;
  border-radius: 10px;
  object-fit: cover;
}

.news-item h3 {
  color: #002366;
  margin: 0;
}

/* ===== FOOTER ===== */
footer {
  text-align: center;
  background-color: #002366;
  color: white;
  padding: 15px 0;
  margin-top: 40px;
  font-size: 0.9em;

  /* 🔹 OPTIONAL FOOTER BACKGROUND IMAGE (texture or school logo pattern) */
  /* background-image: url("images/footer-bg.jpg"); */
  /* background-size: cover;
  background-position: center;
  background-repeat: no-repeat; */
}

/* ===== RESPONSIVE DESIGN ===== */
@media (max-width: 768px) {
  header {
    flex-direction: column;
    padding: 20px;
  }

  nav {
    margin-top: 10px;
  }

  .hero {
    height: 50vh;
    padding: 20px;
  }

  .hero h1 {
    font-size: 2em;
  }

  .grid {
    padding: 20px;
  }

  .news-item {
    flex-direction: column;
    text-align: center;
    align-items: center;
  }

  .news-item img {
    width: 100%;
    height: auto;
  }
}

![r](https://github.com/user-attachments/assets/5c289859-0be5-424c-b1b9-50fe06ffafce)
![d](https://github.com/user-attachments/assets/597be755-710c-4dd2-841f-695a905d0388)
![DSC_0110](https://github.com/user-attachments/assets/83ccb080-fc55-449b-bfbb-8af073762f60)
![IMG_6849](https://github.com/user-attachments/assets/be573e94-83fc-4afe-95d9-09375f7d7fc6)
![l](https://github.com/user-attachments/assets/8c9b0884-1204-4e69-9829-1e7c3ddc151c)
![h](https://github.com/user-attachments/assets/e542749a-c4bf-4496-9d82-684e060d383f)
![o](https://github.com/user-attachments/assets/af697e8e-b1ab-4ebd-a386-fd1708215507)
![images](https://github.com/user-attachments/assets/cd391167-0abc-46da-998e-e1bb710ae4bd)
![ll](https://github.com/user-attachments/assets/f088102b-8e11-4630-9bf9-ba5dbc614c7a)
![j](https://github.com/user-attachments/assets/286c9060-1760-4e3f-a332-27a2f440ff1a)
![jk](https://github.com/user-attachments/assets/acf1f92c-f880-4dfe-8718-9e44c060a11a)
![download](https://github.com/user-attachments/assets/be6a5419-8046-449a-b387-4052e88d676a)
![news-bg](https://github.com/user-attachments/assets/843732de-2244-4d12-abf9-63d1da55050a)
