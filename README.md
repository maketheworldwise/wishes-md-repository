<h1 align="center">소원 저장소에 오신것을 환영합니다 👋</h1>

> 자신의 소원을 자유롭게 작성하고 기여해보세요!

## 🏠 Homepage

 프로젝트에 대한 더 자세한 설명은 하단의 홈페이지 링크를 클릭해 확인해주세요.

- [오픈 소스 기여용 소원 저장 프로젝트!](https://velog.io/@maketheworldwise/%EC%98%A4%ED%94%88-%EC%86%8C%EC%8A%A4-%EA%B8%B0%EC%97%AC%EC%9A%A9-%EC%86%8C%EC%9B%90-%EC%A0%80%EC%9E%A5-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8)

## 🙋🏻 You

- 오픈 소스에 기여하는 방법을 숙지를 목표로 합니다.
- 오픈 소스에 대한 두려움을 없애고 재미와 자신감을 가질 수 있도록 도전해봅니다.

## 🚀 Your Mission

- 이 저장소에 Issue를 등록합니다.
- 이 저장소를 Fork 하고 자신의 소원을 작성한 파일을 추가한 뒤 이슈에 연결하여 PR을 보냅니다.
- PR 승인 결과를 확인합니다.

## ✍🏻 Usage

프로젝트 기여를 위해 필요한 내용은 다음과 같습니다.

**(소원 파일 양식은 [소원 템플릿](docs/WISHES_TEMPLATE.md)를 참고해주세요.)**

```shell
# 1. 원본 원격 저장소 Fork

# 2. Fork한 원본 원격 저장소를 로컬에 Clone
$ git clone https://github.com/YOUR_FORK_USERNAME/YOUR_FORK.git

# 3. Clone한 로컬 저장소에 PR을 보낼 원본 원격 저장소(origin) 설정
$ git remote add upstream https://github.com/maketheworldwise/wishes-md-repository

# 4. 로컬 저장소에 PR용 새로운 브랜치 생성 및 이동
$ git checkout -b prbranch

# 5. 원격 저장소에 커밋 및 푸시 (단, 등록한 Issue Number와 연결 커밋)
$ git add .
$ git commit -m "close maketheworldwise/wishes-md-repository#[Issue Number]"
$ git push origin prbranch

# 6. PR 전송
# Compare & pull request > Create pull request

# 7. 브랜치 삭제
$ git checkout master
$ git branch -D prbranch
$ git push origin --delete prbranch
```

## 🤝 Contributing

이슈 내용은 [이슈 템플릿](docs/ISSUE_TEMPLATE.md)를, PR 내용은 [PR 템플릿](docs/PULL_REQUEST_TEMPLATE.md)를 참고해주세요.

## 💪🏻 Supports

도움이 되었다면 ⭐️ 을 주세요 :)