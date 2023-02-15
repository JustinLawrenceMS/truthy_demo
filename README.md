This is a comparison of php8 and php7 for checking truthiness.

To install, do this:

```git clone https://github.com/JustinLawrenceMS/truthy_demo.git```

Fall into your truthy_demo directory and do this:

```docker compose build```

```docker compose up```

Access the container terminal with docker, and then cd into the truthy directory:

```cd truthy```

```php truth.php```

If a variable is not set, it evaluates as false in php7 and throws a warning in php8.  Apart from that, I don't see a difference. This could because of a refinement of earlier versions of php8, when truthiness checks were a frequent breaking change.
