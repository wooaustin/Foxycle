<template>
</template>

<script lang="ts">
import { Component, Vue, Prop} from 'vue-property-decorator';
@Component
export default class Login extends Vue{
	@Prop() private msg!: string;
}
</script>
<style lang ="scss">
</style>