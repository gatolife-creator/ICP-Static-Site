<script>
  let projects = [
    {
      name: "AVAX Messenger",
      url: "https://avax-messenger-b2jpmijxu-gatolife-creator.vercel.app/",
    },
    {
      name: "ETH NFT Collection",
      url: "https://eth-nft-collection-starter-project-i7m3h4j9l-gatolife-creator.vercel.app/",
    },
    {
      name: "ETH dApp",
      url: "https://eth-nft-collection-starter-project-i7m3h4j9l-gatolife-creator.vercel.app/",
    },
  ];
</script>

<section id="portfolio">
  <div class="container mx-auto">
    <div class="py-32">
      <h1 class="text-center mb-10 font-medium text-3xl">PORTFOLIO</h1>
      <div class="flex flex-wrap lg:w-4/5 sm:mx-auto">
        {#each projects as project}
          <div class="p-2 md:w-1/3 w-full">
            <div
              class="bg-gray-400 text-white hover:bg-gray-800 cursor-pointer rounded p-4 text-center"
            >
              <a href={project.url}>{project.name}</a>
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
