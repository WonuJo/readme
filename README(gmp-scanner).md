# GMP SCANNER

## 설명
GMP 환경에서 OTQ V2 기기의 QR 스캔, NFC 및 BLE 통신을 통해 데이터를 전송하기 위한 App 입니다.

## 기술스택
```ReactNative, TypeScript, apollo, recoil```

## 설치 및 실행
npm 등 package 설치를 위해 아래와 같이 입력합니다.
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
