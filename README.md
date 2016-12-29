# resp-sass
Making writing responsive sass easy.

## Getting started : 
1. npm install resp-sass
2. Import [_resp-mixin.scss](https://github.com/paulpatarinski/resp-sass/blob/master/src/_resp-mixin.scss)

    ```
    @import "node_modules/resp-sass/src/resp-mixin";
    ```

3. Use the **set-resp-value** mixin in your sass

    ```
    .cat-img {
        @include set-resp-value((height,width),140px,180px,240px);
    }
    ```

4. Modify the breakpoints in [_resp-config.scss](https://github.com/paulpatarinski/resp-sass/blob/master/src/_resp-config.scss) to your own liking
    > Default values are mobile-centric

## Examples :

1. clone repo
2. npm run init
3. open examples/index.html
4. sad...responsive cat
5. take a look at [examples/app.scss](https://github.com/paulpatarinski/resp-sass/blob/master/examples/app.scss) & [examples/_features.scss](https://github.com/paulpatarinski/resp-sass/blob/master/examples/_feature.scss) to figure out how it all works...
