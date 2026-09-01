# TURTLE PIPELINE

마야·블렌더 3D 프로젝트 파이프라인 도구. 이 저장소는 **내려받는 곳**이다 (소스는 따로 있다).

## 사용 안내서

처음 쓰는 사람을 위한 안내서 → **https://lhb424.github.io/Turtle-dist/**

실행부터 저장 · wip/pub 규칙 · 막혔을 때까지 한 페이지에 있다.

## 처음 설치할 때

1. [Releases](../../releases) 에서 최신 `Turtle_setup_<버전>.zip` 을 받는다
2. 원하는 폴더에 풀면 `Turtle` 폴더 하나가 나온다 (예: `C:\Turtle`)
3. 안의 **`Turtle.exe`** 를 실행한다

한글이 들어간 경로에 풀어도 되지만, 되도록 짧고 영문인 경로를 권한다.

## 갱신할 때

다시 받을 필요가 없다. 창구(TURTLE SHELL)를 켜면 새 버전이 있을 때 위에 띠가
뜨고, **UPDATE** 를 누르면 알아서 받아 설치한 뒤 다시 켜면 된다.

`Turtle_update_<버전>.zip` 은 창구가 쓰는 파일이다. 사람이 직접 받을 일은 없다.

## 폴더 구조

```
Turtle\
  Turtle.exe        실행하는 것
  bin\              공용 도구 (버전이 올라가도 그대로 쓴다)
  versions\<버전>\   버전마다 한 폴더
  current.txt       지금 쓰는 버전
```

옛 버전 폴더는 지워도 되고, `current.txt` 를 옛 버전으로 고치면 되돌아간다.
