
# usage

```php
# router
Route::get('path','controller')->middleware(LaravelRequestId::class);

# controller
Log::debug('debug information');

# log file
# datetime [uuid] channel.level info

# http reponse header
# X-Request-Id: uuid

# get current request id
request()->attributes->get('request-id');
```
