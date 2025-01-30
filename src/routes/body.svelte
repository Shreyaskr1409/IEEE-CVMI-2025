<script>
	import { Card, CardContent } from "@/components/ui/card";

	import CarouselContent from "@/components/ui/carousel/carousel-content.svelte";
	import Carousel from "@/components/ui/carousel/carousel.svelte";
	import CarouselItem from "@/components/ui/carousel/carousel-item.svelte";
	import CarouselNext from "@/components/ui/carousel/carousel-next.svelte";
	import CarouselPrevious from "@/components/ui/carousel/carousel-previous.svelte";
	import Profile from "@/my-components/profile.svelte";
	import CarouselShow2 from "./carouselShow2.svelte";

</script>

<div class="flex flex-col gap-4">
    <div class="text-center self-center mt-4">
        <h1 class="text-5xl font-extrabold">Welcome to 4th IEEE CVMI 2025!</h1>
        <p class=" font-semibold text-xl">National Institute of Technology, Rourkela</p>
    </div>
    
    <div class="bg-zinc-800 flex justify-center items-center py-4 text-white">
        <div class="max-w-[1000px] w-full">
            <h2 class="text-2xl font-bold">CVMI 2024 program schedule:</h2>
            <Card class="dark">
                <CardContent>
                    
                <iframe class="w-full max-w-none h-[400px]" title="Schedule"
                src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRPuLND99MFJNDK7NoSmUmVA6vJUptCnYThSp9jFfJoGq6O9QhlTWKHC7OG1xkV_fMBbizVqhSmNFaV/pubhtml?widget=true&amp;headers=false"></iframe>
        
                </CardContent>
            </Card>
        </div>
    </div>

    <div class="px-4 grid grid-cols-2 gap-4 max-w-full max-lg:grid-cols-1">
        <div>
            <main>
                <section class="my-4">
                    <h2 class="text-3xl font-bold my-2">About</h2>
                    <p class="my-2">
                        The present world is witnessing rapid advancements in the field of Information Technology,
                        specifically in the areas of Computer Vision and Machine Intelligence, cherished by society 
                        and industry. The 4th IEEE CVMI is being organized by the Electronics & Communication Engineering 
                        department at NIT Rourkela from October 12-14, 2024. The world-wide leading research labs, 
                        including the Applied Al Research Lab, University of South Dakota, USA. Computer Vision Laboratory, 
                        University of Ljubljana, Slovenia, Sorbonne Center for Artificial Intelligence, Abu Dhabi, UAE, and 
                        Multimedia and Computer Vision Laboratory, National Cheng Kung University, Taiwan, are the organizing 
                        knowledge partners. The 1st CVMI in 2022 & 3rd CVMI in 2024 were organized by IIIT Allahabad while the 
                        2nd CVMI 2023 was organized by IIITM Gwalior. The conference programme will include regular paper 
                        presentations and PhD symposium along with keynote talks by prominent speakers in the field.
                    </p>
                    <p class="my-2">
                        The conference programme will include regular paper presentations, along with keynote talks
                        by prominent expert speakers in the field. All submitted papers will be double-blind peer-reviewed.
                        Paper acceptance will be based on originality, significance, technical soundness, and clarity of presentation.
                        The IAPR Best Paper Award and the CVMI-2025 Best Paper Awards will be given to the outstanding papers. The Best 
                        PhD Dissertation Awards will also be given in the PhD Symposium during IEEE CVMI 2025.
                    </p>
                </section>

                <section>
                    <h2 class="text-3xl font-bold">CVMI Committee</h2>
                    <div class="my-2 grid grid-cols-3 max-xl:grid-cols-2 max-lg:grid-cols-3 max-md:grid-cols-2 max-sm:grid-cols-1 gap-2">
                        <Profile name="Prof. Umamaheshwar Rao" position="Honorable Director of NIT Rourkela" picture="/associates/CVMI Committee/UmaMaheshwar rao.jpg"
                        coverFlag="object-cover"></Profile>
                        <Profile name="Prof. Poonam Singh" position="NIT Rourkela" picture="/associates/CVMI Committee/Poonam Singh.jpeg"
                        coverFlag="object-cover"></Profile>
                        <Profile name="Prof. Manish Okade" position="NIT Rourkela" picture="/associates/CVMI Committee/Manish Okade.jpeg"
                        coverFlag="object-cover"></Profile>
                    </div>
                </section>

                <section class="my-4">
                    <h2 class="text-3xl font-bold">Conference Details</h2>
                    <div>
                        <ul class="ml-6 list-disc [&>li]:mt-2">
                            <li><strong>Date:</strong> October 12-13, 2025</li>
                            <li><strong>Location:</strong> NIT Rourkela, Rourkela, India</li>
                        </ul>
                    </div>
                </section>
                <section class="my-4 relative">
                    <h2 class="text-3xl font-bold">Conference Topics</h2>
                    <Carousel>
                        <CarouselContent>
                            <CarouselItem>
                                <Card class="w-full">
                                    <CardContent class="p-2 px-16">
                                        <ul>
                                            <li>Biometrics, Forensics, Content Protection</li>
                                            <li>Face, Iris, Emotion, Sign and Gesture Recognition</li>
                                            <li>Image/video processing for Autonomous Vehicles</li>
                                            <li>3D image/video processing</li>
                                            <li>Enhancement/Super-Resolution/Restoration</li>
                                            <li>Action and Event Detection/Recognition</li>
                                            <li>Motion and Tracking</li>
                                            <li>Medical Image and Video Analysis</li>
                                            <li>Image/ Video Retrieval</li>
                                            <li>Vision based Human GAIT Analysis</li>
                                            <li>Document and Synthetic Visual Processing</li>
                                            <li>Remote Sensing & HSI Processing</li>
                                        </ul>
                                    </CardContent>
                                </Card>
                            </CarouselItem>
                            <CarouselItem>
                                <Card class="w-full">
                                    <CardContent class="p-2 px-16">
                                        <ul>
                                            <li>Datasets and Evaluation</li>
                                            <li>Segmentation and Shape Representation</li>
                                            <li>Image/Video Scene Understanding</li>
                                            <li>Image/Video Security</li>
                                            <li>Human Computer Interaction</li>
                                            <li>Visual Sensor Hardware</li>
                                            <li>Document Image Analysis</li>
                                            <li>Compressed Image/Video Analytics</li>
                                            <li>Other Computer Vision Applications</li>
                                            <li>Machine Learning</li>
                                            <li>Deep Learning</li>
                                            <li>Computational Intelligence</li>
                                            <li>Optimization Techniques</li>
                                        </ul>
                                    </CardContent>
                                </Card>
                            </CarouselItem>
                            <CarouselItem>
                                <Card class="w-full">
                                    <CardContent class="p-2 px-16">
                                        <ul>
                                            <li>Explainable AI</li>
                                            <li>Fairness, Transparency and Ethics</li>
                                            <li>Brain Computer Interaction</li>
                                            <li>Hand-sensor based Intelligence</li>
                                            <li>Robotic Intelligence</li>
                                            <li>Light-weight Intelligent Systems</li>
                                            <li>Limited Data Intelligence</li>
                                            <li>Hardware Intelligent Systems</li>
                                            <li>Multimedia Intelligent Systems</li>
                                            <li>Supervised Intelligence</li>
                                            <li>Unsupervised Intelligence</li>
                                            <li>Self-supervised Intelligence</li>
                                            <li>Transfer Learning</li>
                                        </ul>
                                    </CardContent>
                                </Card>
                            </CarouselItem>
                            <CarouselItem>
                                <Card class="w-full h-full">
                                    <CardContent class="p-2 px-16">
                                        <ul>
                                            <li>Multi-task Learning</li>
                                            <li>Fooling Intelligent Systems</li>
                                            <li>Robustness of Intelligent Systems</li>
                                            <li><strong>Other Topics of Machine Intelligence...</strong></li>
                                        </ul>
                                    </CardContent>
                                </Card>
                            </CarouselItem>
                        </CarouselContent>
                        <CarouselPrevious variant="default" class="absolute top-1/2 left-4 border-2" />
                        <CarouselNext variant="default" class="absolute top-1/2 right-4 border-2" />
                    </Carousel>
                    
                </section>

                <section class="my-4">
                    <h2 class="text-3xl font-bold">Call for papers</h2>
                    <p class="my-2">
                        Researchers are invited to submit their original contributions in the domains of computer vision,
                        machine learning,
                        and imaging. Selected papers will be published in reputed journals or conference proceedings.
                    </p>
                </section>

                <section class="my-4">
                    <h2 class="text-3xl font-bold">Important Dates</h2>
                    <ul class="ml-6 list-disc [&>li]:mt-2">
                        <li><strong>Paper Submission Deadline:</strong> TBA</li>
                        <li><strong>Notification of Acceptance:</strong> TBA</li>
                        <li><strong>Camera-Ready Submission:</strong> TBA</li>
                        <li><strong>Conference Dates:</strong> TBA</li>
                    </ul>
                </section>

                <section class="my-4">
                    <h2 class="text-3xl font-bold">Contacts</h2>
                    <p class="my-2">
                        For inquiries, please email us at <a class="underline" href="mailto:cvmi2025@nitrkl.ac.in">cvmi2025@nitrkl.ac.in</a>.
                    </p>
                </section>
            </main>
        </div>

        <div class="relative">
            <div class="sticky top-16">
                <CarouselShow2></CarouselShow2>
            </div>
        </div>

    </div>

</div>
