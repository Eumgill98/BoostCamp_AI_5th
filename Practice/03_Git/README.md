
- `git config --global alias.l "log --oneline --all --graph"`

- 긴 명령어를 l로 지정해줬음 "git l" 사용하면 "log --oneline -all --grahp"가 실행된다

- `git commit -m "message"`
- 깃 commit 메시지 창 띄우지 않고 바로 commit

- `git commit -m "message" -a`
- -a옵션은 untracked 파일을 제외하고 auto add을 진행해준다

- `.gitignore` 파일 : commit을 하고싶지 않은 파일 리스트를 기록해주면 막을 수 있음 
- ex - config * -> config 이름인 파일들은 어떤 확장자라도 커밋을 막아줌 -> .gitignore 파일도 commit 해야함 

