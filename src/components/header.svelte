<script>
import Logo from '../lib/assets/Logo.webp'
import Hamburer from '../lib/assets/hamburger.png'

</script> 

<main>
    <div class="w-10/12	mx-auto">
        <div class="flex justify-between">
            <div>
                <img src={Logo} alt="logo" width="200" height="150">
            </div>
            <div class>
                <nav class=""> 
                    <img class="md:hidden mt-10" src={Hamburer} width="30" height="30" alt="hamburger menu icon">
                    <ul class="hidden md:flex mt-10 items-center ">
                        <li class="px-2"> <a> Home </a></li>
                        <li class="px-2"> <a href="/profile"> Profile </a>  </li>
                        <li class="px-2"> <a href="/account"> Account </a> </li>
                        <a href="/upload"> <button class="text-md font-bold p-2 bg-black rounded-md text-white"> Upload </button></a>
                    </ul>
                </nav>
            </div>
        </div>
    </div>
</main>