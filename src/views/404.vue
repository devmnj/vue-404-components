<template>
  <div class="home">
    <v-404 v-if="$route.params.id==1" class="" />
    <a-404 v-else-if="$route.params.id==2" class="" />
    <c-404 v-else-if="$route.params.id==3" class="" />
    <m-404 v-else-if="$route.params.id==4" class="" />
    <t-404 v-else-if="$route.params.id==5" class="" />
    <f-404 v-else-if="$route.params.id==6" class="" />
    <o-404 v-else-if="$route.params.id==7" class="" />
    <mo-404 v-else-if="$route.params.id==8" class="" />
    <a-404 v-else-if="$route.params.id>8" class="" />

<!-- {{$route.params.id}}      -->
  </div>
</template>

<script>
// @ is an alias to /src
 import { A404, PNF,C404,M404,T404,Fargo404,OH404,MO404 } from "@/components";
export default {
  name: "PNF",
  components: {
 "v-404": PNF,
    "a-404": A404,
    'c-404': C404,
    'm-404': M404,
    't-404':T404,
    'f-404':Fargo404,
    'o-404':OH404,
    'mo-404':MO404
  },
};
</script>
