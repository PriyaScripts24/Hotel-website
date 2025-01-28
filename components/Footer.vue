<template>
  <div>
    <section class="mt-[40px] md:mt-[80px]">
      <footer class="py-12 text-white bg-black">
        <div
          class="flex flex-row items-center justify-around gap-20 px-4 mx-auto max-w-7xl md:flex-row"
        >
          <div class="relative flex flex-row md:gap-3">
            <div class="flex-1">
              <h3 class="mb-6 text-[16px] md:text-xl font-bold">Quick Links</h3>
              <ul class="space-y-2 md:space-y-4">
                <li><a href="#" class="hover:underline">Home</a></li>
                <li><a href="#" class="hover:underline">About Us</a></li>
                <li><a href="#" class="hover:underline">Our Properties</a></li>
                <li><a href="#" class="hover:underline">Testimonials</a></li>
                <li><a href="#" class="hover:underline">Contact Us</a></li>
              </ul>
            </div>
            <div class="flex-1">
              <h3 class="mb-6 text-xl font-bold">Contact Info</h3>
              <ul class="space-y-6">
                <li class="flex items-center gap-2">
                  <img
                    src="/phone.png"
                    alt="Phone"
                    class="w-6 h-6 p-1 bg-white rounded-full"
                  />
                  <p class="text-[12px]">(+30) 2241022871-2</p>
                </li>
                <li class="flex items-center gap-2">
                  <img
                    src="/location.png"
                    alt="Address"
                    class="w-6 h-6 p-1 bg-white rounded-full"
                  />
                  <p class="text-[12px]">25is Martiou 31-35, Rhodes 851 00</p>
                </li>
                <li class="flex items-center gap-2">
                  <img
                    src="/gmail.png"
                    alt="Email"
                    class="w-6 h-6 p-1 bg-white rounded-full"
                  />
                  <p class="text-[12px]">info@lydiahotel.gr</p>
                </li>
              </ul>
            </div>
          </div>
          <div class="py-4 bg-gray-50 -mt-[170px] hidden md:block">
            <div class="w-full h-auto max-w-3xl mx-auto text-center">
              <h3 class="mb-2 text-sm text-gray-500 uppercase">
                One of the best places to relax & enjoy
              </h3>
              <h1 class="text-3xl font-bold text-gray-800">
                Lydia City Hotel Rhodes
              </h1>
            </div>

            <form class="max-w-3xl p-8 mx-auto mt-8 bg-white rounded-lg">
              <div class="grid grid-cols-1 gap-2 md:grid-cols-2">
                <div>
                  <label
                    for="name"
                    class="block text-sm font-medium text-gray-700"
                    >Your Name:</label
                  >
                  <input
                    type="text"
                    id="name"
                    placeholder="Your Name"
                    class="w-full px-4 py-2 mt-1 border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  />
                </div>
                <div>
                  <label
                    for="email"
                    class="block text-sm font-medium text-gray-700"
                    >Email:</label
                  >
                  <input
                    type="email"
                    id="email"
                    placeholder="Your Email ID"
                    class="w-full px-4 py-2 mt-1 border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  />
                </div>

                <div>
                  <label
                    for="check-in"
                    class="block text-sm font-medium text-gray-700"
                    >Check In:</label
                  >
                  <input
                    type="date"
                    id="check-in"
                    class="w-full px-4 py-2 mt-1 text-black border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  />
                </div>
                <div>
                  <label
                    for="check-out"
                    class="block text-sm font-medium text-gray-700"
                    >Check Out:</label
                  >
                  <input
                    type="date"
                    id="check-out"
                    class="w-full px-4 py-2 mt-1 text-black border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  />
                </div>

                <div>
                  <label
                    for="rooms"
                    class="block text-sm font-medium text-gray-700"
                    >Rooms:</label
                  >
                  <select
                    id="rooms"
                    class="w-full px-4 py-2 mt-1 text-black border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  >
                    <option class="text-black">Select</option>
                    <option class="text-black">1</option>
                    <option class="text-black">2</option>
                    <option class="text-black">3</option>
                  </select>
                </div>
                <div>
                  <label
                    for="children"
                    class="block text-sm font-medium text-gray-700"
                    >Children:</label
                  >
                  <select
                    id="children"
                    class="w-full px-4 py-2 mt-1 text-black border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  >
                    <option class="text-black">Select</option>
                    <option class="text-black">0</option>
                    <option class="text-black">1</option>
                    <option class="text-black">2</option>
                  </select>
                </div>
                <div>
                  <label
                    for="adults"
                    class="block text-sm font-medium text-gray-700"
                    >Adult:</label
                  >
                  <select
                    id="adults"
                    class="w-full px-4 py-2 mt-1 text-black border rounded-md outline-none focus:ring-2 focus:ring-blue-500"
                  >
                    <option class="text-black">Select</option>
                    <option class="text-black">1</option>
                    <option class="text-black">2</option>
                    <option class="text-black">3</option>
                  </select>
                </div>
              </div>

              <div class="flex items-center mt-6">
                <input
                  type="checkbox"
                  id="terms"
                  class="w-5 h-5 text-blue-600 border-gray-300 rounded focus:ring-2 focus:ring-blue-500"
                />
                <label for="terms" class="ml-2 text-sm text-gray-700"
                  >I have read and agree with the terms</label
                >
              </div>
              <button
                type="submit"
                class="w-full py-2 mt-6 text-white transition bg-black rounded-md hover:bg-gray-800"
              >
                Send
              </button>
            </form>
          </div>
        </div>
      </footer>
    </section>
  </div>
</template>
