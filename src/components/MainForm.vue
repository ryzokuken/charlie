<template>
  <b-card bg-variant="light">
    <b-form-group horizontal
                  breakpoint="lg"
                  label="Submit an article"
                  label-size="lg"
                  label-class="font-weight-bold pt-0"
                  class="mb-0">
      <b-form-group horizontal
                    label="Title:"
                    label-class="text-sm-right"
                    label-for="nestedStreet">
        <b-form-input id="nestedStreet"></b-form-input>
      </b-form-group>
      <b-form-group horizontal
                    label="Body:"
                    label-class="text-sm-right"
                    label-for="nestedCity">
        <b-form-input id="nestedCity"></b-form-input>
      </b-form-group>
    </b-form-group>
  </b-card>
</template>
