<!-- TOC -->

- [CSS/SCSS/SASS](#cssscsssass)
- [Javascript](#javascript)
  - [Angular](#angular)
  - [Node](#node)
- [Markdown](#markdown)

<!-- /TOC -->

### CSS/SCSS/SASS

- `bb`
    ```css
    box-sizing: border-box;
    ```
    
    ```sass
    box-sizing: border-box
    ```

### Javascript

- `cl`
    ```js
    console.log(#);
    ```
- `use`
    ```js
    'use strict;'
    ```
- `rp`
    ```js
    return new Promise((resolve, reject) => {
    });
    ```

#### Angular

- `rq`
    ```js
    return $q((resolve, reject) => {
    });

- `factory`
    ```js
    angular.module('#').factory('#Factory', function($q, $http) {
    });
    ```
- `ngController`
    ```js
    angular.module('#').controller('#Ctrl', function($scope) {
    });
    ```
- `router` (`ngRoute`)
    ```js
    angular.module('#', ['ngRoute'])
        .config($routeProvider => {
            $routeProvider
                .when('#', {
                    templateUrl: '#',
                    controller: '#'
                })
                .otherwise('#');
    });
    ```

#### Node
- `dx`
    ```js
    #!/usr/bin/env node
    ```
- `pe`
    ```js
    process.exit();
    ```
- `di`
    ```js
    describe('#', () => {
        it('#', () => {
        });
    });
    ```
- `ddi`
    ```js
    describe('#', () => {
        describe('#', () => {
            it('#', () => {
            });
        });
    });
    ```
- `ch`
    ```js
    const { assert } = require('chai');
    ```

### Markdown

- `badge`
    ```md
    ![](https://img.shields.io/badge/#-#-#.svg)
    ```
    
    - `bs`
        
        ![](https://img.shields.io/badge/css-bootstrap-5F2C7C.svg)

    - `materialize`

        ![](https://img.shields.io/badge/css-materialize-F95972.svg)

    - `sass`

        ![](https://img.shields.io/badge/css_preprocessor-sass-DC4497.svg)

    - `postgres`

        ![](https://img.shields.io/badge/data-postgres-316391.svg)

    - `jquery`

        ![](https://img.shields.io/badge/jquery-version-005FAD.svg)
        
    - `node`
        
        ![](https://img.shields.io/badge/node-version-61BC62.svg)

    - `lodash`
        
        ![](https://img.shields.io/badge/lodash-version-3554FF.svg)

    - `angular`
        
        ![](https://img.shields.io/badge/angularJS-version-D00027.svg)