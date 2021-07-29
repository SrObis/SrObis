```php
<?php

  nombre JordiObisFarre;

  class Sobre extends Mi
  {
      public function getTrabajoActual()
      {
          return [
              'lugarDeTrabajo' => [
                  'compañía' => 'Indra Sistemas',
                  'position' => 'Técnico Software SharePoint'         
              ]
          ];
      }

      public function getDConocimientosSobre()
      {
          return [
              Angular::class,
              Bootstrap::class,
              C#::class,
              CSS::class,
              GitHub::class,
              HTML5::class,
              Java::class,
              Javascript::class,
              PowerShell::class,
              React::class,
              ReactNative::class,
              SharePoint::class,
              Php::class,
          ];
      }


  }
  
?>
```
