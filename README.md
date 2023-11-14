<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/9c7b9485-f1fa-4729-96ee-0a0d48c5badd.png" width="800" height="320"/>

'금시초문'(**금**쪽이 육아 **시**뮬레이션 - **초**보 부모가 겪는 **문**제 해결 서비스) 프로젝트의 프론트엔드 서버에 사용되는 레포지토리입니다.
## 👉 연계 Backend Repo
> https://github.com/khuthon-parenting-sim/parenting-sim-backend

---
## 프로젝트 소개
'금시초문'는 초보 부모들을 위한 육아 정보 안내 서비스입니다.

## 개발 동기 및 개발 목적
최근 저출산 문제가 심각해지고 있고, '금쪽같은 내 새끼' 같은 프로그램이나 초등학교의 교권추락 같은 사건들이 사회적으로 크게 이슈가 되고 있습니다.

'금시초문'은 이러한 사회적 이슈의 원인 중 하나인 잘못된 가정 환경과 교육을 인식하고, 올바른 가정 교육 방법을 제시해 잘못된 가정 교육을 통해 문제 아이가 되는 것을 방지하게끔 도와줍니다. 

특히, 부모 역할을 처음 하게 되어 어떤 게 좋은 가정 교육이고 어떤 게 나쁜 가정 교육인지 인지하지 못하는 초보 부모들을 위해 서비스를 개발하게 되었습니다. 

## 개발 환경 및 사용 기술
- FrontEnd : React, TypeScript, Vite
- BackEnd : Spring Boot, MySQL, Docker, EC2
- 공통 : Git, Postman
- 협업툴 : Notion, GitHub, Figma

## 페이지별 기능
### 금쪽이 시뮬레이션 페이지
<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/fa2ce1fe-00e8-4297-9bbc-2c88505861e4.png" width="320" height="800"/> |<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/0171df5a-e700-4ba6-8804-68cae49cbe87.png" width="320" height="800"/>
--- | --- |

금쪽이 시뮬레이션을 에피소드별로 진행할 수 있습니다.


<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/4700a8da-9560-4746-acda-df95c02ad9e2.png" width="320" height="800"/> |<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/6a7bc9a9-f698-4eb6-8a9b-eef99857a849.png" width="320" height="800"/>
--- | --- |

사용자 아이디를 입력하고 에피소드를 시작하면, 각 에피소드의 첫번째 시나리오가 나타납니다. 시나리오는 금쪽이가 어떤 상황에 주어졌을 때 어떻게 행동할지에 대한 선택지가 나타납니다.

<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/b538063a-0d74-4431-a2c1-be97b46669b8.png" width="320" height="800"/> |<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/19080731-516f-4676-b984-8c7b3619b31a.png" width="320" height="800"/>
--- | --- |

선택지는 정답인 선택지와 오답인 선택지가 존재하며, 정답인 선택지를 선택할 경우 정답인 이유를, 오답인 선택지를 선택할 경우 오답인 이유와 정답을 보여줍니다.

<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/bceec247-14d9-4a8d-8a5f-3eb21348d94b.png" width="320" height="800"/> |
--- |

모든 시나리오가 끝나면 에피소드에 대한 결과를 보여줍니다. 결과는 종합 육아 점수, 사회성, 자기 통제, 상황 인지, 집중력 점수가 있습니다.

### 육아 사전 페이지
<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/c89877c3-cba2-4d53-81ef-4e2fb2f43956.png" width="320" height="800"/> |
--- |

육아 사전에서는 유용한 육아 정보들을 볼 수 있습니다. 각 정보들을 제목이나, 내용, 키워드로 검색할 수 있습니다.

상단에 있는 '오늘의 육아'에서 매일 바뀌는 육아 정보를 확인할 수 있습니다.

### 상황별 육아 예시 페이지
<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/5e85393b-eca7-4e78-840a-04c7ac129374.png" width="320" height="800"/> |<img src="https://github.com/khuthon-parenting-sim/parenting-sim-backend/assets/82189072/6a9649c8-eb14-46f5-af00-d5f4a6386590.png" width="320" height="800"/>
--- | --- |

육아 중 특정 상황이 발생하였을 때 행동 수칙을 보여줍니다. 각각의 상황별로 좋은 예시와 나쁜 예시를 알려주고, 각각에 해당하는 관련 유튜브 영상도 확인할 수 있습니다. 

## 기대 효과
- 부모가 자기 자신이 인지하지 못한 잘못된 교육 방식을 깨닫고 고칠 수 있습니다.
- 올바른 가정 교육을 통해 자녀가 문제 아이가 되는 것을 막을 수 있습니다.
- 문제 아이가 일으킬 수 있는 여러 사회적 문제를 막을 수 있습니다.

---
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list
