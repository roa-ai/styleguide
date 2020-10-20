# ROA Python Style Guide

## 프로젝트 구성
뼈대는 다음의 가이드라인을 따릅니다
https://python-guide-kr.readthedocs.io/ko/latest/writing/structure.html
- Skeleton
https://github.com/navdeep-G/samplemod


## 기본 원칙
1. 하나의 함수는 하나의 일만 하도록 하자
2. 밑줄이 앞에 붙은 함수 이름은 패키지 내부에서만 사용되는 함수이다
3. 메인 코드가 실행되기 전에 의존성 버전 차이를 처리한다
4. Spinx 자동 문서화 확장을 사용하자
5. [PEP8](https://www.python.org/dev/peps/pep-0008/)을 준수한다


## 환경
1. Python 3.6 이상을 사용한다
2. 마이너 업데이트가 있을 시 첫 패치 업데이트 이후 사용한다
   * 예) 3.9 버전은 3.9.1 이후로 사용


## 세부논의

#### Single quote, double quote

둘 중 무엇이든 한 프로젝트에선 하나의 스타일로 통일성을 유지하게끔 사용합니다.

* `docstrings`에는 triple double quotes를 사용한다
* `\\` 이스케이프를 피하고자 둘을 잠시 혼용하는 걸 허용한다


## 참고 문헌
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
