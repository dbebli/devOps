# devOps
#copier mon dossier sur linux: scp -p -r ./[nomdudossier] [nom du compte]@[ip machine]:[chemin vers ou copier]
#exemple sur mon encironnemt: scp -p -r ./TP5 dani@192.168.191.129:/home/dani/



#mise en place test unitaire (executer dans la vm)

#docker run --rm -v $(pwd):/app composer/composer:latest require --dev phpunit/phpunit ^6.0
#cd TP5
#lancer le test (a la racine du dossier) : docker run -v $(pwd):/app --rm phpunit/phpunit:latest --bootstrap tests/ExampleClass.php tests/testviashell.php
