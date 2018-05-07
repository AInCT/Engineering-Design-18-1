# Graduation Design 18-1

### 업로드 방법
* 본인의 폴더내에 공학설계를 수행한 날짜 + 제목으로 폴더를 만든 후, 해당 폴더에 자료를 업로드하세요.
* 가능하면 각 수행한 폴더 내에 README.md 파일을 소신껏 꾸며서 추가해두시기 바랍니다.
    - 해당 폴더, 즉 해당 날짜에 수행한 공학설계 내용 및 코멘트등을 정리하는 문서를 README.md로 작성하세요.
    - MarkDown 문법을 확인해보세요.
* 본 repository의 folder tree는 다음과 같이 구성될 수 있습니다.(예시)

```
 .
├── Professor
│   └── XXX(folder)
│          └── some files
│          └── README.md
├── 2014136005-박윤호
│   └── XXXX-XX-XX-IoT자료조사(folder)
│          └── some files
│          └── README.md
├── 2014136106-임찬규
│   └── XXXX-XX-XX-AI주제탐색(folder)
│          └── some files
│          └── README.md
├── 2016136032-김형찬
│   └── XXXX-XX-XX-MacineLearning주제탐색(folder)
│          └── some files
│          └── README.md
├── 2016136044-박주영
│   └── XXXX-XX-XX-BigData주제탐색(folder)
│          └── some files
│          └── README.md
├── 2016136112-정현석
│   └── XXXX-XX-XX-BlockChain주제탐색(folder)
│          └── some files
│          └── README.md
├── LICENSE.md
└── README.md
```

### GIT 사용 방법 

```c
[최초에만] 1. repo 클론하기
zero@ubuntu:~/Desktop$ git clone https://github.com/AInCT/Engineering-Design-18-1.git

2. 최신상태로 업데이트 하기
zero@ubuntu:~/Desktop/Engineering-Design-18-1$ git pull
Already up-to-date. <-- 확인필수

3. 자기 폴더에 폴더생성하고 ppt 넣기

4. git 에 올린 폴더 추가 해 주기 (. 이 현재 폴더라는 뜻, 안전하게? 자기 폴더로 이동해서 명령어 치기)
zero@ubuntu:~/Desktop/Engineering-Design-18-1$ git add -A .

5. 커밋하기 (커밋하면 뭐라 아래 뜸)
zero@ubuntu:~/Desktop/Engineering-Design-18-1$ git commit -m "remove file"
[master fad931b] remove file
 Committer: AInCT <zero@ubuntu.ubuntu-domain>
...
 1 file changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 2018-04-18-Blockchain.pptx

6. github repo 에 최종적으로 업로드하기
zero@ubuntu:~/Desktop/Engineering-Design-18-1$ git push
...
```
