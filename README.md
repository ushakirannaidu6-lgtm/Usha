# Usha
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Usha Kiran Naidu| Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background: linear-gradient(135deg,#0f172a,#1e293b,#0f172a);
    color:white;
    scroll-behavior:smooth;
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    position:fixed;
    width:100%;
    top:0;
    backdrop-filter: blur(12px);
    background:rgba(30,41,59,0.6);
    z-index:1000;
}

nav h2{
    color:#38bdf8;
    font-weight:700;
}

nav ul{
    list-style:none;
    display:flex;
    gap:30px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-weight:500;
    transition:0.3s;
}

nav ul li a:hover{
    color:#38bdf8;
}

/* Hero Section */
.hero{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    gap:60px;
    padding:0 8%;
}

.profile-pic{
    width:260px;
    height:260px;
    border-radius:50%;
    object-fit:cover;
    border:5px solid #38bdf8;
    box-shadow:0 0 40px rgba(56,189,248,0.5);
    transition:0.4s;
}

.profile-pic:hover{
    transform:scale(1.05);
}

.hero-text h1{
    font-size:50px;
}

.hero-text span{
    color:#38bdf8;
}

.hero-text p{
    margin-top:15px;
    font-size:20px;
    opacity:0.8;
}

/* Download Button */
.btn{
    display:inline-block;
    margin-top:25px;
    padding:12px 28px;
    background:#38bdf8;
    color:black;
    border:none;
    border-radius:30px;
    cursor:pointer;
    font-weight:600;
    transition:0.3s;
    box-shadow:0 10px 25px rgba(56,189,248,0.3);
    text-decoration:none;
}

.btn:hover{
    background:white;
    transform:translateY(-3px);
}

/* Sections */
section{
    padding:100px 8%;
}

section h2{
    text-align:center;
    margin-bottom:50px;
    color:#38bdf8;
    font-size:32px;
}

/* About */
.about{
    text-align:center;
    max-width:800px;
    margin:auto;
    line-height:1.8;
    font-size:18px;
    opacity:0.85;
}

/* Skills */
.skills-container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:25px;
}

.skill{
    background:rgba(255,255,255,0.05);
    padding:25px;
    border-radius:15px;
    width:170px;
    text-align:center;
    backdrop-filter:blur(10px);
    transition:0.4s;
    border:1px solid rgba(255,255,255,0.1);
}

.skill:hover{
    transform:translateY(-8px);
    background:#38bdf8;
    color:black;
}

/* Projects */
.projects-container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:30px;
}

.project{
    background:rgba(255,255,255,0.05);
    padding:30px;
    border-radius:15px;
    backdrop-filter:blur(10px);
    transition:0.4s;
    border:1px solid rgba(255,255,255,0.1);
}

.project:hover{
    transform:scale(1.05);
    background:#1e40af;
}

.project h3{
    margin-bottom:10px;
}

/* Footer */
footer{
    text-align:center;
    padding:25px;
    background:rgba(30,41,59,0.8);
    margin-top:60px;
}

/* Responsive */
@media(max-width:900px){
    .hero{
        flex-direction:column;
        text-align:center;
    }

    .hero-text h1{
        font-size:36px;
    }

    .profile-pic{
        width:200px;
        height:200px;
    }
}

</style>
</head>
<body>

<nav>
    <h2>Appikatla.Usha Kiran Naidu </h2>
    <ul>
        <li><a href="about.html">About</a></li>
        <li><a href="skills.html">Skills</a></li>
        <li><a href="contact_me.html">Contact</a></li>
        
    </ul>
</nav>

<!-- Hero -->
<div class="hero">
    <img src="9067b8bf-64b1-43ba-8d79-398b2d56c597.png" class="profile-pic" alt="Profile Picture">

    <div class="hero-text">
        <h1>Hi, I'm <span>Usha Kiran Naidu</span></h1>
        <p>soft skills Developer | Technical Educator</p>

        <!-- DIRECT DOWNLOAD ENABLED -->
        <a href="Usha Kiran " download="Siva_Raghu_Resume.pdf" class="btn">
            <i class="fa fa-download"></i> Download Resume
        </a>

    </div>
</div>
<footer>
    © 2026 Usha Kiran| All Rights Reserved
</footer>

</body>
</html>
<img width="1881" height="901" alt="Screenshot 2026-03-03 225148" src="https://github.com/user-attachments/assets/6775b879-8128-46b1-8ccc-313f13637eaa" />
