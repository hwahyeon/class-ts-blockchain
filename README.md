# Typescript for Beginners

`Typescript` `Blockchain`

## 개요

이 저장소는 **Typescript로 블록체인 만들기**의 학습 내용이 정리되어 있습니다.

> 강사 : Nicolas

## 학습 목표
- Typescript 기초 학습

## 학습 내용
- Interface
- Classes
- Call Signatures / Polymorphism / Generics
- JSDoc

### 구현 내용
* 객체지향으로 블록 생성

```
[
  Block {
    prevHash: '',
    height: 1,
    data: 'Frist',
    hash: '1186935ee5761c733dc65d29f194489d525fe58646eca11cdcc1051fbd864632'     
  },
  Block {
    prevHash: '1186935ee5761c733dc65d29f194489d525fe58646eca11cdcc1051fbd864632',
    height: 2,
    data: 'Second',
    hash: 'c5e4819da1be646f75216c9412eaf655b56c6885e9f16bc0104ed440f2dda619'     
  },
  Block {
    prevHash: 'c5e4819da1be646f75216c9412eaf655b56c6885e9f16bc0104ed440f2dda619',
    height: 3,
    data: 'Third',
    hash: 'ec0ec604e91b6baff07d51b69be1234074f972c5a24580de97be0d41f1ea8817'
  }
]
```

## 참고 자료
[강의 소개](https://nomadcoders.co/typescript-for-beginners)

[챌린지 소개](https://nomadcoders.co/typescript-challenge)
