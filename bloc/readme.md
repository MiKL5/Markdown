# Le bloc de code

Il affiche le code brut avec une coloration pour que l'on puisse facilement le lire.  
Le bloc commence par 3 backtics ` ``` ` suivi du langage exemple `php` et de le refermer par 3 backtics.

```php
public function save(Order $entity, bool $flush = false): void
    {
        $this->getEntityManager()->persist($entity);

        if ($flush) {
            $this->getEntityManager()->flush();
        }
    }
```