<template>
    <Head title="Dashboard" />
    <Master>
			<div class="card-box pd-20 height-100-p mb-30">
				<div class="row align-items-center">
					<div class="col-md-4">
						<img src="assets/vendors/images/banner-img.png" alt="">
					</div>
					<div class="col-md-8">
						<h4 class="font-20 weight-500 mb-10 text-capitalize">
							Welcome to Teacher Panel <div class="weight-600 font-30 text-blue">{{$page.props.auth.user.name}}!</div>
						</h4>
						<p class="font-18 max-width-600">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Unde hic non repellendus debitis iure, doloremque assumenda. Autem modi, corrupti, nobis ea iure fugiat, veniam non quaerat mollitia animi error corporis.</p>
					</div>
				</div>
			</div>
    </Master>
</template>

<style scoped>
    
</style>

<script>
import { Head, Link } from '@inertiajs/inertia-vue3';
import Master from '@/Layouts/App.vue';

export default {
    components: {
      Head,
      Link,
      Master,
    },
}
</script>
