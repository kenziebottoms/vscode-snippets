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