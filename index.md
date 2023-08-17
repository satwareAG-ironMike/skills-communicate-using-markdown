# H1 Header

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

``` php
<?php declare(type="strict)

class Animal {
   abstract public function makeSound();
}

class YaktoCat extends Animal {
   public function makeSound() {
      return 'MEOW';
   }
}
```
