# The Past, Present & Future of Local Storage for web Applications.

- (Ref: http://diveinto.html5doctor.com/storage.html) Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over. 

- Cookies are included with every HTTP request, thereby sending datat unenvrypted over the interent.

- Cookies are limited to about 4 KB of data - enough to slow down your application


## What we really want is: 

1.  (Ref: http://diveinto.html5doctor.com/storage.html) A lot of space, on the client, that persists beyond a page refresh, and isn't transmitted to the server. 

## HTML 5 Storage

-  (Ref: http://diveinto.html5doctor.com/storage.html) is based on named key/value pairs. You store data based on a named key, then you can retrieve that data witht the same key. They named key is a string. 

## Tracking changes to the HTML5

-   (Ref: http://diveinto.html5doctor.com/storage.html) If you want to keep track prgrammatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. 
 
-   (Ref: http://diveinto.html5doctor.com/storage.html) The storage event is supported everywhere the localStorage object is supported, which includes Internet Explorer 8. IE 8 does not support the W3C standard addEventListener. 

### StorageEvent Objects:

- **Key** String, the named key that was added, removed, or modified. 
- **oldValue** Any, the previous value (now overwritten), or null if a new item was added. 
- **newValue** Any, the new value, or null if an item was removed. 
- **url** String, the page which called a method that triggered this change.