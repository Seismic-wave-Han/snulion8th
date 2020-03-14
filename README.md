초기 세팅 방법입니다 :)
1. `hyesoo5115/snulion8th` 레포지토리를 fork 합니다
2. 본인의 노트북의 원하는 위치에서 터미널에 `git clone https://github.com/본인 아이디/snulion8th.git` 실행하여 snulion8th 폴더를 생성합니다
3. `cd snulion8th`로 snulion8th 폴더로 이동합니다
4. `git pull`
5. `git checkout -b 본인이름 origin/본인이름` 으로 자기 이름으로 생성된 브랜치를 가져옵니다
6. `git remote add upstream https://github.com/hyesoo5115/snulion8th.git` 으로 원본 레포지토리를 upstream이라는 이름으로 추가합니다

과제 제출 방법입니다 :)

1. 본인 컴퓨터의 로컬 레포지토리에서 작업
2. 본인의 레포지토리인 `본인 아이디/snulion8th`에 수업 내용 및 과제 commit & push
3. 과제 완료 시 `hyesoo5115/snulion8th`의 **본인 이름** 브랜치로 Pull Request 요청
4. 과제 미완료 시 `hyesoo5115/snulion8th`의 master 브랜치에 올라온 정답 코드 확인 후 다음 명령으로 불러옵니다
```bash
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
$ git push origin master
```

