# How to properly set-up the wp-api for production

In our latests projects we make use of the Wordpress API. This guide is to help you set-up the api, and create your first requests to the api.

1. How to set up
2. Plugins
3. WPML
4. Making the requests (Enpoints)
4. Next steps

## 1. How to set up

<p>
Use the bash script:
</p>

1. See {ROOT_FOLDER}api/bin
2. Run install.sh

// TODO: write something about the bashscript<br>
// TODO: add all plugins


## 2. Plugins

The plugins we need:

- **ACF to REST API**<br>
  Plugin to add custom fields to posts/pages/etc.
- **ACF to REST API Recursive**
- **Advanced Custom Fields PRO**
- **Classic Editor**<br>
  (we don't like the new editor)
- **Custom Post Type UI**<br>
  Plugin the create and edit post types, without the need of writing PHP
- **User Switching** <br>
  Plugin we use to easily switch between users to see what they see.
- **WP Migrate DB Pro**<br>
  Plugin to migrate db-between different eviroments
- **WP Migrate DB Pro Media Files**<br>
  Plugin to migrate media-files
- **WP REST Cache**<br>
  Efficiently cache the api
- **WPML Multilingual CMS**<br>
  Translation management
- **WPML Translation Management**<br>
  Translation management


## 2. ACF

### Cavats
Never make the fields translatable<br>
Don't forget to add a license-key!

## 3. WPML 

Start with installing the wpml plugin.

### Cavats
Don't forget to add a license-key!

## 4. Making the requests


## 5. Migrating the database to another enviorment


## 6. Next steps

- Dive into GraphQL wp plugin, to query efficiently from the client.
- How do we handle multisites?
