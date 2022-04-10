<template>
  <div class="h-full w-full py-12 px-4">
    <div class="flex flex-col items-center justify-center">
      <div class="bg-white shadow-sm shadow-indigo-500 rounded lg:w-5/12 md:w-6/12 w-full py-10 px-16">
        <p tabindex="0" class="focus:outline-none text-2xl font-extrabold leading-6 text-gray-800">Login to your account</p>
        <p tabindex="0" class="focus:outline-none text-sm mt-4 font-medium leading-none text-gray-500">Dont have account? <a href="javascript:void(0)"   class="hover:text-gray-500 focus:text-gray-500 focus:outline-none focus:underline hover:underline text-sm font-medium leading-none  text-gray-800 cursor-pointer"> Sign up here</a></p>
        
        <button aria-label="Continue with google" role="button" class="focus:outline-none focus:ring-2 focus:ring-offset-1 focus:ring-gray-700 py-2.5 px-4 border rounded-lg border-gray-700 flex items-center w-full mt-10">
            <svg-google/>
            <p class="text-base font-medium ml-4 text-gray-700">Continue with Google</p>
        </button>

        <button aria-label="Continue with github" role="button" class="focus:outline-none  focus:ring-2 focus:ring-offset-1 focus:ring-gray-700 py-2.5 px-4 border rounded-lg border-gray-700 flex items-center w-full mt-4">
            <svg-github/>                            
            <p class="text-base font-medium ml-4 text-gray-700">Continue with Github</p>
        </button>

        <div class="w-full flex items-center justify-between py-5">
          <hr class="w-full bg-gray-400">
          <p class="text-base font-medium leading-4 px-2.5 text-gray-400">OR</p>
          <hr class="w-full bg-gray-400  ">
        </div>

        <div>
            <label for="first-name" class="block text-sm font-medium text-gray-700">First name</label>
            <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="mt-1 py-2.5 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
        </div>

        <div class="mt-6  w-full">
          <label for="first-name" class="block text-sm font-medium text-gray-700">Password</label>
            <div class="relative flex items-center justify-center">
            <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="mt-1 py-2.5 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
              <div class="absolute right-0 mt-2 mr-3 cursor-pointer">
                  <svg-eye/>
              </div>
            </div>
        </div>

        <div class="mt-8">
            <button role="button" class="focus:ring-2 focus:ring-offset-2 focus:ring-indigo-700 text-sm font-semibold leading-none text-white focus:outline-none bg-indigo-700 border rounded hover:bg-indigo-600 py-4 w-full">Create my account</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'false',
  head() {
    return {
      title: 'Login'
    }
  }
}
</script>

<style>

</style>