### CSS/SCSS

- `bb`
    ```css
    box-sizing: border-box;
    ```

### Javascript

- `cl`
    ```js
    console.log(#);
    ```
- `use`
    ```js
    "use strict;"
    ```
- `dx`
    ```js
    #!/usr/bin/env node
    ```

#### Angular

- `router`
    ```js
    angular.module("#", ["ngRoute"])
        .config($routeProvider => {
            $routeProvider
                .when("#", {
                    templateUrl: "#",
                    controller: "#"
                })
                .otherwise("#");
    });
    ```
- `factory`
    ```js
    angular.module("#").factory("#Factory", function($q, $http) {
    });
    ```
- `ngController`
    ```js
    angular.module("#").controller("#Ctrl", function($scope) {
    });
    ```