## Laravel

```

composer global require laravel/installer
laravel new Testseite
cd Testseite

php artisan serve

```

## Laravel UI
### Installation
```
composer require laravel/ui
```

### Frontend-Gerüst

```

Generieren // Grundgerüst ... 
php artisan ui bootstrap
php artisan ui vue
php artisan ui react

// generieren Login / Registrierung Baugerüst ... 
php artisan ui bootstrap --auth
php artisan ui vue --auth
php artisan ui react --auth


```
### CSS Schreiben

```
npm install
npm run dev

```

### Javascript

```
npm install
npm run dev

```


### Mysql Datenbank erstellen 

```
CREATE DATABASE Lavarel CHARACTER SET 'utf8mb4' COLLATE 'utf8mb4_unicode_ci';
exit;
```

### Server Restarten

```
php artisan config:cache
```

### Ausführen von Migrationen

```

php artisan migrate

```
