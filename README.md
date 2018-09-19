Support for Adj-RIB-Out in BGP Monitoring Protocol (BMP) 
========================================================

> ### draft-ietf-grow-bmp-adj-rib-out

- - -

Generating text from xml
------------------------

> One time only

* Install the latest [xml2rfc](https://xml2rfc.tools.ietf.org/)
* On Mac, you can install it using ```brew install xml2rfc```

> You'll do this each time you want to generate a text version

```
tievens@$ xml2rfc draft-ietf-grow-bmp-adj-rib-out.xml --text
Parsing file draft-ietf-grow-bmp-adj-rib-out.xml
Created file draft-ietf-grow-bmp-adj-rib-out.txt
```

Diff/Changes
------------

Normally use github to see the diffs but you can use command line ```git diff```, standard ```diff```, ```colordiff``` or something better such as Jetbrains [IntelliJ](https://www.jetbrains.com/idea/) which will provide one of the best side by side diffs.  

Example using colordiff.  

* Install colordiff: ```brew install colordiff```
* Run: ```colordiff -bBu draft-evens-grow-bmp-adj-rib-out-01.txt draft-ietf-grow-bmp-adj-rib-out.txt```

##### Example:

```diff
colordiff -Bbu draft-evens-grow-bmp-adj-rib-out-01.txt draft-ietf-grow-bmp-adj-rib-out.txt
--- draft-evens-grow-bmp-adj-rib-out-01.txt	2017-06-07 15:37:32.000000000 -0700
+++ draft-ietf-grow-bmp-adj-rib-out.txt	2017-06-07 17:30:24.000000000 -0700
@@ -5,18 +5,17 @@
 Global Routing Operations                                       T. Evens
 Internet-Draft                                              S. Bayraktar
 Updates: 7854 (if approved)                                Cisco Systems
-Intended Status: Standards Track                              P. Lucente
-Expires: October 1, 2017                              NTT Communications
+Intended status: Standards Track                              P. Lucente
+Expires: December 9, 2017                             NTT Communications
                                                                    P. Mi
                                                                  Tencent
                                                                S. Zhuang
                                                                   Huawei
-                                                          March 30, 2017
+                                                            June 7, 2017


        Support for Adj-RIB-Out in BGP Monitoring Protocol (BMP)
-                  draft-evens-grow-bmp-adj-rib-out-01
-
+                   draft-ietf-grow-bmp-adj-rib-out-00

 Abstract

@@ -26,46 +25,39 @@
    Out RIBs. It adds a new flag to the peer header to distinguish Adj-
    RIB-In and Adj-RIB-Out.
```



