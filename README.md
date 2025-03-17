# Zoocha Editorial Recipe Installation Guide

To install the Zoocha Editorial recipe, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory. 
3. Add the below in the Drupal Root's composer.json installer-paths
```sh
"web/recipes/custom/{$name}": ["type:drupal-recipe"]
```
4. Run the following command:

    ```sh
    ddev drush recipe recipes/custom/admin-theme-starter-recipe
    ```

This command will execute the Zoocha Editorial recipe installation.
