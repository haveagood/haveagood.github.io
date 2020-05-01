# Git Blog 만들기



## 개요

내가 공부하는 것들에 대한 기록을 남기기 위해서 여러가지 방법을 시도해봤다. Notion, Evernote, brunch 등등 시도를 해봤는데, 무엇인가 애착이 생기지 않았다. 그렇기 때문에 조금 더 자유롭게 커스터마이징 할 수 있는 방법에 대해서 고민한 결과, Github의 pages를 이용하여 blog를 만들고, 이를 나만의 홈페이지 처럼 사용해보고자 한다.



## 블로그 개설하기

### Repository 생성

Github의 블로그는 Repository라고 생각하면 된다. Repository를 Jekyll[^1] 이라는 Github에서 개발한 사이트 개발 툴을 활용하여 꾸민다고 생각하면 될 것 같다.

![gitblog-repository](C:\Users\havea\Pictures\gitblog-repository.png)

Git Blog로 사용하기 위한 Repository의 이름은 {ID}.github.io 와 같은 형태를 추천한다. 이 방식대로 Repository를 만들 경우, Git에서 자동으로 Page설정을 해주기 때문이다. 해보지는 않았지만, 아마 다른 형태로 저장소를 만들 경우, Page설정을 별도로 해주어야 할 것이다. 나는 이미 기존에 해당 repository를 생성하였기 때문에, 다음과 같은 메세지가 출력되었다. 추가적으로 README.md는 필수는 아니지만, 같이 생성하는것을 권장한다.

![gitblog-repository2](C:\Users\havea\Pictures\gitblog-repository2.png)

저장소를 만들고 나면, 다음과 같은 기본 화면이 출력 될 것이다.



[^1]: *Jekyll* 이란, Github에서 개발한 사이트 개발 툴이다. 기존의 사이트 or 블로그 개발 툴은 워드프레스(WordPress)가 가장 유명한데, 최근에는 많은 개발자들이 *jekyll*로 사이트를 이전하고 있다고 한다. 