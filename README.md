## Angular 9 RC0 ivy "Hello World"

This shows how small a simple 'hello world' app can be with Angular 9 RC0 (modern browsers only to avoid polyfills, experimental / private "ɵrenderComponent" renderer, no zone.js).

Bundle size (gzip compressed) for this 'hello world' example is only 6.6 KB, the total size of the app is 17.8 KB.

## Build

Run `ng build --prod` to build the project.

## Running

I use [local-web-server](https://github.com/lwsjs/local-web-server) to serve the project, as it supports HTTP2 and content compression.

Build the project, go to `dist/hello-ivy5`, then start the web server with `ws --http2 -z --port 9001`

If you don't have local-web-server, you can run `ng serve --prod`

## Running it from now.sh

I have also uploaded this example to now.sh. You can (run it from now.sh)[https://hello-ivy5.oocx.now.sh/] directly without compiling it yourself. However, now.sh uses a slightly less aggressive compression, so the bundle size is 7.8 KB instead of the 6.6 KB that you can get with local-web-server.
