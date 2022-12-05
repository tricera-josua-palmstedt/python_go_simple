# python_go_simple
https://poweruser.blog/embedding-python-in-go-338c0399f3d5

-	make use of high level API (Python C API)
-	seperate memory management by Python and Go
-	copy memory between runtimes where needed

-> -	performance (higher memory usage)
-> +	more simple (high level API, no C-code required)

-	call Python from Go as shared library (dynamically linked)
