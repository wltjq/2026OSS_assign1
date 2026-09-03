# My First Web Page

한동대학교 AI컴퓨터전자공학부 23학번 심지섭의 자기소개 웹페이지입니다. 

- **Vercel Deploy URL**: https://2026-oss-assign1.vercel.app
- **index.html URL**: https://2026-oss-assign1.vercel.app/index.html
- **index2.html URL**: https://2026-oss-assign1.vercel.app/index2.html

## Key Learning 
1. 터미널 기본 명령어('ls', 'pwd', 'cd')
2. Git 버전 관리 및 GitHub push/pull
3. 기본 HTML 태그 구조

## Development Flow 
VS Code에서 코드 작성 -> git add / git commit으로 로컬에 기록 -> git push로 GitHub에 반영 -> Vercel로 배포 

## Code Modification
index.html을 복사해서 index2.html을 만든 후, 전공 및 이름 수정 및 배경색 변경, 버튼 추가

## Problem & Solution
Problem : git remote add로 mine을 연결할 때 주소를 잘못 입력해서 원하는 저장소로 올라가지 않는 문제가 발생했다.
Solution : git remote -v로 현재 연결된 원격 주소 확인 후, git remote set-url mine을 통해 주소를 정정해서 해결했다.

## Reflection
하나의 로컬 폴더에서 origin과 mine 같은 여러 원격 저장소를 동시에 연결하여 관리할 수 있다는 것을 알게 되었다.