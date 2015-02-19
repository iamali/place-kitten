&lt;place-kitten&gt;
============

##Destructions

Install Bower components
```
bower install
```

Import polyfill
```
<script src="bower_components/webcomponentsjs/webcomponents.js"></script>
```

Import element
```
<link rel="import" href="place-kitten/place-kitten.html">
```

Use element
```
<place-kitten></place-kitten>
```

##Attributes

| Attribute  | Description | Example  | Default  |
|---|---|---|---|
| greyscale  | Greyscale image instead of colour | ```<place-kitten greyscale></place-kitten>``` | false |
|  width | Width of share button | ```<place-kitten width="200"></place-kitten>``` | 400 |
|  height | Height of share button | ```<place-kitten height="150"></place-kitten>``` | 300 |

##Captions
To add a caption beneath the image, add it within the tag:
```
<place-kitten height="400" width="600" greyscale>This is a caption</place-kitten>
```  
