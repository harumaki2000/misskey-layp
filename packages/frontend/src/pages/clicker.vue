<!--
SPDX-FileCopyrightText: syuilo and misskey-project
SPDX-License-Identifier: AGPL-3.0-only
-->

<template>
<MkStickyContainer>
	<template #header><MkPageHeader/></template>
	<MkSpacer :contentMax="800">
		<MkClickerGame/>
	</MkSpacer>
</MkStickyContainer>
</template>

<script lang="ts" setup>
import MkClickerGame from '@/components/MkClickerGame.vue';
import { definePage } from '@/page.js';

definePage(() => ({
	title: '🍪👈',
	icon: 'ti ti-cookie',
}));
</script>

<style lang="scss" module>

</style>
