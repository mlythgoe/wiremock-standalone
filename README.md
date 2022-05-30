# wiremock standalone

Simple configuration using 'non-code' approach.
The files in the 'mappings' directory define the requests that are mapped, i.e. the request
patterns it recognises.
The files show how to respond with a body that is defined within the mapping file,
how to respond with a body that exists in another file and is referenced from the mapping file, 
and how to respond with a http status code and no response body.
