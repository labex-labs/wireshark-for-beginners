# Wireshark 퀵 스타트 가이드

## 언어

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![Wireshark 퀵 스타트 가이드](https://cover-creator.labex.io/quick-start-with-wireshark.png?lang=ko)](https://labex.io/ko/courses/quick-start-with-wireshark)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/ko/courses/quick-start-with-wireshark)

본 과정에서는 Wireshark 를 사용하여 네트워크 트래픽을 캡처하고 분석하는 방법을 배웁니다. Wireshark 설치, 패킷 캡처 및 분석 방법을 익히게 됩니다. 또한 Wireshark 를 사용하여 네트워크 문제를 해결하고, 네트워크 트래픽을 분석하며, 네트워크를 안전하게 보호하는 방법도 배우게 됩니다.

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-whitesmoke?style=for-the-badge&logo=cybersecurity)


## 환경

LabEx 는 코딩과 기술에 전념하는 대화형 실습 학습 플랫폼입니다. 실험실, AI 지원 및 가상 머신을 결합하여 비디오 없는 실용적인 학습 경험을 제공합니다.

![](https://tutorial-screenshot.getvm.io/images/vm-1725247253.png)

- 비디오 없는 독점적인 실습 실험실로 엄격한 "실습을 통한 학습" 접근 방식.
- 브라우저 내 대화형 온라인 환경에서 자동화된 단계별 확인.
- 스킬 트리 기반 시스템으로 구조화된 콘텐츠 구성.
- 30 개의 스킬 트리와 6,000 개 이상의 실험실을 포함하는 성장하는 학습 리소스.
- ChatGPT 를 기반으로 구축된 AI 학습 도우미 Labby 가 제공하는 대화형 학습 경험.

자세히 알아보기 [LabEx VM](https://support.labex.io/using-labex/virtual-machine).

## 연습

|   인덱스 | 이름                                                       | 난이도   | 연습                                                                                                                                                |
|----------|------------------------------------------------------------|----------|-----------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | 📖 Wireshark 로 네트워크 트래픽 설치, 구성 및 분석         | ★★☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-install-configure-and-analyze-network-traffic-with-wireshark-415947'>실습 시작</a> |
|       02 | 🎯 Wireshark 설치 확인                                     | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-verify-wireshark-installation-548783'>도전 시작</a>                                |
|       03 | 📖 Wireshark 인터페이스 탐색 및 사용자 정의                | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-explore-and-customize-wireshark-interface-415949'>실습 시작</a>                    |
|       04 | 🎯 Wireshark 열 표시 사용자 정의                           | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-customize-wireshark-column-display-548785'>도전 시작</a>                           |
|       05 | 📖 Wireshark 로 네트워크 트래픽 캡처 및 분석               | ★★☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-capture-and-analyze-network-traffic-with-wireshark-415956'>실습 시작</a>           |
|       06 | 🎯 암호화된 웹 트래픽 필터링                               | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-filter-encrypted-web-traffic-548806'>도전 시작</a>                                 |
|       07 | 📖 Wireshark 표시 필터로 네트워크 트래픽 분석              | ★★☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-analyze-network-traffic-with-wireshark-display-filters-415944'>실습 시작</a>       |
|       08 | 🎯 노출된 로그인 자격 증명 찾기                            | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-find-exposed-login-credentials-548820'>도전 시작</a>                               |
|       09 | 📖 Wireshark 캡처 필터 적용: 네트워크 트래픽 분석          | ★★☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-apply-wireshark-capture-filters-for-network-traffic-analysis-415940'>실습 시작</a> |
|       10 | 🎯 DNS 통신 필터링                                         | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-filter-dns-communications-548826'>도전 시작</a>                                    |
|       11 | 📖 Wireshark 에서 색상 지정 규칙 생성 및 적용              | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-create-and-apply-colorizing-rules-in-wireshark-415941'>실습 시작</a>               |
|       12 | 🎯 HTTPS 트래픽 감지기 생성                                | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-create-https-traffic-detector-548831'>도전 시작</a>                                |
|       13 | 📖 Wireshark 의 Follow TCP Stream 기능으로 TCP 트래픽 분석 | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-analyze-tcp-traffic-with-wireshark-follow-tcp-stream-feature-415946'>실습 시작</a> |
|       14 | 🎯 웹 트래픽 증거 추출                                     | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-extract-web-traffic-evidence-548842'>도전 시작</a>                                 |
|       15 | 📖 Wireshark 에서 패킷 내보내기                            | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-export-packets-from-wireshark-415945'>실습 시작</a>                                |
|       16 | 🎯 의심스러운 네트워크 증거 내보내기                       | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-export-suspicious-network-evidence-548847'>도전 시작</a>                           |
|       17 | 📖 Wireshark 로 IPv6 트래픽 분석                           | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-analyze-ipv6-traffic-with-wireshark-415950'>실습 시작</a>                          |
|       18 | 🎯 IPv6 트래픽 패턴 추적                                   | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-track-ipv6-traffic-patterns-548851'>도전 시작</a>                                  |
|       19 | 📖 Tshark 를 활용한 네트워크 트래픽 분석                   | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-use-tshark-for-network-traffic-analysis-415942'>실습 시작</a>                      |
|       20 | 🎯 의심스러운 DNS 쿼리 탐지                                | ★☆☆      | <a target='_blank' href='https://labex.io/ko/tutorials/wireshark-uncover-suspicious-dns-queries-548854'>도전 시작</a>                               |

## 더 보기

- 🔗 [Cybersecurity Programming Courses](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [Cybersecurity Programming Projects](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [Cybersecurity Free Tutorials](https://github.com/labex-labs/cybersecurity-free-tutorials)

