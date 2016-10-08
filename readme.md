**Requirements: PHP 5.4+, Composer, MySQL**

1) Install dependencies using composer.

```
composer install
```

2) Build the database index. It will take a few minutes to complete.

```
php load.php
```

3) Run the voice insertion script itself. This will take even longer - anywhere between 10 minutes and an hour depending on the length of the chapter and performance of your computer.

```
php insert.php <path to the txt scripts of the chapter>
```
