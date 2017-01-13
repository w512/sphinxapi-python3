==========
The Python 3 client for Sphinx Search
==========

Sphinx Search documentation: http://sphinxsearch.com/docs/current.html

### Using
<code><pre>import sphinxapi
client = sphinxapi.SphinxClient()
client.SetServer('localhost', 9312)
results = client.Query('test')
</pre></code>
