<template>
  <div class="amida">
    <h1>あみだくじ</h1>
    <Game />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import Game from '@/components/Game.vue';

@Component({
  components: {
    Game,
  },
})

export default class Amida extends Vue { }

</script>
