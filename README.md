`Markdown.php` is a cleaned-up and improved version of Michel Fortin's
[Markdown_Parser](http://michelf.com/projects/php-markdown) (PHP-Markdown).

##Differences from the original:##
1. Complete PHPDoc/Dock Block documentation.
2. Removed global functions that were in place for platform-specific integration. I'll leave that up to the developer.
3. Improved (*subjective, yes*) code formatting.
4. Replaced some/most PHP4-style constructs and routines with modern PHP5.3+ equivalents. (e.g: closures instead of the archaic `create_function`).

##License:##
Markdown.php is free software, available under the terms of the GNU General Public License version 3 or a later version. If you like this software and want to say thanks, you can contribute by making a donation @ [michelf.com](http://michelf.com/projects/php-markdown).