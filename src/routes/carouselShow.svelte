<script>
	import CardContent from "@/components/ui/card/card-content.svelte";
	import Card from "@/components/ui/card/card.svelte";
	import CarouselContent from "@/components/ui/carousel/carousel-content.svelte";
	import CarouselItem from "@/components/ui/carousel/carousel-item.svelte";
	import CarouselNext from "@/components/ui/carousel/carousel-next.svelte";
	import CarouselPrevious from "@/components/ui/carousel/carousel-previous.svelte";
	import Carousel from "@/components/ui/carousel/carousel.svelte";

</script>

<div class="w-full relative">
    <Carousel class="w-full dark bg-zinc-950 px-2 pb-2">
        
        <div class="absolute bottom-6 mx-4 px-2 py-1 z-10 flex flex-row gap-2 bg-zinc-900
        max-w-[600px] rounded-2xl items-center bg-opacity-70">
            <img src="/id65aUZ6hI_1737699275674.svg" alt="" class=" aspect-square h-28"/>

            <div class="flex flex-col gap-2 text-white bg-opacity-70">
                <h1 class="text-3xl font-extrabold"><span class="text-amber-300">CVMI 2025</span> - International Conference on
Computer Vision and Machine Intelligence</h1>
                <p class=" font-medium text-xl text-amber-300">National Institute of Technology, Rourkela</p>
            </div>
        </div>

        <CarouselContent>
            <!-- <CarouselItem>
                <Card class="relative">
                    <img src="/building.jpeg" alt="" class="rounded-xl w-full h-[500px] object-cover"/>
                    <p class="max-w-[400px] font-medium text-lg absolute top-0 p-4">CVMI is a leading conference on Computer Vision and Machine Intelligence, showcasing top experts, groundbreaking research, and innovative discussions.</p>
                </Card>
            </CarouselItem> -->
            <CarouselItem>
                <Card>
                    <div class="relative rounded-xl w-full h-[500px] lg:h-[700px] object-cover flex justify-center items-center overflow-hidden">
                        <div
                            class="absolute inset-0 bg-center bg-cover filter z-0 blur-sm opacity-50"
                            style="background-image: url('/building.jpeg');"
                        ></div>
                    
                        <img
                            id="bg1"
                            src="/building.jpeg"
                            alt=""
                            loading="lazy"
                            class="relative z-10 bg-transparent object-contain object-center h-full"
                        />

                    </div>
                    <p class="max-w-[500px] font-medium text-lg absolute top-0 z-10 p-4">CVMI is a leading conference on Computer Vision and Machine Intelligence, showcasing top experts, groundbreaking research, and innovative discussions.</p>    
                </Card>
            </CarouselItem>
            <CarouselItem>
                <Card>
                    <div class="relative rounded-xl w-full h-[500px] lg:h-[700px] object-cover flex justify-center items-center overflow-hidden">
                        <div
                            class="absolute inset-0 bg-center bg-cover filter z-0 blur-sm opacity-50"
                            style="background-image: url('/la2.jpeg');"
                        ></div>
                    
                        <img
                            id="bg1"
                            src="/la2.jpeg"
                            alt=""
                            loading="lazy"
                            class="relative z-10 bg-transparent object-contain object-center h-full"
                        />

                    </div>
                    <p class="max-w-[500px] w-full font-medium text-lg absolute top-0 z-10 p-4">CVMI is a leading conference on Computer Vision and Machine Intelligence, showcasing top experts, groundbreaking research, and innovative discussions.</p>    
                </Card>
            </CarouselItem>
            <CarouselItem>
                <Card>
                    <div class="relative rounded-xl w-full h-[500px] lg:h-[700px] object-cover flex justify-center items-center overflow-hidden">
                        <div
                            class="absolute inset-0 bg-center bg-cover filter z-0 blur-sm opacity-50"
                            style="background-image: url('/mainbuilding.jpg');"
                        ></div>
                    
                        <img
                            id="bg1"
                            src="/mainbuilding.jpg"
                            alt=""
                            loading="lazy"
                            class="relative z-10 bg-transparent object-contain object-center h-full"
                        />
                    </div>
                    <p class="max-w-[500px] w-full font-medium text-lg absolute top-0 z-10 p-4">CVMI is a leading conference on Computer Vision and Machine Intelligence, showcasing top experts, groundbreaking research, and innovative discussions.</p>    
                </Card>
            </CarouselItem>
        </CarouselContent>
        <CarouselPrevious variant="default" class="absolute top-1/2 left-4 border-2" />
        <CarouselNext variant="default" class="absolute top-1/2 right-4 border-2" />
    </Carousel>
</div>