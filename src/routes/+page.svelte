<script>
    import Step from "../components/Step.svelte";

    let steps = [
        {
            name: "Assemble",
            num: 11,

            icon: "fa-solid fa-hammer",
        },
        {
            name: "Visualize",
            num: 11,

            icon: "fa-regular fa-eye",
        },
        {
            name: "Deploy",
            num: 11,

            icon: "fa-solid fa-cloud-arrow-up",
        },
    ];

    let benefits = [
        {
            metric: "10x",
            name: "Build your own AI blocks",
            description:
                "This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph.",
            icon: "fa-solid fa-cubes",
            descriptors: [
                "Detect anomalies in videos",
                "Monitor telegram",
                "Recognize objects",
                "Analyze sonar",
                "Voice authentication",
                "Detect strategies",
                "GPT-4 applications",
                "Translate text",
                "Analyze language",
            ],
        },
        {
            name: "Build scalable applications",
            description:
                "This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph.",
            icon: "fa-solid fa-layer-group",
            descriptors: [
                "Code agnostics",
                "All types of data",
                "Repeatable",
                "Reliable and secure",
                "Highly collaborative",
            ],
        },
        {
            name: "Understand your operational envelope",
            description:
                "This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph. This is some generic text that can later be replaced with a specific paragraph.",
            icon: "fa-regular fa-envelope",
            descriptors: [
                "Automated model robustness testing for trustable AI",
                "Deep model diagnostics and AI explainability",
            ],
        },
    ];
</script>

