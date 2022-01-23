# Local Storage

Local Storage is a way for your app or web browser to store data locally on your local machine.

code example from http://diveinto.html5doctor.com/storage.html


HTML5 Storage is based on named key/value pairs.

interface Storage {
  getter any getItem(in DOMString key);
  setter creator void setItem(in DOMString key, in any data);
};

Use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

Calling setItem() with a named key that already exists will silently overwrite the previous value.

you can treat the localStorage object as an associative array.

Using the getItem() and setItem() methods.

var foo = localStorage.getItem("bar");
// ...
localStorage.setItem("bar", foo);

Could be rewritten to use square bracket syntax instead:

var foo = localStorage["bar"];
// ...
localStorage["bar"] = foo;

Removing the value for a given named key.

interface Storage {
  deleter void removeItem(in DOMString key);
  void clear();
};

Get the total number of values in the storage area, and to iterate through all of the keys by index.

interface Storage {
  readonly attribute unsigned long length;
  getter DOMString key(in unsigned long index);
};
