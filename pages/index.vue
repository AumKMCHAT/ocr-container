<template>
   <div class="container">
      <div class="upload">
         <v-file-input
            label="File input"
            filled
            prepend-icon="mdi-camera"
        ></v-file-input>
        <v-btn depressed color="primary" v-on:click="submitFile()">Submit</v-btn>
      </div>
   </div>
</template>
