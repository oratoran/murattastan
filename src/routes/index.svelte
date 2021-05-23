<script>
	import "../app.postcss";
    import { fly } from 'svelte/transition';
	let nvisible=false, ivisible=false;
    let nationwide = () => {
        nvisible = !nvisible;
        ivisible = false;
    }
    let intl = () => {
        ivisible = !ivisible;
        nvisible = false;
    }
</script>

<svelte:head>
    <title>Murat Taştan - Creative Director @Bucephalus</title>
    <meta name="description" content="Grafik Tasarımcısı Murat Taştan'ın kişisel web sitesi">
</svelte:head>

<main class="flex md:flex-row flex-wrap justify-center items-center mx-auto h-screen border-t-8  border-b-8 border-pink-700">
    <div class="flex flex-col w-full md:w-1/4 bg-gray-900 h-full space-between items-center  ">
        <img src="/murat-tastan-1.jpg" alt="Murat Taştan">
        <h1 class="text-red-500 text-2xl md:text-3xl tracking-widest  pt-10">MURAT TAŞTAN</h1> 
        <p class="text-white text-md md:text-lg tracking-widest">CREATIVE DIRECTOR</p>
        <p class="text-white text-md md:text-lg tracking-widest">MARKA DANIŞMANI</p>
        <p class="text-white text-md md:text-lg tracking-widest"><a href="https://www.bucephalus.com.tr">@BUCEPHALUS <svg xmlns="http://www.w3.org/2000/svg" class="inline h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122" />
          </svg></a></p>

        <div class="text-white text-left text-xs py-5 md:pt-6">
            <p><svg xmlns="http://www.w3.org/2000/svg" class="mr-1 h-4 w-4 inline text-pink-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
            </svg>MURAT@MURATTASTAN.COM</p>

            <p><svg xmlns="http://www.w3.org/2000/svg" class="mr-1 h-4 w-4 inline text-pink-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 3l-6 6m0 0V4m0 5h5M5 3a2 2 0 00-2 2v1c0 8.284 6.716 15 15 15h1a2 2 0 002-2v-3.28a1 1 0 00-.684-.948l-4.493-1.498a1 1 0 00-1.21.502l-1.13 2.257a11.042 11.042 0 01-5.516-5.517l2.257-1.128a1 1 0 00.502-1.21L9.228 3.683A1 1 0 008.279 3H5z" />
            </svg>+90 532 675 83 43</p>
    
            <p><svg xmlns="http://www.w3.org/2000/svg" class="mr-1 h-4 w-4 inline text-pink-700" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" />
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
            </svg>ACIBADEM / KADIKÖY</p>
        </div>

        <div class="text-white">
            <p><a href="https://www.linkedin.com/in/murat-tastan-55a26038/" target="_blank" rel="nofollow">Linkedin</a> <span class="text-pink-700">|</span> <a href="https://www.instagram.com/dejavumn/" target="_blank" rel="nofollow">Instagram</a></p>
        </div>
    </div>
    <div class="w-full md:w-1/3 p-6">
        <div>
            <p class="border-red-600 w-full">Çocukluğumdan beri ilgi duyarak izlediğim televizyon reklamlarının, bugün hayatımı kazanmamı sağlayan mesleğimin kökleri olacağını hayal bile etmemiştim. </p>
            <p class="pt-6">Eğitim hayatım boyunca önce lisans ve sonrasında yüksek lisans seviyesinde alt yapısını sağlamlaştırdığım bilgilerimi, yirmi yıllık ulusal ve uluslararası şirketlere sunduğum yaratıcı ve farklı çalışmalarla birleştirerek yaklaşık 9 yıldır serbest olarak markalara hizmet vermekten çok mutluyum.</p>
            <p class="pt-6">İnanıyorum ki; yapılan tasarımın 1528’de Baldessare Castiglione’nin Il Cortegiano adlı eserinde belirttiği gibi  “doğal olarak yapılmış izlenimi uyandırması” gerekir.</p>
        </div>
        <div class="border-red-600 w-full border-t border-b py-6 my-6 md:my-12">
            <p>Atatürk Üniversitesi - Grafik Bölümü Lisans</p>
            <p>Marmara Üniversitesi - Yüksek Lisans</p>
        </div>
        <p class="text-base text-pink-700 pb-4">TECRÜBELERİM</p>
        <p><button on:click="{nationwide}">Ulusal Şirketler <svg xmlns="http://www.w3.org/2000/svg" class="inline h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122" />
          </svg></button>
        </p>
          {#if nvisible}
          <img src="/ulusal.jpg" alt="Ulusal Firmalar" class="sm:hidden h-auto mx-auto">
          <div in:fly="{{ y: -200, duration: 2000 }}" out:fly="{{ y: -200, duration: 2000 }}" class="hidden sm:block h-3/4 w-2/3 border-t-8 bg-white p-4 border-b-8 border-pink-700 absolute right-0 top-0 shadow-lg">
              <img src="/ulusal.jpg" alt="Ulusal Firmalar" class="h-auto mx-auto">
              <p class="font-semibold text-xl text-right pr-6">ULUSAL ŞİRKETLER</p>
              <button on:click="{nationwide}" class="bg-pink-700 text-white inline-block "><svg xmlns="http://www.w3.org/2000/svg" class="inline h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                </svg></button>
          </div>
        {/if}
        <p><button on:click="{intl}">Çok Uluslu Şirketler<svg xmlns="http://www.w3.org/2000/svg" class="inline h-4 w-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122" />
          </svg></button></p>

          {#if ivisible}
          <img src="/cok-uluslu.jpg" alt="Çok Uluslu Firmalar" class="sm:hidden h-auto mx-auto">
        <div in:fly="{{ y: -200, duration: 2000 }}" out:fly="{{ y: -200, duration: 2000 }}" class="hidden sm:block h-3/4 w-2/3 border-t-8 bg-white p-4 border-b-8 border-pink-700 absolute right-0 top-0 shadow-lg">
            <img src="/cok-uluslu.jpg" alt="Çok Uluslu Firmalar" class="h-5/6 mx-auto">
            <p class="font-semibold text-xl text-right pr-6">ÇOK ULUSLU ŞİRKETLER</p>
            <button on:click="{intl}" class="bg-pink-700 text-white inline-block fixed "><svg xmlns="http://www.w3.org/2000/svg" class="inline h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
              </svg></button>
        </div>
{/if}
    </div>
    <div class="w-full md:w-1/3 border-pink-700 border-b-8 md:border-b-0 md:border-l p-6">
        <p class="text-red-500 font-bold mt-6">1997 - 1999</p>
        <p>Birikim FCA! / Graphic Designer</p>

        <p class="text-red-500 font-bold mt-6">1999 - 2001</p>
        <p>CenAjans Grey  / Graphic Designer</p>

        <p class="text-red-500 font-bold mt-6">2001 - 2003</p>
        <p>Grey İstanbul / Senior Graphic Designer</p>

        <p class="text-red-500 font-bold mt-6">2003 - 2004</p>
        <p>Poyraz Advertising / Art Director</p>

        <p class="text-red-500 font-bold mt-6">2004 - 2007</p>
        <p>Publicis Groupe / Senior Art Director</p>
        
        <p class="text-red-500 font-bold mt-6">2007 - 2013</p>
        <p>Antorium iletişim /  Yarı zamanlı<br/>
            Creative Director & Brand Consultant</p>
        
        <p class="text-red-500 font-bold mt-6">2013 - 2018</p>
        <p>Freelance / Creative Director & Brand Consultant</p>

        <p class="text-red-500 font-bold mt-6">2018 - 2021</p>
        <p>Bucephalus ADV / Kurucu ( Creative Director & Brand Consultant)</p>
    </div>
</main>