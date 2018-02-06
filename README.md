The XMLHttpRequest.send() method sends the request. If the request is asynchronous (which is the default), this method returns as soon as the request is sent. If the request is synchronous, this method doesn't return until the response has arrived. send() accepts an optional argument for the request body. If the request method is GET or HEAD, the argument is ignored and request body is set to null.

If no Accept header has been set using the setRequestHeader(), an Accept header with the */* is sent.
