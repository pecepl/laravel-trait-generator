<br />
<div align="center">
  <a href="https://github.com/timwassenburg/laravel-trait-generator">
    <img src="img/wrench.png" alt="Logo" width=120>
  </a>

<h1 align="center">Laravel Trait Generator</h1>

  <p align="center">
    Quickly generate traits for your projects!
  </p>
<br><br>
</div>

## Table of Contents

  <ol>
    <li><a href="#installation">Installation</a></li>
    <li>
      <a href="#usage">Usage</a>
    </li>
    <li><a href="#more-generator-packages">More generator packages</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>

## Installation

Install the package with composer.

```bash
composer require timwassenburg/laravel-trait-generator
```

## Usage

Run the following command on the command-line to generate a new trait.

```
php artisan make:trait {name}
```

Optionally, you can add multiple method names (seperated by comma) with the ```--methods``` param.

```bash
php artisan make:trait Notifiable --methods=notify,notifications
```

## More generator packages

Looking for more ways to speed up your workflow? Make sure to check out these packages.

- [Laravel Action Generator](https://github.com/timwassenburg/laravel-action-generator)
- [Laravel Pivot Table Generator](https://github.com/timwassenburg/laravel-pivot-table-generator)
- [Laravel Repository Generator](https://github.com/timwassenburg/laravel-repository-generator)
- [Laravel Service Generator](https://github.com/timwassenburg/laravel-service-generator)

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any
contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also
simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
