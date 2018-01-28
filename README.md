# Bienvenue sur Wordplate/Wordplate

![enter image description here](https://image.noelshack.com/fichiers/2018/04/7/1517162216-wordplate.png)

Je vous propose directement les fichiers pour pouvoir installer librement Wordplate.
**Vous pouvez egalement le faire avec composer**
```
$composer create-project wordplate/wordplate
```


# Configuration

Dans un premier temps, il vous faut configurer la base de données en editant le fichier **.env**

```PHP
	DB_HOST=localhost
	DB_NAME=wordplate
	DB_USER=root
	DB_PASSWORD=root
	
	# Generer les clefs depuis le lien: https://wordplate.github.io/salt/
	AUTH_KEY=
	SECURE_AUTH_KEY=
	LOGGED_IN_KEY=
	NONCE_KEY=
	AUTH_SALT=
	SECURE_AUTH_SALT=
	LOGGED_IN_SALT=
	NONCE_SALT=
```

## Installer un Plugin

Vous avez également la possibilité d'installer des plu gins rapidement depuis votre console grâce a composer.
```
$composer require wpackagist-plugin/woocommerce
```

Vous pouvez trouver les packages relatif a wordpress ici : [wpackagist.org](https://wpackagist.org/)




