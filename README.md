# Class nodebin

This class contains functions for using the pastebin API

## new nodebin(apiKey)

* `apiKey` String

Construct a new API handle object

## handle.callAPI(options, callback)

* `options` Object
  * `action` String
  * `name` String
  * `privacy` Number
  * `format` String
  * `expire` String
  * `pasteKey` String
  * `content` String
  * `limit` Number
