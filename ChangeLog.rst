Version 0.2-alpha2 - to appear
-------------------------------

* Enhancement
    *
* Bugfix
    *

Version 0.2-alpha1 - 2014/05/07
-------------------------------

* Enhancement
    * kNN search using Minhash
    * kNN search using b-Bit Minhash
    * kNN search using cosine similarity
    * Introduced a recommendation scheme using Minhash
    * Modified to use OpenHashTable instead of HashMap for reducing memory consumption [9698972]
* Bugfix
    * Fixed a bug in rand_amplify() [0962c07]

Version 0.2-beta1 - 2013/11/22
-----------------------------
* Enhancement
  * Added rand_amplify() [538d866, 23b4f3b]
  * Added EMR bootstrap for hivemall [2a834e8]
  * Added AROW with a hinge loss [ae5c100]
* Bugfix
  * Fixed a bug in maven pom.xml [0d33ed7]

Version 0.1     - 2013/10/25
----------------------------

* Enhancement
    * Added AROW regression [f2f00a2]
    * Added AROW with a hinge loss (arowh_regress()) [239e90d]

* Bugfix
    * Fixed a bug of null feature handling in classification/regression [1f392a3]

Version 0.1-rc4 - 2013/10/18
----------------------------

* Enhancement
    * Added a function prefixed_hash_values() [0a6ffb3]

* Bugfix
    * Fixed recursion in OnlineVariance#mean() [c5b8c5b]
    * Fixed score calculation w.r.t bias values in predict() [f895269, 0130cfe]

Version 0.1-rc3 - 2013/10/08
----------------------------

* Enhancement
    * Add new classifiers (Confidence Weighted, AROW, Soft Confidence Weighted)

* Bugfix
    * fixed a bug in PA1a and PA2a that stddev was not calculated correctly [75ccdd336c]
    * fixed option handle for aggressive parameter C [095d9395f0]
    * changed the default power_t from 0.25 to 0.1 [7081291]

Version 0.1-rc2 - 2013/10/04 
----------------------------

* Bugfix
    * removed a dependency to serde.Constants for Hive 0.10 and later [054b9b8022]
    * fixed a serious bug in logress() [fb50235268]

Version 0.1-rc1 - 2013/10/02
----------------------------

This is the first release. Hello Hivemall!
