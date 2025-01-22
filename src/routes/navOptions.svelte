<script>
	import { Button } from "@/components/ui/button";
	import { Sheet, SheetTrigger } from "@/components/ui/sheet";
	import SheetContent from "@/components/ui/sheet/sheet-content.svelte";
	import SheetHeader from "@/components/ui/sheet/sheet-header.svelte";
	import SheetTitle from "@/components/ui/sheet/sheet-title.svelte";
	import { ModeWatcher } from "mode-watcher";

</script>


<Sheet>
    <SheetTrigger asChild let:builder>
        <Button builders={[builder]} variant="outline">More</Button>
    </SheetTrigger>
    <SheetContent class="dark flex flex-col w-full max-w-[400px] text-white hover:text-white">
        <SheetHeader>
            <SheetTitle>Welcome to IEEE CVMI 2025</SheetTitle>
        </SheetHeader>

        <Button variant="outline">Home</Button>
        <Button variant="outline">Committee</Button>
        <Button variant="outline">Call for papers</Button>
        <Button variant="outline">Keynote</Button>
        <Button variant="outline">PhD Colloquium</Button>
        <Button variant="outline">Program</Button>
        <Button variant="outline">Registration</Button>
        <Button variant="outline">Sponsors</Button>
        <Button variant="outline">About</Button>
        <Button variant="outline">CVMI History</Button>
    </SheetContent>
</Sheet>