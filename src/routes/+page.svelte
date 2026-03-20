<script>
    import { animate, createDraggable } from "animejs";
</script>

<!-- body -->
<div class="relative w-screen overflow-x-hidden">
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
        <div class="p-[8vh] place-items-center">
            <h1
                class="relative text-4xl lg:text-6xl font-bold text-navy-bright m-[2vh] mb-[4vh] text-center z-10 text-shadow-white-bright text-shadow-lg"
            >
                visit a new planet! learn something new...
            </h1>
            <div
                class="flex flex-col lg:gap-[12vh] lg:flex-row w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[50%] z-10">
                    <h2
                        class="text-navy-bright text-xl md:text-3xl lg:text-5xl m-[2vh] md:m-[3vh] lg:m-[8vh] text-pretty hover:scale-105 duration-300"
                    >
                        You'll randomly get a technical tool to learn. Make and
                        ship a project with it. <br /> Get a spaceship part for every
                        hour you spend on your project, and exchange them for prizes!
                    </h2>
                </div>
                <!-- planet + spinning logos -->
                <div
                    class="relative flex items-center justify-center scale-100 lg:scale-150"
                    style="width: 800px; height: 800px;"
                >
                    <!-- planet -->
                    <img
                        src="landing/icon_webdevplanet.png"
                        alt="planet"
                        class="absolute z-10 w-64 scale-200 duration-300 hover:scale-220 animate-[wiggle_2s_ease-in-out_alternate_infinite]"
                    />
                </div>
            </div>
        </div>
    </div>

    <!-- land -->
    <div
        class="w-full h-[200vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_land.png'), linear-gradient(to bottom, #6DE137, #F9A8D4);"
    >
    <!-- planet and text -->
        <div class="gap-[4vh] p-[8vh] place-items-center lg:-mt-[30vh]">
            <div
                class="flex flex-col lg:gap-[10vh] lg:flex-row-reverse w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[40%]">
                    <h2
                        class="relative z-10 text-navy-bright text-xl md:text-3xl lg:text-5xl m-[2vh] md:m-[3vh] lg:m-[8vh] text-pretty hover:scale-105 duration-300"
                    >
                        Once you get 35 spaceship parts, you can repair
                        your spaceship and get $300 to go on a real trip! You can
                        also exchange your spaceship parts for other prizes...
                    </h2>
                </div>
                <!-- planet +spinning -->
                <div>
                    <div
                        class="relative flex items-center justify-center lg:scale-150"
                        style="width: 800px; height: 800px;"
                    >
                        <!-- planet -->
                        <img
                            src="landing/icon_gamedevplanet.png"
                            alt="planet"
                            class="absolute z-10 w-64 scale-200 duration-300 hover:scale-220 animate-[wiggle_2s_ease-in-out_alternate_infinite]"
                        />
                    </div>
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
