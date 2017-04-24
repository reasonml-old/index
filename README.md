# Index of available BuckleScript bindings and Libraries (and also some tooling)


## Bindings

### Frontend (browser)
Name | Description | Status
--- | --- | ---
[bs-webapi-incubator](https://github.com/BuckleTypes/bs-webapi-incubator) | (Incomplete) [Web APIs](https://developer.mozilla.org/en-US/docs/Web/Specification_list) | Incomplete (but then that's kind of the point)
[bs-director](https://github.com/BuckleTypes/bs-director) | [Director](https://github.com/flatiron/director) - Routing | Basic, Usable
[bs-leaflet](https://github.com/BuckleTypes/bs-leaflet) | [Leaflet.js](http://leafletjs.com/) - Interactive maps | "WIP"
[bs-fetch](https://github.com/BuckleTypes/bs-fetch) | [Fetch API](https://developer.mozilla.org/en/docs/Web/API/Fetch_API) | Feature complete, probably buggy
[reason-react](https://github.com/reasonml/reason-react) | [React](https://facebook.github.io/react/) with some flavor | Mostly complete, but not stable
[ReWebRTC](https://github.com/bsansouci/ReWebRTC) | [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) | "Super simple"
[reasongl](https://github.com/bsansouci/reasongl) | [OpenGL 2.0](https://www.khronos.org/registry/OpenGL/specs/gl/glspec20.pdf) and [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API) | Unknown, probably usable
[bucklescript-jquery](https://github.com/nebuta/bucklescript-jquery) | [jQuery](https://jquery.com/) - Swiss army knife | Unknown, Out of date build process
[bs-dom](https://github.com/0zat/bs-dom) | [DOM API](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model) | Very incomplete, "not test yet"

### Backend (node)
Name | Description | Status
--- | --- | ---
[bs-node](https://github.com/BuckleTypes/bs-node) | [Node API](https://nodejs.org/docs/latest/api/) | Barely started
[bs-express](https://github.com/BuckleTypes/bs-express) | [Express](https://expressjs.com/) - Web application framework | Unknown
[bs-discord-js](https://github.com/BuckleTypes/bs-discord.js) | [Discord.js](https://discord.js.org) - JS Discord API | Unknown
[ReSocket.io](https://github.com/bsansouci/ReSocket.io) | [socket.io](https://github.com/socketio/socket.io) - Event-based communication | Mostly complete, "dead simple"

### Other platforms
Name | Description | Status
--- | --- | ---
[bs-react-native](https://github.com/BuckleTypes/bs-react-native) | [React Native](https://facebook.github.io/react-native/) Native mobile application framework | Barely started
[bucklescript-electron](https://github.com/freebroccolo/bucklescript-electron) | [Electron](https://electron.atom.io/) | Cross-platform desktop application framework | Unknown
[bs-vscode](https://github.com/glennsl/bs-vscode) | [Visual Studio Code extenstion API](https://code.visualstudio.com/docs/extensionAPI/vscode-api) | Incomplete
[bs-atom](https://github.com/glennsl/bs-atom) | [Atom package API](https://atom.io/docs/api) | Barely started

### Bind-once-use-everywhere
Name | Description | Status
--- | --- | ---
[bs-moment](https://github.com/BuckleTypes/bs-moment) | [Moment.js](https://momentjs.com/) - Date processing | Unknown
[bs-immutablejs](https://github.com/BuckleTypes/bs-immutablejs) | [Immutable.js](https://facebook.github.io/immutable-js/) - Immutable collections | Unknown, probably usable
[bs-json](https://github.com/BuckleTypes/bs-json) | Low-level JSON encoding and decoding | Usable, Very experimental
[bs-transit-js](https://github.com/BuckleTypes/bs-transit-js) | [transit.js](https://github.com/cognitect/transit-js) - Marshaling | "rudimentary"
[bs-history](https://github.com/BuckleTypes/bs-history) | [history](https://github.com/reacttraining/history) - Cross-platform abstraction over the HTML history API | "WIP"

### Testing
Name | Description | Status
--- | --- | ---
[bs-jest](https://github.com/BuckleTypes/bs-jest) | [Jest](https://github.com/facebook/jest) | Incomplete, but fully functional
[bs-react-test-renderer](https://github.com/BuckleTypes/bs-react-test-renderer) | [react-test-renderer](https://github.com/facebook/react/tree/master/packages/react-test-renderer) | Mostly complete?


## Libraries

### Frontend (browser)
Name | Description | Status
--- | --- | ---
[bucklescript-tea](https://github.com/OvermindDL1/bucklescript-tea) | Implementation of [The Elm Architecture](https://guide.elm-lang.org/architecture/) (ie. TEA, ya get it?) | Usable but incomplete. Alpha maybe?
[reprocessing](https://github.com/Schmavery/reprocessing) | High-level drawing library inspired by [Processing](https://github.com/Schmavery/reprocessing) | "100% a work in progress"
[ReGlamor](https://github.com/kennetpostigo/ReGlamor) | "CSS in Reason" | No code. Cool logo though

### Backend (node)

### Other platforms

### Bind-once-use-everywhere
Name | Description | Status
--- | --- | ---
[bs-containers](https://github.com/BuckleTypes/bs-containers) | Container library, based on [OCaml-containers](https://github.com/c-cube/ocaml-containers) | Very experimental and unstable
[immutable-re](https://github.com/facebookincubator/immutable-re) | Pure Reason implementation of persistent immutable data structures | Early alpha
[reductive](https://github.com/reasonml/reductive) | [Redux](http://redux.js.org/) reimplementation | Proof of concept?
[transducers.re](https://github.com/IwanKaramazow/transducers.re) | Slojure transducers in Reason | Unknown

### Testing
Name | Description | Status
--- | --- | ---
[infinite-jest](https://github.com/glennsl/infinite-jest) | Cross-platform native/bs test framework | Usable, Alpha

## Tooling
Name | Description | Status
--- | --- | ---
[bucklescript-brunch](https://github.com/OvermindDL1/bucklescript-brunch) | [Brunch](http://brunch.io/) plugin to compile Bucklescript code | Unknown
[ocaml-language-server](https://github.com/freebroccolo/ocaml-language-server) | [Language Server Protocol](https://github.com/Microsoft/language-server-protocol) implementation for OCaml | Feature complete
[vscode-reasonml](https://github.com/freebroccolo/vscode-reasonml) | Reason support for Visual Studio Code | Feature complete
[reason-tools](https://github.com/freebroccolo/reason-tools) | Refmt in the browser | Continuously improving
[babel-plugin-transform-bucklescript](https://github.com/freebroccolo/babel-plugin-transform-bucklescript) | Babel postprocessing transformations for BuckleScript generated JavaScript | Unknown
[bs-loader](https://github.com/rrdelaney/bs-loader) | Bucklescript loader for Webpack | Unknown
[jeason](https://github.com/chenglou/jeason) | Converts JavaScript it into really bad Reason code | "crappy"
[reason](https://github.com/facebook/reason) | Ocaml skin | Alpha? Very usable, but still also very much in flux
[qnd](https://github.com/kennetpostigo/qnd) | Quick and Dirty development builds for reason | Usable?

## Related Links
- [awesome-reasonml](https://github.com/vramana/awesome-reasonml)
- [BuckleScript API](https://bloomberg.github.io/bucklescript/api/index.html)


## Contribute
Have you written a binding or library that's not listed here? Or come across one? Or found a mistake, however unlikely that might be? Then just submit a PR! It'll be very appreciated and probably even accepted!
