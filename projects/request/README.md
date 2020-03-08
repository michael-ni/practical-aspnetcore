# Request

  This section shows all the different ways you capture input and examine request to your web application.

  * **HTTP Verb (1)**
    * [Get request verb](/projects/request/request-verb)
      
      Detect the verb/method of the current request. 

  * **Headers (3)**
    * [Access Request Headers](/projects/request/request-headers)
      
      Enumerate all the available headers in a request.

    * [Access Request Headers using common HTTP header names contained in HeaderNames](/projects/request/request-headers-names)

      This sample shows all the common HTTP header names contained in `HeaderNames` class. So instead of using string to obtain a HTTP Header, you can just use a convenient constant such as `HeaderNames.ContentType`.

    * [Type Safe Access to Request Headers](/projects/request/request-headers-typed)
      
      Instead of using string to access HTTP headers, use type safe object properties to access common HTTP headers.

  * **Query String (3)**
    * [Single value query string](/projects/request/query-string-1)

      Access single value query string.

    * [Multiple values query string](/projects/request/query-string-2)

      Access multiples values query string.

    * [List all query string values](/projects/request/query-string-3)

      List all query string values. Also shows the implicat conversion from ```StringValues``` to ```string```.


  * **Form (2)**

    * [Form Values](/projects/request/form-values) 
      
      Handles the values submitted via a form.

    * [Form Upload File](/projects/request/form-upload-file) 
      
      Upload a single file and save it to the current directory (check out the usage of ```.UseContentRoot(Directory.GetCurrentDirectory())```)

  * **Cookies (2)**
          
      * [Cookies](/projects/request/cookies-1)

        Read and write cookies.

      * [Removing cookies](/projects/request/cookies-2)

        Simply demonstrates on how to remove cookies.