## Example

```javascript
	
	var beanie = require('beanie').loader();

	beanie.
	require(__dirname + "/path/to/plugin.js").
	require(__dirname + "/path/to/dir").
	require(__dirname + "/path/to/**/*.plugin.js").
	load(function() {
		beanie.router.push('init');
	})

```