# MONITOR

## 설명
영업 스텝에서 POC 이전, OTQ V1, OTQ N1 의 시연용으로 보여주기 위해 만든 App 입니다.   
현재는 QR 스캔과 NFC 기능이 구현되어 있습니다.

## 기술스택
```ReactNative, JavaScript, apollo, recoil```

## 설치 및 실행
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

## ETC..
digital envelope routines 등의 에러 발생 시 node version 을 낮춰 실행합니다.
