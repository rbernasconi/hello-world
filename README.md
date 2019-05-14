# hello-world
My first repository

To include this repository in your project create a composer.json file like:
-------------------------------------------------------------------------------
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/rbernasconi/hello-world.git"
        }
    ],
    "require": {
        "rbernasconi/hello-world": "dev-master"
    }
}
-------------------------------------------------------------------------------

and do a "composer install"
