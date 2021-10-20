<template>
  <nav class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between
px-2 py-3">
    <div class="container px-4 mx-auto flex flex-wrap items-center justify-between">
      <div class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start">
        <a href="#home"
           class="text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-nowrap uppercase text-white">Home</a>
        <button
            class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block lg:hidden lg:outline-none focus:outline-none"
            type="button" v-on:click="toggleNavbar('example-collapse-navbar')">
          <i class="text-white fas fa-bars"></i>
        </button>
      </div>
      <div class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden"
           id="example-collapse-navbar"
      >
        <ul class="flex flex-col lg:flex-row list-none mr-auto">
          <li class="flex items-center">
            <a href="#ipod"
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-lg uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fas fa-tablet text-lg leading-lg mr-2"></i>Ipad
            </a>
          </li>
          <li class="flex items-center">
            <a href="#macbook"
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-lg uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fas fa-laptop text-lg leading-lg mr-2"></i>MacBook
            </a>
          </li>
          <li class="flex items-center">
            <a href="#team"
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-lg uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fas fa-users text-lg leading-lg mr-2"></i>Team
            </a>
          </li>
          <li class="flex items-center">
            <a href="#contact"
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-lg uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fas fa-address-card text-lg leading-lg mr-2"></i>Contact Us
            </a>
          </li>
        </ul>
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <li class="flex items-center">
            <a href=""
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fab fa-facebook text-lg leading-lg"></i>
              <span class="lg:hidden inline-block ml-2"></span>
            </a>
          </li>
          <li class="flex items-center">
            <a href=""
               class="lg:text-white lg:hover:text-gray-300 text-gray-800 px-3 py-4 lg:py-2 flex items-center text-xs uppercase font-bold">
              <i class="lg:text-gray-300 text-gray-500 fab fa-twitter text-lg leading-lg"></i>
              <span class="lg:hidden inline-block ml-2"></span>
            </a>
          </li>
          <li class="flex items-center">
            <button class="bg-white text-gray-800 active:bg-gray-100 text-xs font-bold uppercase px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3"><i class="fas fa-arrow-circle-down mr-2"></i> Buy New Macbook</button>

          </li>
        </ul>
      </div>
    </div>
  </nav>
  <main>
    <div class="relative pt-16 lg:pb-32 flex content-center items-center justify-center min-h-home-lg" id="home">
      <div class="absolute w-full h-full">
        <video autoplay muted class="top-0 bg-center">
          <source src="https://www.apple.com/105/media/us/macbook-pro-13/2020/f2b14406-42ad-405e-bfa0-71b52a0bfd67/anim/chip/large.mp4">
        </video>
      </div>
      <div class="container relative mx-auto hidden md:block ">
        <div class="items-center flex flex-wrap">
          <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
            <div class="pr-12">
              <h1 class="text-white font-semibold text-4xl -mt-32">Welcome to Apple.</h1>
            </div>
          </div>
        </div>
      </div>
    </div>
    <section class="pb-20 mt-40 bg-gray-100" id="ipad" style="height: 1200px">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap">
          <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5 flex-auto">
                <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400">
                  <i class="fas fa-tablet"></i>
                </div>
                <h6 class="text-xl font-semibold">Ipad Pro</h6>
                <p class="mt-2 mb-4 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci, alias aperiam architecto aut autem, dicta eligendi esse explicabo illo illum in incidunt iusto magnam necessitatibus neque omnis quibusdam, voluptas voluptatibus!</p>
              </div>
            </div>
          </div>
          <div class="w-full md:w-4/12 px-4 text-center">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5 flex-auto">
                <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400">
                  <i class="fas fa-tablet"></i>
                </div>
                <h6 class="text-xl font-semibold">Ipad Pro</h6>
                <p class="mt-2 mb-4 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci, alias aperiam architecto aut autem, dicta eligendi esse explicabo illo illum in incidunt iusto magnam necessitatibus neque omnis quibusdam, voluptas voluptatibus!</p>
              </div>
            </div>
          </div>
          <div class="lg:pt-12 pt-6 w-full md:w-4/12 px-4 text-center">
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
              <div class="px-4 py-5 flex-auto">
                <div class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-red-400">
                  <i class="fas fa-tablet"></i>
                </div>
                <h6 class="text-xl font-semibold">Ipad Pro</h6>
                <p class="mt-2 mb-4 text-gray-600">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Adipisci, alias aperiam architecto aut autem, dicta eligendi esse explicabo illo illum in incidunt iusto magnam necessitatibus neque omnis quibusdam, voluptas voluptatibus!</p>
              </div>
            </div>
          </div>
        </div>
        <div class="flex flex-wrap items-center mt-32">
          <div class="w-full md:w-5/12 px-4 mr-auto ml-auto">
            <div class="text-gray-600 p-3 text-center inline-flex items-center justify-center
