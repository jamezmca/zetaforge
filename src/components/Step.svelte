<script>
    export let step;
</script>

<div
    class="p-4 sm:p-6 md:p-8 flex flex-col gap-4 group hover:border-indigo-400 duration-200"
>
    <div
        class="bg-slate-950 flex flex-col text-indigo-600 text-5xl md:text-6xl duration-200"
    >
        <i class={step.icon} />
    </div>
    <h3 class="font-medium text-xl sm:text-2xl md:text-3xl headerFont">
        {step.name}
    </h3>
    <slot />
    <!-- <div class="flex-1 flex justify-betweeen gap-4 items-end">
        <div
            class="ml-auto cursor-pointer hover:text-slate-950 duration-200 relative after:absolute after:top-0 after:h-0 after:right-full after:bg-white after:w-full after:h-full after:duration-200 hover:after:translate-x-full after:z-[-1] overflow-hidden"
        >
            <p class="z-4">Go to &rarr;</p>
        </div>
    </div> -->
</div>
