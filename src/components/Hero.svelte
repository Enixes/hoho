<script>
    import Header from "./Header.svelte";
    import SectionWrapper from "./SectionWrapper.svelte";

</script>
<SectionWrapper>
    <Header />
        <div
            class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14"
        >
            <h2
                class="text-5xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1200px] mx-auto w-full text-center font-semibold"
            >
                <span class="text-indigo-400">Property</span> Searching
                <span class="text-slate-600 line-through">Is Hard</span><br />
                Just Got <span class="text-indigo-400">Easier</span>
            </h2>

</SectionWrapper>