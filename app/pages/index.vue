<template>
  <div>
   <br>
    <h1>Welcome to My Nuxt App</h1>
    <br><br>

    <v-row>
      <v-col cols="12" md="3">
       <v-card color="blue" height:150> 
      <v-card-text>
        <v-row>
        <v-col cols="6">
          <v-icon size="90">mdi-account-circle</v-icon>
        </v-col>
        <v-col cols="6">
          <v-row>
            <v-col cols="12" class="text-h6 text-right ">student</v-col>
            <v-col cols="12" class="text-h3 text-right font weight-bold"> 250</v-col>
          </v-row>
        </v-col>
      </v-row>  
      </v-card-text>  
      </v-card> 
    </v-col>

      <v-col cols="12" md="3">
       <v-card color="red" height:150> 
      <v-card-text>
        <v-row>
        <v-col cols="6">
          <v-sheet color="white" height="90"></v-sheet>
        </v-col>
        <v-col cols="6">
          <v-row>
            <v-col cols="12" >
              <v-sheet color="white" height="40"></v-sheet>
            </v-col>
            <v-col cols="12">
              <v-sheet color="white" height="40"></v-sheet>  </v-col>
          </v-row>
        </v-col>
      </v-row>  
      </v-card-text>  
      </v-card> 
    </v-col>

      <v-col cols="12" md="3">
       <v-card color="green" 
      style="width:100%; height: 150px;"> 
      </v-card> 
    </v-col>

      <v-col cols="12" md="3">
       <v-card color="purple"   
      style="width: 100%; height: 150px;"> 
      </v-card> 
    </v-col>
     

    </v-row>

    <br><br>

    <v-btn color="blue">Submit</v-btn>
  </div>
</template>

<script lang="ts" setup>
</script>

<style>
</style>