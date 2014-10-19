# wkhtmltopdf for Ubuntu 12.04 (precise) 0.12.1 qtwebkit

[All the binaries for Ubuntu 12.04 (precise) from http://wkhtmltopdf.org/downloads.html](http://wkhtmltopdf.org/downloads.html)

## Install

1. Install Composer:

    ```    
    curl -s https://getcomposer.org/installer | php
    ```
    
2. Add to your `composer.json` file:

    ```js
    {
        "require": {
            "profburial/wkhtmltopdf-binaries-precise": "0.12.1"
        }
    }
    ```

3. All the binaries are symlinked to the following paths:

```
vendor/bin/wkhtmltoimage-linux-precise-amd64

vendor/bin/wkhtmltoimage-linux-precise-i386

vendor/bin/wkhtmltopdf-linux-precise-amd64

vendor/bin/wkhtmltopdf-linux-precise-i386
```

Enjoy the bin files!