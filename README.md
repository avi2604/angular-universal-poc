# Universal

This is angular universal project plese find the step to make project as universal

1. ng add @nguniversal/express-engine --clientProject ngb-accordian
2. npm install --save @nguniversal/module-map-ngfactory-loader
3. add import { ModuleMapLoaderModule } from "@nguniversal/module-map-ngfactory-loader"; in app.server.ts
4. Do npm run serve:ssr
5. run app on node server using npm run build:ssr
