```php
<?php

namespace KelseyTaylor;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'industry' => 'RF',
                'position' => 'Software engineer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            React::class,
            ReactNative::class,
            Python::class,
            Bash::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
