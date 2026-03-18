<script>
    import { animate, createDraggable } from "animejs";
</script>

<!-- body -->
<div class="relative w-screen">
    <!-- space -->
    <div
        class="w-full h-screen bg-cover bg-top bg-no-repeat space_gradient place-items-center"
    ></div>

    <!-- sky -->
    <div
        class="w-full h-screen bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_sky.png'), linear-gradient(to bottom, transparent, #BEE1F3);"
    >
        <!-- planet and text -->
        <div class="gap-[4vh] p-[8vh] place-items-center">
            <h1
                class="absolute text-4xl lg:text-6xl font-bold text-navy-bright m-[2vh] mb-[4vh] text-center z-10"
            >
                visit a new planet! learn something new...
            </h1>
            <div
                class="flex flex-col lg:flex-row w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[50%]">
                    <h2
                        class="text-navy-bright text-xl md:text-3xl lg:text-6xl m-[2vh] md:m-[3vh] lg:m-[8vh] z-10 text-pretty"
                    >
                        You'll randomly get a technical tool to learn. Make and
                        ship a project with it. <br /> Get a spaceship part for every
                        hour you spend on your project, and exchange them for prizes!
                    </h2>
                </div>
                <!-- planet + spinning logos -->
                <div
                    class="relative flex items-center justify-center scale-150"
                    style="width: 800px; height: 800px;"
                >
                    <!-- planet -->
                    <img
                        src="landing/icon_webdevplanet.png"
                        alt="planet"
                        class="absolute z-10 w-64 scale-200 duration-300 hover:scale-220"
                    />

                    <!-- spinning div -->
                    <div
                        class="absolute inset-0 duration-300 hover:scale-115"
                        style="animation: spin 40s linear infinite; transform-origin: center;"
                    >
                        <!-- top -->
                        <img
                            src="landing/logos/react.png"
                            alt="react"
                            class="absolute top-0 left-1/2 -translate-x-1/2 w-40 drop-shadow-lg"
                        />
                        <!-- right -->
                        <img
                            src="landing/logos/astro.png"
                            alt="astro"
                            class="absolute right-0 top-1/2 -translate-y-1/2 w-30 drop-shadow-lg"
                        />
                        <!-- bottom -->
                        <img
                            src="landing/logos/svelte.png"
                            alt="svelte"
                            class="absolute bottom-0 left-1/2 -translate-x-1/2 w-30 drop-shadow-lg"
                        />
                        <!-- left -->
                        <img
                            src="landing/logos/tailwind.png"
                            alt="tailwind"
                            class="absolute left-0 top-1/2 -translate-y-1/2 w-30 drop-shadow-lg"
                        />
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- land -->
    <div
        class="w-full h-[200vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_land.png'), linear-gradient(to bottom, #6DE137, #F9A8D4);"
    >
        <div class="gap-[4vh] p-[8vh] place-items-center lg:-mt-[30vh]">
            <div
                class="flex flex-col lg:flex-row-reverse w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[40%]">
                    <h2
                        class="text-navy-bright text-xl md:text-3xl lg:text-6xl m-[2vh] md:m-[3vh] lg:m-[8vh] text-pretty"
                    >
                        If you spend 35 hours on your projects, you can repair
                        your spaceship and get $300 to go on a trip! You can
                        also exchange your spaceship parts for other prizes...
                    </h2>
                </div>
                <!-- planet -->
                <div>
                    <img
                        src="landing/icon_gamedevplanet.png"
                        alt="planet with text gamedevplanet on top"
                        class="duration-300 hover:scale-90"
                    />
                </div>
            </div>
        </div>
    </div>

    <!-- footer -->
    <div
        class="w-full h-[200vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_footer.png');"
    ></div>
</div>
