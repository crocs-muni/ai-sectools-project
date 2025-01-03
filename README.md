# AI-Sectools project outputs
![License](https://img.shields.io/badge/License-MIT-blue)

The catalogue of security tools, methods and libraries developed and extended during AI-SecTools project (VJ02010010).

List of reports (in Czech, see tools repositories and reserach papers for documentation in English): [Etapa 3](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_03_MU_tools_2022.pdf), [Etapa 4](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_04_MU_tools_2022.pdf), [Etapa 9](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_09_MU_tools_2023.pdf), [Etapa 10](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_10_MU_tools_2023.pdf), [Etapa 15](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_15_MU_tools_2024.pdf), [Etapa 16](https://github.com/crocs-muni/ai-sectools-project/blob/main/reports/Etapa_16_MU_tools_2024.pdf)  


## Security certification 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [sec-certs](https://github.com/crocs-muni/sec-certs) | ![stars](https://img.shields.io/github/stars/crocs-muni/sec-certs.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/sec-certs.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/sec-certs.svg) | ![][certification] | A tool for data scraping, analysis and advanced searching of security certificates from Common Criteria and FIPS 140-2/3 schemes.  | Etapa_3/2022, Etapa_10/2023, Etapa_16/2024, [[Computers & Security'24/143](https://www.sciencedirect.com/science/article/pii/S0167404824001974)] |  |
| [scrutiny](https://github.com/crocs-muni/scrutiny) | ![stars](https://img.shields.io/github/stars/crocs-muni/scrutiny.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/scrutiny.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/scrutiny.svg) | ![][certification] ![][javacard] ![][tpm] | An automated toolkit to analyze secure hardware, and build user-verifiable hardware profiles. SCRUTINY provides high-level frameworks to verify profiles against its reference values. | |  |

## Smartcards 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [JCAlgTest](https://github.com/crocs-muni/JCAlgTest)   | ![stars](https://img.shields.io/github/stars/crocs-muni/JCAlgTest.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/JCAlgTest.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/JCAlgTest.svg) | ![][javacard] ![][rsa] ![][ecc] | Automated testing tool for algorithms from JavaCard API supported by particular smart card. Performance testing of almost all available methods. The results for more than 100+ cards available at https://jcalgtest.org.    | Etapa_4/2022, [[SECRYPT'22](https://www.scitepress.org/PublishedPapers/2022/112940/)]  |    |
|  [jcAIDScan](https://github.com/petrs/jcAIDScan)     |  ![stars](https://img.shields.io/github/stars/petrs/jcAIDScan.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/petrs/jcAIDScan.svg) ![lastcommit](https://img.shields.io/github/last-commit/petrs/jcAIDScan.svg)  | ![][javacard]   | An automated scanner for JavaCard packages installed and supported by target card. Evaluates all packages from JavaCard API specification up to JC API 3.0.5.  |    |    |
| [JCProfilerNext](https://github.com/lzaoral/JCProfilerNext)  | ![stars](https://img.shields.io/github/stars/lzaoral/JCProfilerNext.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/lzaoral/JCProfilerNext.svg) ![lastcommit](https://img.shields.io/github/last-commit/lzaoral/JCProfilerNext.svg)   |  ![][javacard]   | Performance profiler for on-card JavaCard code. Provides a completely automated preprocessing, compilation, installation and profiling of JavaCard code on JavaCard smart cards. Produces interactive performance graphs. | Etapa_4/2022, Etapa_09/2023, Etapa_10/2023, Etapa_15/2024, sw_modul_c1/2024, [[CARDIS'23](https://link.springer.com/chapter/10.1007/978-3-031-54409-5_9)]  |    |

## Trusted Platform Modules
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
|[TPMAlgTest](https://github.com/crocs-muni/tpm2-algtest)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/tpm2-algtest.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/tpm2-algtest.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/tpm2-algtest.svg)    | ![][tpm] ![][rsa] ![][ecc]  | A scanner for Trusted Platform Module algorithms, performance and properties of cryptographic implementation.    | Etapa_15/2024, [[CHES'24](https://crocs.fi.muni.cz/public/papers/tpm_ches2024)]  |    |

## Side-channels 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
|[scrutiny-power-traces-analyzer](https://github.com/crocs-muni/scrutiny-power-traces-analyzer)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/scrutiny-power-traces-analyzer.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/scrutiny-power-traces-analyzer.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/scrutiny-power-traces-analyzer.svg)    | ![][javacard] |  The SCRUTINY analyzer for power traces of cryptographic operations captured from smartcards with three main modules implemented: Traces comparer, Trace classifier and CO template finder.  | Etapa_15/2024 |    |
|[Catalogue of constant-timeness checkers](https://github.com/crocs-muni/ct-tools)    |  ![stars](https://img.shields.io/github/stars/crocs-muni/ct-tools.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ct-tools.svg)  ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ct-tools.svg)    | ![][ct] |  The list of tools for testing and verification of constant-timeness of programs.   | Etapa_04/2022, [[IEEE S&P'22](https://crocs.fi.muni.cz/public/papers/usablect_sp22)], [[USENIXSec'24](https://crocs.fi.muni.cz/public/papers/usablect_usenix24)]  |   |
| [Attack on DPA-protected Kyber](https://github.com/crocs-muni/Attack_Kyber_ACNS2024)  | ![stars](https://img.shields.io/github/stars/crocs-muni/Attack_Kyber_ACNS2024.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/Attack_Kyber_ACNS2024.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/Attack_Kyber_ACNS2024.svg)  | ![][cryptolibs] ![][pqc]   | Supplementary materials (source code, example traces and simulations) for the Breaking DPA-protected Kyber via the pair-pointwise multiplication paper. The attack uses the mkm4 Kyber implementation. | Etapa_15/2024, [[ACNS'24](https://link.springer.com/chapter/10.1007/978-3-031-54773-7_5)]  |    |

## Software cryptographic libraries
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [JCMathLib - ECPoint library](https://github.com/OpenCryptoProject/JCMathLib)  | ![stars](https://img.shields.io/github/stars/OpenCryptoProject/JCMathLib.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/OpenCryptoProject/JCMathLib.svg)  ![lastcommit](https://img.shields.io/github/last-commit/OpenCryptoProject/JCMathLib.svg)  | ![][javacard] ![][rsa] ![][ecc]   | Provides software re-implementation of low-level operations like ECPoint or BigInteger without any use of proprietary API. Used for JavaCard capabilities testing.  |  Etapa_04/2022, Etapa_09/2023 |    |
| [ECTester](https://github.com/crocs-muni/ectester)  | ![stars](https://img.shields.io/github/stars/crocs-muni/ectester.svg?style=social) ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ectester.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ectester.svg)     |  ![][javacard] ![][cryptolibs] ![][ecc] | ECTester is a tool for testing and analysis of elliptic curve cryptography implementations on JavaCards and inside cryptographic libraries.  |  Etapa_04/2022, sw_modul_c1/2024 |    |
| [pyecsca](https://github.com/J08nY/pyecsca)  | ![stars](https://img.shields.io/github/stars/J08nY/pyecsca.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/J08nY/pyecsca.svg) ![lastcommit](https://img.shields.io/github/last-commit/J08nY/pyecsca.svg)   |  ![][javacard] ![][cryptolibs] ![][ecc] | Python Elliptic Curve cryptography Side-Channel Analysis toolkit. Reverse engineer the curve model, coordinate system, addition formulas, scalar multiplier and even finite-field implementation details from blackbox implementations using side-channels. | Etapa_10/2023, Etapa_16/2024, sw_modul_c1/2024, [[CHES'24](https://tches.iacr.org/index.php/TCHES/article/view/11796)]  |    |
| [ec-detector](https://github.com/crocs-muni/ec-detector)  | ![stars](https://img.shields.io/github/stars/crocs-muni/ec-detector.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/ec-detector.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/ec-detector.svg)  | ![][cryptolibs] ![][ecc]   | EC detector is a code parser that can determine, with some degree of confidence, which elliptic curves a given piece of code contains.   |  Etapa_04/2022 |    |
| [sca25519](https://github.com/sca-secure-library-sca25519/sca25519)  | ![stars](https://img.shields.io/github/stars/sca-secure-library-sca25519/sca25519.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/sca-secure-library-sca25519/sca25519.svg) ![lastcommit](https://img.shields.io/github/last-commit/sca-secure-library-sca25519/sca25519.svg)  | ![][cryptolibs] ![][ecc]   | This repository contains three implementations of X25519 in C and assembly for the Cortex-M4 with countermeasures against side-channel and fault injection attacks. The first implementation is unprotected, the second implementation contains countermeasure required for the case of ephemeral scalar multiplication, and the third implementation contains the most countermeasures for the case of static scalar multiplication. |  Etapa_09/2023, Etapa_15/2024, [[eprint](https://eprint.iacr.org/2024/1350)] |    |


## Self-Encrypting Drives
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [opal-toolset](https://github.com/crocs-muni/opal-toolset)  | ![stars](https://img.shields.io/github/stars/crocs-muni/opal-toolset.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/opal-toolset.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/opal-toolset.svg)   | ![][sed] ![][rng] | A set of tools for managing and analysing self-encrypting devices with Opal standard. | Etapa_16/2024, [[under review](under.submission)]  |    |

## Randomness testing 
| Tool | Repo stats | Target domain | Info | Reports & Publications | Notes | 
|----------|----------|----------|----------|----------|----------|
| [booltest](https://github.com/ph4r05/booltest)   |  ![stars](https://img.shields.io/github/stars/ph4r05/booltest.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/ph4r05/booltest.svg) ![lastcommit](https://img.shields.io/github/last-commit/ph4r05/booltest.svg) | ![][rng] | Statical randomness testing tool for TRNG and PRNG generators based on boolean polynomials. |   |    |
| [cooltest](https://github.com/jirigav/cooltest/)  | ![stars](https://img.shields.io/github/stars/jirigav/cooltest.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/jirigav/cooltest.svg) ![lastcommit](https://img.shields.io/github/last-commit/jirigav/cooltest.svg)   | ![][rng] | Statical randomness testing tool for TRNG and PRNG generators based on a histogram construction.   | Etapa_16/2024, [[under review](under.submission)] |  |
| [Randomness Testing Toolkit](https://github.com/crocs-muni/randomness-testing-toolkit)  | ![stars](https://img.shields.io/github/stars/crocs-muni/randomness-testing-toolkit.svg?style=social)  ![numcontributors](https://img.shields.io/github/contributors-anon/crocs-muni/randomness-testing-toolkit.svg) ![lastcommit](https://img.shields.io/github/last-commit/crocs-muni/randomness-testing-toolkit.svg)   | ![][rng] | Set of statistical randomness tests (NIST STS, Dieherader, TestU01) unified under same interface and results evaluation. |   |    |




[smartcard]: https://img.shields.io/badge/platform-smartcard-lightgreen
[javacard]: https://img.shields.io/badge/platform-javacard-green
[tpm]: https://img.shields.io/badge/platform-tpm-blue
[cryptolibs]: https://img.shields.io/badge/platform-cryptolibs-yellow
[sed]: https://img.shields.io/badge/platform-sed-red
[certification]: https://img.shields.io/badge/platform-certification-magenta

[rsa]: https://img.shields.io/badge/alg-RSA-red
[ecc]: https://img.shields.io/badge/alg-ECC-orange
[pqc]: https://img.shields.io/badge/alg-PQC-lightblue
[rng]: https://img.shields.io/badge/alg-rng-lightgray

[ct]: https://img.shields.io/badge/cataloque-sca-lightred

Development was supported by the AI-SecTools (VJ02010010) project.