<main class="flex flex-col flex-1 max-w-[1400px] mx-auto w-full p-4">
    <section
        class="flex-1 grid grid-cols-1 xl:grid-cols-3 gap-10 py-10 sm:py-14 md:py-24"
    >
        <div class="flex flex-col gap-10 w-full text-center">
            <div class="flex flex-col xl:items-start md:gap-2 w-full gap-y-0">
                <h2 class="font-semibold text-5xl sm:text-6xl md:text-7xl">
                    Assemble.
                </h2>

                <h2 class="font-semibold text-5xl sm:text-6xl md:text-7xl">
                    Visualize.
                </h2>
                <h2 class="font-semibold text-5xl sm:text-6xl md:text-7xl">
                    Deploy.
                </h2>
            </div>
            <p
                class="text-base sm:text-lg max-w-[500px] mx-auto xl:ml-0 text-slate-300 xl:max-w-[400px] xl:text-left"
            >
                ZetaForge™ is a <mark class="text-white bg-indigo-600"
                    >AI platform</mark
                > for rapid development and deployment of advanced safe AI solutions.
            </p>
            <a
                href="https://forms.gle/8dJpYFuLABwpJiWYA"
                target="_blank"
                class="px-5 py-3 cursor-pointer sm:px-6 sm:py-4 md:px-8 relative group text-lg sm:text-xl mx-auto xl:ml-0 bg-indigo-800 hover:bg-indigo-900 duration-200"
            >
                <p class="headerFont">Get started today</p>
            </a>
        </div>
        <div
            class="grid place-items-center xl:col-span-2 w-full max-w-[800px] mx-auto xl:max-w-full"
        >
            <img
                src="neato.png"
                alt="zetaforge interface"
                class="w-full h-full object-contain"
            />
        </div>
    </section>

    <!-- <div class="absolute inset-0 z-[-1] opacity-30" id="bgEffect"/> -->
    <section
        class="flex flex-col py-6 sm:py-10 md:py-14 gap-14 sm:gap-16 md:gap-20"
    >
        <div class="flex flex-col gap-8 sm:gap-10 pt-8">
            <h2
                class="font-medium text-3xl sm:text-4xl md:text-5xl max-w-[700px] mx-auto w-full text-center"
            >
                Simple <span class="text-indigo-500">development</span>
                for complex applications
            </h2>
            <p
                class="text-slate-300 text-base sm:text-lg mx-auto max-w-[600px] w-full mx-auto text-center"
            >
                ZetaForge™ allows you to <mark class="text-white bg-indigo-600"
                    >assemble and customize blocks</mark
                > into highly visual AI pipelines.
            </p>
            <!-- <a
                class="px-5 py-2 relative group flex items-center gap-3 mx-auto"
                href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
                target="_blank"
            >
                <div
                    class="absolute top-0 left-0 w-2/3 h-2/3 border-l-2 border-t-2 border-solid border-slate-900 group-hover:w-full group-hover:h-full duration-200"
                />
                <div
                    class="absolute bottom-0 right-0 w-2/3 h-2/3 border-b border-r border-solid border-slate-900 group-hover:w-full group-hover:h-full duration-200"
                />
                <i class="fa-regular fa-circle-play" />

                <p class="headerFont">Watch the video</p>
            </a> -->
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 lg:gap-10">
            <Step step={steps[0]}>
                <p class="text-slate-300">
                    Effortlessly construct advanced AI pipelines by seamlessly
                    connecting drag-and-drop, containerized code blocks,
                    ensuring a smooth and efficient development experience.
                </p>
            </Step>
            <Step step={steps[1]}>
                <p class="text-slate-300">
                    Elevate transparency and credibility with integrated
                    visualization and AI explainability blocks, enhancing both
                    understanding and demonstrable robustness throughout the
                    data flow.
                </p>
            </Step>
            <Step step={steps[2]}>
                <p class="text-slate-300">
                    Instantly deploy and access sophisticated AI pipelines,
                    retrieving workload results swiftly and seamlessly through
                    our user-friendly API.
                </p>
            </Step>
        </div>
        <div class="mx-auto text-center">
            <p class="opacity-80 italic headerFont">
                To be notified when ZetaForge™ is publicly available, and for
                development updates, <a
                    href="https://forms.gle/8dJpYFuLABwpJiWYA"
                    target="_blank"
                    ><span class="cursor-pointer text-indigo-400 headerFont"
                        >subscribe to the newsletter &rarr;</span
                    ></a
                >
            </p>
        </div>
    </section>
    <section
        id="about"
        class="flex flex-col py-6 sm:py-10 md:py-14 gap-14 sm:gap-16 md:gap-20"
    >
        <div class="flex flex-col gap-8 sm:gap-10">
            <div class="w-full grid place-items-center relative">
                <h2
                    class="font-medium text-3xl sm:text-4xl md:text-5xl max-w-[700px] w-full text-center relative py-4"
                >
                    How can <span class="text-indigo-500">ZetaForge™</span>
                    benefit you?
                </h2>
            </div>
            <p
                class="text-slate-300 text-base sm:text-lg mx-auto max-w-[700px] w-full mx-auto text-center"
            >
                <mark class="text-white bg-indigo-600"
                    >Automate the boring work</mark
                >
                and spend more time doing the development you love. ZetaForge™ helps
                accelerate your AI deployment, benefit from repeatability and reusibility,
                experience responsible AI and risk governance and so much more.
            </p>
        </div>

        <div class="flex flex-col gap-20 w-fit mx-auto max-w-[900px]">
            {#each benefits as benefit, index}
                <!-- <div class="flex flex-col gap-2 mx-auto">
                    <div class="flex items-end gap-4">
                        <p
                            class="poppins text-6xl sm:text-7xl md:text-8xl text-slate-500 font-medium"
                        >
                            {benefit.metric}
                        </p>
                        <p
                            class="text-xl sm:text-2xl md:text-3xl capitalize pb-2"
                        >
                            {benefit.name}
                        </p>
                    </div>
                    <p class="text-center italic">- {benefit.description}</p>
                </div> -->

                <div class="flex flex-col gap-2 sm:gap-4 md:gap-6 lg:gap-8">
                    <div class="flex items-start gap-2 sm:gap-4">
                        <div
                            class="grid opacity-0 place-items-center shrink-0 text-2xl sm:text-3xl md:text-4xl lg:text-5xl text-indigo-500 border py-2 w-8 sm:w-10 md:w-14 lg:w-20"
                        />
                        <div
                            class="bg-indigo-800 mr-auto rounded text-white text-base sm:text-lg md:text-xl px-2 py-1"
                        >
                            <p>Step <b>{index + 1}</b></p>
                        </div>
                    </div>
                    <div class="flex items-start gap-2 sm:gap-4">
                        <div
                            class="grid place-items-center shrink-0 text-2xl sm:text-3xl md:text-4xl lg:text-5xl text-indigo-500 py-2 w-8 sm:w-10 md:w-14 lg:w-20"
                        >
                            <i class={benefit.icon} />
                        </div>
                        <div class="flex flex-col gap-6 sm:gap-8">
                            <h3
                                class="text-2xl sm:text-3xl md:text-4xl headerFont"
                            >
                                {benefit.name}
                            </h3>
                            <div
                                class="grid grid-cols-1 lg:grid-cols-3 gap-2 gap-x-4"
                            >
                                {#each benefit.descriptors as descriptor, i}
                                    <div class="flex items-center gap-2">
                                        <p class="headerFont">· {descriptor}</p>
                                    </div>
                                {/each}
                            </div>
                        </div>
                    </div>
                </div>
            {/each}
        </div>
    </section>
    <a
        href="https://forms.gle/8dJpYFuLABwpJiWYA"
        target="_blank"
        class="px-5 py-3 cursor-pointer sm:px-6 sm:py-4 md:px-8 relative group text-lg sm:text-xl mx-auto bg-indigo-800 hover:bg-indigo-900 duration-200"
    >
        <p class="headerFont">Get started today</p>
    </a>
</main>

<svelte:head>
    <title>Zetaforge</title>
    <meta
        name="description"
        content="Effortlessly construct advanced AI pipelines by seamlessly
        connecting drag-and-drop, containerized code blocks,
        ensuring a smooth and efficient development experience."
    />
</svelte:head>
