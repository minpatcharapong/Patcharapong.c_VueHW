<template>
  <div class="p-8">
    <figure class="bg-gray-100 rounded-xl p-8 shadow-md">
      <div class="pt-6 text-center space-y-4">
        <figcaption class="font-medium">
          <div class="text-gray-500 text-center">
            <li>Tel : {{ tel }}</li>
            <li>E-mail : {{ email }}</li>
            <li>Facebook : {{ facebook }}</li>
            <li>Line : {{ idline }}</li>
          </div>
        </figcaption>
      </div>
    </figure>
  </div>
</template>

<script>
export default {
  data: () => ({
    email: "ch.patcharapong_st@tni.ac.th",
    facebook: "Min Patcharapong",
    tel: "097-181-5647",
    idline: "minpatcharapong",
  }),
};
</script>