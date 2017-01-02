### Include: SCSS

``` scss
// @INSERT :: START @tag: scss-import //
@import "blocks/_b-overlay";
// @INSERT :: END //

// @INSERT :: START @tag: scss-self-contained-import //
@import "../templating/partials/blocks/overlay/scss/_b-overlay";
// @INSERT :: END //
```

### Include: JavaScript

#### Import
``` js
// @INSERT :: START @tag: js-import //
import Overlay from './modules/overlay/overlay';
// @INSERT :: END //

/ @INSERT :: START @tag: js-self-contained-import //
import SlideFox from '../templating/partials/blocks/overlay/js/overlay';
// @INSERT :: END //
```

#### Initializing
``` js
// @INSERT :: START @tag: js-init-once-v3 //
/**
 * Init Overlay
 */
new Overlay();
// @INSERT :: END //
```

#### Custom Events
``` js
// @INSERT :: START @tag: js-events //
/**
 * Events Overlay
 */
EVENTS.overlay = {
	open: 'overlay:open'
};
// @INSERT :: END //
```