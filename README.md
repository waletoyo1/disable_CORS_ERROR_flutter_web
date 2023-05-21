# disable_CORS_ERROR_flutter_web
How to disable CORS error in flutter web







A CORS (Cross-Origin Resource Sharing) error occurs when a web page or application, such as a Flutter web app, makes a request to a different domain or origin, and the server hosting the requested resource doesn't allow the request due to security restrictions.

CORS is a security mechanism implemented by web browsers to protect users from cross-origin attacks. It ensures that resources, such as data or APIs, are only accessed by authorized origins (domains) to prevent unauthorized access or data leakage.

When a Flutter web app makes a request to a different domain, the browser checks if the server hosting the requested resource has specified the necessary CORS headers to allow the request. If the required headers are missing or don't match the security policy of the server, the browser blocks the request and throws a CORS error.







flutter run -d chrome --web-browser-flag "--disable-web-security"

https://stackoverflow.com/questions/65630743/how-to-solve-flutter-web-api-cors-error-only-with-dart-code/66879350#66879350
