# ScarlettMVC ![CI status](https://img.shields.io/badge/build-passing-brightgreen.svg)

ScarlettMVC is a lightweight framework to get you building your next PHP application
using an MVC architectural design style. As a result of bypassing
the initial setup, you can start building your project immediately.

## Installation

Download or clone the git repository.

### Requirements

-   Apache local server environment (Nginx can be used but .htaccess files will need to be deleted/changed)
-   MySQL database environment
-   PHP 5+

## Recommendations

-   If you are a relatively new programmer, it is recommended that you use WAMP, MAMP, XXAMP, or any pre-bundled variation of LAMP stack to fulfill the above requirements.

## IMPORTANT NOTE - PLEASE READ BEFORE USE

-   In the `.htaccess` file inside of the public directory, one line must be changed or the
    framework WILL NOT WORK for your personal development environment. It occurs on line 4.

```
RewriteBase /ScarlettMVC/public
```

-   Replace `/ScarlettMVC/public` with the path to your public folder. If your root project directory
    is `My_Project` then you would replace `/ScarlettMVC` with `/My_Project`. The full line for this
    example:

```
RewriteBase /My_Project/public
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
