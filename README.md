
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shourya Patil | Personal Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Segoe UI',sans-serif;
    background:linear-gradient(-45deg,#0f172a,#1e293b,#0ea5e9,#2563eb);
    background-size:400% 400%;
    animation:gradientBG 12s ease infinite;
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.container{
    max-width:850px;
    width:100%;
    background:rgba(255,255,255,0.12);
    backdrop-filter:blur(15px);
    border:1px solid rgba(255,255,255,0.2);
    border-radius:20px;
    padding:40px;
    color:white;
    box-shadow:0 8px 30px rgba(0,0,0,0.3);
    animation:fadeUp 1s ease;
}

.header{
    text-align:center;
    margin-bottom:35px;
}

.profile-pic{
    width:120px;
    height:120px;
    margin:auto;
    border-radius:50%;
    background:linear-gradient(135deg,#38bdf8,#2563eb);
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:48px;
    font-weight:bold;
    margin-bottom:20px;
    animation:float 3s ease-in-out infinite;
}

.header h1{
    font-size:3rem;
    margin-bottom:10px;
    animation:slideDown 1s ease;
}

.header p{
    color:#dbeafe;
    font-size:1.1rem;
}

section{
    margin:25px 0;
    animation:fadeIn 1.2s ease;
}

h2{
    margin-bottom:15px;
    color:#7dd3fc;
    position:relative;
}

h2::after{
    content:"";
    position:absolute;
    left:0;
    bottom:-5px;
    width:60px;
    height:3px;
    background:#38bdf8;
    border-radius:10px;
}

.intro{
    line-height:1.8;
    color:#e2e8f0;
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:15px;
}

.skill{
    padding:12px 22px;
    background:rgba(255,255,255,0.15);
    border-radius:30px;
    transition:.3s;
    cursor:pointer;
}

.skill:hover{
    transform:translateY(-5px) scale(1.05);
    background:#0ea5e9;
}

.contact{
    display:grid;
    gap:12px;
}

.contact-item{
    background:rgba(255,255,255,0.12);
    padding:15px;
    border-radius:12px;
    transition:.3s;
}

.contact-item:hover{
    transform:translateX(10px);
    background:rgba(14,165,233,0.4);
}

footer{
    margin-top:30px;
    text-align:center;
    color:#cbd5e1;
}

/* Animations */

@keyframes gradientBG{
    0%{background-position:0% 50%;}
    50%{background-position:100% 50%;}
    100%{background-position:0% 50%;}
}

@keyframes fadeUp{
    from{
        opacity:0;
        transform:translateY(40px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@keyframes slideDown{
    from{
        opacity:0;
        transform:translateY(-40px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

@keyframes fadeIn{
    from{opacity:0;}
    to{opacity:1;}
}

@keyframes float{
    0%,100%{
        transform:translateY(0);
    }
    50%{
        transform:translateY(-12px);
    }
}

@media(max-width:768px){
    .header h1{
        font-size:2.2rem;
    }

    .container{
        padding:25px;
    }
}
</style>
</head>
<body>

<div class="container">

    <div class="header">
        <div class="profile-pic">SP</div>
        <h1>Shourya Patil</h1>
        <p>Aspiring Software Developer & Technology Enthusiast</p>
    </div>

    <section>
        <h2>Introduction</h2>
        <p class="intro">
            Hello! I'm Shourya Patil, a passionate programmer who enjoys
            learning new technologies and building innovative projects.
            I love solving real-world problems through code and continuously
            improving my skills in software development.
        </p>
    </section>

    <section>
        <h2>Skills</h2>
        <div class="skills">
            <div class="skill">Java</div>
            <div class="skill">Python</div>
            <div class="skill">C++</div>
        </div>
    </section>

    <section>
        <h2>Contact Details</h2>
        <div class="contact">
            <div class="contact-item">📧 shouryapatil069@gmail.com</div>
            <div class="contact-item">📱 +91 9960049208</div>
        </div>
    </section>

    <footer>
        © 2026 Shourya Patil • Personal Portfolio Website
    </footer>

</div>

</body>
</html>

