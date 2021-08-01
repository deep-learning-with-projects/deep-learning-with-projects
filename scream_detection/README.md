# Scream Detection using CNN
CNN을 활용하여 비명인지 비명이 아닌지 Binary Classification 하는 프로젝트입니다.

* [Dependency Install](#Dependency-Install)
* [데이터 다운로드 가이드](#데이터-다운로드-가이드)

## Dependency Install
```shell
pip3 install -r requirements.txt
```

## 데이터 다운로드 가이드
데이터를 다운로드 받을 수 있는 2가지 방법입니다.

1. Git LFS 설치
   1. Git LFS 설치하기
      1. [window](https://hengbokhan.tistory.com/20)
      2. Mac - `brew install git-lfs`
      3. [Linux](https://docs.github.com/en/github/managing-large-files/versioning-large-files/installing-git-large-file-storage) 에서 Linux 탭 참조
   2. 프로젝트에서 git lfs 설치
      ```bash
      git lfs install
      ```
   3. 파일 가져오기
      ```bash
      git lfs pull
      ```
2. Google Drive 에서 직접 다운로드
   1. https://drive.google.com/drive/folders/1WNjEaImJlm-7qmoRgOxRePDYQj7aQXLc?usp=sharing 접속
   2. `data` 디렉토리 다운로드
      <img src="![60511C24-D15E-4DBF-A3E2-2852BF4EE858](https://user-images.githubusercontent.com/36983960/127764561-ecc337fa-9b81-429a-8448-b98a4f83b65b.png)" alt="Google Drive for Deep Learning with Projects" style="zoom:50%;" />
   3. `data` 디렉토리 `scream_detection` 프로젝트로 이동
