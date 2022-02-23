# WP-CLI Commands

List of commonly used WP-CLI commands

---

### Installation, status, clean-up

| Command | Description |
| ------- | ----------- |
| `wp core download` | Downloads WordPress core |
| `wp core version` | |
| `wp config get` | |
| `wp db size --tables` | |
| `wp media image-size` | List of registered image sizes |
| `wp option list` | 
| `wp site empty` | 
| `wp site empty --uploads` | 

### Plugins

| Command | Description |
| ------- | ----------- |
| `wp plugin list` | |
| `wp plugin install all-in-one-wp-migration --activate` | Installs and activates the plugin |
| `wp plugin install query-monitor --activate` | Installs and activates the plugin |
| `wp plugin update --all` | |
| `wp plugin delete --all` | NB! Plugins should be deactivated at this point |

### Posts

| Command | Description |
| ------- | ----------- |
| `wp post list --post_type=page --fields=ID,post_title,post_name,page_template` | List on pages with used page templates |
| `wp post meta list 119` | Show meta fields for the post ID 119 |
