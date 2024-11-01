# Lab8 Project
# Lab8 Project

## 프로젝트 개요
이 프로젝트는 Git과 GitHub의 기본 개념을 학습하고, 버전 관리를 이해하기 위한 것입니다. Git을 사용하여 로컬 저장소를 생성하고, 브랜치를 관리하며, 변경 사항을 추적하는 방법을 익힐 것입니다. 최종적으로 GitHub에 프로젝트를 업로드하여 원격 저장소에서 협업할 수 있는 방법을 배웁니다.

## 사용 방법
1. **프로젝트 폴더 생성**
   - 원하는 위치에 새로운 폴더를 생성합니다.
   - 예: `C:\Users\ghwjd\Documents\Lab8_Project`

2. **Git 저장소 초기화**
   - 생성한 폴더로 이동한 후, Git 저장소를 초기화합니다.
   - 명령어: `git init`

3. **브랜치 생성**
   - 새로운 브랜치를 생성하고 이동합니다.
   - 명령어: `git checkout -b feature-setup`

4. **파일 추가 및 커밋**
   - README.md 파일을 생성한 후, Git에 추가하고 커밋합니다.
   - 명령어:
     - 파일 생성: `echo "# Lab8 Project" > README.md`
     - Git에 추가: `git add README.md`
     - 커밋: `git commit -m "Add README.md file"`

5. **브랜치 병합**
   - 작업이 완료된 후, master 브랜치로 돌아가 feature 브랜치를 병합합니다.
   - 명령어:
     - master 브랜치로 체크아웃: `git checkout master`
     - 병합: `git merge feature-setup`

6. **GitHub에 푸시**
   - 원격 저장소를 추가한 후, 변경 사항을 GitHub에 푸시합니다.
   - 명령어:
     - 원격 저장소 추가: `git remote add origin https://github.com/hojung025/Lab8_Project.git`
     - 푸시: `git push -u origin master`

## 참고 자료
- [Git 공식 문서](https://git-scm.com/doc)
- [GitHub 사용법](https://docs.github.com/en)

## 결론
이 프로젝트를 통해 Git과 GitHub의 기본적인 사용 방법을 익혔으며, 향후 프로젝트 관리와 협업에 유용하게 활용할 수 있을 것입니다.
