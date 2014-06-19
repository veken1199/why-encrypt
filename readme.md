Java and PHP classes used to encrypt and decrypt strings with a private key, or any key scheme that you create, and pass data between PHP and Java clients or servers.


***

Java Dependencies  
- [Apache Commons Coded](http://commons.apache.org/codec/)

***


iOS Usage  

- In the ***arc*** project, you have to add the `-fno-objc-arc` in the build phases.
- Encrypt and Decrypt in this way:
```
NSString *encStr = [AESTool encryptData:@"hello" withKey:@"1234567890123456"];
NSLog(@"%@", encStr);
```
***



Steven Holder
http://stevenholder.com


Copyright (C) 2011 by Steven Holder

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.