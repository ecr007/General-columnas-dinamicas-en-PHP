# General columnas dinamicas en PHP

```php

$contentPerPage = 8;
$informacion = 10;

echo "\n<open>";
for($i = 0; $i < 10; $i++){
    
    if($i % $contentPerPage === 0 && $i != 0){
        echo "\n<close>";
        echo "\n<open>";
      
    }
    
    echo "\ninfo";
    
    
}

 echo "\n<close>";
 ```
 
 Esta en uso en el proyecto tg
