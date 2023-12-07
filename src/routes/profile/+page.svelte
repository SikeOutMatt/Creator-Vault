<script>
import Header from "../../components/header.svelte";
import Footer from '../../components/footer.svelte';
import thumbnail from "../../lib/assets/thumbnail.webp";
import profilebanner from "../../lib/assets/profilebanner.png";
import xlogo from "../../lib/assets/x-twitter.svg";
import instagram from "../../lib/assets/instagram.png";
import oflogo from "../../lib/assets/ofLogo.png";
import profllepic from "../../lib/assets/profilepic.jpeg";




let userTitle = "BunnyFuFuu's Vault";

    /** @type {import('./$types').PageData} */
    export let data;
</script>

<main>
    <Header />
    <div>
            <div class="">
                <section class="w-4/5 mx-auto bg-gray-100 rounded-md">
                    <div class="flex justify-center w-full">
                        <img class="rounded-md w-full max-h-48 object-fill" src={profilebanner} alt="Banner">
                    </div>
                    <div>
                        <img src={profllepic} alt="profilepic" class="rounded-full w-40 h-30 mx-auto -mt-20 object-fill">
                    </div>
                    <div class="flex flex-col justify-start items-center">
                        <h1 class="text-4xl font-bold"> BunnyFuFuu's Vault </h1>
                    </div>
                    <div class="flex justify-center items-center">
                        <h5 class="text-xl font-semibold"> @BunnyFuFuu </h5>
                    </div>
                    <div class="flex justify-center items-center pb-5">
                        <img class="mx-2" src={xlogo} height="30px" width="30px" > 
                        <img class="mx-2" src={instagram} height="30px" width="30px"> 
                        <img class="mx-2" src={oflogo} height="30px" width="30px">
                    </div>
                </section>

                <div class=" w-4/5 mx-auto grid sm-grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-3 mt-4">
                    <div class="bg-gray-100 rounded-md"> 
                        <img class="rounded-xl p-1" src={thumbnail} alt="thumbnail" width="100%" height="100%">
                        <div class="px-2">
                            <h1 class="font-bold text-2xl"> Video Title </h1>
                            <div class="flex justify-between">
                                <p> Video Description </p>
                                <p> Video Length </p>
                            </div>
                            <h4> Price: $49.99 </h4>
                        </div>
                    </div>
                    
            

                 
                </div>
                
            </div>
        </div>
<Footer />


</main>