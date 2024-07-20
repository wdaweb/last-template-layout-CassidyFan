<template>
  <v-app >
      <v-main>
        <router-view v-slot="{Component}">
          <keep-alive include="index">
            <component :is="Component"></component>
          </keep-alive>
        </router-view>
      </v-main>
    </v-app>
  </template>
  <style>
    body{
      font-weight: bolder;
      font-family: "微軟正黑體";
      background-color: #d6cedf;
    }

    .title-size{
    font-size: 13px;
  }

  </style>
