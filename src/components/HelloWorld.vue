<template>
	<Page class="page">
		<ActionBar title="home" class="action-bar"/>
		<ScrollView>
			<StackLayout class="">
				<StackLayout class="" backgroundColor="red">
					<!--Add your page content here-->
					<Button text="Go to next" backgroundColor="orange" @tap="$navigateTo(HelloWorld2)"/>
					<Label textWrap="true" text="Play with NativeScript!" class="h2 description-label"/>
					<Label textWrap="true"
					       text="Write code in the editor or drag and drop components to build a NativeScript mobile application."
					       class="h2 description-label"/>
					<Label textWrap="true"
					       text="Scan the QR code with your mobile device and watch the changes sync live while you play with the code."
					       class="h2 description-label"/>
				</StackLayout>
				<StackLayout class="" backgroundColor="lime">
					<!--Add your page content here-->
					<Label textWrap="true" text="Play with NativeScript!" class="h2 description-label"/>
					<Label textWrap="true"
					       text="Write code in the editor or drag and drop components to build a NativeScript mobile application."
					       class="h2 description-label"/>
					<Label textWrap="true"
					       text="Scan the QR code with your mobile device and watch the changes sync live while you play with the code."
					       class="h2 description-label"/>
				</StackLayout>
				<StackLayout class="" backgroundColor="red">
					<!--Add your page content here-->
					<Label textWrap="true" text="Play with NativeScript!" class="h2 description-label"/>
					<Label textWrap="true"
					       text="Write code in the editor or drag and drop components to build a NativeScript mobile application."
					       class="h2 description-label"/>
					<Label textWrap="true"
					       text="Scan the QR code with your mobile device and watch the changes sync live while you play with the code."
					       class="h2 description-label"/>
				</StackLayout>
				<StackLayout class="" backgroundColor="lime">
					<!--Add your page content here-->
					<Label textWrap="true" text="Play with NativeScript!" class="h2 description-label"/>
					<Label textWrap="true"
					       text="Write code in the editor or drag and drop components to build a NativeScript mobile application."
					       class="h2 description-label"/>
					<Label textWrap="true"
					       text="Scan the QR code with your mobile device and watch the changes sync live while you play with the code."
					       class="h2 description-label"/>
				</StackLayout>
			</StackLayout>
		</ScrollView>
	</Page>
</template>

<script>
	import HelloWorld2 from './HelloWorld2';

	export default {
		data() {
			return {
				HelloWorld2,
				surprise: false,
			};
		},
	};
</script>

<style scoped>
	Label {
		color: blue;
	}
</style>
