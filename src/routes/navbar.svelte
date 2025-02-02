<script>
	import Button from "@/components/ui/button/button.svelte";
	import NavOptions from "./navOptions.svelte";
</script>

<div class="w-full flex flex-row items-center justify-between bg-zinc-950 px-4 py-1 fixed gap-4 z-50">
    <div class="prose text-nowrap">
        <h1 class="text-white text-4xl font-bold">IEEE CVMI 2025</h1>
    </div>
    <div class="flex gap-1 items-center justify-center text-nowrap">
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-md:hidden">Home</Button>
        
        <a href="/committee">
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-md:hidden">Committee</Button>
        </a>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-lg:hidden">Call for papers</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-2xl:hidden">Keynote</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-lg:hidden">PhD Colloquium</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-2xl:hidden">Program</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-xl:hidden">Registration</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-md:hidden">Sponsors</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-md:hidden">About</Button>
        <Button variant="ghost" class="text-white hover:text-white hover:bg-zinc-800 max-xl:hidden">CVMI History</Button>

        <NavOptions></NavOptions>
    </div>
</div>
