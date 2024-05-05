<template>
  <v-container>
    <v-row>
      <v-col cols="12" sm="6" theme="dark">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo,
          earum quam consequatur a asperiores sunt inventore sequi impedit
          quaerat, velit, accusantium ducimus aliquid possimus! Vitae voluptate
          doloremque amet maxime consequuntur
        </p>
      </v-col>
      <v-col cols="12" sm="6">
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Explicabo,
          earum quam consequatur a asperiores sunt inventore sequi impedit
          quaerat, velit, accusantium ducimus aliquid possimus! Vitae voluptate
          doloremque amet maxime consequuntur
        </p>
      </v-col>
    </v-row>
    <!-- uses the current default theme -->
    <v-card>...</v-card>

    <v-theme-provider theme="high-contrast">
      <!-- uses the high-contrast theme -->
      <v-card>...</v-card>
      <v-btn>...</v-btn>
    </v-theme-provider>
  </v-container>
</template>
