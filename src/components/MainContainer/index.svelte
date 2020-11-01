<script>
import Textbox from '../Textbox/index.svelte'
</script>
  
<style>

</style>
  
<div class="h-full w-full bg-pink-300 md:pt-20">
  <div class=" p-10 py-70 flex flex-col flex-wrap justify-items-center content-center">
    <Textbox />
    <h1 class=" m-0 p-0 text-3xl font-extrabold text-black text-center">DO NOT HIRE</h1>
    <div class=" m-0  p-0  text-xl  text-black  antialiased  text-center">Link to the linkedin profile</div>
    <div class=" mt-3 md:w-2/5 flex flex-row">
      <input type="text" class=" text-gray-600  w-3/4  p-2  rounded-l-lg" placeholder="http://www.linkedin.com/do-not-hire"/>
      <button class="p-3  w-1/4  bg-teal-600  rounded-r-lg  text-black hover: bg-teal-300" type="button">Submit</button>
    </div>
  </div>
</div>