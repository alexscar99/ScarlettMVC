# ScarlettMVC ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

ScarlettMVC is a lightweight framework to get you building your next PHP application
using an MVC architectural design style. As a result of bypassing
the initial setup, you can start building your project immediately.

## Installation

Download or clone the git repository.

### Requirements

-   PHP 5+

## IMPORTANT NOTE - PLEASE READ BEFORE USE

-   In the .htaccess file inside of the public directory, one line must be changed or the
    framework WILL NOT WORK for your personal development environment. It occurs on line 4.

```
RewriteBase /ScarlettMVC/public
```

-   Replace /ScarlettMVC/public with the path to your public folder. If your root project directory
    is `My_Project` then you would write the following:

```
RewriteBase /ScarlettMVC/public
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

```

```
