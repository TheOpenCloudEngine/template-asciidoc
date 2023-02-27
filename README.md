# AsciiDoc Template Project

AsciiDoc으로 PDF 및 HTML을 만들기 위한 템플릿 프로젝트입니다.
Gradle을 기반으로 빌드를 진행합니다.

## 문서 생성

AsciiDoc으로 작성한 문서를 생성하기 위해서 다음의 커맨드를 사용합니다.

```
# ./gradlew build --console=verbose --no-build-cache
```

만약에 Gradle 캐쉬로 문서 생성이 잘 되지 않는다면 다음과 같이 Gradle 캐쉬를 삭제하십시오.

```
rm -rf .gradle
rm -rf build
```

## 참고

* https://asciidoctor.github.io/asciidoctor-gradle-plugin/master/user-guide/
