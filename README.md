### Javascript

- `log`
    ```js
    console.log("#");
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
    angular.module("#").factory("#", function($q, $http) {
    });
    ```
- `ngController`
    ```js
    angular.module("#").controller("#", function($scope) {
    });
    ```
- `use`
    ```js
    "use strict;"
    ```
- `dx`
    ```js
    #!/usr/bin/env node
    ```

### CSS/SCSS

- `bb`
    ```css
    box-sizing: border-box;
    ```