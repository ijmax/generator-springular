angular.module('<%= _.camelize(appname) %>', ['ui.router','ngAnimate','ng-polymer-elements']);

angular.module('<%= _.camelize(appname) %>').config(['$stateProvider','$urlRouterProvider',function($stateProvider, $urlRouterProvider) {
    
$stateProvider.state('index', {
        url: '/',
        templateUrl: 'home.html'
    });

    /* Add New States Above */
    $urlRouterProvider.otherwise('/');

}]);

