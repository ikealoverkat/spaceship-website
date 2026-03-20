<script>
    import { animate, createDraggable } from "animejs";
</script>

<!-- body -->
<div class="relative w-screen overflow-x-hidden">
    <!-- space -->
    <div
        class="w-full h-screen bg-cover bg-top bg-no-repeat space_gradient place-items-center justify-center flex flex-col"
    >
        <div class="flex flex-col place-items-center">
            <img
                src="logo_spaceship.png"
                alt="spaceship logo"
                class="w-[150vh] hover:scale-105 duration-300"
            />
            <h1
                class="text-5xl text-center jojoba text-white-bright text-shadow-lg text-shadow-white-bright/60 hover:text-shadow-xl hover:text-shadow-white-bright duration-300 hover:scale-101"
            >
                <b class="underline decoration-white-bright">Learn</b> something
                technical, get money for a
                <b class="underline decoration-white-bright">trip!</b>
            </h1>
            <div class="flex flex-row">
                <input
                    type="text"
                    class="outline-6 rounded-4xl outline-blue-bright hover:bg-blue-bright/25 hover:scale-105 duration-300 drop-shadow-lg bg-blue-bright/15 drop-shadow-blue-bright w-[65vh] m-[3vh] p-[2vh] place-self-center text-center jojoba text-4xl text-blue-bright text-shadow-sm text-shadow-blue-bright hover:drop-shadow-xl hover:drop-shadow-blue-bright"
                    placeholder="enter your email here..."
                />
                <input
                    type="submit"
                    value="RSVP!"
                    class="rounded-4xl bg-amber-500 p-[4vh] m-[2vh] text-4xl jojoba font-extrabold text-navy-bright text-border"
                />
            </div>
        </div>
    </div>

    <!-- sky -->
    <div
        class="w-full h-screen bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_sky.png'), linear-gradient(to bottom, transparent, #BEE1F3);"
    >
        <!-- planet and text -->
        <div class="p-[8vh] place-items-center">
            <h1
                class="interphases large-text-border drop-shadow-md drop-shadow-navy-bright/40 relative text-4xl lg:text-6xl hover:scale-102 duration-300 font-bold text-purple-dark m-[2vh] mb-[4vh] text-center z-10"
            >
                visit a new planet! learn something new...
            </h1>
            <div
                class="flex flex-col lg:gap-[12vh] lg:flex-row w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[50%] z-10">
                    <h2
                        class="jojoba text-border drop-shadow-md drop-shadow-navy-bright/40 text-purple-mid text-xl md:text-3xl lg:text-5xl m-[2vh] md:m-[3vh] lg:m-[8vh] text-pretty hover:scale-105 duration-300"
                    >
                        You'll randomly get a technical tool to learn. Make and
                        ship a project with it. <br /> Get a spaceship part for every
                        hour you spend on your project, and exchange them for prizes!
                    </h2>
                </div>
                <!-- planet & background star -->
                <div
                    class="relative flex items-center justify-center scale-100 lg:scale-150"
                    style="width: 800px; height: 800px;"
                >
                    <!-- planet -->
                    <img
                        src="landing/icon_webdevplanet.png"
                        alt="planet"
                        class="absolute z-10 w-100 duration-300 hover:scale-110 animate-[wiggle_2s_ease-in-out_alternate_infinite]"
                    />
                    <img
                        src="landing/star_purple.png"
                        alt="purple star behind the planet"
                        class="absolute z-9 w-130 hover:scale-120 duration-500 animate-[spin_150s_linear_infinite]"
                    />
                </div>
            </div>
        </div>
    </div>

    <!-- land -->
    <div
        class="w-full h-[200vh] mt-[2vh] lg:mt-[8vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_land.png'), linear-gradient(to bottom, #6DE137, #F9A8D4);"
    >
        <!-- planet and text -->
        <div class="gap-[5vh] p-[8vh] place-items-center lg:-mt-[30vh]">
            <div
                class="flex flex-col lg:gap-[10vh] lg:flex-row-reverse w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-full lg:w-[40%]">
                    <h2
                        class="relative z-10 jojoba text-border drop-shadow-md drop-shadow-navy-bright/40 text-navy-bright/65 text-xl md:text-3xl lg:text-5xl m-[2vh] md:m-[3vh] lg:m-[8vh] text-pretty hover:scale-105 duration-300"
                    >
                        Once you get 35 spaceship parts, you can repair your
                        spaceship and get $300 to go on a real trip! You can
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
                            class="absolute z-10 w-105 duration-300 hover:scale-120 animate-[wiggle_2s_ease-in-out_alternate_infinite]"
                        />
                        <img
                            src="landing/star_yellow.png"
                            alt="yellow star behind the planet"
                            class="absolute z-9 w-150 hover:scale-120 duration-500 animate-[spin_150s_linear_infinite]"
                        />
                    </div>
                </div>
            </div>
        </div>
        <!-- prizes text -->
        <h2
            class="interphases text-8xl ml-[6vh] mb-[4vh] large-text-border drop-shadow-lg drop-shadow-[#317BD0]/80 text-[#317BD0]"
        >
            prizes
        </h2>
        <div class="flex">
            <!-- prizes -->
            <div
                class="animate-[scroll_20s_linear_infinite] relative left-[-20%] flex flex-row [&>img]:hover:scale-105 [&>img]:opacity-75 [&>img]:duration-200 [&>img]:drop-shadow-white [&>img]:drop-shadow-lg [&>img]:hover:drop-shadow-2xl [&>img]:hover:drop-shadow-white"
            >
                <img src="landing/prize_ikeaalien.png" alt="ikea alien prize" />
                <img src="landing/prize_crunch.png" alt="crunch prize" />
                <img src="landing/prize_drone.png" alt="drone prize" />
                <img src="landing/prize_camera.png" alt="camera prize" />
                <img src="landing/prize_tickets.png" alt="tickets prize" />
                <img
                    src="landing/prize_vlogcamera.png"
                    alt="vlog camera prize"
                />
            </div>
            <div
                class="relative left-[50%] animate-[scroll_20s_linear_infinite] flex flex-row [&>img]:hover:scale-105 [&>img]:opacity-75 [&>img]:duration-200 [&>img]:drop-shadow-white [&>img]:drop-shadow-lg [&>img]:hover:drop-shadow-2xl [&>img]:hover:drop-shadow-white"
            >
                <img src="landing/prize_ikeaalien.png" alt="ikea alien prize" />
                <img src="landing/prize_crunch.png" alt="crunch prize" />
                <img src="landing/prize_drone.png" alt="drone prize" />
                <img src="landing/prize_camera.png" alt="camera prize" />
                <img src="landing/prize_tickets.png" alt="tickets prize" />
                <img
                    src="landing/prize_vlogcamera.png"
                    alt="vlog camera prize"
                />
            </div>
        </div>
    </div>

    <!-- footer -->
    <div
        class="w-full h-[200vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_footer.png');"
    ></div>
</div>
