  # local storage for web applications

  ## problem
  _before html5 there was'nt a storage only opearting system provideng alayer for storing and retreving data and these data may be stored in files or registry so basically a client needed a storage that is persistant and not transmitted to a server , so what is a web storage_


  
 -it's way used by pages to store values 
-not transmitted to a  web server
- data persists even after you navigate away from the web site

**all browsers at this time support HTML5 storage.**

**you can access local storage through local storage object from the global object _window_**

## Using

_it is based on value pairs you store data based on anamed key then you can retrieve data with the same key and the key is a string data type but it can also ant other Js supported types as booleans , integers , floats but if you are storing in any other type than string you use some methods for casting to retrieve data into the expected Js datatype such ParseInt() ParseFloat()_
_you can use some methods for local storage for dealing with values such removing , clear, set and get item,you can treat it as an array and other methods could be used_

## limitation
* 5 megabytes is the storage space by default it is consistent across browsers , no more suggestions to html Storage specification , storing strings *

> no browser supports any mechanism for web developers to request more storage space.

**and it's not worth to developers due to opening many pages for search and the need to store these pages inaddition but we can store the progress locally**


                    