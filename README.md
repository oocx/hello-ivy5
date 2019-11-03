## Angular 9 RC0 ivy "Hello World"

This shows how small a simple 'hello world' app can be with Angular 9 RC0 (modern browsers only to avoid polyfills, experimental / private "ɵrenderComponent" renderer, no zone.js).

Bundle size (gzip compressed) for this 'hello world' example is only 7 KB, the total size of the app is 17.8 KB.

## Build

Run `ng build --prod` to build the project.

## Running

I use [local-web-server](https://github.com/lwsjs/local-web-server) to serve the project, as it supports HTTP2 and content compression.

Build the project, go to `dist/hello-ivy5`, then start the web server with `ws --http2 -z --port 9001`

If you don't have local-web-server, you can run `ng serve --prod`

