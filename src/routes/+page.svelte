<script>
    import '../app.css';
    let src = '../src/lib/avatar-jessica.jpeg'
  </script>
  
  <slot />

  <body class="bg-neutral-950 m-40 flex justify-center">
    <div class="bg-neutral-900 p-4 w-96 rounded-xl">
        <div class="flex justify-center">
            <img {src} alt="avatar-jessica" class="rounded-full m-6 size-20"/>
        </div>
        <div class="text-center">
            <h1 class="font-bold text-white text-2xl">Jessica Randall</h1>
            <h4 class="font-bold text-lime-400 text-sm m-2">London, United Kingdom</h4>
            <p class="text-white font-semibold text-sm m-6">"Front-end developer and avid reader."</p>
        </div>
        <div class="flex-col flex align-items justify-center text-white ">
            <button class="bg-neutral-800 m-2 p-3 rounded-md">GitHub</button>
            <button class="bg-neutral-800 m-2 p-3 rounded-md">Frontend Mentor</button>
            <button class="bg-neutral-800 m-2 p-3 rounded-md">Linkedln</button>
            <button class="bg-neutral-800 m-2 p-3 rounded-md">Twitter</button>
            <button class="bg-neutral-800 m-2 p-3 rounded-md">Instagram</button>
        </div>
    </div>

  </body>
