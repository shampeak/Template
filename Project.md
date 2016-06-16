Ŀ¼
---

1. src     - ����
2.  vendor  - packagist
3.  test    - phpunit  ��Ԫ����
4.  docs    - �ĵ�
5.  example - ���Գ���
6.  wwwroot - ���ز���

�ļ�
---
- .gitattributes
- .gitignore
- README.md
- LICENSE.md
- composer.json
- phpunit.xml.dist

#### composer.json

```
{
    "name": "grace/base",
    "description": "dev",
    "type": "library",
    "license": "MIT",
    "minimum-stability": "dev",
    "authors": [
        {
            "name": "shampeak",
            "email": "shampeak@sina.com"
        }
    ],
    "require-dev": {
        "phpunit/phpunit": "^4.0",
        "squizlabs/php_codesniffer": "^2.5",
        "phpdocumentor/phpdocumentor": "2.*"
    },

    "require": {
        "php" : "5.5.*"
    },
    "autoload":{
        "psr-4":{
            "Grace\\": "src"
        }
    },

    "SiteAbout":{
        "psr-4":{
            'https://packagist.org/',
            'https://poser.pugx.org/',
            'https://github.com/shampeak'
        }
    }

}
```



