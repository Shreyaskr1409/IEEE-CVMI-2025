<script>
  export let name = "John Doe";
  export let position = "Software Engineer";
  export let picture = "/la1.jpg";
  export let coverFlag = "object-contain"
</script>

<div
  class="bg-zinc-900 text-zinc-100 rounded-2xl shadow-lg p-4 w-full "
>

    <div class="w-full aspect-square relative rounded-2xl object-cover flex justify-center
        border-2 border-zinc-700 items-center overflow-hidden  transition-transform transform hover:scale-105 hover:shadow-xl">    
        <div
            class="absolute w-full h-full inset-0 bg-center bg-cover filter z-0 blur-sm opacity-50"
            style="background-image: url('{picture}');"
        ></div>

        <img
            id="bg1"
            src={picture}
            alt=""
            loading="lazy"
            class="relative z-10 bg-transparent {coverFlag} object-center h-full"
        />
    </div>
  <h2 class="text-lg font-semibold text-center mt-4">{name}</h2>
  <p class="text-sm text-zinc-400 text-center">{position}</p>
</div>
