<template>
  <div class="px-10 border border-stone-400">
    <div class="flex items-center justify-center">
      <img src="/public/user.png" alt="user" class="w-20 h-20" />
    </div>
    <div class="flex flex-col gap2">
      <p>Name</p>
      <p>Email id</p>
      <button class="p-1 px-6 bg-green-400">verified</button>
    </div>
    <hr />
    <div>
      <div class="flex justify-center gap-4">
        <label for="text">Eamil</label>
        <input type="text" placeholder="Email id" />
      </div>
      <div class="flex justify-center gap-4">
        <label for="text">Mobile</label>
        <input type="text" placeholder="Mobile" />
      </div>
      <div class="flex justify-center gap-4">
        <label for="text">Website Url</label>
        <input type="text" placeholder="Url" />
      </div>
    </div>
  </div>
</template>
