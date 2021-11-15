
<template>
   <v-container
    id="user-profile"
    fluid
    tag="section"
  >
    <v-row justify="center">
      <v-col
        cols="12"
        md="12"
      >
        <template >
            <div class="display-2 font-weight-light mb-10">
              Editer votre Profile
            </div>
        </template>
        <v-card class="mt-md-12 pa-md-10 mt-sm-10">
          <v-form>
            <v-container class="py-10 px-10">
              <v-row>
                <v-col
                cols="12"
                md="12"
                >
                  <div class="pa-16 secondary rounded-circle d-inline-block mb-8 profile" >
                  </div>
                  <input
                  ref="file"
                  type="file"
                  class="custom-file-input"
                  id="customFile"
                />
                </v-col>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Nom"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    class="purple-input"
                    label="Prénom (s)"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Adresse Email"
                    class="purple-input"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="6"
                >
                  <v-text-field
                    label="Profession"
                    class="purple-input"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="6"
                >
                  <v-text-field
                    label="Téléphone"
                    class="purple-input"
                    type="number"
                  />
                </v-col>

                <v-col cols="12">
                  <v-text-field
                    label="Adresse"
                    class="purple-input"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Ville"
                    class="purple-input"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Pays"
                    class="purple-input"
                  />
                </v-col>

                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    class="purple-input"
                    label=" Code Postal"
                    type="number"
                  />
                </v-col>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Numero whatsapp"
                    class="purple-input"
                  />
                </v-col>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Url Facebook"
                    class="purple-input"
                  />
                </v-col>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Url Instagram"
                    class="purple-input"
                  />
                </v-col>
                <v-col
                  cols="12"
                  md="4"
                >
                  <v-text-field
                    label="Url Linkedin"
                    class="purple-input"
                  />
                </v-col>

                <v-col cols="12">
                  <v-textarea
                    class="purple-input"
                    label="Biographie"
                    value="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
                  />
                </v-col>

                <v-col
                  cols="12"
                  class="text-right"
                >
                  <v-btn
                    color="success"
                    class="mr-0"
                  >
                    Mettre à jour
                  </v-btn>
                </v-col>
              </v-row>
            </v-container>
          </v-form>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
.profile {
  background: url('https://cdn.intra.42.fr/users/medium_matraore.jpg');
  background-size: cover;
}
</style>

</template>
