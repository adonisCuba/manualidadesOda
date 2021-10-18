<template>
  <header>
    <nav
        class="
          flex flex-wrap
          items-center
          justify-between
          w-full
          py-4
          md:py-0
          px-4
          text-lg text-gray-700
          bg-white
        "
    >
       <div>
          <a href="#" class="title text-2xl">
            Manualidades Oda
          </a>
        </div>
       
         <svg
            id="menu-button"
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6 cursor-pointer md:hidden block"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            />
          </svg>
       
       <div id="menu" class="hidden w-full md:flex md:items-center md:w-auto">
          <ul
            class="
              pt-4
              text-base text-gray-700
              md:flex
              md:justify-between 
              md:pt-0"
          >
            <li>
              <a class="md:p-4 py-2 block hover:text-purple-400" href="#"
                >Artículos</a
              >
            </li>
            <li>
              <a class="md:p-4 py-2 block hover:text-purple-400" href="#"
                >Contáctenos</a
              >
            </li>            
            <li>
              <a
                class="md:p-4 py-2 block hover:text-purple-400 text-purple-500"
                href="#"
                >Iniciar sesión</a
              >
            </li>
          </ul>
        </div>
    </nav>
  </header>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css?family=Lobster");
.title {
  font-family: Lobster;
}
</style>