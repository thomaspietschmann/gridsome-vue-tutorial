<template>
  <v-app>
    <v-app-bar app>
      <v-toolbar-title>Welcome to E-Vents</v-toolbar-title>
      <v-text-field placeholder="Search" class="ml-8"> </v-text-field>
      <v-spacer></v-spacer>
      <v-btn>Create Event</v-btn>
    </v-app-bar>
    <v-main>
      <slot />
    </v-main>
  </v-app>
</template>

<static-query>
query {
  metadata {
    siteName,
    siteDescription
  }
}
</static-query>

<style>
</style>