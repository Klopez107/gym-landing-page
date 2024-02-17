<script>
    export let dark
</script>

<div class="flex items-center gap-4">
    <button class={"specialBtn" + (dark ? " bg-[#1813b4]" : " ")}>
        <p class="text-base sm:text-lg md:text-xl">Contact Us</p>
    </button>
    <button class="specialBtnDark">
        <p class="text-base sm:text-lg md:text-xl">Get started &rarr;</p>
    </button>
</div>
