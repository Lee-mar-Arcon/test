<template>
	<div class="h-screen w-screen relative text-white">
		<TitleBar />
		<Sidebar />
		<StatusBar />
		<Terminal />
		<Editor />
	</div>
</template>

<script setup>
import Editor from './Layouts/Editor.vue';
import Terminal from './Layouts/Terminal.vue';
import TitleBar from './Layouts/TitleBar.vue';
import StatusBar from './Layouts/StatusBar.vue';
import Sidebar from './Layouts/Sidebar.vue';
</script>
<style scoped></style>
