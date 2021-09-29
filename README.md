# tugaskuliah
I usually put my task code here.
<?php

namespace Rahmat AY;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'college' => 'Yogyakarta State University',
                'position' => 'Student'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Python::class,
            Java::class,
            C++::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'be come a developer someday.';
    }
}
