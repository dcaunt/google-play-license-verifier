google-play-license-verifier
============================

A simple PHP library for verifying responses from the [Google Play licensing service](http://developer.android.com/google/play/licensing/index.html). By verifying responses signed using [public-key cryptography](http://en.wikipedia.org/wiki/Public-key_cryptography#Description) you can check whether a user has genuinely purchased your application. 

You can use this library to [validate licensing responses](http://android-developers.blogspot.com/2010/09/securing-android-lvl-applications.html) before allowing a user to download files from your server or access restricted content. It is PEAR compliant (PSR-0) and can easily be integrated with your server-side applications.

The only requirements for this library are PHP compiled with [OpenSSL](http://php.net/openssl) support, and a PHP version of 4.0.4 or higher. PHP5 works too. If you want to run the unit tests you will need PHPUnit 3.5 or later.

This library does not support verifying purchases made via [Google Play's In-app Billing](http://developer.android.com/guide/google/play/billing/index.html).
