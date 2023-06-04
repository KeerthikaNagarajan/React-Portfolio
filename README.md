# React-Portfolio
## PROGRAM:
### App.js:
```
import React from 'react';
import './App.css'

function App() {
  return (
    <div className="App">
      <header className="header">
        <img src={ require("./logo.png")} alt="logo" width="14%"></img>
        <nav>
          <ul className="top-nav">
            <li><a href="#about"><b>About</b></a></li>
            <li><a href="#education"><b>Education</b></a></li>
            <li><a href="#skills"><b>Skills</b></a></li>
            <li><a href="#intern"><b>Internship</b></a></li>
            <li><a href="#contact"><b>Contact</b></a></li>
          </ul>
        </nav>
        <br></br>
      </header>
      <main>
        <section>
          <div className="container">
          <div className="image-container">
            <img src={ require("./photo.jpg")} alt="keerthika" width="20%" className="center-image" />
          </div>
            <h4>Keerthika Nagarajan<br></br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;STUDENT</h4>
          </div>
        </section>
        <section id="about" className="section card">
          <h2>About Me</h2>
          <p>As an Artificial Intelligence and Data Science student, my career objective is to utilize my skills,
             knowledge, and expertise to make a significant contribution to the field of AI and data science. 
             I aspire to work in a challenging and dynamic environment that fosters creativity and innovation, 
             where I can apply my expertise in machine learning, data analysis, and predictive modeling to solve 
             complex real-world problems.</p>
             <br/>
            <p> My ultimate goal is to become a leading expert in the field of AI and data science and to contribute
             to the development of cutting-edge technologies that can revolutionize the way we live and work. 
             I am passionate about exploring the limitless possibilities of AI and data science, and I am committed
             to continuously learning and improving my skills to stay at the forefront of this rapidly evolving field.</p>
             <br/>
             <p>In pursuit of my career objectives, I aim to work with diverse teams of experts in AI and data science 
             to collaborate on exciting projects that push the boundaries of what is possible. I am driven by the desire
             to make a positive impact on society and to use my skills to create meaningful solutions that can improve 
             people's lives.</p>
        </section>
        <section id="education" className="section card skills-card">
          <h2>Education</h2>
          <div className="card">
          <ul>
            <li><b>Saveetha Engineering College</b></li>
            <p>Bachelor in Artificial Intelligence & Data Science<br></br>2022-2025</p>
            </ul>
          </div>
          <div className="card"> 
          <ul>
            <li><b>S.B.O.A Matric. & Hr. Sec. School</b></li>
            <p>SSLC<br></br>2018-2019</p>
            </ul>
          </div>
          <div className="card">
            <ul>
            <li><b>S.B.O.A Matric. & Hr. Sec. School</b></li>
            <p>HSC<br></br>2020-2021</p>
            </ul>
          </div>
        </section>
        <section id="skills" className="section card skills-section">
          <h2>Skills</h2>
          <div className="skills-cards">
            <div className="skills-card">
              <div className="card">
          <ul>
            <li>C Programming</li>
            <li>Python</li>
            <li>Java</li>
            <li>JavaScript</li>
            <li>HTML/CSS</li>
            <li>React JS</li>
          </ul>
          </div>
          </div>
          <div className="skills-card">
            <div className="card">
          <ul>
            <li>Product Development</li>
            <li>3D Printing</li>
            <li>Digital Image Processing</li>
            <li>Project Management</li>
            <li>Data Science</li>
            <li>Complex Problem Solver</li>
          </ul>
          </div>
          </div>
          </div>
        </section>
        <section id="intern" className="section card skills-card">
          <h2>Internship</h2>
          <div className="card">
          <ul>
            <li><b>Monolith Technologies</b></li>
            <p>Virtual Reality</p>
          </ul>
          </div>
          <div className="card">
          <ul>
            <li><b>Technook</b></li>
            <p>Artificial Intelligence</p>
            </ul>
          </div>
        </section>
        <section id="contact" className="section card skills-card">
          <h2>Contact Information</h2>
          <div className="card">
          <p><b>Address:</b>
          <br></br>
            M-5, M Block, 2nd Street, Agathiar Nagar,
            Villivakkam, Chennai - 600049</p>
            </div>
            <div className="card">
          <p><b>Email:</b>
          <br></br>
            nkeerthi2004@gmail.com</p>
            </div>
            <div className="card">
          <p><b>Phone:</b>
          <br></br>
            7094248484</p>
            </div>
        </section>
      </main>
      <footer>
      <div>
      <a href="https://www.linkedin.com/in/keerthikanagarajan/"><img src={ require("./linked.png")} alt="linkedin" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://github.com/KeerthikaNagarajan"><img src={ require("./git.png")} alt="github" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://www.instagram.com/keerthika.nagarajan/"><img src={ require("./insta.png")} alt="instagram" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://www.snapchat.com/add/keerthikan2004?share_id=y97ne9PaQxy5jzdk3Olj5Q&locale=en_IN"><img src={ require("./snap.png")} alt="snapchat" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://twitter.com/nkeerthika2004"><img src={ require("./twitter.png")} alt="twitter" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://in.pinterest.com/keerthikanagarajan/"><img src={ require("./pintrest.png")} alt="pintrest" width="30"/></a>
      &nbsp;&nbsp;
      <a href="https://www.facebook.com/KeerthikaNagarajan2004/"><img src={ require("./face.png")} alt="facebook" width="30"/></a>
      </div>
        <p>&copy; 2023 My Portfolio</p>
      </footer>
    </div>
  );
}

export default App;
```
### App.css:
```
.App {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  background-color: #EFE2BA;
  
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #C5CBE3;
  color: #000000;
  padding: 10px;
}

.top-nav {
  list-style-type: none;
  padding: 0;
  display: flex;
  padding-left: 300px;
}

.top-nav li {
  padding-left: 40px;
}

.top-nav a {
  color: #000000;
  text-decoration: none;
}

h1 {
  margin: 0;
}

h2{
  text-align: center;

}

main {
  flex: 1;
  padding: 50px;
}

.card {
  background-color: #d79822ca;
  border-radius: 10px;
  box-shadow: 2px 4px 8px #F13C20;
  padding: 10px;
  transition: transform 0.4s ease-in-out;
  padding-left: 90px;
  padding-right: 90px;
  margin-bottom: 30px;
  margin-left: 40px ;
  margin-right: 40px;
}

.card:hover {
  transform: translateY(-6px);
}

.card-section {
  flex: 1;
}

.section-title {
  text-align: center;
}

.contact-info {
  display: flex;
}

.contact-info div {
  flex: 1;
}

footer {
  background-color: #C5CBE3;
  color: #000000;
  padding: 20px;
  text-align: center;
}



.container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.image-container {
  display: flex;
  justify-content: center;
}

.center-image {
  text-align: center;
  border-radius: 30px;
  
}




.skills-section {
  text-align: center;
}

.skills-section h2 {
  margin-bottom: 20px;
}

.skills-cards {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.skills-card {
  flex: 0 0 calc(50% - 10px);
  margin: 0 5px;
  margin-bottom: 20px;
}

@media (max-width: 768px) {
  .skills-card {
    flex: 0 0 100%;
  }
}

.skills-card .card {
  background-color: #ffc3c3;
  border-radius: 10px;
  box-shadow: 0 2px 4px #F13C20;
  padding: 20px;
  transition: transform 0.4s ease-in-out;
}

ul {
  list-style: none;
  padding: 0;
}
```
## OUTPUT:

![1](https://github.com/KeerthikaNagarajan/React-Portfolio/assets/93427089/08fc7f09-e8f7-4206-bfad-152c041569c6)
![2](https://github.com/KeerthikaNagarajan/React-Portfolio/assets/93427089/a01ab725-b49f-4150-936c-4e09ccf540fe)
