# phpunit-code-coverage-theme

This is a Dark Theme for phpunit's code coverage report to html. I got really tired getting blinded by the white screen every night so I made this css file.

All you have to do is when your generating your report to copy the dark mode css file and replace the custom.css file with the new dark mode css.

I personally did this in a composer command like so.

Edit your composer.json to something like this to make it happen in 1 solid motion.

```
"scripts": {
        "cover": "vendor/bin/phpunit && cp -f tests/custom.css .phpunit.cache/html/_css/custom.css",
    },
```

Enjoy Here are before and after pics.

## Before
![image](https://user-images.githubusercontent.com/34264214/194009823-9063c45d-5309-454f-a942-d836bd48e47d.png)

## After
![image](https://user-images.githubusercontent.com/34264214/194009888-f1a5623d-6115-4a93-ae9a-53f168606ea4.png)
