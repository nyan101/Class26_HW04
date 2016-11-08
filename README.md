# Class26_HW04
WinDivert를 이용한 패킷 변조 실습
### Requirements
* Windows 환경에서 동작
* [PyDivert](https://github.com/ffalcinelli/pydivert) 패키지 필요 (pip install pydivert)

### What it does
 * Outbound tcp(http)패킷에 대해 Accept-Encoding애서 gzip을 제외
 * Inbound tcp(http) 패킷에 대해 "Michael"이라는 문자열을 "Gilbert"로 변조