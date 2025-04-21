```php
<?php

  nombre JordiObisFarre;

  class Sobre extends Mi
  {
      public function getTrabajoActual()
      {
          return [
              'lugarDeTrabajo' => [
                  'compañía' => 'Freelance / Autònom',
                  'posición' => 'Desarrollador Web y de Aplicaciones',
                  'especialización' => [
                      'Frontend' => ['React', 'Angular', 'Bootstrap'],
                      'Backend' => ['PHP', 'MySQL'],
                      'Fullstack' => true
                  ]
              ]
          ];
      }

      public function getConocimientosSobre()
      {
          return [
              Angular::class,
              Bootstrap::class,
              CSharp::class,
              CSS::class,
              GitHub::class,
              HTML5::class,
              Java::class,
              Javascript::class,
              MySQL::class,
              PHP::class,
              PowerShell::class,
              React::class,
              ReactNative::class,
              SharePoint::class,
              TailwindCSS::class,
              Wordpress::class
          ];
      }     
  }

?>

```
