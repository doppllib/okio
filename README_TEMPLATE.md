# Doppl Fork

This is a fork of the Okio library to provide tests and modifications to support
iOS development with J2objc using the [Doppl build framework](http://doppl.co/).

This is mostly stock, except a couple calls have been removed due to lack of some
nio support in J2objc.

## Usage

```groovy
dependencies {
    compile 'com.squareup.okio:okio:1.13.0'
    doppl '{{GROUP}}:okio:{{VERSION}}'
}
```

## Status

Published for established usage, but unit tests are not 100% and need to be updated.

License
--------

    Copyright 2013 Square, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
 [1]: https://github.com/square/okhttp
 [2]: https://search.maven.org/remote_content?g=com.squareup.okio&a=okio&v=LATEST
 [3]: http://square.github.io/okio/1.x/okio/okio/ByteString.html
 [4]: http://square.github.io/okio/1.x/okio/okio/Buffer.html
 [5]: http://square.github.io/okio/1.x/okio/okio/Source.html
 [6]: http://square.github.io/okio/1.x/okio/okio/Sink.html
 [7]: http://square.github.io/okio/1.x/okio/okio/BufferedSource.html
 [8]: http://square.github.io/okio/1.x/okio/okio/BufferedSink.html
 [snap]: https://oss.sonatype.org/content/repositories/snapshots/
