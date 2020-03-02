OpenSSL-Pod
===========
Forked & updated for bitcode and version 1.1.1d

### Installing

>pod 'OpenSSL', :git => 'https://github.com/thejeff77/OpenSSL-Pod.git' :tag => '1.1.104' 

### Version numbering 

Because OpenSSL's version numbers are not compatible with the CocoaPods version numbering, versioning is as follows:

OpenSSL version: A.B.CD will become A.B.C*100 + place of D in the alphabet (indexed by 1).

Example: OpenSSL 1.1.1d => OpenSSL 1.1.104

### Updating the Pod

1. Update the podspec to reference the latest 1.1.* tarball and sha256
2. checksum file in repo root updated with sha256 and url from https://www.openssl.org/source/
3. Add a pull request
