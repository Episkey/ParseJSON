# Parser un fichier JSON de données météos

Ouvre le fichier `weather.json` afin d'en comprendre sa structure, puis complète la classe `WeatherParse`.

1. *Parser* le fichier `weather.json`
2. Récupérer la racine du document
3. Afficher la valeur de l'attribut "name" de la racine
4. Afficher les valeurs des attributs "lat" et "lon" de l'élément "coord" contenu dans la racine
5. Parcourir tous les éléments de "weather" et afficher le contenu de "main"
6. Compiler et exécuter le code afin d'obtenir l'affichage du résultat attendu :

```
* City name: London
* City latitude: 51.51
* City longitude: -0.13
* Weather: Drizzle
* Weather: Clear
```

Tu pourras compiler et exécuter ton code avec les commandes suivantes :
``` bash
javac -cp .:json-simple-1.1.1.jar WeatherParse.java
java -cp .:json-simple-1.1.1.jar WeatherParse
```
