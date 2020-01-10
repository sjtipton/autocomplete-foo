<template>
  <div id="userdetailview">
    <v-form autocomplete="off" method="post">
      <v-card>
        <v-container fluid>
          <v-row>
            <v-col>
              <h3>
                User Details
              </h3>
            </v-col>
          </v-row>
          <v-row>
            <v-col col="6">
              <v-card flat>
                <v-container fluid>
                  <v-row>
                    <v-col>
                      <v-text-field id="UserName" label="Username" outlined v-model="userName" placeholder="Username"></v-text-field>
                    </v-col>
                  </v-row>

                  <v-row>
                    <v-col>
                      <v-text-field label="First Name" outlined v-model="firstName" placeholder="First Name"></v-text-field>
                    </v-col>

                    <v-col>
                      <v-text-field label="Last Name" outlined v-model="lastName" placeholder="Last Name"></v-text-field>
                    </v-col>
                  </v-row>

                  <v-row>
                    <v-col>
                      <v-text-field label="Email" outlined v-model="email" placeholder="Email"></v-text-field>
                    </v-col>
                  </v-row>

                  <v-row>
                    <v-col>
                      <v-text-field label="Phone" outlined v-model="phoneNumber" placeholder="Phone"></v-text-field>
                    </v-col>
                  </v-row>
                </v-container>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </v-card>
    </v-form>
  </div>
</template>

<script>
export default {
  name: 'userDetails',
  created: function () {
  },
  computed: {
  },
  data: function () {
    return {
      userName: '',
      email: '',
      firstName: '',
      lastName: '',
      phoneNumber: ''
    }
  },
  methods: {
  }
}
</script>

<style scoped>
</style>
