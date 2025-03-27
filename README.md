# ZR Editorial Recipe Installation Guide

To install the ZR Editorial recipe, follow the steps below:

1. Open your terminal.
2. Navigate to your project directory. 
3. Add the below in the Drupal Root's composer.json installer-paths
```sh
"web/recipes/custom/{$name}": ["type:drupal-recipe"]
```
4. Run the following command:

    ```sh
    ddev drush recipe recipes/custom/zr-editorial-bundle
    ```

This command will execute the ZR Editorial recipe installation.
