<template>
<row>
  <column col="5">
    <card align="center">
      <card-header>Success!</card-header>
      <card-body>
        <h3 class="card-title">This is a card</h3>
        <p class="card-text">And here comes some special text, just for you.</p>
        <btn color="deep-purple" size="sm">Go somewhere</btn>
      </card-body>
      <card-footer><p class="mb-0">Please enjoy this footer</p></card-footer>
    </card>
  </column>
</row>
</template>

<script>
import Row from '@/components/Row.vue';
import Column from '@/components/Col.vue';
import Btn from '@/components/Button.vue';
import Card from '@/components/Card.vue';
import CardHeader from '@/components/CardHeader.vue';
import CardBody from '@/components/CardBody.vue';
import CardFooter from '@/components/CardFooter.vue';

export default {
  name: 'PanelPage',
  components: {
    Row,
    Column,
    Btn,
    Card,
    CardFooter,
    CardBody,
    CardHeader,
  },
  data(){
    return {

    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
