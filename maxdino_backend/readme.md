About Debbuge API:
- config file app.php:
+ At providers:         Lanin\Laravel\ApiDebugger\ServiceProvider::class,
About JWT:
- config file app.php:
+ At providers:       Tymon\JWTAuth\Providers\LaravelServiceProvider::class,
+ At aliases:         'JWTAuth' => Tymon\JWTAuth\Facades\JWTAuth::class,
- Run this command: 
+ php artisan vendor:publish --provider="Tymon\JWTAuth\Providers\LaravelServiceProvider"
+ php artisan jwt:secret
About L5-Swagger:
- config file .env:
+ SWAGGER_VERSION=2.0