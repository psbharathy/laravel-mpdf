### mPDF Wrapper for Laravel 5

## Installation
Begin by installing this package through Composer. Edit your project's `composer.json` file to require `compassites/laravel-mpdf`.

```json
{
  "require": {
       "compassites/laravel-mpdf" : "master"
    }
}
```

Next, update Composer from the Terminal:
```bash
$ composer update
```

Once this operation completes, the final step is to add the service provider. Open `app/config/app.php`, and add a new item to the providers array.
```php
'Compassites\Mpdf\ServiceProvider',
```

You can also register facade.


```php
'PDF' => 'Compassites\Mpdf\Facades\Pdf',
```


### License

This mPDF Wrapper for Laravel5 is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)
