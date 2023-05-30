<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard">
        <!-- Start Hero -->
        <section
            class="relative md:py-64 py-36 items-center bg-[url('../../assets/images/bg-seo.html')] bg-center bg-no-repeat bg-cover">
                <div class="grid grid-cols-1 justify-center text-center">
                    <div class="">
                        <h1 class="font-bold lg:leading-normal leading-normal text-4xl lg:text-5xl mb-5">Scammers Database<span
                            class="typewrite" data-period="2000"
                            data-type='[ "Plugin", "Website", "Toolkit", "Agency" ]'> <span class="wrap"></span> </span>
                        </h1>
                        <p class="text-lg max-w-xl mx-auto">Search for a scammer by id, name, number or email</p>
                        <div class="subcribe-form mt-6 mb-3">
                            <form class="relative max-w-xl mx-auto">
                                <input type="url" id="site-url" name="url"
                                       class="pt-4 pe-40 pb-4 ps-6 w-full h-[50px] outline-none text-black rounded-full bg-white/60 shadow"
                                       placeholder="Enter search term">
                                <button type="submit"
                                        class="btn absolute top-[2px] end-[3px] h-[46px] w-[100px] bg-indigo-600 hover:bg-indigo-700 border-indigo-600 hover:border-indigo-700 text-white rounded-full">
                                    Search
                                </button>
                            </form>
                        </div>
                    </div>
            </div>
        </section>
        <section class="relative md:pb-24 pb-16">
                <div class="md:flex justify-center">
                    <div class="lg:w-3/4 md:w-full relative -mt-16">
                        <div class="p-6 bg-white rounded-md shadow">
                            <div class="md:flex justify-center">
                                <div class="md:w-1/3">
                                    <div class="text-center">
                                        <h6 class="text-slate-400 mb-0">External Backlinks</h6>
                                        <h2 class="mb-0 text-4xl mt-3 font-bold"><span class="counter-value" data-target="2021">1990</span>K+
                                        </h2>
                                    </div>
                                </div>

                                <div class="md:w-1/3 mt-8 md:mt-0">
                                    <div class="text-center">
                                        <h6 class="text-slate-400 mb-0">Pages Crawled Daily</h6>
                                        <h2 class="mb-0 text-4xl mt-3 font-bold"><span class="counter-value"
                                                                                       data-target="210">2</span>B+</h2>
                                    </div>
                                </div>

                                <div class="md:w-1/3 mt-8 md:mt-0">
                                    <div class="text-center">
                                        <h6 class="text-slate-400 mb-0">Domain Indexed</h6>
                                        <h2 class="mb-0 text-4xl mt-3 font-bold"><span class="counter-value"
                                                                                       data-target="18">1</span>M+</h2>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div><!--end col-->
            </div><!--end container-->
            <div class="md:mt-24 mt-16">
                <div class="grid grid-cols-1 pb-8 text-center">
                    <h6 class="text-indigo-600 text-sm font-bold uppercase mb-2">Services</h6>
                    <h3 class="mb-4 md:text-3xl md:leading-normal text-2xl leading-normal font-semibold bg-gradient-to-r from-red-600 to-indigo-600 text-transparent bg-clip-text">
                        We are SEO Professionals</h3>
                    <p class="text-slate-400 max-w-xl mx-auto">Your content is an integral part of your SEO efforts and online
                        marketing strategy</p>
                </div>
            </div>
        </section>
    </AppLayout>
</template>
