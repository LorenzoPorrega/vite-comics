<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  components:{
    MyHeader,
    MyFooter,
  },
  data() {
    return {
      menuLinks: [
        {
          link: `characters`,
        },
        {
          link: `comics`,
        },
        {
          link: `movies`,
        },
        {
          link: `tv`,
        },
        {
          link: `games`,
        },
        {
          link: `collectibles`,
        },
        {
          link: `videos`,
        },
        {
          link: `fans`,
        },
        {
          link: `news`,
        },
        {
          link: `shop`,
        },
      ],
    };
  },
  methods: {},
}

</script>

<template>
  <MyHeader></MyHeader>
  <MyFooter></MyFooter>
</template>

<style lang="scss">


</style>
