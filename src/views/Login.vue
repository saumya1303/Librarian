<!-- div is used to bind all elements in 1 file only because page can have only 1 root element -->
<template>
    <div class="center">
        <v-row>
            <v-col cols="10" sm="6" offset-sm="3" md="4" offset-md="4" offset="1">
                <v-avatar  size="36" tile></v-avatar>
                <v-img src="@/assets/logo.jpg" alt="Welcome to login page"></v-img>
                <v-text-field label="username" v-model="username"></v-text-field>
                <v-text-field label="password" v-model="password" type="password"></v-text-field>
                <v-btn block elevation="2" @click="authenticate()">Login</v-btn>
            </v-col>
        </v-row>
    </div>
</template>
<script>
export default {
    data() {
        return {
            username: '',
            password: ''
        }
    },
    methods: {
        authenticate() {
            alert("Login clicked")
        }
    },
}
</script>

<style lang="scss" scoped></style>