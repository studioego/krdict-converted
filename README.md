# 한국어기초사전 XDXF

국립국어원의 한국어기초사전에서 다운로드한 XML 데이터를 XDXF 형식으로 변환한
사전입니다. 여러가지 사전 프로그램에서 사용할 수 있습니다.

## 한국어기초사전의 업스트림 데이터 업데이트

다운로드 방법은 한국어기초사전 사이트 참고. XML 파일이 들어 있는 zip 파일을
다운로드하면 다음과 같이 update-upstream.py를 이용해 소스코드를 업데이트할 수
있습니다. 다운로드한 파일이 .../123456.zip 파일이라고 하면,

$ python3 update-upstream.py .../123456.zip

## 빌드

make, xsltproc, dictzip이 필요합니다. make를 실행하면 dict.xdxf.dz 파일을
만듭니다.

```
$ make
```

## 기타

이 저작물은크리에이티브 커먼즈 저작자표시-동일조건변경허락 2.0 대한민국
라이선스에 따라 이용할 수 있습니다.
