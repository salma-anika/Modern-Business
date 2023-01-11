<script>
    
    import '../routes/index';
import Button from './Button.svelte';

</script>

<nav class=" w-[100%] flex py-6 justify-between items-center navbar">
    <img src="logo.svg"
    alt="logo"
    class="w-[124px] h-[32px]"/>
    <ul class="list-none sm:flex hidden justify-center items-center flex-1 uppercase">
      
        <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5 max-md:text-[10px]">  
            <a href="/about"> about us</a> 
          </li>
          <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5 max-md:text-[10px]">  
              <a href="/office"> our offices</a> 
            </li>
            <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5 max-md:text-[10px]">  
              <a href="/resource"> resources</a> 
            </li>
            <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5 max-md:text-[10px]">  
              <a href="/company"> for companies</a> 
            </li>
       
    </ul>
    <div class=" max-sm:justify-center items-center max-xs:mr-1 ">
        <Button/>
    </div>
       

    
    
    <div class="sm:hidden flex  flex-1 justify-end items-center uppercase">
        <img src="menu.svg"
        alt="menu"
        class="w-[28px] h-[28px] object-contain"/>
      
        <div class=" p-6 bg-gradient-to-b from-gray-900 to-gray-600 absolute top-20 right-0 mx-4 my-2 min-w-[140px] rounded-xl sidebar">
        <ul class ="list-none flex flex-col justify-end items-center flex-1">
            <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5 ">  
                <a href="/about"> about us</a> 
              </li>
              <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5">  
                  <a href="/office"> our offices</a> 
                </li>
                <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5">  
                  <a href="/resource"> resources</a> 
                </li>
                <li class="font-normal font-poppins cursor-pointer text-[16px]  text-white mr-5">  
                  <a href="/company"> for companies</a> 
                </li>
            </ul>
        </div>
        
      </div>

</nav>