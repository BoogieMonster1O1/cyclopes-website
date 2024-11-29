<script>
    import Footer from "../lib/Footer.svelte";
</script>

<svelte:head>
    <title>The Cyclopes</title>
</svelte:head>

<main class="flex flex-col items-center justify-center min-h-screen gap-5">
    <!-- Header Section -->
    <div class="contents">
        <header
            class="flex max-md:flex-col max-md:gap-5 flex-1 my-20 items-center p-6 rounded-lg"
        >
            <img
                src="/logo.png"
                alt="The Cyclopes Logo"
                class="w-80 h-80 md:mr-6 rounded-3xl"
            />
            <div class="flex flex-col items-center">
                <h1
                    class="max-sm:text-5xl text-7xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-yellow-300 to-pink-500"
                >
                    The Cyclopes
                </h1>
                <p class="text-xl text-neutral-300">One Pedal at a Time</p>
            </div>
        </header>

        <!-- History Section -->
        <section class="px-8 max-w-screen-lg">
            <h2
                class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-teal-400 mb-4"
            >
                What are we?
            </h2>
            <p class="text-xl leading-relaxed">
                We are The Cyclopes, the cycling club of RV College of
                Engineering. Founded on November 30, 2024, we have been
                promoting cycling as a sport and as a lifestyle ever since. We
                primarily conduct long distance rides.
            </p>
        </section>
    </div>

    <!-- Vision Section -->
    <section class="px-8 max-w-screen-lg mt-16">
        <h2
            class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-purple-400 to-pink-400 mb-4"
        >
            Vision
        </h2>
        <p class="text-xl leading-relaxed">
            To create a thriving community of cyclists who embrace
            sustainability, fitness, and adventure, and foster a culture of
            cycling in the college and beyond.
        </p>
    </section>

    <!-- Team Section -->
    <section class="flex flex-col px-8 max-w-screen-lg mt-16 w-full">
        <h2
            class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-green-400 to-blue-400 mb-8"
        >
            Team
        </h2>

        <div class="flex flex-col md:flex-row gap-8 justify-center">
            <div
                class="bg-neutral-800 text-gray-100 rounded-lg shadow-lg p-6 flex flex-col items-center basis-1/3"
            >
                <img
                    src="/svd.png"
                    alt="Team Member 1"
                    class="w-32 h-32 rounded-full mb-4"
                />
                <h3 class="text-2xl font-semibold">Shrish Deshpande</h3>
                <p class="text-sm text-neutral-400 mb-4">Cycling Zealot</p>
                <div class="flex flex-col items-center gap-2">
                    <a
                        href="https://www.linkedin.com/in/shrishdeshpande/"
                        class="text-blue-400 hover:underline"
                        target="_blank">LinkedIn</a
                    >
                    <a
                        href="https://shrishdeshpande.com"
                        class="text-blue-400 hover:underline"
                        target="_blank">Website</a
                    >
                </div>
            </div>

            <div
                class="bg-neutral-800 text-gray-100 rounded-lg p-6 shadow-lg flex flex-col items-center basis-1/3"
            >
                <img
                    src="/aa.png"
                    alt="Team Member 2"
                    class="w-32 h-32 rounded-full mb-4"
                />
                <h3 class="text-2xl font-semibold">Atharva Agarwal</h3>
                <p class="text-sm text-neutral-400 mb-4">Cycling Enthusiast</p>
                <div class="flex flex-col items-center gap-2">
                    <a
                        href="https://www.linkedin.com/in/atharva-agarwal-9480a0281/"
                        class="text-blue-400 hover:underline"
                        target="_blank">LinkedIn</a
                    >
                </div>
            </div>

            <div
                class="bg-neutral-800 text-gray-100 rounded-lg p-6 shadow-lg flex flex-col items-center basis-1/3"
            >
                <img
                    src="/vt.png"
                    alt="Team Member 3"
                    class="w-32 h-32 rounded-full mb-4"
                />
                <h3 class="text-2xl font-semibold">Varenya Thaker</h3>
                <p class="text-sm text-neutral-400 mb-4">Cycling Aficionado</p>
                <div class="flex flex-col items-center gap-2">
                    <a
                        href="https://www.linkedin.com/in/varenya-thaker-703635290/"
                        class="text-blue-400 hover:underline"
                        target="_blank">LinkedIn</a
                    >
                </div>
            </div>
        </div>
    </section>

    <!-- Goals Section -->
    <section class="px-8 max-w-screen-lg mt-16 w-full">
        <h2
            class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-red-400 to-sky-400 mb-4"
        >
            Goals
        </h2>
        <ul class="text-xl list-disc list-inside">
            <li>
                Conduct cycling trips to promote fitness and adventure among
                students.
            </li>
            <li>
                Write blogs about our trips, and publish them on our
                website.
            </li>
            <li>
                Build our own unicycle using recycled materials and a scrap
                bicycle.
            </li>
        </ul>
    </section>

    <section class="px-8 max-w-screen-lg mt-16 w-full">
        <h2
            class="text-4xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-sky-400 to-purple-400 mb-4"
        >
            Contact
        </h2>
        <p class="text-xl leading-relaxed">
            If you have any queries or would like to join us, feel free to
            contact us at <a href="mailto:sysadmin@teamdhruva.com"
                >sysadmin@teamdhruva.com</a
            >
        </p>
    </section>

    <Footer />
</main>
