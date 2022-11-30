# yoonjujeon.github.io
blog - 자신의 프로젝트를 Build한 과정\
\
먼저 사용하고 싶은 지킬 테마를 골라 다운받았다.\
환경 설정 파일인 _config.yml 을 내 정보에 맞게 수정했다.\
_config.yml 에서 하트모양 favicon 설정도 하였다.\
\
_post라는 폴더에 작성하려는 글을 markdown형식으로 작성한다.\
그리고 bundle exec jekyll serve  명령을 통해서 build 시키면, 저장된 글에 대해 컴파일이 진행되고 결과물이 destination 폴더에 생성된다.\
*jekyll build 작업할 때 주의해야 할 점: JEKYLL_ENV 환경변수의 값을 production으로 설정해야한다.\
\
다음 차례로 author 수정을 했다. \
만약 회사에서 쓸 경우에, 글을 작성하는 사람이 다수일 수 있으므로 author를 여러명 지정해서 사용가능하다.\
*개인 블로그 개설이 목표이기 때문에 author를 한명만 만들었다.\
\
_data폴더 안의 authors.yml파일의 내용을 수정하여 만들었다.\
그 다음 tag를 설정하였다.\
tag는 글의 범주를 설정하는 기능이다.\
다른 author라도 같은 tag의 글을 작성할 수 있다.\
_data폴더 안의 tags.yml파일의 내용을 수정하여 만들었다.\
\
그리고 메뉴를 수정하였다.\
_includes 폴더의 navigation.html을 수정해서 git, jekyll, tag 메뉴를 생성하였다.\
\
그 다음 post 작성을 했다.\
먼저 tag명과 같은 폴더를 하단에 생성한다.\
그리고 .md로 되어 있는 파일을 아무거나 하나 복사해서 "2022-11-30-jekyll-basic.md"와 같이 이름을 설정한다.\
해당 파일의 내용의 정보를 jekyll의 정보의 맞추어서 수정하고,\
내용 입력란에 jekyll에 관해서 배운 내용들을 작성하고, 다시 실행하면 post가 나타나는것을 볼 수있다.\
이러한 작업들을 반복해서 "jekyll, git, tag설정법"에 대해 포스팅을 하였다.\
\
로컬에서 작업을 모두 끝낸 후, GitHub Page에 Blog를 올렸다.\
C:[GitHubPage]/ 파일안의 내용을 깃허브페이지에 Publishing 하면 된다.
"yoonjujeon.github.io"라는 이름의 repository를 만든 후에\
Git을 이용하여 작업 내용을 repository에 push한다.\
\
그러면 이제 http://yoonjujeon.github.io로 접속해서 블로그를 볼 수 있다.
