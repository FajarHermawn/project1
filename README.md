<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Fajar Hermawan</title>
    <link rel="stylesheet" href="css/style.css" />
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      .dark-mode {
        background-color: rgb(15, 15, 42);
        color: white;
      }
    </style>
  </head>
  <body>
    <!-- navbar -->
        <div class="px-3 py-2">
          <div class="flex justify-between items-center">
            <a href="" class="ml-5 text-white bg-black h-8 text-2xl font-bold transition-colors">FH</a>
            <div class="items-center space-x-6 flex">
              <a href="#tech-stack" class="text-gray text-sm">Tech stack</a>
              <a href="#experience" class="text-gray text-sm">Experience</a>
              <a href="#project" class="text-gray text-sm">Projects</a>
              <a
                href="https://wa.me/62895331438446"
                target="_blank"
                class="bg-green-400 rounded-lg px-4 py-2 flex items-center font-medium text-sm text-black"><img
                  src="/svg/Logo WA.png" alt="WhatsApp" class="w-7 h-auto mr-2"/>Let's Talk</a
              >
              <a
                href="cv/FH CV .pdf"
                target="_blank"
                class="bg-black text-white text-sm px-4 py-2 rounded-lg flex items-center font-medium"
              >Download CV</a>
              <button onclick="toggleDarkMode()"><img src="svg/moon-stars.svg" alt="darkmode"/></button>
            </div>
          </div>
        </div>
        <!-- hero  -->
      <div class="h-10"></div>
      <section id="hero">
  <div id="hero" class="container mx-auto px-6 py-12 ">
    <div class="flex flex-col mb-30 lg:flex-row justify-between items-center gap-8 ">
      <div class="relative w-full lg:w-1/3 flex justify-center lg:justify-start">
        <div class="relative group">
          <img src="image/IMG_6097.JPG" alt="Profile" class="relative w-64 h-64 lg:w-[320px] lg:h-[320px] rounded-xl shadow-lg ">
        </div>
      </div>
    
      <div class="w-full lg:w-2/3">
        <div class="mb-8">
          <h1 class="text-6xl font-bold mb-6">Hi, I'm Fajar 👋</h1>
          <p class="text-2xl text-gray-600 font-medium mb-6">
            Engginering &amp; Full-Stack Developer
          </p>
          <p class="text-base text-gray-400 dark:text-gray-600 leading-relaxed">
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. A ut recusandae vel veniam cupiditate dolor aut iusto debitis distinctio eius est quisquam, pariatur temporibus quidem repellendus quo illo deserunt minus!
 
          </p>
        </div>
    
        <div class="flex flex-col items-start space-y-3 mb-8">
          <div class="flex items-center space-x-2 ">
           <span class="w-5 h-5"><img src="svg/location-pin-svgrepo-com.svg" alt=""></span>
             <p class="text-gray">Jakarta, Indonesia</p>
          </div>
          <div class="flex items-center space-x-2">
            <span class="w-7 h-auto">
                <svg xmlns="http://www.w3.org/2000/svg" fill="currentColor" class="bi bi-dot" viewBox="0 0 16 16">
                 <path d="M8 9.5a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3"/>
                </svg>
            </span>
            <span class="text-gray">Available for new projects</span>
          </div>
        </div>
    
        <div class="flex items-center justify-center lg:justify-start space-x-10">
          <a href="https://wa.me/62895331438226" target="_blank" class="bg-green-400 rounded-lg px-4 py-2 flex items-center font-medium text-sm text-black">
            <img src="svg/Logo WA.png" alt="Wa" class="w-7 h-auto mr-2">
            Let's Talk
          </a>
          <a href="/cv/FH CV .pdf" target="_blank" class="bg-black text-white text-sm px-4 py-2 rounded-lg flex items-center font-medium">
            <img src="/icons/box-arrow-in-up-right.svg" alt="" class="bg-white items-center mr-2">
            Download CV
          </a>
        </div>
      </div>
    </div>  
</div>
<!-- tech stack F -->
      </section>
<section id="tech-stack">
    <div class="container mx-auto px-6 py-12">
    <div class="mb-10">
    <h2 class="text-4xl text-grey font-bold ">Tech stack - Tools i use everyday</h2>
  </div>
  <div class="tech-stack-wrapper">
<div class="tech-stack">
  <div class="picture-section">
    <img src="./svg/react.jpg" alt="">
    <span>React</span>
  </div>
  <div class="picture-section">
    <img src="/svg/next.jpg" alt="">
    <span>Next.js</span>
  </div>
  <div class="picture-section">
    <img src="/svg/net.jpg" alt="">
    <span>.Net</span>
  </div>
  <div class="picture-section">
    <img src="/svg/node.jpg" alt="">
    <span>Node js</span>
  </div>
  <div class="picture-section">
    <img src="/svg/post.jpg" alt="">
    <span>PostgreSQL</span>
  </div>
  <div class="picture-section">
    <img src="/svg/express.png" alt="">
    <span>Express js</span>
  </div>
  <div class="picture-section">
    <img src="/svg/java.jpg" alt="">
    <span>Java Script</span>
  </div>
   <div class="picture-section">
    <img src="./svg/mongo.jpg" alt="">
    <span>Mongo</span>
  </div>
  <div class="picture-section">
    <img src="/svg/github.svg" alt="">
    <span>Github</span>
  </div>
  <div class="picture-section">
    <img src="/svg/uniti.jpg" alt="">
    <span>Unity</span>
  </div>
  </div>
  </div>
