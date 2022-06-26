# Shutdown YouTube

### 경희대학교 컴퓨터공학과 정병석, 최원석, 황세훈

License: MIT

## Shutdown YouTube

Node.js를 사용하여 나만의 Youtube의 shutdown program 만들어보기
Create your own Youtube site using Node.js and create shutdown program using Node.js

## Configuration

- Frontend: Vanilla.js(Pug Template)
- Backend : Node.js
- Database: mongoDB Atlas
- A W S : EC2(Ubuntu), S3

## Quickstart

### Prerequisite

- node v12.x
- npm 6.x

### Required File

위 저장소를 클론한 후 /myYoutube 위치에 .env 파일을 추가해주세요. 내용은 다음과 같습니다.
If you cloned this repo, please add the .env file in /myYoutube
The .env file is ..

```bash
MONGO_URL = "mongodb://localhost:27017/yourDBname"
PORT = "Your port number"
COOKIE_SECRET = "anything"
GH_ID = "Your github developer Access ID"
GH_SECRET = "Your github developer Secret Key"
FB_ID = "Your facebook developer Access ID"
FB_SECRET = "Your facebook developer Secret Key"
AWS_KEY = "Your AWS IAM Access ID"
AWS_PRIVATEE_KEY = "Your AWS IAM Secret Key"
```

### Install

```bash
npm install
```

### Run program

서버상에서 어떻게 실행되는지 확인하고 싶다면 터미널에 다음과 같이 입력해주세요

```bash
npm run dev:server
```

## Reference links

[Passport JS](http://www.passportjs.org/)

[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web)

[Github Developer](https://developer.github.com/program/)

[Facebook Developer](https://developers.facebook.com/)

[Webpack-cli](https://www.npmjs.com/package/webpack-cli)

[Multer-S3](https://www.npmjs.com/package/multer-s3)

[Mongoose](https://mongoosejs.com/)

[Axios](https://www.npmjs.com/package/axios)

[AWS SDK](https://aws.amazon.com/ko/sdk-for-javascript/)

## Pages:

- [x]  Home
- [x]  Join
- [x]  Login
- [x]  Search
- [x]  Shutdown
- [x]  User Detail
- [x]  Edit Profile
- [x]  Change Password
- [x]  Upload
- [x]  Video Detail
- [x]  Edit Video
- [x]  License
- [x]  MIT License

## Contact

이용하시다가 궁금한 점이 있으시면 이쪽으로 연락 부탁드립니다.
정병석 [qudtjr0409@khu.ac.kr](mailto:qudtjr0409@khu.ac.kr)