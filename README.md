Thumbor is a smart imaging service. It enables on-demand crop, resizing and flipping of images.
This module always sends a head request to the server to make sure the file is still available and the user still has
permission to access it.

example thumbor config :


RESULT_STORAGE = 'thumbor_head.result_storage'
