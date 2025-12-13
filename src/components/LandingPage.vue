<script setup lang="ts"></script>

<template>
  <div
    class="min-h-screen bg-[url(../assets/starlight.gif)] bg-size-[400px] font-[Jost] font-semibold text-gray-200 position: relative overflow-hidden"
  >
    <div class="flex flex-col justify-between items-center min-h-[90vh]">
      <div class="flex flex-col items-center">
        <h1
          class="text-8xl mt-6 font-bold shadow-2xl rounded-2xl p-2 shadow-gray-800/45 bg-gray-800/30 font-[MoonveilStellarion]"
        >
          Vahlaz.ᵈᵉᵛ
        </h1>
        <h2
          class="text-3xl md:text-4xl text-center max-w-[65vw] shadow-2xl mt-2 rounded-2xl p-2 shadow-gray-800/45 bg-gray-800/30"
        >
          Hi, I'm Atte! A developer and computer science student from Aalto
          university
        </h2>
      </div>
      <img src="../assets/moon.gif" class="size-45" />
      <h2
        class="text-4xl font-bold shadow-2xl rounded-2xl p-2 shadow-gray-800/60 bg-gray-800/30"
      >
        Portfolio
      </h2>
    </div>

    <div class="flex flex-col justify-center items-center">
      <div
        class="md:hidden flex justify-around max-w-[95vw] space-x-5 p-2 invert text-black font-[Antonio] text-xl shadow-xl rounded-2xl shadow-gray-400/30 bg-gray-400/30"
      >
        <a
          href="https://github.com/Vahlaz"
          class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
        >
          <div class="flex items-center align-middle">
            <img
              class="h-6 w-6 aspect-square mr-1"
              src="../assets/github-mark.svg"
            />
            - GitHub
          </div>
        </a>

        <a
          href="https://www.linkedin.com/in/atte-räty"
          class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
        >
          <div class="flex h-7 items-center align-middle">
            <img
              class="h-5 w-6 aspect-square mr-1"
              src="../assets/linkedin.svg"
            />
            - LinkedIn
          </div>
        </a>
        <a
          href="./cv.pdf"
          class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
        >
          <div class="flex h-7 items-center align-middle">
            <img
              class="h-6 w-6 aspect-square mr-1"
              src="../assets/article_person.svg"
            />
            - CV
          </div>
        </a>
      </div>
      <div
        alt="backdrop"
        class="bg-[url(../assets/FutuBoard.png)] bg-cover bg-center transition-all delay-75 duration-200 w-300 h-200 max-w-[95vw] text-white rounded-xl shadow-xl outline-1 outline-gray-700 shadow-gray-800 m-8"
      >
        <div
          class="flex flex-col columns-1 justify-center align-middle items-center h-full w-full position: relative"
        >
          <div
            class="text-5xl md:text-6xl p-4 max-w-[90vw] font-bold overflow-hidden wrap-break-word"
          >
            Futuboard
          </div>
          <div class="text-xl md:text-2xl p-4 max-w-225 overflow-hidden">
            Futuboard is a free, easy-to-use and open-source web tool for
            workflow management that requires no registration. It can be used to
            manage individual or team work efficiently and remotely. It allows
            for an easier to use platform than alternative tools with the same
            features, and it includes automatic visualizations and statistics
            about the progress of work.
          </div>
          <div class="text-lg md:text-xl p-4 max-w-150 overflow-hidden">
            React, Redux, Django, Typescript, Python, CSS, Scrum
          </div>
          <a
            href="https://futuboard.live/"
            class="position: absolute flex justify-center bottom-15 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            website
          </a>
          <a
            href="https://github.com/Futuboard/Futuboard"
            class="position: absolute flex justify-center bottom-5 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            code
          </a>
        </div>
      </div>
      <div
        alt="backdrop"
        class="bg-[url(../assets/KaraSaber.png)] bg-center bg-cover transition-all delay-75 duration-200 w-300 h-200 max-w-[95vw] text-white rounded-xl shadow-xl outline-1 outline-gray-700 shadow-gray-800 m-8"
      >
        <div
          class="flex flex-col columns-1 justify-center align-middle items-center h-full w-full position: relative"
        >
          <div
            class="text-5xl md:text-6xl p-4 max-w-[90vw] font-bold overflow-hidden wrap-break-word"
          >
            KaraSaber
          </div>
          <div class="text-2xl p-4 max-w-225 overflow-hidden">
            A beat saber clone that creates boxes based on Ultrastar deluxe
            karaoke files. All you need to add a song is to add the sound file
            and lyric file to the resources folder. Buttons are created
            dynamically for added songs.
          </div>
          <div class="text-lg md:text-xl p-4 max-w-150 overflow-hidden">
            C#, Unity, VR
          </div>
          <a
            href="https://github.com/Vahlaz/KaraSaber"
            class="position: absolute flex justify-center bottom-5 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            code
          </a>
        </div>
      </div>
      <div
        alt="backdrop"
        class="bg-[url(../assets/ByTheLake.png)] bg-center transition-all delay-75 duration-200 w-300 h-200 max-w-[95vw] text-white rounded-xl shadow-xl outline-1 outline-gray-700 shadow-gray-800 m-8"
      >
        <div
          class="flex flex-col columns-1 justify-center align-middle items-center h-full w-full position: relative backdrop-brightness-50 bg-contain"
        >
          <div
            class="text-5xl md:text-6xl p-4 max-w-[90vw] font-bold overflow-hidden wrap-break-word"
          >
            ByTheLake
          </div>
          <div class="text-2xl p-4 max-w-225 overflow-hidden">
            ByTheLake transports the user into the middle of a lakeside
            landscape in the summer, where they can explore the environment,
            listen to nature's sounds, and feel the calmness brought by the
            forest and water.
          </div>
          <div class="text-lg md:text-xl p-4 max-w-150 overflow-hidden">
            C#, Unity, VR
          </div>
          <a
            href="https://youtu.be/91lK5Wssfn0"
            class="position: absolute flex justify-center bottom-15 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            Video
          </a>
          <a
            href="https://version.aalto.fi/gitlab/ratya3/bythelake"
            class="position: absolute flex justify-center bottom-5 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            code
          </a>
        </div>
      </div>
      <div
        alt="backdrop"
        class="bg-[url(../assets/Kirjakirppis.png)] bg-cover bg-center transition-all delay-75 duration-200 w-300 h-200 max-w-[95vw] text-white rounded-xl shadow-xl outline-1 outline-gray-700 shadow-gray-800 m-8"
      >
        <div
          class="flex flex-col columns-1 justify-center align-middle items-center h-full w-full position: relative"
        >
          <div
            class="text-5xl md:text-6xl p-4 max-w-[90vw] font-bold overflow-hidden wrap-break-word"
          >
            KirjaKirppis
          </div>
          <div class="text-2xl p-4 max-w-225 overflow-hidden">
            KirjaKirppis is a simple website made for selling and purchasing
            second hand high school course books. It has specific sites for all
            high schools in Finland, as well as icons for all course books
            officially in use by the schools. It also has users with token based
            authentication.
          </div>
          <div class="text-lg md:text-xl p-4 max-w-150 overflow-hidden">
            React, NodeJS, GraphQl, Material UI
          </div>
          <a
            href="https://github.com/Vahlaz/kirjakirppis"
            class="position: absolute flex justify-center bottom-5 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            code
          </a>
        </div>
      </div>
      <div
        alt="backdrop"
        class="bg-[url(../assets/ScuffedPuolustus.png)] bg-cover bg-center transition-all delay-75 duration-200 w-300 h-200 max-w-[95vw] text-white rounded-xl shadow-xl outline-1 outline-gray-700 shadow-gray-800 m-8"
      >
        <div
          class="flex flex-col columns-1 justify-center align-middle items-center h-full w-full position: relative"
        >
          <div
            class="text-5xl md:text-6xl p-4 max-w-[90vw] font-bold overflow-hidden wrap-break-word"
          >
            ScuffedPuolustus
          </div>
          <div class="text-2xl p-4 max-w-225 overflow-hidden">
            ScuffedPuolustus is a simple tower defense game in which the player
            tries to prevent enemies from reaching the end of the path. The
            player earns money by destroying enemies, and with the money earned,
            the player can place more towers. The number and strength of enemies
            increase with each round.
          </div>
          <div class="text-lg md:text-xl p-4 max-w-150 overflow-hidden">
            Scala
          </div>
          <a
            href="https://github.com/Vahlaz/ScuffedPuolustus"
            class="position: absolute flex justify-center bottom-5 outline-2 bg-gray-600 hover:bg-gray-700 transition duration-150 outline-gray-800 rounded-xl w-30"
          >
            code
          </a>
        </div>
      </div>
      <h2
        class="text-4xl font-bold shadow-2xl rounded-2xl p-2 shadow-gray-800/60 bg-gray-800/30 flex justify-center"
      >
        Activity
        <div class="text-sm p-1">(in CS2)</div>
      </h2>
      <div
        class="bg-gray-700/30 shadow-2xl shadow-gray-700/30 rounded-2xl mb-20 m-8 w-300 max-w-[95vw]"
      >
        <img src="../assets/activity.png" />
      </div>
    </div>
  </div>
  <div
    class="max-md:hidden position: fixed left-4 top-4 flex-col p-2 invert font-[Antonio] text-xl shadow-xl rounded-2xl shadow-gray-400/30 bg-gray-400/30"
  >
    <a
      href="https://github.com/Vahlaz"
      class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
    >
      <div class="flex items-center align-middle">
        <img
          class="h-6 w-6 aspect-square mr-1"
          src="../assets/github-mark.svg"
        />
        - GitHub
      </div>
    </a>

    <a
      href="https://www.linkedin.com/in/atte-räty"
      class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
    >
      <div class="flex h-7 items-center align-middle">
        <img class="h-5 w-6 aspect-square mr-1" src="../assets/linkedin.svg" />
        - LinkedIn
      </div>
    </a>
    <a
      href="./cv.pdf"
      class="flex hover:text-green-500 hover:font-bold p-1 rounded-xl"
    >
      <div class="flex h-7 items-center align-middle">
        <img
          class="h-6 w-6 aspect-square mr-1"
          src="../assets/article_person.svg"
        />
        - CV
      </div>
    </a>
  </div>
</template>
