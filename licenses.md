---
layout: default
title: Razmova - Third Party Licenses
description: Third Party Licenses
permalink: /licenses
---

Razmova is built with the open-source software listed below. Each entry links to
its source and to the full text of its license.

## Libraries

| component | version | license | copyright |
|---|---|---|---|
| [eventsource](https://github.com/mattt/EventSource) | 1.4.1 | [MIT](https://opensource.org/license/mit) | Copyright 2025 Mattt (https://mat.tt) |
| [mlx-swift](https://github.com/ml-explore/mlx-swift) | 0.31.4 | [MIT](https://opensource.org/license/mit) | Copyright (c) 2023 ml-explore |
| [mlx-swift-lm](https://github.com/ml-explore/mlx-swift-lm) | 3.31.4 | [MIT](https://opensource.org/license/mit) | Copyright (c) 2024 ml-explore |
| [swift-atomics](https://github.com/apple/swift-atomics) | 1.3.1 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright (c) 2020-2025 Apple Inc. and the Swift project authors |
| [swift-collections](https://github.com/apple/swift-collections) | 1.5.1 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright (c) 2019-2026 Apple Inc. and the Swift project authors |
| [swift-crypto](https://github.com/apple/swift-crypto) | 4.5.1 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright 2019 The SwiftCrypto Project |
| [swift-huggingface](https://github.com/huggingface/swift-huggingface) | 0.9.0 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright 2025 Hugging Face SAS. |
| [swift-jinja](https://github.com/huggingface/swift-jinja) | 2.3.6 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright 2022 Hugging Face SAS. |
| [swift-nio](https://github.com/apple/swift-nio) | 2.101.3 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright 2017, 2018 The SwiftNIO Project |
| [swift-numerics](https://github.com/apple/swift-numerics) | 1.1.1 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright (c) 2017-2025 Apple Inc. and the Swift Numerics project authors |
| [swift-transformers](https://github.com/huggingface/swift-transformers) | 1.3.3 | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright 2022 Hugging Face SAS. |
| [yyjson](https://github.com/ibireme/yyjson) | 0.12.0 | [MIT](https://opensource.org/license/mit) | Copyright (c) 2020 YaoYuan &lt;ibireme@gmail.com&gt; |

## Included within those libraries

| component | license | copyright | included in |
|---|---|---|---|
| mlx | [MIT](https://opensource.org/license/mit) | Copyright © 2023 Apple Inc. | mlx-swift |
| mlx-c | [MIT](https://opensource.org/license/mit) | Copyright (c) 2023 ml-explore | mlx-swift |
| metal-cpp | [Apache-2.0](https://www.apache.org/licenses/LICENSE-2.0) | Copyright © 2024 Apple Inc. | mlx-swift |
| fmt | [MIT](https://opensource.org/license/mit) | Copyright (c) 2012 - present, Victor Zverovich and {fmt} contributors | mlx-swift |
| json | [MIT](https://opensource.org/license/mit) | Copyright (c) 2013-2022 Niels Lohmann | mlx-swift |

## Language model

Razmova runs its conversations on-device using
[Llama-3.2-3B-Instruct-4bit](https://huggingface.co/mlx-community/Llama-3.2-3B-Instruct-4bit),
downloaded on first launch and used under the
[Llama 3.2 Community License](https://huggingface.co/meta-llama/Llama-3.2-1B/blob/main/LICENSE.txt).

## Notices

The following notices accompany the libraries above and are reproduced in full.

### swift-crypto

```
                            The SwiftCrypto Project
                            =======================

Please visit the SwiftCrypto web site for more information:

  * https://github.com/apple/swift-crypto

Copyright 2019 The SwiftCrypto Project

The SwiftCrypto Project licenses this file to you under the Apache License,
version 2.0 (the "License"); you may not use this file except in compliance
with the License. You may obtain a copy of the License at:

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.

Also, please refer to each LICENSE.<component>.txt file, which is located in
the 'license' directory of the distribution file, for the license terms of the
components that this product depends on.

-------------------------------------------------------------------------------

This product contains test vectors from Google's wycheproof project.

  * LICENSE (Apache License 2.0):
    * https://github.com/C2SP/wycheproof/blob/31387e2cd596587c859c611027b6a44d2e2b65ff/LICENSE
  * HOMEPAGE:
    * https://github.com/google/wycheproof

---

This product contains a derivation of various files from SwiftNIO.

  * LICENSE (Apache License 2.0):
    * https://www.apache.org/licenses/LICENSE-2.0
  * HOMEPAGE:
    * https://github.com/apple/swift-nio
```

### swift-nio

```

                            The SwiftNIO Project
                            ====================

Please visit the SwiftNIO web site for more information:

  * https://github.com/apple/swift-nio

Copyright 2017, 2018 The SwiftNIO Project

The SwiftNIO Project licenses this file to you under the Apache License,
version 2.0 (the "License"); you may not use this file except in compliance
with the License. You may obtain a copy of the License at:

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.

Also, please refer to each LICENSE.<component>.txt file, which is located in
the 'license' directory of the distribution file, for the license terms of the
components that this product depends on.

-------------------------------------------------------------------------------

This product is heavily influenced by Netty.

  * LICENSE (Apache License 2.0):
    * https://github.com/netty/netty/blob/4.1/LICENSE.txt
  * HOMEPAGE:
    * https://netty.io

---

This product contains NodeJS's llhttp.

  * LICENSE (MIT):
    * https://github.com/nodejs/llhttp/blob/1e1c5b43326494e97cf8244ff57475eb72a1b62c/LICENSE-MIT
  * HOMEPAGE:
    * https://github.com/nodejs/llhttp

---

This product contains "cpp_magic.h" from Thomas Nixon & Jonathan Heathcote's uSHET

  * LICENSE (MIT):
    * https://github.com/18sg/uSHET/blob/c09e0acafd86720efe42dc15c63e0cc228244c32/lib/cpp_magic.h
  * HOMEPAGE:
    * https://github.com/18sg/uSHET

---

This product contains "sha1.c" and "sha1.h" from FreeBSD (Copyright (C) 1995, 1996, 1997, and 1998 WIDE Project)

  * LICENSE (BSD-3):
    * https://opensource.org/licenses/BSD-3-Clause
  * HOMEPAGE:
    * https://github.com/freebsd/freebsd-src

---

This product contains a derivation of Fabian Fett's 'Base64.swift'.

  * LICENSE (Apache License 2.0):
    * https://github.com/swift-extras/swift-extras-base64/blob/b8af49699d59ad065b801715a5009619100245ca/LICENSE
  * HOMEPAGE:
    * https://github.com/fabianfett/swift-base64-kit

---

This product contains a derivation of "XCTest+AsyncAwait.swift" & "StructuredConcurrencyHelpers" from AsyncHTTPClient.

  * LICENSE (Apache License 2.0):
    * https://www.apache.org/licenses/LICENSE-2.0
  * HOMEPAGE:
    * https://github.com/swift-server/async-http-client

---

This product contains a derivation of "_TinyArray.swift" from SwiftCertificates.

  * LICENSE (Apache License 2.0):
    * https://www.apache.org/licenses/LICENSE-2.0
  * HOMEPAGE:
    * https://github.com/apple/swift-certificates

---

This product contains a derivation of the mocking infrastructure from Swift System.

  * LICENSE (Apache License 2.0):
    * https://www.apache.org/licenses/LICENSE-2.0
  * HOMEPAGE:
    * https://github.com/apple/swift-system

---

This product contains a derivation of "TokenBucket.swift" from Swift Package Manager.

  * LICENSE (Apache License 2.0):
    * https://www.apache.org/licenses/LICENSE-2.0
  * HOMEPAGE:
    * https://github.com/swiftlang/swift-package-manager
```
