<template>
    <!-- Main section start -->
	<section class="h-screen px-12 lg:px-32 py-32 mb-8">
		<div class="w-full md:w-1/2 h-full flex flex-col md:justify-center ">
			<!-- Main text start -->
			<h1 class="uppercase text-5xl xl:text-7xl mb-4 font-semibold ">
				AGILA
			</h1>
			<p class="capitalize xl:w-1/2 text-stone-500">
				This application requires a smartphone or a device with a QR Code 
				reader application installed to scan a QR Code and retrieve
				information about a favorite landmark. The app will then decode the
				information contained in the QR Code and display the 3D model of
				the landmark on your screen
			</p>
			<!-- Main text end -->


		</div>

		<!-- Photographer image start -->
		<div class="absolute bottom-0 right-0 overflow-hidden h-2/5 sm:h-1/2 md:h-3/5 lg:h-4/6 -z-50">
			<img src="@/assets/image.jpg" alt="img" class="h-full">
		</div>

		<!-- Photographer image end -->

		<!-- "More" button start -->
		<div class="w-full h-20 flex justify-start md:justify-center items-center">
			<a href="#about-section">
				<i class="fa-solid fa-arrow-down transition text-stone-100 text-xl bg-stone-700 rounded-full shadow p-4 hover:-translate-y-2 hover:shadow-xl"></i>
			</a>
		</div>
		<!-- "More" button end -->

	</section>
	<!-- Main section end -->
</template>

<script>
export default {

}
</script>

<style>

</style>