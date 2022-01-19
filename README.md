### Hi there 👋

```php
<?php

namespace caullird;

class About extends Me
{
    private String name = 'Dorian';
    private String surname = 'CAULLIREAU';
    private Int age = 21;
    
   
    public function getCurrentSchool(): array
    {
        return [
            'school' => [
                'name' => 'Polytech Annecy Chambéry',
                'formation' => 'IDU [Informatique Données d'Usages]'       ,
                'keywords' => 'Data, Machine Learning, IA'
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            JAVA::class,
            SQL::class,
            C#::class,
            C::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'Develop, learn and advance..';
    }
}
```
