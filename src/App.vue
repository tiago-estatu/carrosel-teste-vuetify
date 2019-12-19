<template>
	<v-app>
		<app-navigator></app-navigator>
		
		<v-content>
			<app-carrosel></app-carrosel>	
		</v-content>

		<app-footer></app-footer>
		<p>{{texto}}</p>
	</v-app>
</template>

<script>
import Navigator from '@/componentes/template/Nav.vue'
import Carrosel from '@/componentes/widgets/Carrosel.vue'
import Footer from '@/componentes/template/Footer.vue'

export default {
	components: {
			'app-navigator':Navigator, 
			'app-carrosel':Carrosel, 
			'app-footer':Footer
		}
}
</script>
