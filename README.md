


## About Tweet Project

- **[Tweet: Laravel 10 and Breez,Initial Installation ](https://github.com/RishikantSri/tweet/commit/a1eee05ec16bd4f3892fbeb2fe0c76a2be5658e5)**
- **[Tweet : Show All Tweets, Index file and functionality](https://github.com/RishikantSri/tweet/commit/a4a56845ab4b3e6e61bb43e54d3bd4a19921152d)**
- **[Tweet : Storing data to database](https://github.com/RishikantSri/tweet/commit/8b98e09bc9addc8ad7c1fcc4202e8900a6ab4681)**
- **[Tweet : Showing Tweets ](https://github.com/RishikantSri/tweet/commit/5a61cd576f4e1fd87f92ae93c542cb49add367e5)**
- **[Tweet : Edit Tweet, Policy and Authorization](https://github.com/RishikantSri/tweet/commit/90fe0665f43071f8cc38b3379e1ead5d807d8efc)**
- **[Tweet : Delete Tweet, Policy and Authorization](https://github.com/RishikantSri/tweet/commit/6949ba796a94e933b16773b09da18e00b860d188)**
- **[Tweet: Notifications, Event, Listner, Event Listner, Event Provider ](https://github.com/RishikantSri/tweet/commit/484d9bc72a2c0653bc9a02ea6fe3b09e18507c91)**

| | |
|-|-|
|Installtion Steps | |
|******************| |
| | |
|a) Clone repository | |
|b) Copu .env.example to .enve file| update .env file|
|c) Run these commands in terminal | |
|    1) npm install | |
|    2) npm run dev| |
|    3) composer install | |
| | |
|    4) create app key| |
|        php artisan key:generate| |
|    5)  migrate tables| |
|        php artisan migrate | |
|    6)  create users|comment out in database\seeders\DatabaseSeeder.php|
|        password =&gt; password    | |
| | |
|        // \App\Models\User::factory()-&gt;create([| |
|        //     'name' =&gt; 'Tweet User1'| |
|        //     'email' =&gt; 'tweetuser1@example.com'| |
|        // ]);| |
|        // \App\Models\User::factory()-&gt;create([| |
|        //     'name' =&gt; 'Tweet User2'| |
|        //     'email' =&gt; 'tweetuser2@example.com'| |
|        // ]);| |
| | |
|        php artisan db:seed --class=DatabaseSeeder| |
| | |
|d) Login using above credentials or register new user| |
