<script>
    import { animate, createDraggable } from "animejs";
</script>

<!-- body -->
<div class="relative w-screen overflow-x-hidden">
    <!-- space -->
    <div
        class="w-full h-screen bg-cover bg-top bg-no-repeat space_gradient place-items-center justify-center flex flex-col"
        id="home"
    >
        <!-- nav -->
        <div class="fixed flex flex-row place-self-end top-0 scale-90 lg:scale-75 z-100">
            <a href="#home">
                <img
                    src="landing/icon_home.png"
                    alt="planet with home text on top that links to home screen"
                    class="duration-300 hover:scale-110"
                />
            </a>
            <a href="#about">
                <img
                    src="landing/icon_about.png"
                    alt="planet with about text on top that links to about screen"
                    class="duration-300 hover:scale-110"
                />                
            </a>
            <a href="../../src/routes/faq.svelte">
                <img
                    src="landing/icon_faq.png"
                    alt="planet with faq text on top that links to faq page"
                    class="duration-300 hover:scale-110"
                />
            </a>
            <a href="placeholder.com">
                <img
                    src="landing/icon_signin.png"
                    alt="planet with text on top that says sign in that links to hca auth"
                    class="duration-300 hover:scale-110"
                />
            </a>
        </div>
        <!-- everything -->
        <div class="flex flex-col place-items-center">
            <img
                src="logo_spaceship.png"
                alt="spaceship logo"
                class="w-[50vh] lg:w-[150vh] hover:scale-105 duration-300"
            />
            <h1
                class="text-2xl lg:text-5xl text-center jojoba text-white-bright text-shadow-lg text-shadow-white-bright/60 hover:text-shadow-xl hover:text-shadow-white-bright duration-300 hover:scale-101"
            >
                <b class="underline decoration-white-bright">Learn</b> something
                technical, get money for a
                <b class="underline decoration-white-bright">trip!</b>
            </h1>
            <div class="flex flex-col lg:flex-row">
                <input
                    type="text"
                    class="outline-6 rounded-4xl outline-white-bright  lg:outline-blue-bright hover:bg-blue-bright/25 hover:scale-105 duration-300 drop-shadow-lg bg-white-bright/15 lg:bg-blue-bright/15 
                    drop-shadow-white-bright lg:drop-shadow-blue-bright w-[35vh] lg:w-[65vh] m-[3vh] p-[2vh] place-self-center text-center jojoba text-2xl lg:text-4xl lg:text-blue-bright text-shadow-sm text-white-bright lg:text-shadow-blue-bright hover:drop-shadow-xl hover:drop-shadow-blue-bright"
                    placeholder="enter your email here..."
                />
                <input
                    type="submit"
                    value="            "
                    class="rounded-4xl p-[15vh] lg:p-[4vh] -m-[10vh] lg:m-[2vh] text-4xl jojoba font-extrabold text-navy-bright text-border bg-[url('landing/icon_rsvp.png')] bg-cover scale-40 lg:scale-130 lg:hover:scale-145 hover:rotate-5 rotate-0 duration-300"
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
        <div class="p-[8vh] place-items-center" id="about">
            <h1
                class="interphases large-text-border drop-shadow-md drop-shadow-navy-bright/40 relative text-4xl lg:text-6xl hover:scale-102 duration-300 font-bold text-purple-dark m-[2vh] mb-[4vh] mt-0 md:-mt-[30vh] lg:mt-0 text-center z-10"
            >
                visit a new planet! learn something new...
            </h1>
            <div
                class="flex flex-col lg:gap-[12vh] lg:flex-row w-fit place-items-center text-center place-content-center lg:m-[4vh] "
            >
                <!-- text -->
                <div class="w-[40%] md:w-[80%] lg:w-[50%] z-10 ">
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
        class="w-full h-[200vh] -mt-[2vh] lg:mt-[8vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_land.png'), linear-gradient(to bottom, #6DE137, #F9A8D4);"
    >
        <!-- planet and text -->
        <div class="gap-[5vh] p-[8vh] place-items-center lg:-mt-[30vh]">
            <div
                class="flex flex-col lg:gap-[10vh] lg:flex-row-reverse w-fit place-items-center text-center place-content-center lg:m-[4vh]"
            >
                <!-- text -->
                <div class="w-[40%] md:w-[80%] lg:w-[40%] mt-[40vh] md:-mt-[20vh] lg:mt-0">
                    <h2
                        class="relative screen z-10 jojoba text-border drop-shadow-md drop-shadow-navy-bright/40 text-navy-bright/65 text-xl md:text-3xl lg:text-5xl md:m-[3vh] lg:m-[8vh] text-pretty hover:scale-105 duration-300"
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
            class="interphases text-8xl ml-[6vh] mb-[4vh] large-text-border drop-shadow-lg drop-shadow-[#317BD0]/80 text-[#317BD0] hover:text-[#3562D7] hover:scale-102 place-self-start duration-300"
        >
            prizes
        </h2>
        <div class="flex">
            <!-- prizes -->
            <div
                class="lg:animate-[scroll_20s_linear_alternate_infinite] md:animate-[scroll_6s_linear_alternate_infinite] relative left-[-20%] flex flex-row [&>img]:hover:scale-105 [&>img]:opacity-75 [&>img]:duration-200 [&>img]:drop-shadow-white [&>img]:drop-shadow-lg [&>img]:hover:drop-shadow-2xl [&>img]:hover:drop-shadow-white"
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
                class="relative left-[50%] animate-[scroll_20s_linear_alternate_infinite] flex flex-row [&>img]:hover:scale-105 [&>img]:opacity-75 [&>img]:duration-200 [&>img]:drop-shadow-white [&>img]:drop-shadow-lg [&>img]:hover:drop-shadow-2xl [&>img]:hover:drop-shadow-white"
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
        <h3 class="interphases text-5xl text-border text-[#317BD0] hover:text-[#3562D7] w-fit hover:scale-104 duration-300 drop-shadow-md drop-shadow-navy-bright/75 place-self-end m-[8vh]">+ more!</h3>
    </div>

    <!-- footer -->
    <div
        class="w-full h-[200vh] bg-cover bg-center bg-no-repeat"
        style="background-image: url('/landing/backgrounds/bg_footer.png');"
    >
        <!-- the container with words -->
        <div>
            <h1 class="interphases p-[4vh] text-6xl large-text-border drop-shadow-md drop-shadow-navy-bright/75 text-navy-bright text-center">cool prizes → cool projects → cool trips!</h1>
        </div>
        <!-- pink thing -->
        <div
            class="p-[4vh] m-[6vh] rounded-4xl outline-pink-dull outline-8 w-[75%] place-self-center hover:outline-pink-bright duration-300 drop-shadow-xl drop-shadow-pink-dull bg-pink-dull/30 hover:drop-shadow-pink-bright hover:drop-shadow-xl hover:p-[5vh]"
        >
            <h1
                class="text-6xl hover:font-bold jojoba text-navy-bright drop-shadow-navy-bright/50 drop-shadow-md text-center"
            >
                made w/<b class="text-pink-bright">❤︎⁠</b> &
                <b class="text-yellow-bright">★</b> by kat wang
            </h1>
            <h2
                class="text-4xl jojoba text-[#317BD0] m-[2vh] text-center drop-shadow-navy-bright/50 drop-shadow-sm"
            >
                <a
                    href="https://hackclub.com"
                    class="hover:text-[#3562D7] hover:font-bold duration-300 decoration-wavy hover:underline"
                    >hack club</a
                > <b class="text-[#3562D7]">||</b> by teens, for teens
            </h2>
        </div>
    </div>
</div>
