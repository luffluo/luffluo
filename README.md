```php
<?php

namespace LuffLuo;

class About extends Me
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'CHUANG KE EDU',
                'position' => 'Backend Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            TailwindCss::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'To contribute to open source.';
    }
}
```
