# WordPress Example

This is a quick example of running WordPress in CodeSandbox.

## Usage

1. Create a folder for the theme you want to work on (for example `myTheme`)
2. Modify `docker-compose.yml` to add a mounted volume for the theme:
  ```
  - ./myTheme:/var/www/html/wp-content/themes/myTheme
  ```
3. Restart the `Start WordPress` task.
4. Visit the preview (port 8080) to finish installation.

If necessary, additional volumes can be mounted for other themes, plugins, and uploaded content.
Whenever `docker-compose.yml` changes, restart the `Start WordPress` task.
