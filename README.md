# AI-Sectools project outputs
![License](https://img.shields.io/badge/License-MIT-blue)

The catalogue of security tools, methods and libraries developed and extended during AI-SecTools project (VJ02010010).

## Security certification 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [sec-certs](https://github.com/crocs-muni/sec-certs) | ![stars](https://img.shields.io/github/stars/crocs-muni/sec-certs.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/sec-certs.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/sec-certs.svg) | ![][certification] | A tool for data scraping, analysis and advanced searching of security certificates from Common Criteria and FIPS 140-2/3 schemes.  |    |    |

## Smartcards 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [JCAlgTest](https://github.com/crocs-muni/JCAlgTest)   | ![stars](https://img.shields.io/github/stars/crocs-muni/JCAlgTest.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/JCAlgTest.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/JCAlgTest.svg) | ![][javacard] ![][rsa] ![][ecc] | Automated testing tool for algorithms from JavaCard API supported by particular smart card. Performance testing of almost all available methods. The results for more than 100+ cards available at https://jcalgtest.org.    |   |    |
|  [jcAIDScan](https://github.com/petrs/jcAIDScan)     |  ![stars](https://img.shields.io/github/stars/petrs/jcAIDScan.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/petrs/jcAIDScan.svg) ![lastcommit](https://img.shields.io/github/last-commit/petrs/jcAIDScan.svg)  | ![][javacard]   | An automated scanner for JavaCard packages installed and supported by target card. Evaluates all packages from JavaCard API specification up to JC API 3.0.5.  |    |    |
| [JCProfilerNext](https://github.com/lzaoral/JCProfilerNext)  | ![stars](https://img.shields.io/github/stars/lzaoral/JCProfilerNext.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/lzaoral/JCProfilerNext.svg) ![lastcommit](https://img.shields.io/github/last-commit/lzaoral/JCProfilerNext.svg)   |  ![][javacard]   | Performance profiler for on-card JavaCard code. Provides a completely automated preprocessing, compilation, installation and profiling of JavaCard code on JavaCard smart cards. Produces interactive performance graphs. |    |    |


## Trusted Platform Modules
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
|[TPMAlgTest](https://github.com/crocs-muni/tpm2-algtest)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/tpm2-algtest.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/tpm2-algtest.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/tpm2-algtest.svg)    | ![][tpm] ![][rsa] ![][ecc]  | A scanner for Trusted Platform Module algorithms, performance and properties of cryptographic implementation.    |     |    |

## Side-channels 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
|[scrutiny-power-traces-analyzer](https://github.com/crocs-muni/scrutiny-power-traces-analyzer)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/scrutiny-power-traces-analyzer.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/scrutiny-power-traces-analyzer.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/scrutiny-power-traces-analyzer.svg)    | ![][javacard] |  The SCRUTINY analyzer for power traces of cryptographic operations captured from smartcards with three main modules implemented: Traces comparer, Trace classifier and CO template finder.  |    |    |
|[Catalogue of constant-timeness checkers](https://github.com/crocs-muni/ct-tools)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/ct-tools.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ct-tools.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ct-tools.svg)    | ![][ct] |  The list of tools for testing and verification of constant-timeness of programs.   |    |    |


## Software cryptographic libraries
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [JCMathLib - ECPoint library](https://github.com/OpenCryptoProject/JCMathLib)  | ![stars](https://img.shields.io/github/stars/OpenCryptoProject/JCMathLib.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/OpenCryptoProject/JCMathLib.svg)  ![lastcommit](https://img.shields.io/github/last-commit/OpenCryptoProject/JCMathLib.svg)  | ![][javacard] ![][rsa] ![][ecc]   | Provides software re-implementation of low-level operations like ECPoint or BigInteger without any use of proprietary API. Used for JavaCard capabilities testing.  |    |    |
| [ECTester](https://github.com/crocs-muni/ectester)  | ![stars](https://img.shields.io/github/stars/crocs-muni/ectester.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ectester.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ectester.svg)     |  ![][javacard] ![][cryptolibs] ![][ecc] | ECTester is a tool for testing and analysis of elliptic curve cryptography implementations on JavaCards and in cryptographic libraries.  |    |    |
| [pyecsca](https://github.com/J08nY/pyecsca)  | ![stars](https://img.shields.io/github/stars/J08nY/pyecsca.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/J08nY/pyecsca.svg) ![lastcommit](https://img.shields.io/github/last-commit/J08nY/pyecsca.svg)   |  ![][javacard] ![][cryptolibs] ![][ecc] | Python Elliptic Curve cryptography Side-Channel Analysis toolkit. Reverse engineer the curve model, coordinate system, addition formulas, scalar multiplier and even finite-field implementation details from blackbox implementations using side-channels. |    |    |
| [ec-detector](https://github.com/crocs-muni/ec-detector)  | ![stars](https://img.shields.io/github/stars/crocs-muni/ec-detector.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ec-detector.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ec-detector.svg)  | ![][cryptolibs] ![][ecc]   | EC detector is a code parser that can determine, with some degree of confidence, which elliptic curves a given piece of code contains.   |    |    |

## Self-Encrypting Drives
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [opal-toolset](https://github.com/crocs-muni/opal-toolset)  | ![stars](https://img.shields.io/github/stars/crocs-muni/opal-toolset.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/opal-toolset.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/opal-toolset.svg)   | ![][sed] ![][rng] | A set of tools for managing and analysing self-encrypting devices with Opal standard. |   |    |

## Randomness testing 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [booltest](https://github.com/ph4r05/booltest)   |  ![stars](https://img.shields.io/github/stars/ph4r05/booltest.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/ph4r05/booltest.svg) ![lastcommit](https://img.shields.io/github/last-commit/ph4r05/booltest.svg) | ![][rng] | Statical randomness testing tool for TRNG and PRNG generators based on boolean polynomials. |   |    |
| [cooltest](https://github.com/jirigav/cooltest/)  | ![stars](https://img.shields.io/github/stars/jirigav/cooltest.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/jirigav/cooltest.svg) ![lastcommit](https://img.shields.io/github/last-commit/jirigav/cooltest.svg)   | ![][rng] | Statical randomness testing tool for TRNG and PRNG generators based on a histogram construction.   |    |    |
| [Randomness Testing Toolkit](https://github.com/crocs-muni/randomness-testing-toolkit)  | ![stars](https://img.shields.io/github/stars/crocs-muni/randomness-testing-toolkit.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/randomness-testing-toolkit.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/randomness-testing-toolkit.svg)   | ![][rng] | Set of statistical randomness tests (NIST STS, Dieherader, TestU01) unified under same interface and results evaluation. | [[1](https://crocs.fi.muni.cz/public/papers/usablect_sp22)], [[2](https://crocs.fi.muni.cz/public/papers/usablect_usenix24)]   |    |




[smartcard]: https://img.shields.io/badge/platform-smartcard-lightgreen
[javacard]: https://img.shields.io/badge/platform-javacard-green
[tpm]: https://img.shields.io/badge/platform-tpm-blue
[cryptolibs]: https://img.shields.io/badge/platform-cryptolibs-yellow
[sed]: https://img.shields.io/badge/platform-sed-red
[certification]: https://img.shields.io/badge/platform-certification-magenta

[rsa]: https://img.shields.io/badge/alg-RSA-red
[ecc]: https://img.shields.io/badge/alg-ECC-orange
[rng]: https://img.shields.io/badge/alg-rng-lightgray

[ct]: https://img.shields.io/badge/cataloque-sca-lightred

Development was supported by the AI-SecTools (VJ02010010) project.
