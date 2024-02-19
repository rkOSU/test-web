<template>
    <MDBCard>
        <a v-mdb-ripple="{ color: 'light' }">
            <MDBCardImg :src=imageUri alt="..." />
        </a>
        <MDBCardBody>
            <MDBCardTitle>{{ text }}</MDBCardTitle>
            <MDBCardText>
                Some quick example text to build on the card title and make up the bulk of the
                card's content.
            </MDBCardText>
            <MDBBtn tag="a" href="#!" color="primary">Button</MDBBtn>
        </MDBCardBody>
    </MDBCard>
</template>

<script setup lang="ts">
import { MDBCard, MDBCardBody, MDBCardTitle, MDBCardText, MDBCardImg, MDBBtn, mdbRipple } from "mdb-vue-ui-kit";

const vMdbRipple = mdbRipple

defineProps({
    imageUri: String,
    text: String
})
</script>