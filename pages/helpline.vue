<template>
  <v-row align="center" justify="center">
    <v-col cols="12" md="6">
      <p class="title">Reporting illness</p>
      If you feel unwell, have a <u>cold</u> or a <u>cough</u> or fever, please
      call <a href="tel:719">719</a> or text <a href="tel:*719#">*719#</a> which
      is a toll-free number provided by the Government of Kenya.
      <v-list flat>
        <v-subheader>
          You can also call the following County Hotline numbers:
        </v-subheader>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title> Nairobi </v-list-item-title> (tollfree) /
            0732353535</v-list-item-content
          >
          <v-list-item-action>
            <v-btn large color="primary" icon href="tel:0732353535">
              <v-icon>
                mdi-phone
              </v-icon>
            </v-btn>
          </v-list-item-action>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title> Garissa</v-list-item-title> 0111207207 /
            0110040836 / 011040708</v-list-item-content
          >
          <v-btn large color="primary" icon href="tel:0111207207">
            <v-icon>
              mdi-phone
            </v-icon>
          </v-btn>
        </v-list-item>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title> Turkana</v-list-item-title>
            0758722023</v-list-item-content
          >
          <v-btn large color="primary" icon href="tel:0758722023">
            <v-icon>
              mdi-phone
            </v-icon>
          </v-btn>
        </v-list-item>
      </v-list>
    </v-col>
  </v-row>
</template>

<script>
export default {
  transition: 'scroll-y-reverse-transition',
  head() {
    return {
      title: 'Helpline',
      titleTemplate: null,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content:
            'COVID_19 contact information Kenya. All the helpline numbers are toll free'
        }
      ]
    }
  }
}
</script>

<style></style>
