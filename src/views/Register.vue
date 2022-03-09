<template>
    <v-container>
        <v-app>
            <v-card  width="500px" class = "my-auto mx-auto">
                <v-card-title>
                    REGISTER
                </v-card-title>
                <v-card-text>
                    <v-form>

                        <v-text-field
                            label = "Email"
                            prepend-icon = "mdi-account-circle"
                            required />
                        <v-text-field
                            label = "Password"
                            required
                            prepend-icon = "mdi-lock"
                        />
                         <v-checkbox
                            class = "my-4"
                            v-model="ex4"
                            label="Agree to terms and conditions"
                            color="warning"
                            value=""
                            hide-details
                            ></v-checkbox>
                        <v-divider></v-divider>
                        <v-btn
                        color = "warning"
                        class = "my-4"
                        >
                            REGISTER
                        </v-btn>
                    </v-form>
                </v-card-text>
            </v-card>
        </v-app>
    </v-container>
</template>