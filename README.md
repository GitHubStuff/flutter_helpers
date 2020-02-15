# flutter_helpers
Source code for helpful dart/flutter code snippets

# broadcast_stream.dart
Defines a class for a StreamController, that will have take care of
implementation details like access to the stream, and sink.

The 'void dispose()' abstract will "remind" implementations to
to call 'close()' to close the stream in the Widget class's 'void dispose()'

# json_data.dart
This mixin is for classes that deal with json data and adds helper methods
to override 'toString()', and helper method 'dataString' that can turn
the class into a string suitable for http payloads or saving to a file.

It will also require the class to implement toJson() to create a map
of key/value pairs

