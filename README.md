# &lt;static-map&gt;

Web Component wrapper for Google Static Maps (API V2) using Polymer.

## Demo

![Google Static Maps](http://s28.postimg.org/wok1ycpzh/staticmap.png)

## Usage

1. Include Web Components' polymer library:

	```xml
	<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
	```
	or use the one included
	```xml
	<script src="lib/polymer.min.js"></script>
	```

2. Import custom element:

	```xml
	<link rel="import" href="src/static-map.html">
	```

3. Thats it! Include it in your body.

	```xml
	<static-map></static-map>
	```

## Options

Attribute   | Type		| Defaults					| Description
---         | ---		| ---						| ---
`center`	| *string*	| (required) - *None*		| The center location of the map. Can be a latitude/longitude combination or a street address.
`width`		| *int*		| (optional) - `200`		| The width of the map in pixels.
`height`	| *int*		| (optional) - `150`		| The height of the map in pixels.
`zoom`      | *int*		| (optional) - `13`			| The zoom level of the map.
`maptype`	| *string*	| (optional) - `roadmap`	| The map type to construct. Can be either `roadmap`, `hybrid`, `satellite` or `terrain`.
`marker`	| *string*	| (optional) - *None*		| The marker location of the map. See `center` above.
`key`		| *string*	| (optional) - *None*		| Your Google Static Maps API key.

> See [Google Static Maps API V2 documentation](https://developers.google.com/maps/documentation/staticmaps/).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [release](https://github.com/umarsheikh13/google-static-maps-element/releases) list.

## License

[MIT License](http://opensource.org/licenses/MIT)
