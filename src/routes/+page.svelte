<script>
    import { faGithub, faTwitter, faLinkedin } from '@fortawesome/free-brands-svg-icons';
    import { FontAwesomeIcon } from '@fortawesome/svelte-fontawesome';
</script>

<div class="flex flex-col items-center justify-center min-h-screen bg-slate-800 text-slate-50">

    <div class="text-center">
        <div class="relative custom-circle mx-auto mb-7" >
            <img src="/eren.jpg" alt="Profile" class="w-full h-full rounded-full border-4 border-slate-50 object-cover"/>
        </div>

        <h1 class="text-3xl md:text-5xl font-bold mb-4">
            Hi! I'm <span class="bg-purple-600 px-2 py-1 rounded-md">Eren</span>
        </h1>
        <p class="text-lg md:text-xl mb-4">Full-stack web developer</p>
        <div class="text-base mb-6">
            Currently based in <a href="#" class="underline">Germany</a>
        </div>

        <div class="flex justify-center space-x-4">
            <a href="https://github.com/erenvxl/" class="text-white hover:text-gray-400">
                <FontAwesomeIcon icon={faGithub} size="3x" class="w-6 h-6"/>
            </a>
            <a href="https://x.com/erenvxl" class="text-white hover:text-gray-400">
                <FontAwesomeIcon icon={faTwitter} size="3x" class="w-6 h-6"/>
            </a>
            <a href="https://www.linkedin.com/in/armaganguel/" class="text-white hover:text-gray-400">
                <FontAwesomeIcon icon={faLinkedin} size="3x" class="w-6 h-6"/>
            </a>
        </div>
    </div>
</div>

<style lang="postcss">
    .custom-circle {
        width: 200px;
        height: 200px;
    }
</style>