</section>
<section id="experience">
    <div class="container px-6 py-12 mx-auto">
    <div class="mb-10">
    <h2 class="font-bold text-4xl">Work Experience:</h2>
    </div>
    <!-- BOX PADA WORK Experience -->
     
    <div class="bg-gray-900 p-4 rounded-lg mb-10">
        <div class="flex gap-8">
            <img src="image/Logo.png" alt="" class="rounded-lg w-15 h-10 ml-2 mt-2 ">
        <div class="justify-between flex">
         <div>
        <h3 class="font-bold text-2xl text-white">Mentor fullstack Web Developper</h3>
        <p class="text-green-500">Dumbwyas Indonesia</p>
           <ul class="list-disc text-gray-400">
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
        </ul>
        </div>
        <span class="text-gray-400 ml-80">oct 2022-present</span>
        </div> 
        </div>
    </div>
     <div class="bg-gray-900 p-4 rounded-lg mb-10">
        <div class="flex gap-8">
            <img src="image/Logo.png" alt="" class="rounded-lg w-15 h-10 ml-2 mt-2 ">
        <div class="justify-between flex">
         <div>
        <h3 class="font-bold text-2xl text-white">Mentor fullstack Web Developper</h3>
        <p class="text-green-500">Dumbwyas Indonesia</p>
           <ul class="list-disc text-gray-400">
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
        </ul>
        </div>
        <span class="text-gray-400 ml-80">oct 2022-present</span>
        </div> 
        </div>
    </div>
     <div class="bg-gray-900 p-4 rounded-lg mb-10">
        <div class="flex gap-8">
            <img src="image/Logo.png" alt="" class="rounded-lg w-15 h-10 ml-2 mt-2 ">
        <div class="justify-between flex">
         <div>
        <h3 class="font-bold text-2xl text-white">Mentor fullstack Web Developper</h3>
        <p class="text-green-500">Dumbwyas Indonesia</p>
           <ul class="list-disc text-gray-400">
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
        </ul>
        </div>
        <span class="text-gray-400 ml-80">oct 2022-present</span>
        </div> 
        </div>
    </div>
     <div class="bg-gray-900 p-4 rounded-lg mb-10">
        <div class="flex gap-8">
            <img src="image/Logo.png" alt="" class="rounded-lg w-15 h-10 ml-2 mt-2 ">
        <div class="justify-between flex">
         <div>
        <h3 class="font-bold text-2xl text-white">Mentor fullstack Web Developper</h3>
        <p class="text-green-500">Dumbwyas Indonesia</p>
           <ul class="list-disc text-gray-400">
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
            <li>Mentoring students in Full Stack Development bootcamp</li>
        </ul>
        </div>
        <span class="text-gray-400 ml-80">oct 2022-present</span>
        </div> 
        </div>
    </div>
    </div>
</section>
<section id="project">
    <div class="container px-6 py-12 mx-auto">
        <h2 class="font-bold text-4xl mb-20 text-gray-900">Projects:</h2>
        <div class="flex space-x-5">
            <div class="bg-white shadow-lg gap-10 px-2 py-4">
            <img src="image/IMG_6097.JPG" alt="">
            <h2 >Faktury</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente perspiciatis veritatis aperiam illum reiciendis velit rerum eius nulla dolor veniam! Repellendus est iste doloremque amet adipisci perferendis ea cupiditate nesciunt!</p>
        <div class="flex gap-5 mt-10 mb-2 px-1 py-2">
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Nextjs</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >PHP</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Hacker</p>
        </div>
        <div class="flex gap-6 px-2 mt-10 py-2">
        <span><img src="" alt="">Private Repository</span>
        <span><img src="" alt="">live demo</span>
        </div>
        </div>
        <div class="flex space-x-10">
            <div class="bg-white shadow-lg gap-10 px-2 py-4">
            <img src="image/IMG_6097.JPG" alt="">
            <h2 >Faktury</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente perspiciatis veritatis aperiam illum reiciendis velit rerum eius nulla dolor veniam! Repellendus est iste doloremque amet adipisci perferendis ea cupiditate nesciunt!</p>
        <div class="flex gap-5 mt-10 mb-2 px-1 py-2">
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Nextjs</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >PHP</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Hacker</p>
        </div>
        <div class="flex gap-6 px-2 mt-10 py-2">
        <span><img src="" alt="">Private Repository</span>
        <span><img src="" alt="">live demo</span>
        </div>
        </div>
        <div class="flex space-x-10">
            <div class="bg-white shadow-lg gap-10 px-2 py-4">
            <img src="image/Logo.png" alt="">
            <h2 >Faktury</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente perspiciatis veritatis aperiam illum reiciendis velit rerum eius nulla dolor veniam! Repellendus est iste doloremque amet adipisci perferendis ea cupiditate nesciunt!</p>
        <div class="flex gap-5 mt-10 mb-2 px-1 py-2">
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Nextjs</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >PHP</p>
         <p class="bg-grey-400 rounded-lg text-sm px-4 py-1" >Hacker</p>
        </div>
        <div class="flex gap-6 px-2 mt-10 py-2">
        <span><img src="" alt="">Private Repository</span>
        <span><img src="" alt="">live demo</span>
        </div>
        </div>
        </div>
    </div>
</section>
    <script>
      function toggleDarkMode() {
        var element = document.body;
        element.classList.toggle("dark-mode");
      }
    </script>
  </body>
</html>
