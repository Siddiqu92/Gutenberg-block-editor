=== BlockForge - Advanced Gutenberg Blocks ===
Contributors: [Siddique khan ]
Tags: Gutenberg, blocks, WordPress, custom blocks
Requires at least: 5.0
Tested up to: 6.2


== Description ==
BlockForge is a powerful Gutenberg block plugin that introduces custom-built blocks to enhance the WordPress editor experience. This plugin currently includes two blocks:

1. Hero Section Block - A customizable block for adding hero sections with media and text.
2. Call-To-Action Block - A block designed for compelling calls-to-action with customizable content.

== Installation & Activation ==
Before installing BlockForge, ensure that no other custom block plugins are installed to prevent conflicts. If you have any other block editor plugins installed, deactivate and uninstall them first.

 Step 1: Install the Plugin
1. Download the BlockForge plugin or place the folder inside `wp-content/plugins/`.
2. Ensure the folder structure is correct:
   - `blockforge.php` - Main plugin file
   - `package.json` - Node.js dependencies
   - `webpack.config.js` - Webpack configuration
   - `src/` - Source folder containing JavaScript and styles
   - `blocks/` - Contains individual block files
   - `build/` - Compiled output folder
   - `readme.txt` - Plugin details

 Step 2: Activate the Plugin
1. Go to your WordPress Dashboard.
2. Navigate to Plugins > Installed Plugins.
3. Locate BlockForge in the list.
4. Click Activate.

== Plugin Setup & Configuration ==
 Step 1: Configure WordPress Settings
1. Go to Settings > Writing.
2. Enable Gutenberg if necessary.
3. Save your changes.

 Step 2: Add Blocks to a New Post
1. Navigate to Posts > Add New.
2. Click on the + (Add Block) button.
3. Search for:
   - `Hero Section`
   - `Call-To-Action`
4. Select the desired block and customize it according to your needs



 Register Blocks
- Create Hero Section Block
- Create Call-To-Action Block
- Utilize Media Upload and RichText Editor for customization

 Build the Plugin
Run:
```sh
npm run build
```
This will generate production-ready files inside the `build/` folder.

== Usage ==
1. Open the WordPress post editor.
2. Click on the + (Add Block) button.
3. Search for `Hero Section` or `Call-To-Action`.
4. Add the block and customize it as needed.



