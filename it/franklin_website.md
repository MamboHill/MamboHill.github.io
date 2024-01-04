@def title = "Franklin - Mambo IT"
@def tags = ["Julia", "Franklin", "GitHub", "Website", "hosting"]

# Franklin을 이용하여 GitHub에 static Website hosting 하기

이 posting에서는 Julia 기반 Franklin 패키지를 사용하여 GitHub에서 웹사이트를 호스팅하는 방법에 대해 알아보겠습니다. 
Julia로 작성된 Franklin 패키지는 static 웹사이트를 구축하고 관리하는 데 탁월한 도구로, GitHub Pages와의 통합을 통해 간편한 호스팅을 제공합니다. 
여기서는 Franklin 패키지를 사용하여 GitHub를 활용하여 웹사이트를 구축하고 배포하는 단계를 살펴볼 것입니다. 

\tableofcontents <!-- you can use \toc as well -->

## Julia 인스톨하기
윈도우즈 환경에서는 다음의 명령어로 Julia를 인스톨하도록 하자.
```
> winget install julia -s msstore
```
Julia 인스톨 및 사용에 대한 자세한 내용은 [Julia 공식 사이트](https://julialang.org/)에서 확인할 수 있다.

## Franklin 인스톨하기
Franklin은 Julia REPL에서 다음과 같이 인스톨할 수 있다.
```julia
pkg> add Franklin
```

## Website 생성하기
Franklin의 `newsite` 함수를 사용하여 Website를 생성할 수 있다.
```julia
julia> using Franklin

julia> newsite("MamboFamily"; template="bootstrap5")
✓ Website folder generated at "MamboFamily" (now the current directory).
→ Use serve() from Franklin to see the website in your browser.
```

Website가 생성된 후 다음과 같이 웹사이트를 로컬에서 시작할 수 있다.
```julia
julia> serve()
```

## GitHub에 repository 만들기
GitHub에 `username.github.io` repository를 생성한다.
자세한 내용은 [Github pages](https://pages.github.com/) 문서에서 확인할 수 있다.

## 로컬 웹사이트 폴더와 GitHub repository 동기화하기
`Git CMD`를 실행하고 웹사이트 폴더로 이동한수 다음의 명령을 실행한다.
```
git init && git remote add origin URL_TO_YOUR_REPO
git add -A && git commit -am "initial files"
git branch -M main
git push -u origin main
```

위의 과정이 제대로 수행되면 GitHub repository에 push될 때마다 GitHub 액션이 트리거되어 __site 폴더의 내용을 gh-pages 브랜치에 배포하며, GitHub은 이를 통해 웹사이트를 배포합니다.