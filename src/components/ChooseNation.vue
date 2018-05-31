<template>
    <div class="choose-nation">
        <h1>
            Follow the path of 
            <div class="select-wrapper">
                <select v-model="choosedNation">
                    <option disabled value="">your nation</option>
                    <option>🇧🇪 Belgium</option>
                    <option>🇵🇦 Panama</option>
                    <option>🇹🇳 Tunisia</option>
                    <option>🏴 England󠁧󠁢󠁥󠁮󠁧󠁿</option>
                </select> 
            </div>
            at World Cup! 🏆
        </h1>
    </div>
</template>

<script>
export default {
  name: 'ChooseNation',
  data: function() {
      return {
        choosedNation: ''
      };
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '../main.scss';
</style>