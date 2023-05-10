# RMS

## 설명
실제 배송환경에서 OTQ N2 사용 운송자(기사) 를 위한 App 입니다.   
NFC 통신을 통해 기기연결 및 운행종료, 접촉식 도착 처리가 가능하며
BLE 통신을 통한 별도 접촉식 스캔 없이 (hand-off) 도착 처리가 가능합니다.

## 기술스택
```
ReactNative, TypeScript, GraphQL
```

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

## ETC..
digital envelope routines 등의 에러 발생 시 node version 을 낮춰 실행합니다.
