## Introduction

Grillage js décompose une image en plusieurs colonnes et sur 3 lignes en hauteur, pour donner un effet de grille. Il est ensuite possible d'appliquer une classe de son choix sur chacun des ses éléments pour leur attribuer un effet d'animation par exemple.


## How To Use

1. Wrap your image with an html element
2. import jQuery
3. import grillage js
4. Aplly grillage & grillage options


```bash

# 1. Your code with grillage
<div class="test">
<img src="your-image?jpg" />
</div>

# 2. add jQuery
 <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

# 3. add grillage Js
<script src="js/grillage.js"></script>
 
# 4. add your option configuration
  <script>
    $('.test').grillage({
      borderColor: "yellow",
      borderSize: "3px",
      hoverEffect: "animate__shakeX",
      structure : [
      [33.33,33.33,33.33],
      [20,20,30,30],
      [20,50,20,10],
      ],
    });
  </script>
```


## Download

You can [preview grillage js there](https://projetsmerlin.github.io/grillage/)
You can [download grillage js there](https://github.com/ProjetsMerlin/grillage/archive/refs/heads/master.zip)


## Credits

Created by https://lintermediaire.be


## Related

[https://jquery.com/download/] (https://jquery.com/download/) : dependencies
[animated.css](https://github.com/amitmerchant1990/markdownify-web) if you want a classes


## License

FREE

---