<template>
  <div class="main">
    <MDBContainer>
      <MDBRow>
        <MDBCol md="6">
          <Card image-uri="https://mdbootstrap.com/img/new/standard/nature/184.webp" text="Text2" />
        </MDBCol>
        <MDBCol md="6">
          <Card image-uri="https://mdbootstrap.com/img/new/standard/nature/182.webp" text="Text1" />
        </MDBCol>
      </MDBRow>
    </MDBContainer>
  </div>
</template>

<script setup lang="ts">
import { MDBCol, MDBRow, MDBContainer } from 'mdb-vue-ui-kit';

import Card from "./Card.vue";
</script>