# HTML for Web Components Support
Current html syntax highlight doesn't color html elements with "dash" in it.  
In example, the following youtube-player element will be displayed with 2 colors instead of one:
```html
	<youtube-player id="#$5213123"></youtube-player>
```
With this HTML extended package, it will color the html element properly:
![example for web components](https://raw.github.com/orizens/html-extended/master/images/example.png)

This package should work with any color scheme.

## Set HTML or other extension files to automatically open with html extended syntax
1. open an html file that has a web component in it
2. from the menu, select: View -> Syntax -> Open all with current extension as... -> Html Extended