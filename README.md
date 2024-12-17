@primaryClr: #fed75a; 
@pacman-zise: 70px;

body {
  background: #1d1d1d;
  height: 100%;
}

.pac-man {
  border-radius: 50%;
  margin: 0 auto;
  margin-top: 5em;
  border-radius: 100em 100em 0 0;
  background: #f00;
  transform-origin: bottom;
  animation: eating-top .5s infinite;
  
  &, &::before {
    width: @pacman-zise;
    height: calc(@pacman-zise/2);
    background: @primaryClr;
  }
  
  &::before {
    content: '';
    display: block;
    margin-top: calc(@pacman-zise/2);
    position: absolute;
    transform-origin: top;
    border-radius: 0 0 100em 100em;
    transform: rotate(80deg);
    animation: eating-bottom .5s infinite;
  }
  
  &::after {
    position: absolute;
    border-radius: 100em;
    content: '';
    display: block;
    height: 20px;
    width: 20px;
    margin-top: calc((@pacman-zise / 2) - 10px);
    margin-left: calc((@pacman-zise / 2) - 10px);
    transform-origin: center;
    animation: 
      center .5s infinite,
      ball .5s -.33s infinite linear;
  }
}

@keyframes eating-top{
  0%{ transform: rotate(-40deg); }
  50% { transform: rotate(0deg); }
  100%{ transform: rotate(-40deg); }
}

@keyframes eating-bottom{
  0%{ transform: rotate(80deg); }
  50% { transform: rotate(0deg); }
  100%{ transform: rotate(80deg); }
}

@keyframes center{
  0%{ transform: rotate(40deg); }
  50% { transform: rotate(0deg); }
  100%{ transform: rotate(40deg); }
}

@keyframes ball{
  0%{ 
    opacity: .7;
    box-shadow: 
      70px 0 0 0 @primaryClr,
      120px 0 0 0 @primaryClr,
      170px 0 0 0 @primaryClr,
      220px 0 0 0 @primaryClr
    ;
  }
  100% { 
    box-shadow: 
      20px 0 0 0 @primaryClr,
      70px 0 0 0 @primaryClr,
      120px 0 0 0 @primaryClr,
      170px 0 0 0 @primaryClr
    ;
  }
  
}
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Press+Start+2P&size=30&duration=4000&pause=1000&color=33FF99¢er=true&vCenter=true&width=1000&lines=Hello%2C+I'm+Muhammad+Rafi;Full+Stack+Developer;Always+Learning+New+Things"/>
</div>



# 💫 About Me
🔭 I'm currently working on AI-powered and API development  
👯 I'm looking to collaborate on open source projects  
💬 Ask me about Bot Development, API Integration, and Full Stack Development  
📫 Reach me at: [portofolio.mrfh.site](https://portofolio.mrfh.site/)  
🌍 Based in Jakarta, Indonesia  
🔒 Note: Some projects are private due to privacy concerns or company policies. Reach out if you'd like to know more!

## 💻 Languages

![Python](https://img.shields.io/badge/-Python-000?style=for-the-badge&logo=Python)
![JavaScript](https://img.shields.io/badge/-JavaScript-000?style=for-the-badge&logo=JavaScript)
![Java](https://img.shields.io/badge/-Java-000?style=for-the-badge&logo=Java&logoColor=007396)
![TypeScript](https://img.shields.io/badge/-TypeScript-000?style=for-the-badge&logo=TypeScript)
![C++](https://img.shields.io/badge/-C++-000?style=for-the-badge&logo=c%2b%2b&logoColor=00599C)
![SQL](https://img.shields.io/badge/-SQL-000?style=for-the-badge&logo=MySQL)
![PHP](https://img.shields.io/badge/PHP-000?style=for-the-badge&logo=php&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-000?style=for-the-badge&logo=dart&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-000?style=for-the-badge&logo=Swift)
![.NET](https://img.shields.io/badge/-.NET%208.0-000?style=for-the-badge&logo=dotnet)
![Kotlin](https://img.shields.io/badge/-Kotlin-000?style=for-the-badge&logo=kotlin)

## 🛠 Tech Stack

### Frontend Development
![React](https://img.shields.io/badge/-React-000?style=for-the-badge&logo=React)
![Next.js](https://img.shields.io/badge/-Next.js-000?style=for-the-badge&logo=next.js)
![Vue.js](https://img.shields.io/badge/-Vue.js-000?style=for-the-badge&logo=vue.js)
![Redux](https://img.shields.io/badge/-Redux-000?style=for-the-badge&logo=redux)
![Tailwind](https://img.shields.io/badge/Tailwind-000?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Material UI](https://img.shields.io/badge/Material%20UI-000?style=for-the-badge&logo=mui&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-000?style=for-the-badge&logo=bootstrap)

### Backend Development
![Node.js](https://img.shields.io/badge/-Node.js-000?style=for-the-badge&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-000?style=for-the-badge&logo=express&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-000?style=for-the-badge&logo=laravel&logoColor=white)
![Spring](https://img.shields.io/badge/-Spring-000?style=for-the-badge&logo=Spring)
![FastAPI](https://img.shields.io/badge/-FastAPI-000?style=for-the-badge&logo=fastapi)

### Database & Cloud
![AWS](https://img.shields.io/badge/-AWS-000?style=for-the-badge&logo=Amazon-AWS&logoColor=F90)
![MongoDB](https://img.shields.io/badge/-MongoDB-000?style=for-the-badge&logo=mongodb)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-000?style=for-the-badge&logo=postgresql)
![Redis](https://img.shields.io/badge/-Redis-000?style=for-the-badge&logo=Redis)
![Firebase](https://img.shields.io/badge/-Firebase-000?style=for-the-badge&logo=firebase)
![Supabase](https://img.shields.io/badge/-Supabase-000?style=for-the-badge&logo=supabase)

### DevOps & Tools
![Docker](https://img.shields.io/badge/-Docker-000?style=for-the-badge&logo=Docker)
![Linux](https://img.shields.io/badge/-Linux-000?style=for-the-badge&logo=Linux)
![Git](https://img.shields.io/badge/-Git-000?style=for-the-badge&logo=git)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-000?style=for-the-badge&logo=github-actions)

### AI/ML

![TensorFlow](https://img.shields.io/badge/-TensorFlow-000?style=for-the-badge&logo=TensorFlow)
![PyTorch](https://img.shields.io/badge/-PyTorch-000?style=for-the-badge&logo=pytorch)
![OpenAI](https://img.shields.io/badge/-OpenAI-000?style=for-the-badge&logo=openai)
![Google Gemini](https://img.shields.io/badge/-Google%20Gemini-000?style=for-the-badge&logo=google&logoColor=4285F4)
![Claude](https://img.shields.io/badge/-Claude%20AI-000?style=for-the-badge&logo=anthropic&logoColor=white)
![LLaMA](https://img.shields.io/badge/-LLaMA-000?style=for-the-badge&logo=meta&logoColor=white)

## 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=muhammadrafihq&show_icons=true&theme=gotham&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=muhammadrafihq&layout=compact&langs_count=7&theme=gotham"/>
</div>


## 🔍 Where to find me

<div align="center">
  <a href="https://github.com/muhammadrafihq" target="_blank">
    <img src="https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white" alt=github style="margin-bottom: 5px;" />
  </a>
  <a href="https://linkedin.com/in/muhammadrafihq" target="_blank">
    <img src="https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt=linkedin style="margin-bottom: 5px;" />
  </a>
  <a href="https://portofolio.mrfh.site/" target="_blank">
    <img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="website" style="margin-bottom: 5px;" />
  </a>
</div>

<div class='pac-man' />



