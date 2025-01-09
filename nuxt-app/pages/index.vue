<template>
  <div>
    <!-- section1.. -->
    <Header />
    <!-- section2... -->
    <section>
      <div class="relative">
        <img src="/bg.png" alt="bg" />
      </div>
      <div
        class="flex items-center justify-around absolute w-full px-6 md:px-16 z-10 -mt-[900px]"
      >
        <img src="/logo.png" alt="logo" class="w-[160px] h-[60px]" />
        <div class="flex items-center gap-6 md:gap-16">
          <nav class="flex gap-6 md:gap-16">
            <a
              href="#"
              class="font-medium md:text-[18px] text-[10px] text-white"
              >Home</a
            >
            <a
              href="#"
              class="font-medium md:text-[18px] text-[10px] text-white"
              >Rooms</a
            >
            <a
              href="#"
              class="font-medium md:text-[18px] text-[10px] text-white"
              >Gallery</a
            >
            <a
              href="#"
              class="font-medium md:text-[18px] text-[10px] text-white"
              >Contact Us</a
            >
          </nav>
          <div class="flex gap-12">
            <button class="flex gap-2 p-4 text-center text-black bg-white">
              Book now
              <img
                src="/arrow.png"
                alt="arrow"
                class="w-[15px] h-[15px] mt-1"
              />
            </button>
            <button
              class="flex gap-2 p-4 text-center text-white border border-white"
            >
              hotel with flight
              <img
                src="/arrow.png"
                alt="arrow"
                class="w-[15px] h-[15px] mt-1 text-white"
              />
            </button>
          </div>
        </div>
      </div>
      <div
        class="absolute flex flex-col -mt-[600px] justify-center items-center ml-[650px]"
      >
        <h4 class="mb-2 text-sm tracking-widest text-white uppercase">
          Indoors & Outdoors
        </h4>
        <h1
          class="mb-6 text-4xl font-bold leading-tight text-white md:text-6xl"
        >
          Enjoy A Luxury<br />
          Experience
        </h1>
        <button
          class="flex gap-2 p-2 text-center text-white border border-white"
        >
          ROOMS & SUITS
          <img src="/arrow.png" alt="arrow" class="w-[15px] h-[15px] mt-1" />
        </button>
      </div>
      <div
        class="absolute flex space-x-2 -bottom-0 ml-[820px] justify-center items-center"
      >
        <span class="block w-3 h-3 bg-white rounded-full"></span>
        <span class="block w-3 h-3 bg-gray-400 rounded-full"></span>
        <span class="block w-3 h-3 bg-gray-400 rounded-full"></span>
      </div>
    </section>

    <!-- section3.. -->
    <section
      class="py-12 absolute -mt-[205px] flex flex-col justify-center items-center ml-[390px]"
    >
      <div class="max-w-4xl mx-auto text-center">
        <form class="p-6 bg-[#F5F5F5] rounded-lg shadow-md w-[900px] mt-5">
          <h3 class="mb-2 text-sm tracking-wide text-black uppercase">
            One of the Best Places to Relax & Enjoy
          </h3>
          <h2 class="mb-8 text-3xl font-bold text-black">
            Lydia City Hotel Rhodes
          </h2>

          <div class="flex flex-row items-center justify-around gap-3">
            <div>
              <label
                for="name"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Your Name:</label
              >
              <input
                type="text"
                id="name"
                placeholder="Your Name"
                class="w-full p-2 border rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"
              />
            </div>
            <div>
              <label
                for="email"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Email:</label
              >
              <input
                type="email"
                id="email"
                placeholder="Your Email ID"
                class="w-full p-2 border rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"
              />
            </div>

            <div>
              <label
                for="checkin"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Check In:</label
              >
              <input
                type="date"
                id="checkin"
                class="w-full p-2 border rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"
              />
            </div>
            <div>
              <label
                for="checkout"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Check Out:</label
              >
              <input
                type="date"
                id="checkout"
                class="w-full p-2 border rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500"
              />
            </div>
          </div>

          <div
            class="flex flex-row items-center justify-start w-full gap-3 mt-4 ml-[16px]"
          >
            <div>
              <label
                for="rooms"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Rooms:</label
              >
              <select
                id="rooms"
                class="p-2 border rounded-md px-14 focus:outline-none focus:ring-2 focus:ring-blue-500"
              >
                <option>Select</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
              </select>
            </div>
            <div>
              <label
                for="adults"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Adults:</label
              >
              <select
                id="adults"
                class="p-2 border rounded-md px-14 focus:outline-none focus:ring-2 focus:ring-blue-500"
              >
                <option>Select</option>
                <option>1</option>
                <option>2</option>
                <option>3</option>
              </select>
            </div>
            <div>
              <label
                for="children"
                class="block mb-1 text-sm font-medium text-gray-700"
                >Children:</label
              >
              <select
                id="children"
                class="p-2 border rounded-md px-14 focus:outline-none focus:ring-2 focus:ring-blue-500"
              >
                <option>Select</option>
                <option>0</option>
                <option>1</option>
                <option>2</option>
              </select>
            </div>
          </div>
          <div class="flex items-center mt-4 mb-4 ml-[16px]">
            <input
              type="checkbox"
              id="terms"
              class="w-4 h-4 text-blue-600 border-gray-300 rounded focus:ring-2 focus:ring-blue-500"
            />
            <label for="terms" class="ml-2 text-sm text-gray-600"
              >I have read and agree with the terms</label
            >
          </div>
          <button
            type="submit"
            class="-ml-[700px] px-8 py-2 text-white bg-black rounded-md hover:bg-gray-800 focus:outline-none focus:ring-2 focus:ring-blue-500"
          >
            Send
          </button>
        </form>
      </div>
    </section>

    <!-- section4.. -->
    <section class="py-12 bg-white mt-[253px]">
      <div class="flex items-center justify-around gap-4">
        <div class="flex flex-col">
          <h3 class="text-[#515151] text-[24px] font-[300px]">
            About Lydia Hotel
          </h3>
          <h2 class="font-[400px] text-[48px] mt-4">
            Enjoy A Luxury Experience
          </h2>
          <p
            class="w-[634px] h-[380px] text-[#535353] font-[300px] text-[20px] mt-4"
          >
            Lorem ipsum dolor sit amet consectetur. Pretium gravida non integer
            magna. Nibh facilisi eget justo tristique. Nunc purus vehicula
            curabitur egestas. Vel eget est semper ut. Nibh duis nec in at nulla
            sit. Congue ut commodo eu nunc. Tincidunt proin nec lobortis
            imperdiet auctor id aliquet. Morbi dignissim scelerisque est erat.
            Tincidunt eu porta vivamus id magnis tellus volutpat aliquet. Velit
            ut non vitae ornare. Pretium interdum volutpat bibendum malesuada
            odio nulla tellus. Tortor cursus quam elit sagittis in. Arcu ut
            magna arcu sit. Leo dignissim neque luctus ornare volutpat neque.
            Morbi integer aliquam fermentum diam ac. Nunc.
          </p>
        </div>
        <div>
          <img src="/about.png" alt="room" class="w-[550px] h-[500px]" />
        </div>
      </div>
    </section>

    <!-- section5.. -->
    <section class="py-16 bg-[#F5F5F5]">
      <div class="px-4 mx-auto max-w-7xl">
        <div class="mb-12">
          <h4 class="mb-2 text-[18px] tracking-wide text-gray-600 uppercase">
            What We Provide
          </h4>
          <h2 class="text-[42px] font-bold text-gray-800">Our Services</h2>
        </div>

        <div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/room.png" alt="Room Services" class="w-12 h-12" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Room Services</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/bathroom.png" alt="Luxury Bathroom" class="w-12 h-124" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Luxury Bathroom</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis.
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img
              src="/tv.png"
              alt="Satellite Television Set"
              class="w-12 h-12"
            />
            <h3 class="mt-4 mb-2 text-lg font-semibold">
              Satellite Television Set
            </h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/eat.png" alt="Breakfast" class="w-12 h-124" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Breakfast</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/wifi.png" alt="WiFi" class="w-12 h-12" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">WiFi</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolornsectetur. Pretium gravida non integer magna.
              Nibh facilisi eget justo tristique. Nunc purus vehicula curabitur
              egestas. Vel eget est semper ut. Nibh duis nec in at nulla sit.
              Congue ut commodo eu nunc. Tincidunt proin nec lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/bar.png" alt="Mini Bar" class="w-12 h-12" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Mini Bar</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum doloonsectetur. Pretium gravida non integer magna.
              Nibh facilisi eget justo tristique. Nunc purus vehicula curabitur
              egestas. Vel eget est semper ut. Nibh duis nec in at nulla sit.
              Congue ut commodo eu nunc. Tincidunt proin nec lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img
              src="/chair.png"
              alt="Double Glazed Windows"
              class="w-12 h-12"
            />
            <h3 class="mt-4 mb-2 text-lg font-semibold">
              Double Glazed Windows And Balcony
            </h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/icon.png" alt="Friendliness" class="w-12 h-124" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Friendliness</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
          <div class="p-6 bg-[#F5F5F5] rounded-lg shadow">
            <img src="/sun.png" alt="Sun Deck Area" class="w-12 h-124" />
            <h3 class="mt-4 mb-2 text-lg font-semibold">Sun Deck Area</h3>
            <p class="text-sm text-gray-600">
              Lorem ipsum dolor sit amet consectetur. Pretium gravida non
              integer magna. Nibh facilisi eget justo tristique. Nunc purus
              vehicula curabitur egestas. Vel eget est semper ut. Nibh duis nec
              in at nulla sit. Congue ut commodo eu nunc. Tincidunt proin nec
              lobortis
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- section6.. -->
    <section class="py-16">
      <div class="px-4 mx-auto max-w-7xl">
        <div class="mb-12">
          <h4 class="mb-2 text-[18px] tracking-wide text-gray-600 uppercase">
            Hotel's Beauty
          </h4>
          <h2 class="text-[42px] font-bold text-gray-800">Our Gallery</h2>
        </div>

        <div class="flex flex-row items-center justify-center gap-4">
          <div class="flex flex-col gap-4">
            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart1.png"
                alt="Gallery Image 1"
                class="object-cover w-full h-[600px]"
              />
            </div>

            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart2.png"
                alt="Gallery Image 2"
                class="object-cover w-full h-auto"
              />
            </div>
          </div>

          <div class="flex flex-col gap-4">
            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart2.png"
                alt="Gallery Image 3"
                class="object-cover w-full h-auto"
              />
            </div>

            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart4.png"
                alt="Gallery Image 4"
                class="object-cover w-full h-auto"
              />
            </div>

            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart6.png"
                alt="Gallery Image 5"
                class="object-cover w-full h-auto"
              />
            </div>
          </div>

          <div class="flex flex-col gap-4">
            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart3.png"
                alt="Gallery Image 6"
                class="object-cover w-full h-auto"
              />
            </div>
            <div class="overflow-hidden rounded-lg shadow">
              <img
                src="/cart7.png"
                alt="Gallery Image 6"
                class="object-cover w-full h-auto"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- section7.. -->
    <Footer />
    <div class="flex items-center justify-around pt-6 mb-2 -mt-5 text-sm">
      <p>
        We use cookies to ensure that we give you the best experience on our
        website.
      </p>
      <div class="flex gap-6 mt-2 space-x-4">
        <a href="#" class="hover:underline">Ok</a>
        <a href="#" class="hover:underline">Privacy Policy</a>
      </div>
    </div>
  </div>
</template>
