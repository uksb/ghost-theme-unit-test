# The Ghost Theme Unit Test

An importable file of test cases for [Ghost](https://ghost.org/) themes. It's based on the concept (and the content!) of the [WordPress Theme Unit Test](http://codex.wordpress.org/Theme_Unit_Test).

This step in Theme testing correlates to a Ghost export (`json`) file that you can import into a Ghost installation to test your theme. To be clear, this is only one of many ways you should/could test a theme.

## Getting Setup
Assuming you've already gotten Ghost set up locally and it is running your theme, here are the steps to setting up the unit test:

1. Go to the Staff section, click on the Ghost user if you have one and click on the cog icon (top-right) and delete the Ghost user and posts
2. Download this repo.
3. Go to the labs section of your Ghost installation's settings (`http://example.com/ghost/settings/labs/`)
4. Click the red 'Delete' button to clear the database of all existing content, and confirm (this gives us a clean slate)
5. Click 'Choose File' under Import 
6. In the resulting file picker, navigate to wherever you downloaded the repo and select the `json` file.
7. Click the blue `Import` button.

## Testing
Each post or page is usually pretty self explanatory, or has instructions included. Have fun!

## License

Released under the [WTFPL](http://wikipedia.org/wiki/WTFPL).

## Contributing
Submit a pull request
