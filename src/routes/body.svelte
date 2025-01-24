<script>
	import { Card, CardContent } from "@/components/ui/card";


	import Carousel from "./carousel.svelte";

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
                    
                <iframe class="w-full max-w-none h-[400px]"
                src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRPuLND99MFJNDK7NoSmUmVA6vJUptCnYThSp9jFfJoGq6O9QhlTWKHC7OG1xkV_fMBbizVqhSmNFaV/pubhtml?widget=true&amp;headers=false"></iframe>
        
                </CardContent>
            </Card>
        </div>
    </div>

    <div class="px-4 flex flex-row gap-4 max-w-full">
        <div class="prose w-1/2">
            <main>
                <section>
                    <h2>About</h2>
                    <p>
                        The present world is witnessing rapid advancements in the field of Information Technology, 
                        specifically, in the areas of Computer Vision and Machine Intelligence, cherished by the 
                        society and industry. The amount of Research and Development activities across the globe 
                        has been drastically scaled up from the past one decade in these research areas. Hence, a 
                        new state-of-the-art Computer Vision and Machine Intelligence (CVMI) Conference avenue was 
                        conceived by Computer Vision and Biometrics Lab (CVBL), Department of Information Technology, 
                        Indian Institute of Information Technology Allahabad, India for the researchers to disseminate 
                        their research outcomes in 2022. 2nd CVMI 2023 was conducted by ABV-IIITM Gwalior. The 3rd 
                        version of CVMI is being organized during October 19-20, 2024 at IIIT Allahabad, Prayagraj, 
                        India. The world-wide leading research labs, including the Applied AI Research Lab, University 
                        of South Dakota, USA, Computer Vision Laboratory, Faculty of Computer and Information Science, 
                        University of Ljubljana, Slovenia, Sorbonne Center for Artificial Intelligence, Abu Dhabi, UAE, 
                        and Multimedia and Computer Vision Laboratory, Department of Computer Science and Information 
                        Engineering, National Cheng Kung University, Taiwan, are the organizing knowledge partners.
                        The IEEE CVMI 2024 conference is financially and technically sponsored by IEEE Uttar Pradesh 
                        Section. The CVMI 2024 conference is "Endorsed by International Association for Pattern Recognition 
                        (IAPR)" and "Technically Sponsored by IEEE SPS UP Chapter".
                    </p>
                    <p>
                        The conference programme will include regular paper presentations, along with keynote talks
                        by prominent expert speakers in the field. All submitted papers will be double-blind peer-reviewed.
                        Paper acceptance will be based on originality, significance, technical soundness, and clarity of presentation.
                        The IAPR Best Paper Award and the CVMI-2024 Best Paper Awards will be given to the outstanding papers. The Best 
                        PhD Dissertation Awards will also be given in the PhD Symposium during IEEE CVMI 2024.
                    </p>
                </section>

                <section>
                    <h2>Conference Details</h2>
                    <ul>
                        <li><strong>Date:</strong> July 11-14, 2024</li>
                        <li><strong>Location:</strong> NIT Rourkela, Rourkela, India</li>
                    </ul>
                </section>

                <section>
                    <h2>Call for Papers</h2>
                    <p>
                        Researchers are invited to submit their original contributions in the domains of computer vision,
                        machine learning,
                        and imaging. Selected papers will be published in reputed journals or conference proceedings.
                    </p>
                </section>

                <section>
                    <h2>Important Dates</h2>
                    <ul>
                        <li><strong>Paper Submission Deadline:</strong> March 15, 2024</li>
                        <li><strong>Notification of Acceptance:</strong> May 1, 2024</li>
                        <li><strong>Camera-Ready Submission:</strong> June 1, 2024</li>
                        <li><strong>Conference Dates:</strong> July 11-14, 2024</li>
                    </ul>
                </section>

                <section>
                    <h2>Contact</h2>
                    <p>
                        For inquiries, please email us at <a href="mailto:cvmi2025@nitrkl.ac.in">cvmi2025@nitrkl.ac.in</a>.
                    </p>
                </section>
            </main>
        </div>

        <div class="w-1/2 relative">
            <div class="sticky top-16">
                <Carousel></Carousel>
            </div>
        </div>

    </div>

</div>