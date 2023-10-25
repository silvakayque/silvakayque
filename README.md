```php
class Attributes {
    public static function contact() {
        $discord = "polakznx";
        $email = "kayqueeduardo28@gmail.com";

        return [$discord, $email];
    }

    public static function life() {
        $langs = ['portuguese', 'english'];
        $age = 19;

        return [$langs, $age];
    }

    public static function coding() {
        $langs = [
            'intermediate' => ['javascript'],
            'learning' => ['php', 'c', 'c++']
        ];

        $specialities = ['back-end'];
        $environnement = ['vscode'];

        return [$langs, $specialities, $environnement];
    }
}
