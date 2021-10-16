# Custom Frameworks
Xcode에서 사용할 수 있도록 구현된 Framework 모음이다. 

# 목차
- [소개](#Custom-Frameworks)
- [개발 정보](#개발-정보)
- [기능 설명](#기능-설명)
- [사용](#사용)

# 개발 정보
- 개발 환경: Xcode 12.4
- 개발 언어: Swift 5

# 기능 설명
- DataStructure.framework: 다양한 데이터 구조에 대한 타입과 기본 연산 제공
    - Linked List
        - Queue
        - List
    - Heap
        - Heap
        - Prority Queue
    - Binary Tree
- FileRW.framework: 텍스트 파일을 읽거나 쓸 수 있도록 함수 제공


# 사용
- macOS Deployment Target: 11.0
- 사용 방법
    1. 사용을 원하는 Xcode 프로젝트에 복사
    2. Project → Targets → General → Frameworks and Libraries → Embed 탭에서 Embed & Sign 선택
    3. 사용을 원하는 소스파일에서 import
    4. 프레임워크에서 제공되는 기능 사용
    - 프레임워크 추가하는 방법은 [사이트](https://taeminator1.tistory.com/38) 참고
    - 각 타입에 대한 사용은 각 프레임워크의 Quick Help 참고
    (조회를 원하는 요소에서 option(⌥) + click 또는 Inspectors → Quick Help)
