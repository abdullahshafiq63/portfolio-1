<template>
  <div class="mt-8">
    <div class="mt-2">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Frontend
      </h2>

      <ul class="flex flex-wrap gap-4 items-center">
        <li class="flex items-center">
          <React class="h-10 w-10"></React>
        </li>
        <li class="flex items-center">
          <Next class="next h-10 w-10"></Next>
        </li>
        <li class="flex items-center">
          <Angular class="angular h-10 w-10"></Angular>
        </li>
        <li class="flex items-center">
          <Vuejs class="h-10 w-10"></Vuejs>
        </li>
        <li class="flex items-center">
          <Nuxt class="h-10 w-10"></Nuxt>
        </li>
        <!-- <li class="flex items-center">
          <Html class="h-10 w-10 rounded-sm drop-shadow-sm"></Html>
        </li>
        <li class="flex items-center">
          <Css class="h-10 w-10 rounded-sm drop-shadow-sm"></Css>
        </li> -->
        <li class="flex items-center">
          <Javascript class="h-10 w-10"></Javascript>
        </li>
        <li class="flex items-center">
          <Bootstrap class="h-10 w-10"></Bootstrap>
        </li>
        <li class="flex items-center">
          <TailwindCss class="h-10 w-10"></TailwindCss>
        </li>
      </ul>
    </div>
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Backend
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <Node class="h-10 w-10"></Node>
        </li>
        <li class="flex items-center">
          <Ruby class="backend h-10 w-10"></Ruby>
        </li>
        <li class="flex items-center">
          <Rails class="rails h-10 w-10"></Rails>
        </li>
        <li class="flex items-center">
          <AWS class="backend h-10 w-10"></AWS>
        </li>
        <li class="flex items-center">
          <Postgres class="h-10 w-10"></Postgres>
        </li>
      </ul>
    </div>
    <!-- <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Databases
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center">
          <Postgres class="h-10 w-10"></Postgres>
        </li>
        <li class="flex items-center">
          <Mysql class="h-10 w-10"></Mysql>
        </li>
        <li class="flex items-center">
          <Mongodb class="h-10 w-10"></Mongodb>
        </li>
      </ul>
    </div> -->
    <div class="mt-4">
      <h2
        class="mb-2 text-xl text-gray-700 font-bold dark:text-blue-200 capitalize"
      >
        Mobile App Development
      </h2>
      <ul class="mb-6 flex flex-wrap gap-4">
        <li class="flex items-center rn">
          <React class="h-10 w-10"></React>
        </li>
        <li class="flex items-center">
          <Flutter class="h-10 w-10"></Flutter>
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
import Javascript from "../assets/devicon/javascript.svg?inline";
import Html from "../assets/devicon/html.svg?inline";
import Css from "../assets/devicon/css.svg?inline";
import Vuejs from "../assets/devicon/vuejs.svg?inline";
import TailwindCss from "../assets/devicon/tailwindcss.svg?inline";
import Nuxt from "../assets/devicon/nuxt.svg?inline";
import Bootstrap from "../assets/devicon/bootstrap.svg?inline";
import Laravel from "../assets/devicon/laravel.svg?inline";
import Node from "../assets/devicon/node.svg?inline";
import React from "../assets/devicon/react.svg?inline";
import Next from "../assets/devicon/next.svg?inline";
import Angular from "../assets/devicon/angular.svg?inline";
import AWS from "../assets/devicon/aws.svg?inline";
import Rails from "../assets/devicon/rails.svg?inline";
import Ruby from "../assets/devicon/ruby.svg?inline";
import Strapi from "../assets/devicon/strapi.svg?inline";
import RN from "../assets/devicon/rn.svg?inline";
import Flutter from "../assets/devicon/flutter.svg?inline";
import Postgres from "../assets/devicon/postgresql.svg?inline";
import Mysql from "../assets/devicon/mysql.svg?inline";
import Mongodb from "../assets/devicon/mongodb.svg?inline";
export default {
  components: {
    Javascript,
    Html,
    Css,
    Bootstrap,
    Vuejs,
    TailwindCss,
    Nuxt,
    Laravel,
    Node,
    React,
    Next,
    Angular,
    AWS,
    Rails,
    Ruby,
    Strapi,
    RN,
    Flutter,
    Postgres,
    Mongodb,
    Mysql,
  },
};
</script>

<style>
  .next {
    width: 4rem;
  }
  .angular {
    height: 3rem;
    width: 3rem;
  }
  .backend {
    height: 60px;
    width: 60px;
  }
  .rails {
    height: 70px;
    width: 70px;
  }
  .strapi {
    height: 70px;
    width: 70px;
  }
  .rn {
    background-color: #000;
    border-radius: 3px;
  }
</style>
