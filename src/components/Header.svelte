<!-- This example requires Tailwind CSS v2.0+ -->
<script>
    export let imgsource = 'https://images.unsplash.com/photo-1525130413817-d45c1d127c42?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1920&q=60&&sat=-100';
    export let headline = "Headline";
    export let description = "Description";
</script>

<div class="relative bg-indigo-800">
    <div class="absolute inset-0">
        <img class="w-full h-full object-cover" src="{imgsource}" alt="">
        <div class="absolute inset-0 bg-indigo-800 mix-blend-multiply" aria-hidden="true"></div>
    </div>
    <div class="relative max-w-7xl mx-auto py-24 px-4 sm:py-32 sm:px-6 lg:px-8">
        <h1 class="text-4xl font-extrabold tracking-tight text-white sm:text-5xl lg:text-6xl">{headline}</h1>
        <p class="mt-6 text-xl text-indigo-100 max-w-3xl">{description}</p>
    </div>
</div>
  