# Unhandled JSON Decoding Exception in Dart HTTP Request

This example demonstrates a common error in Dart where JSON decoding is not handled properly in an HTTP request.  The code fetches data from a URL, but doesn't specifically handle the `FormatException` that can occur if the response isn't valid JSON.  This can lead to unexpected crashes or silent failures.

The `bug.dart` file contains the buggy code. The `bugSolution.dart` file shows how to improve the code by implementing proper error handling.
