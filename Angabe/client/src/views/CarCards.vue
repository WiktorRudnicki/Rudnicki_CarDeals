<template>
    <v-app>
        <v-card v-for="car in cars" :key="car">
            <v-image src="car.image"></v-image>
            <h1>
                {{car.title}}
            </h1>
            <br>
            <span>
                Owner: {{car.owner}}
            </span>
            <br>
            <span>
                Year: {{car.yearOfMake}}
            </span>
            <span>
                Miles: {{car.miles}}
            </span>
            <span>
                Price: {{car.price}}
            </span>
            <br>
            <span>
                {{car.description}}
            </span>
            <v-button @click="gekauft()">
                BUY CAR
            </v-button>
        </v-card>
    </v-app>
</template>

<script>
export default {
    data: () => {

    },
    
}
</script>