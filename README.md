
# usage

```php
# router
Route::get('path','controller')->middleware(LaravelRequestId::class);

# controller
Log::debug('debug information');

# log file
# datetime [uuid] channel.level info
```
