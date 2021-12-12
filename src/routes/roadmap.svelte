<script>
    import Header from "../components/Header.svelte";
    import NFTTriptych from "../images/nft-triptych.png";

    let DiscordLink = 'https://discord.gg/vGFZEZzy8T';
    let NiFTyHorsesLink = 'https://NiFTyHorses.com';
    let TwitterLink = 'https://twitter.com/NiFTyHorses';
</script>

<svelte:head>
    <title>NiFTy Horses - Roadmap</title>
</svelte:head>

<Header 
    headline="Roadmap"
    imgsource="https://images.unsplash.com/photo-1531403009284-440f080d1e12?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=60&&sat=-100"
    description="NiFTy Horses does not strive to over-saturate or over-promise perks that come with owning one of our Horses."
/>

<div class="relative py-16 bg-white overflow-hidden">
    <div class="relative px-4 sm:px-6 lg:px-8">
        <div class="text-lg max-w-prose mx-auto">
            <img src="{NFTTriptych}" alt="NiFTy Horses Triptych" class="mb-16 w-full" />
            <h2><span class="block text-base text-center text-indigo-600 font-semibold tracking-wide uppercase">Roadmap</span></h2>
            <div class="text-xl text-gray-500 leading-8">
                <h3>
                    <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">In The Workshop</span>
                </h3>
    
                <ul role="list" class="mt-4">
                    <li>Launch NiFTy Horses website (niftyhorses.com)  <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-blue-500 rounded-full">In Progress</span></li>
                    <li>Unveil NiFTy Horses Attributes <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-rose-500 rounded-full">Launching after mint</span></li>
                    <li>Open NiFTy Horses Marketplace <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-rose-500 rounded-full">Launching after mint</span></li>
                </ul>
            </div>

            <div class="mt-16 text-xl text-gray-500 leading-8">
                <h3>
                    <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Completed</span>
                </h3>
                
                <ul role="list" class="mt-4">
                    <li>NiFTy Horses base artwork  <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-green-500 rounded-full">Completed</span></li>
                    <li><a href="{DiscordLink}" class="underline hover:no-underline">NiFTy Horses Discord</a> Launch <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-green-500 rounded-full">Completed</span></li>
                    <li><a href="{TwitterLink}" class="underline hover:no-underline">NiFTy Horses Twitter</a> <span class="px-3 py-0.5 text-white text-xs font-semibold leading-5 uppercase tracking-wide bg-green-500 rounded-full">Completed</span></li>
                </ul>
            </div>

            <div class="mt-16 text-xl text-gray-500 leading-8">
                <h3>
                    <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Minting</span>
                </h3>
                
                <ul role="list" class="mt-4">
                    <li>NiFTy Horses will be minted via our website <a href="{NiFTyHorsesLink}" class="underline hover:no-underline">NiFTyHorses.com</a></li>
                    <li>Our target supply is currently 4,000 with a minting price of .25 SOL</li>
                    <li>The goal is to provide a donation before the New Year. As such, we are aiming for a mid-December launch</li>
                    <li>After mint, we will work with community members to create a DAO that will have their own server on <a href="{DiscordLink}" class="underline hover:no-underline">our Discord</a>!</li>
                </ul>
            </div>

            <div class="mt-16 text-xl text-gray-500 leading-8">
                <h3>
                    <span class="mt-2 block text-3xl text-center leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl">Perks &amp; Incentives</span>
                </h3>
                <p class="mt-8 text-xl text-gray-500 leading-8">NiFTy Horses does not strive to over-saturate or over-promise perks that come with owning one of our Horses. By minting a NiFTy Horse, you’re choosing to support a terrific 501 (c)(3) nonprofit. Your contribution will have real-world implications and long-lasting effects. The generosity of the NiFTy Horses community will allow the organization to continue to provide enriching experiences. The funds raised will positively impact the mental health and overall wellbeing of program participants for many years to come.</p>
                <p class="mt-8 text-xl text-gray-500 leading-8">Our perks are currently oriented towards those who mint a Nifty Horse. The goal of the project is to raise funds for a charity, but also to mint something for your wallet that can remind you that having fun can also mean doing good!</p>
            </div>
        </div>
    </div>
</div>

<style>
    ul {
        list-style: disc;
    }
</style>
