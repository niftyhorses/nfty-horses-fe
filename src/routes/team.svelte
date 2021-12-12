<script>
    import Header from "../components/Header.svelte";
    import Team from "../components/Team.svelte";
</script>

<svelte:head>
    <title>NiFTy Horses - Team</title>
</svelte:head>


<Header 
    headline="Team"
    imgsource="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1920&q=60&&sat=-100"
    description="We are a community of developers, designers, artists and collectors who are passionate about giving back."
/>
<div class="container max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
    <Team />
</div>
