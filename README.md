# :toilet: Phlush Permalinks

**Phlush Permalinks** is a WordPress plugin that automates the process of flushing permalink rules at custom intervals. Additionally, it allows you to select specific actions that will trigger an automatic permalink flush. This plugin is ideal for those who frequently modify post types, taxonomies, or other WordPress structures that rely on permalinks.

## Features

- **Automatic Permalink Flushing**: Flushes WordPress permalinks at user-defined intervals.
- **Custom Action Triggers**: Allows you to select specific actions that will automatically trigger a permalink flush.
- **Easy-to-Use Settings**: Integrated settings page within the WordPress admin area for easy configuration.
- **Support for Popular Plugins**: Includes conditional support for WooCommerce, Yoast SEO, and Advanced Custom Fields (ACF).

## Installation

1. **Upload the Plugin Files**: Upload the `phlush-permalinks` folder to the `/wp-content/plugins/` directory.
2. **Activate the Plugin**: Activate the plugin through the 'Plugins' screen in WordPress.
3. **Configure the Settings**: Navigate to `Settings > Phlush Permalinks` to configure the plugin.

## Usage

### 1. Setting the Flush Interval
- Go to `Settings > Phlush Permalinks`.
- Enter the number of minutes for the flush interval.
- The plugin will automatically flush the permalinks at the specified interval.

### 2. Selecting Actions to Trigger a Flush
- In the same settings page, you can select from a list of predefined actions that will trigger an automatic permalink flush.
- Available actions include:
  - Post Save/Edit
  - Post Creation
  - Page Save/Edit
  - Category Creation/Edit/Deletion
  - Menu Update
  - Widget Update
  - WooCommerce Product Save/Edit (if WooCommerce is active)
  - Yoast SEO Post Save (if Yoast SEO is active)
  - ACF Field Group Save (if ACF is active)
- The plugin will hook into these actions and automatically flush permalinks whenever they occur.

### 3. Manual Permalink Flush
- A manual flush button is available in the settings page for on-demand flushing of permalinks.

## Development

### Hooks and Filters

- **Filters**:
  - `phlush_permalinks_available_actions`: Modify the list of available actions that can trigger a permalink flush.

### Code Structure

- **Main Plugin File**: `phlush-permalinks.php` - Contains all the core logic for the plugin.
- **Assets**: 
  - CSS and JS files for the Select2 library are located in the `assets` folder.

### Sanitization and Security

- User inputs for the flush interval and selected actions are sanitized before being saved to the database.
- The plugin uses WordPress's nonce system for security on the settings page.

## Frequently Asked Questions

**Q: Why should I use this plugin?**
- A: If you frequently modify your site's structure, like adding or updating custom post types or taxonomies, this plugin ensures your permalinks are always up-to-date without manual intervention.

**Q: Will this plugin affect my site's performance?**
- A: Flushing permalinks can be a resource-intensive operation, so the plugin is designed to only flush when necessary, based on user-defined intervals or specific actions.

**Q: Is this plugin compatible with WooCommerce and Yoast SEO?**
- A: Yes, the plugin includes conditional support for WooCommerce and Yoast SEO, allowing you to trigger a flush on specific actions related to these plugins.

## Changelog

### 1.0.0
- Initial release of Phlush Permalinks.

## License

This plugin is licensed under the GPLv3 License. See the [LICENSE](http://www.gnu.org/licenses/gpl-3.0.txt) file for more information.

## Support

If you have any questions or need help, please visit [https://robertdevore.com](https://robertdevore.com) for more information.
