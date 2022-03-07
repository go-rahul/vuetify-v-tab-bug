# vuetify-v-tab-bug
v-tabs and v-tab components are not working.

# Error
[Vue warn]: Failed to resolve component: v-tab<br>
If this is a native custom element, make sure to exclude it from component resolution via compilerOptions.isCustomElement. 

[Vue warn]: Failed to resolve component: v-tabs<br>
If this is a native custom element, make sure to exclude it from component resolution via compilerOptions.isCustomElement. 

# How to reproduce?
1. Clone this repo.
2. Run `yarn install`.
3. Run `yarn serve`.

or,

1. Create a new Vue 3 project using Vue CLI.
2. Add Vuetify by running `vue add vuetify` & select Vuetify 3 Preview.
3. Try to use the v-tab component.
