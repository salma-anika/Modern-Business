<script>
    import '../app.css';
	import Navbar from '../components/Navbar.svelte';
    import Hero from '../components/Hero.svelte';
	import About from '../components/About.svelte';
  </script>
      <div class=" w-[100%] overflow-hidden bg-black">
        <div class="px-6 sm:px-16 flex justify-center items-center">
          <div class='xl:max-w-[1280px] w-full'>
            <Navbar/>
          </div>
        </div>
  </div>
  <div class='bg-black flex justify-center items-start'>
    <div class='xl:max-w-[1280px] w-full'>
    <Hero/>
    </div>
          </div>
          <div class=' bg-white px-6 sm:px-16 flex justify-center items-start'>
            <div class='xl:max-w-[1280px] w-full'>
            <About/>
            </div>
                  </div>