w-16 h-16 mb-6 shadow-lg rounded-full bg-gray-100">
              <i class="fas fa-tablet text-lg"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold">New Ipad Pro.</h3>
            <p class="text-lg font-light leading-relaxed mt-4 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque aut, cumque cupiditate, distinctio enim fugit ipsam mollitia natus nostrum officiis pariatur ratione soluta velit? Commodi debitis ducimus magnam nisi quae?</p>
            <p class="text-lg font-light leading-relaxed mt-4 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque aut, cumque cupiditate, distinctio enim fugit ipsam mollitia natus nostrum officiis pariatur ratione soluta velit? Commodi debitis ducimus magnam nisi quae?</p>
          </div>
          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto">
            <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg
rounded-lg bg-black">
              <img src="https://www.apple.com/v/ipad-pro/ag/images/shared/ipad_trade_in__ggq1dqvyb56y_large.png" class="w-full align-middle rounded-t-lg" alt="">
              <blockquote class="relative p-8 mb-4 bg-black ">
                <h4 class="text-lg font-bold text-white">Ipad Pro 12.9 & 11In.</h4>
                <p class="text-md font-light mt-2 text-white">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Atque dolor, earum error expedita hic laborum maiores
                </p>
              </blockquote>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="relative py-20 bg-black" id="macbook">
      <div class="bottom-auto top-0 left-0 right-0 w-full absolute overflow-hidden -mt-20" style="height: 80px">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-black fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
      <div class="container mx-auto px-4 bg-black">
        <div class="items-center flex flex-wrap">
          <div class="w-full md:w-4/12 ml-auto mr-auto px-4">
            <img src="https://www.apple.com/kr/macbook-pro-13/h/images/overview/magic_keyboard__brx9diaauwaa_large.jpg" class="max-w-full rounded-lg shadow-lg" style="width: 400px" alt="">
          </div>
          <div class="w-full md:w-5/12 mr-auto ml-auto px-4">
            <div class="md:pr-12">
              <div class="text-black p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white">
                <i class="fas fa-laptop text-xl"></i>
              </div>
              <h3 class="text-3xl font-semibold text-white">Macbook Pro 13&16in.</h3>
              <p class="mt-4 text-lg leading-relaxed text-gray-300">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dignissimos facere inventore ipsa mollitia nostrum obcaecati qui rem sunt velit voluptatibus! Amet, animi at dolore eius ipsam necessitatibus officia officiis veritatis?</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="relative py-20 bg-white" id="team" style="height: 900px">
      <div class="bottom-auto top-0 left-0 right-0 w-full absolute overflow-hidden -mt-20" style="height: 80px">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-white fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center text-center mb-24">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-4xl font-semibold">Here are our Legents</h2>
            <p class="m-4 text-gray-600 leading-relaxed text-lg">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad expedita illo nemo perferendis quaerat ullam. Animi earum neque obcaecati velit veritatis? Consectetur distinctio eos fugiat itaque nisi, quos recusandae vel!</p>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full md:2-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Steve_Jobs_Headshot_2010-CROP2.jpg/225px-Steve_Jobs_Headshot_2010-CROP2.jpg" class="shadow-lg rounded-full mx-auto" style="max-width: 120px" alt="">
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Steve Jobs</h5>
                <p class="mt-1 text-sm uppercase font-semibold text-gray-500">Former CEO</p>
                <div class="mt-6">
                  <button class="bg-blue-400 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-twitter"></i>
                  </button>
                  <button class="bg-blue-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-facebook"></i>
                  </button>
                  <button class="bg-purple-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-instagram"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full md:2-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Steve_Jobs_Headshot_2010-CROP2.jpg/225px-Steve_Jobs_Headshot_2010-CROP2.jpg" class="shadow-lg rounded-full mx-auto" style="max-width: 120px" alt="">
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Steve Jobs</h5>
                <p class="mt-1 text-sm uppercase font-semibold text-gray-500">Former CEO</p>
                <div class="mt-6">
                  <button class="bg-blue-400 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-twitter"></i>
                  </button>
                  <button class="bg-blue-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-facebook"></i>
                  </button>
                  <button class="bg-purple-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-instagram"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full md:2-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Steve_Jobs_Headshot_2010-CROP2.jpg/225px-Steve_Jobs_Headshot_2010-CROP2.jpg" class="shadow-lg rounded-full mx-auto" style="max-width: 120px" alt="">
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Steve Jobs</h5>
                <p class="mt-1 text-sm uppercase font-semibold text-gray-500">Former CEO</p>
                <div class="mt-6">
                  <button class="bg-blue-400 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-twitter"></i>
                  </button>
                  <button class="bg-blue-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-facebook"></i>
                  </button>
                  <button class="bg-purple-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-instagram"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full md:2-6/12 lg:w-3/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f5/Steve_Jobs_Headshot_2010-CROP2.jpg/225px-Steve_Jobs_Headshot_2010-CROP2.jpg" class="shadow-lg rounded-full mx-auto" style="max-width: 120px" alt="">
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Steve Jobs</h5>
                <p class="mt-1 text-sm uppercase font-semibold text-gray-500">Former CEO</p>
                <div class="mt-6">
                  <button class="bg-blue-400 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-twitter"></i>
                  </button>
                  <button class="bg-blue-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-facebook"></i>
                  </button>
                  <button class="bg-purple-600 text-white w-8 h-8 rounded-full mr-1 mb-1">
                    <i class="fab fa-instagram"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="pb-20 relative block bg-black" id="contact">
      <div class="bottom-auto top-0 left-0 right-0 w-full absolute overflow-hidden -mt-20" style="height: 80px">
        <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" version="1.1" viewBox="0 0 2560 100" x="0" y="0">
          <polygon class="text-black fill-current" points="2560 0 2560 100 0 100"></polygon>
        </svg>
      </div>
      <div class="container mx-auto px-4 lg:pt-24 lg:pb-64">
        <div class="flex flex-wrap text-center justify-center text-white">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-4xl font-semibold">Contact Us</h2>
            <p class="text-lg leading-relaxed mt-4 mb-4 text-gray-300">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Amet, beatae consequatur cumque cupiditate, distinctio dolorum eos eum minima molestiae mollitia nisi nobis nostrum odio quisquam recusandae repellendus saepe sapiente sequi, tempora voluptatem?</p>
          </div>

        </div>
        <div class="flex flex-wrap mt-12 justify-center">
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center">
              <i class="fas fa-medal text-lg"></i>
            </div>
            <h6 class="text-white mt-5 font-semibold text-xl">lorem, ipsum</h6>
            <p class="mt-2 mb-4 text-white text-gray-300">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio porro provident reprehenderit.</p>
          </div>
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center">
              <i class="fas fa-lightbulb text-lg"></i>
            </div>
            <h6 class="text-white mt-5 font-semibold text-xl">lorem, ipsum</h6>
            <p class="mt-2 mb-4 text-white text-gray-300">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio porro provident reprehenderit.</p>
          </div>
          <div class="w-full lg:w-3/12 px-4 text-center">
            <div class="text-gray-900 p-3 w-12 h-12 shadow-lg rounded-full bg-white inline-flex items-center justify-center">
              <i class="fas fa-poll text-lg"></i>
            </div>
            <h6 class="text-white mt-5 font-semibold text-xl">lorem, ipsum</h6>
            <p class="mt-2 mb-4 text-white text-gray-300">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio porro provident reprehenderit.</p>
          </div>
        </div>
      </div>
    </section>
    <section class="bg-black relative block lg:px-24 pt-36 lg:pt-0">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
          <div class="w-full lg:w-6/12 px-4">
            <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded-lg bg-gray-300">
              <div class="flex-auto p-5 lg:p-10">
                <h4 class="text-2xl font-semibold">Want To Work Us?</h4>
                <p class="mt-1 mb-4 text-gray-600 leading-relaxed">Complete this form and we will get back to you in 24 hours.</p>
                <div class="relative w-full mb-3 mt-8">
                  <label for="name" class="block uppercase text-gray-700 font-bold">Full Name</label>
                  <input type="text" class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow w-full" placeholder="">
                </div>
                <div class="relative w-full mb-3 mt-8">
                  <label for="email" class="block uppercase text-gray-700 font-bold">Email</label>
                  <input type="email" class="border-0 px-3 py-3 placeholder-gray-400 text-gray-700 bg-white rounded text-sm shadow w-full" placeholder="">
                </div>
                <div class="relative w-full mb-3 ">
                  <label for="message" class="block uppercase text-gray-700 font-bold">Message</label>
                  <textarea name="" id="" cols="30" rows="10" class="w-full rounded"></textarea>
                </div>
                <div class="text-center mt-6">
                  <button class="text-white active:bg-gray-700 text-sm bg-gray-900 font-bold uppercase px-6 py-3 rounded hover:shadow-lg shadow outline-none mb-1" type="button">Send Message</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
  <footer class="relative pt-8 pb-6 bg-white">
    <div class="bottom-auto top-0 left-0 right-0 w-full absolute overflow-hidden -mt-20" style="height: 80px">
      <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none" version="1.1" viewBox="0 0 2560 100" x="0" y="0">
        <polygon class="text-white fill-current" points="2560 0 2560 100 0 100"></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4 ">
      <div class="flex flex-wrap">
        <div class="w-full lg:w-6/12 px-4">
          <h4 class="text-3xl font-semibold">Lets keep In Touce!</h4>
          <h5 class="text-lg mb-2 text-gray-700">You Can Find Us On Any These Platforms.</h5>
          <div class="mt-6 ">
            <button class="bg-white text-blue-400 p-3 shadow-lg font-normal h-10 w-10 items-center justify-center align-middle rounded-full outline-none mr-2">
              <i class="fab fa-twitter"></i>
            </button>
            <button class="bg-white text-blue-600 p-3 shadow-lg font-normal h-10 w-10 items-center justify-center align-middle rounded-full outline-none mr-2">
              <i class="fab fa-facebook"></i>
            </button>
            <button class="bg-white text-purple-500 p-3 shadow-lg font-normal h-10 w-10 items-center justify-center align-middle rounded-full outline-none mr-2">
              <i class="fab fa-instagram"></i>
            </button>
            <button class="bg-white text-red-500 p-3 shadow-lg font-normal h-10 w-10 items-center justify-center align-middle rounded-full outline-none mr-2">
              <i class="fab fa-youtube"></i>
            </button>
            <button class="bg-white text-black p-3 shadow-lg font-normal h-10 w-10 items-center justify-center align-middle rounded-full outline-none mr-2">
              <i class="fab fa-github"></i>
            </button>
          </div>
        </div>
        <div class="w-full lg:w-6/12 px-4">
          <div class="flex flex-wrap mb-6">
            <div class="w-full lg:w-4/12 px-4 ml-auto">
              <span class="block uppercase text-gray-600 text-sm font-semibold mb-2">Useful Links</span>
              <ul>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">About Us</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Contact Us</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Our Products</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Our Locations</a>
                </li>
              </ul>
            </div>
            <div class="w-full lg:w-4/12 px-4 ml-auto">
              <span class="block uppercase text-gray-600 text-sm font-semibold mb-2">Useful Resources</span>
              <ul>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">About Us</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Contact Us</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Our Products</a>
                </li>
                <li >
                  <a href="" class="text-gray-700 hover:text-gray-900 font-semibold text-sm pb-2">Our Locations</a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <hr class="my-6 border-gray-400">
      <div class="flex flex-wrap items-center md:justify-between justify-center">
        <div class="w-full md:w-4/12 px-4 mx-auto text-center">
          <div class="text-sm text-gray-600 font-semibold py-1">Copywrite 2021 Apple Clone by aaa</div>
        </div>
      </div>
    </div>
  </footer>

</template>

<script>
export default {
  name: 'App',
  components: {},
  methods: {
    toggleNavbar(collapseId) {
      console.log('click')
      document.getElementById(collapseId).classList.toggle('hidden');
      document.getElementById(collapseId).classList.toggle('block');
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  bg:black
}

@media (min-width: 550px) {
  .min-h-home-lg {
    min-height: 75vh;
  }
}
</style>
