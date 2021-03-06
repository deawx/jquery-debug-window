# Debug Window
Creates a debug window that displays mouse position x/y and window width/height.
Listens for `console.log`, `console.warn` and `console.error` calls and outputs them to a debug window on the page.

Helps with debuging on devices that don't have console.

## Options

###showMousePosition
default: `false`
Outputs the mouse position to the debug window.

###showWindowDimensions
default: `false`
Outputs the current window dimensions to the debug window.

## Using the Debug Window

1. Import jQuery
2. Import JavaScript before the closing </body> tag`<script src="[your path to source]/jquery.debug-window.js"></script>`
3. Import CSS in the <head> `<link rel="stylesheet" href="[your path to source]jquery.debug-window.css" />`
4. Call plugin `$('body').debugWindow();`
With options:
```
$('body').debugWindow({
    showMousePosition: true,
    showWindowDimensions: true
});
```

## Development

```
git clone https://github.com/brandontrowe/jquery-debug-window.git
cd jquery-debug-window
npm install
npm start
```
Open: http://localhost:3000/build/demo.html

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request
