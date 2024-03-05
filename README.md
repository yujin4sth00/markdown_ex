# markdown_ex

# This is a H1.
## This is a H2.
### This is a H3.
#### This is a H4.

> This is a first blockqute.
>   > This is a second blckqute.

1. 첫 번째 목록
2. 두 번째 목록

* 첫 번째
  * 두 번째
    * 세 번째

+ 안녕하세요
  + 안녕하세요
    + 안녕하세요

* 1단계
  - 2단계
    + 3단계
      + 4단계

안녕하세요.

    만나서 반갑습니다. (스페이스바 4번)
  
환영합니다.
<pre><code>
public class helloWorld {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
</code></pre>
* * *
```
public class helloWorld {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
----------------------------
*******************************
_________________________________________
-참조링크-

[link keyword][id]

[id]: URL "Link Keyword Here"

// code

Link: [Naver][naverlink]

[naverlink]: https://www.naver.com/"

-외부링크-

사용문법: [Title](link)

적용예: [Naver](https://www.naver.com/, "Naver link")

-자동연결-

외부링크: <http://example.com/>

이메일링크: <address@example.com>

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

~~cancelline~~ (~~ 사용)

줄바꿈하려면   
3칸이상 띄어쓰기(윗 문장에서)

#### 구현 리스트
- [ ] 기존 서비스 복사하기
- [ ] Domain으로 옮길 로직을 찾기
    - [ ] [1]saveLine메소드의 getStations.
    - [x] [2]findLines메소드의 persistLines.stream().
    - [ ] [3]findLineResponseById메소드의 getStations.

최종 결과물(스페이스바 3번씩)

| 런닝맵  | FCP   | TTI   | SI    | TBT    | LCP   | CLS   |
|------|-------|-------|-------|--------|-------|-------|
| 현재   | 15.3초 | 16.0초 | 15.3초 | 700밀리초 | 15.9초 | 0.042 |
| 예상치  | 1.35초 | 2.05초 | 1.35초 | 700밀리초 | 1.95초 | 0.042 |
| 목표치  | 2.3초  | 3.0초  | 2.3초  | 700밀리초 | 2.9초  | 0.042 |


# SpringBoot-Project-MEGABOX
------------------
스프링 부트 + JSP 파싱_영화 예매 사이트

# 🖥 프로젝트 소개
MEGA BOX를 참고하여 만든 영화 예매 사이트입니다.

# 🕰 개발 기간
+ 22.04.26일 - 22.05.24일

# 👭 멤버 구성
+ 팀장: 이윤재 - 영화 예매, 영화 업로드, Database Script 제작, 통합 및 형상관리
+ 팀원1: 채현우 - 로그인, 회원가입, ID 찾기, PW 찾기, 마이페이지, 메인 페이지, 통합 및 형상관리, PPT 제작, 발표
+ 팀원2: 이종원 - 메인 페이지, 메인 CSS
+ 팀원3: 전성덕 - 1대1 문의 게시판(CRUD), 공지사항 게시판(CRUD)

# 주요 기능
## 로그인 - 


