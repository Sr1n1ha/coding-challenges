1. Create a base VueJS app using [Vue CLI](https://cli.vuejs.org/guide/installation.html). 
2. For UI, you can use [Vue Bootstrap](https://bootstrap-vue.js.org/) and or [Vue Ant Design](https://vue.ant.design/docs/vue/introduce/)
3. In the root of the app, add a view which rendrs the geoJSON data provided in [this file](testBlob.json).
4. View has two componenets:
- A Sidebar component which renders various filters populated based on the data attributes and associated values given in the geoJSON file. Filter can can be a slider, an autocomplete, dropdown select, or switch.
- A Map dispaly component which displays the Mapbox map and overlays geo-data points provided in the file on top of it. You can use [Vue-Mapbox wrapper](https://github.com/soal/vue-mapbox) or directly use [Mapbox GL JS library](https://github.com/mapbox/mapbox-gl-js).
- Create the binding between filter interactions and map display - so when a user interacts with sidebar filter, map gets updated with matching condition.
5. Add your app as Github repo and send us the link for the code review. Add a `Readme.md` file in your repository with instructions to build the app locally.
6. Bonus point if you want to deploy your app to Netlify using their free accounts.
