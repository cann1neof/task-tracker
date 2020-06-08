<template>
  <v-app>
	<v-app-bar fixed app>
	</v-app-bar>

    <v-content>
		<v-container>
			<nuxt />
		</v-container>
    </v-content>

    <v-footer 
		color="transparent"
		fixed
		app
	>
		<v-stepper>
    <v-stepper-header>
      <v-stepper-step
        complete
        editable
        step="1"
      >
        Select campaign settings
      </v-stepper-step>

      <v-divider></v-divider>

      <v-stepper-step
        complete
        step="2"
      >Create an ad group</v-stepper-step>

      <v-divider></v-divider>

      <v-stepper-step
        step="3"
        editable
      >
        Create an ad
      </v-stepper-step>
    </v-stepper-header>
  </v-stepper>
    </v-footer>
  </v-app>
</template>

<script>
  export default {}

</script>
