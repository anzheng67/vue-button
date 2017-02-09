# vue-button
Button component for Vue 2.

## Installation

    npm install @nylira/vue-button

## Usage

    <template>
      <btn date="February 28, 2017"></btn>
    </template>

    <script>
      import Btn from '@nylira/vue-button'
      export default {
        components: {
          Btn
        }
      }
    </script>

    <style>
      .ni-btn-wrapper {
        display: inline-block;
      }
      .ni-btn {
        background: #f00;
      }
    </style>

## Props

    value=""
    // The label of the button
    // Options: Any valid string"

    icon=""
    // If you're using FontAwesome, places an icon to the left of the label
    // Options: Check http://fontawesome.io/icons

    icon-pos=""
    // Move the icon to the right side instead of the left
    // Options: "right"

    size=""
    // Chanage the size of the button
    // Options: "lg", "sm"

    theme="tendermint"
    // Adds a custom button theme
    // Options: "tendermint", "alpha-black"

    type="button"
    // Button type (mainly used for HTML forms)
    // Options: "button", "submit"
