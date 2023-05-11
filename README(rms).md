# RMS

## 설명
OTQ V1 의 기기 등록, RMS DB 내 중복 확인, 저장된 데이터 확인 등의 내부에서 사용하기 위한 App 입니다.

## 기술스택
```React Native, Apollo Client, React Navigation, GraphQL, Moment.js, Styled Components, XLSX```

## 설치 및 실행
요구 사항은 아래와 같습니다.
* Node.js
* 패키지 매니저(npm 또는 yarn, yarn 권장)
* Android Studio(안드로이드 개발 환경 구성 시)
* Xcode(IOS 개발 환경 구성 시)


종속성 설치를 위해 아래와 같이 입력합니다.
```
yarn
```

ios 환경구축을 위한 cocoapod 설치를 위해 아래와 같이 입력합니다.
```
yarn pod
```
또는
```
cd ios
pod install
cd ..
```

실행을 위해 아래와 같이 입력합니다.
```
yarn start
```

배포 시, 아래와 같이 입력합니다.
```
yarn build
```

## ETC..
digital envelope routines 등의 에러 발생 시 node version 을 낮춰 실행합니다.
