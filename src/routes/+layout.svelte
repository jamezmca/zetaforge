<script>
    import "../app.css";
</script>

<header
    class="sticky top-0 left-0 w-full p-4 sm:py-6 bg-slate-950 text-white border-b border-solid border-indigo-950 z-[100]"
>
    <div
        class="flex max-w-[1400px] mx-auto w-full items-center gap-4 justify-between"
    >
        <h1 class="text-base sm:text-lg">
            <b class="font-light headerFont">Zeta</b>forge
        </h1>
        <div class="flex items-center gap-2 sm:gap-4">
            <a class="" href="#about">
                <p class="headerFont px-4">About</p>
            </a>
            <a
                href="https://forms.gle/8dJpYFuLABwpJiWYA"
                target="_blank"
                class="px-5 py-2 cursor-pointer relative group border-[1.5px] border-solid border-indigo-700 duration-200 hover:border-indigo-800"
            >
                <p class="headerFont">Subscribe</p>
            </a>
        </div>
    </div>
</header>
<slot />
<footer class="py-20 sm:py-24 border-t border-solid border-white mt-20">
    <section
        class="max-w-[1000px] mx-auto w-full grid grid-cols-1 md:grid-cols-3 gap-4"
    >
        <div class="flex flex-col gap-2 sm:gap-4 mx-auto text-center">
            <p class=" jetbrains py-2">ZetaForge™</p>
            <p class=" jetbrains py-2">Zetane Systems © 2023</p>
        </div>
        <div
            class="flex items-start mx-auto gap-4 text-xl sm:text-2xl md:text-3xl"
        >
            <a target="_blank" class="text-slate-300">
                <i class="fa-brands fa-linkedin-in" />
            </a>
            <a target="_blank" class="text-slate-300">
                <i class="fa-brands fa-youtube" />
            </a>
            <a target="_blank" class="text-slate-300">
                <i class="fa-brands fa-discord" />
            </a>
        </div>
        <div class="flex flex-col gap-2 text-center sm:gap-4 mx-auto">
            <a target="_blank" class="jetbrains py-1 text-center md:text-left"
                ><p>Zetane Product Suite &rarr;</p></a
            >
            <a target="_blank" class="jetbrains py-1 text-center md:text-left"
                ><p>Contact us &rarr;</p></a
            >
        </div>
    </section>
</footer>
