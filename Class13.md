# Local Storage

**HTML5 Storage?**
- web applications can store data locally within the user's browser.
it’s a way for web pages to store named key/value pairs locally, within the client web browser.
- the storage limit is far larger (at least 5MB) and information is never transferred to the server.

- HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats.

- Calling setItem() with a named key that already exists will silently overwrite the previous value.
- Calling getItem() with a non-existent key will return null rather than throw an exception.

- The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.