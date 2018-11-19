<!-- TOC -->

- [CSS/SCSS/SASS](#cssscsssass)
- [Javascript](#javascript)
  - [Angular](#angular)
  - [Node](#node)
- [Markdown](#markdown)
- [Java](#java)

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
- `ep`
    ```js
    export default {
    }
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

#### Vue
- `sc`
    ```html
    <script>
    </script>
    ```
- `ep`
    ```js
    export default {
    }
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

    - `pg`

        ![](https://img.shields.io/badge/data-postgres-316391.svg)

    - `jq`

        ![](https://img.shields.io/badge/jquery-version-005FAD.svg)
        
    - `node`
        
        ![](https://img.shields.io/badge/node-version-61BC62.svg)

    - `lo`
        
        ![](https://img.shields.io/badge/lodash-version-3554FF.svg)

    - `ng`
        
        ![](https://img.shields.io/badge/angularJS-version-D00027.svg)
    
    - `gr`

        ![](https://img.shields.io/badge/grunt-version-ED8024.svg)

    - `hb`

        ![](https://img.shields.io/badge/handlebars-version-F47904.svg)
    
    - `ch`

        ![](https://img.shields.io/badge/testing-chai+mocha-a40802.svg)

### Java

- `main`
    ```java
    public static void main(String[] args) {
        #
    }
    ```

- `out`
    ```java
    System.out.println(#);
    ```

- `bi`
    ```java
    BigInteger
    ```

- `mmtest`
    ```java
	@Test
	public void test_#_expect#() throws Exception {
	    mockMvc.perform(
            #("/#")
                .contentType(MediaType.APPLICATION_JSON_UTF8)
		)
            .andExpect(status().#());
	}
    ```

- `psf`
    ```java
    public static final
    ```

- `pv`
    ```java
    public void 
    ```