# LOGIS LINKER

## 설명
실제 배송 환경에서 OTQ V1의 QR과 엮고싶은 배송의 배송라벨을 스캔하여,
매핑을 하기위해 만들어진 Logis 고객사용 App 입니다.

## 기술스택
```ReactNative, TypeScript, apollo, recoil```

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
