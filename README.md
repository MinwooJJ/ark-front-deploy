# π Inflearn-Clone-Frontend

## π κ°μ(Summary)

μΈνλ° μΉμ±μ λ§λ€μ΄λ³΄λ ννλ‘μ νΈ

[Inflearn-clone-back repository](https://github.com/Ark-inflearn/inflearn-clone-back)

---

<br />

## π― λͺ©ν(Objectives)

- ννλ‘μ νΈ λ° νμ κ²½ν
- Hard skill λ° Soft skill ν₯μ

---

<br />

## π κ°λ°κΈ°κ°(Develop period)

2021.07.05 ~ μ§νμ€

---

<br />

## π» λΌμ΄λΈλ¬λ¦¬ λ° κΈ°μ  μ€ν(Library & Stack)

- Language : Typescript
- Library : Reactjs
- Server : Nextjs
- Style : Meterial-UI & Styled-components

---

<br />

## π ν  μΌ (Things to do)

- [x] νλ‘ νΈμλ μΈν : Typescript, Layout ...
- [ ] λ©μΈ νμ΄μ§
- [ ] νμκ°μ νμ΄μ§
- [ ] Header, Footer layout

---

<br />

## β¨ μ£Όμ κΈ°λ₯

- λ°μν μΉ νμ΄μ§
- SSR

---

<br />

## π μμ λ΄μ©

<details>
<summary>2021.07.08(NOAH))</summary>

github repository μμ±

- collaborator μ΄λ
- branch protect rule μ€μ 

</details>

<details>
<summary>2021.07.09(NOAH))</summary>

Readme μμ±
react-hook-form μ μ©

μ°Έκ³ λ¬Έν

- [nextjs, typescript, meterial-ui and jest set-up](https://documentationnerds.com/blog/tech/setup-next-frontend-with-typescript-eslint-prettier-jest-and-react-testing-library)
</details>

<details>
<summary>2021.07.10(Tony)</summary>

### npm run dev μ€ν μλ¨

- [x] nextμ next devμ μ°¨μ΄λ ?

  - [What is the difference between next (dev) and next build && next start ?](https://github.com/vercel/next.js/discussions/15053)
  - κ°λ€

- [x] cross-env NODE_OPTIONS='--inspect' next devλ μ€νμ΄ μλλ€.
  - NODE_OPTIONS='--inspect' μ΄κ² λλ¬Έμ μλ¨
    - NODE_OPTIONS=inspect μΌλ‘ μμ νλ©΄ μ€ν λ¨
    - NODE_OPTIONS μ΄λ νκ²½λ³μκ° μ νμνμ§ μ λͺ¨λ₯΄κ² μ

### dir λ°°μΉ μμ 

- [x] src μμ λ€μ΄κ°μΌ ν  κ²μ ?
  - https://nextjs.org/docs/advanced-features/src-directory
  - μ±μ μ€ννλλ° νμν λ΄κ° μμ±ν μμ€μ½λ

### λ μ΄μμ λ° μ»΄ν¬λνΈ μμ ([Semantic tag](https://velog.io/@ru_bryunak/HTML-%EA%B8%B0%EC%B4%88-2-%EC%8B%9C%EB%A7%A8%ED%8B%B1-%ED%83%9C%EA%B7%B8%EB%9E%80#:~:text=2%2F8-,%EC%8B%9C%EB%A7%A8%ED%8B%B1%20%ED%83%9C%EA%B7%B8%EB%9E%80%3F,%EC%9D%B4%20%EC%8B%A4%ED%98%84%EB%90%A0%20%EC%88%98%20%EC%9E%88%EB%8B%A4.))

- [x] nav νκ·Έλ₯Ό divμμ navλ‘ λ³κ²½, navλ₯Ό headerλ‘ κ°μΈμ€

  - inflearn κ³΅νμμ κ°λ°μ λκ΅¬λ‘ νκ·Έλ₯Ό νμΈνμ¬ λκ°μ΄ λ§λ€μ΄ μ€

- [ ] pages dir μμ \_document, \_app, index λ± nextμμ μ μνλ νμ΄μ§ κ΅¬μ±λ°©μ νμΈ ν μ λ¦¬
  - \_document :
  - \_app :
  - index :

### κΈ°ν μ€μ νμΌ νμΈ

- [ ] tsconfig.json μμ include λΆλΆ λ€μ νμΈνκΈ°

</details>

<details>
<summary>2021.07.11(Tony)</summary>

- [x] header, footer μ€κ³½λ§ μ‘κΈ°

### home page

- [ ] slider κ³΅κ°λ§ λ§λ€κΈ°
- [x] κ²μμ°½ λͺ¨μλ§ λ§λ€κΈ°
- [ ] κ°μ μΉ΄λ μ»΄ν¬λνΈ λ§λ€κΈ°
  - li.lecture\_\_card{card$}\*10
  - [emmetμ ν΅ν΄ ν¨μ¨μ μΌλ‘ μμ±](https://webruden.tistory.com/77)

```html
<li className="lecture__card">card1</li>
<li className="lecture__card">card2</li>
<li className="lecture__card">card3</li>
<li className="lecture__card">card4</li>
<li className="lecture__card">card5</li>
<li className="lecture__card">card6</li>
<li className="lecture__card">card7</li>
<li className="lecture__card">card8</li>
<li className="lecture__card">card9</li>
<li className="lecture__card">card10</li>
```

</details>

<details>
<summary>2021.07.12(Tony)</summary>

### Things to do

- [x] κ°μ μΉ΄λ μ»΄ν¬λνΈ λ§λ€κΈ°
- [x] λλ―Έ λ°μ΄ν°(json)μΌλ‘ κ°μ μ»΄ν¬λνΈ homeμ λμ°κΈ°
  - [ ] μ€μ λ‘ apiλ‘ λ°μμ€λ κ³Όμ  μμλ³΄κΈ°
- [ ] media query λ‘ λ°μν νλ©΄ λ§λ€ λ μ€ν¬λ¦° μ¬μ΄μ¦ λλλ κ΅¬κ° μμλ³΄κΈ°
- [x] slider κ³΅κ°λ§ λ§λ€κΈ°
- [ ] searchμμ title λ¬Έκ΅¬ λ§€μΌ λ°λκ² νκΈ°

### home page

- html μλ¬λ¬ νμ : `&#8361;`
- μ²λ¨μ μ½€λ§ : [μ κ·μ μ΄μ©](https://hianna.tistory.com/441)

### μ°Έκ³  λ¬Έν

- [htmlμ μλ¬λ¬ νμ λμ  reverse solidus λμ¬ λ](https://sqlplus.tistory.com/entry/html-%EC%86%8C%EC%8A%A4%EC%97%90-%EC%9B%90%ED%99%94%ED%86%B5%ED%99%94%ED%91%9C%EC%8B%9C%EB%A5%BC-%ED%95%A0%EB%95%8C-%EC%97%AD%EC%8A%AC%EB%A0%88%EC%89%AC%EB%A1%9C-%EB%82%98%EC%98%AC%EB%95%8C-%EC%B2%98%EB%A6%AC%EB%B0%A9%EB%B2%95)

</details>

<details>
<summary>2021.07.17(Tony)</summary>

### tsconfig.json μμ±

- [μ»΄νμΌλ¬ μ΅μ μ€μ ](https://typescript-kr.github.io/pages/compiler-options.html)

- include, exclude μμ±μ globκ³Ό μ μ¬ν νμΌ ν¨ν΄ λͺ©λ‘μ κ°μ§

  - \*: λͺ¨λ  λ¬Έμ(λλ ν λ¦¬ κ΅¬λΆκΈ°νΈ μ μΈ)
  - ?: ν λ¬Έμμ λ§€μΉ­(λλ ν λ¦¬ κ΅¬λΆκΈ°νΈ μ μΈ)
  - \*\*/ : λ°λ³΅μ μΌλ‘ λͺ¨λ  νμ λλ ν λ¦¬μ λ§€μΉ­
  - "src/\*/\*\*" : src μμ λͺ¨λ  νμ λλ ν λ¦¬ + μ§μνλ νμ₯μ(ex. .ts, .tsx, .d.ts)
    - allowJsκ° true(trueλ‘ μ€μ  ν΄λμ μν)μ΄λ©΄ .jsμ .jsx λ ν¬ν¨

- [ ] nextμμ typescript return type, prop type μμλ³΄κΈ°
  - [x] type vs interface
    - interfaceλ‘ ννν  μ μλ ννκ° μλλ©΄ interfaceλ₯Ό μ΄μ©νμ
  - [ ] nextμμ return type, prop typeμ μ΄λ»κ² μ§μ νλκ² μ’μμ§ μμλ³΄κΈ°

### μ°Έκ³  λ¬Έν

- [typescript-kr, tsconfig.json](https://typescript-kr.github.io/pages/tsconfig.json.html)
- [type vs interfaceκ° λ λ«λ€](https://yceffort.kr/2021/03/typescript-interface-vs-type)
- [typeκ³Ό interface μ°¨μ΄](https://medium.com/@alexsung/typescript-type%EA%B3%BC-interface-%EC%B0%A8%EC%9D%B4-86666e3e90c)

</details>

<details>
<summary>2021.07.23(Tony)</summary>

## Issue #9 : AppLayout κ΅¬μ‘° μ μ©

### \_document, \_app, index μ°μ μμ νμ

- \_document.jsλ μμμ  : HTML Document
- \_app.js : κ³΅ν΅μ λ μ΄μμ μμ±
- index.js : "/"λ‘ μμλλ κ²½λ‘
- \_error.js : Error page : μμ§ μ λͺ¨λ¦

μ°Έκ³  λ¬Έν

- [κ°μΈλΈλ‘κ·Έ : next.js κ΅¬μ‘°](https://salgum1114.github.io/nextjs/2019-05-06-nextjs-static-website-1/)

document > app > index μμΌλ‘ λ΄λ €μμ indexμ λ³Έκ²©μ μΌλ‘ λ§λ€λ©΄ λ  κ² κ°λ€

- νμ¬ AppLayout μ΄λΌλ κ³΅ν΅ componentλ₯Ό λ§λ€μ΄μ headerμ footerκ° νμν κ³³μ΄λ©΄ μ¬μ© ν  μ μκ² ν¨

### styled component μ€μΉ

- npm i styled-components
- noahλνκ³  μμνκ³  μ¬λ§νλ©΄ .cssνμΌμ μμ±νμ§ μλ λ°©ν₯μΌλ‘ μ§νν΄λ³Ό μμ 

typescriptλ μλ ₯μ΄ μμλλ propsμ λν typeκ²μ¬λ ν  μ μκ² μ§λ§
reactμμ μ΄λ»κ² μ¨μΌλλμ§λ μμλ³Ό νμκ° μμ

</details>

<details>
<summary>2021.07.24(Tony)</summary>

### μμλ΄μ©

- MainSlider μ»΄ν¬λνΈ μΆκ°
  - react-slick λΌμ΄λΈλ¬λ¦¬ μ¬μ©

### ν₯ν κ³ν

#### style

- [ ] .CSS νμΌ styled componentλ‘ λ³κ²½ν  μμ 
- [ ] CSS style κ΄λ ¨ κ³΅ν΅μΌλ‘ μ¬μ©νλ μμ λ±μ λν μμκ°μ λͺ¨μλμ νμΌ μμ±

#### slider κΈ°λ₯ μΆκ° λ° μμ 

- [ ] ν₯ν λ°°κ²½μμ μ΄λ―Έμ§μ κ°κ²νλ λ°©λ²μ λν΄ μκ°ν΄λ³΄κ³  λ³κ²½
- [ ] ν΄λΉ μ¬λΌμ΄λλ‘ μ΄λνλ λ²νΌ μΆκ°
- [ ] λͺ¨λ°μΌ νλ©΄μ μ¬λΌμ΄λ λͺ¨μ λ³ννλλ‘ μμ 
- [ ] μ¬λΌμ΄λμ λ§ν¬ μΆκ°

#### λ¦¬λμ€ λ° μ¬κ° μ€μ 

</details>

<details>
<summary>2021.08.03(NOAH)</summary>

### μμλ΄μ©

- signup page μμ±
  - Material-UI( CSS)
    - TextField: inputκ³Ό κ°μ μ­ν μ ν¨
    - Typography: divμ κ°μ μ­ν 
    - Grid: Gridλ₯Ό μ¬μ©νμ¬ Flexλ Gridμ κ°μ λμμΈμ μ½κ² κ΅¬ν
    - IconButton: Materialμμ μ κ³΅νλ iconμ buttonμΌλ‘ μ¬μ©νκ² ν΄μ€
    - styles.ts: custom cssνμΌ, classNameμΌλ‘ λ³μκ°μ λκΈ°λ©΄ custom λμμΈμ΄ μ μ©λ¨
  - react-hook-form( form)
  - yup( signup rule)

### ν₯ν κ³ν

#### style

- [x] SNS λ‘κ·ΈμΈ λμμΈ

#### νμκ°μ rule

- [x] yupμ μ¬μ©νμ¬ νμκ°μ rule μ€μ 
- [x] ruleμ λ§μ§ μμ κ²½μ° error λ©μμ§ μΆλ ₯
- [ ] μ΄μ©μ½κ΄, κ°μΈμ λ³΄μ·¨κΈλ°©μΉ¨ νμ΄μ§ μμ±

</details>

<details>
<summary>2021.08.01~2, 5, 7, 8(Tony)</summary>

## Redux setting

### 1. μ€μΉ λͺ¨λ

#### npm install redux next-redux-wrapper react-redux --save

- redux
- next-redux-wrapper
  - Next.jsμ μλ²μ¬μ΄λ λ λλ§ κ΄λ ¨ λ³΅μ‘ν μ€μ μ μ½κ² ν΄μ£Όλ HOC
- react-redux
  - react λ°μΈλ©

#### npm install -d redux-devtools-extension @types/next-redux-wrapper @types/react-redux

- redux-devtools-extension : κ°λ°μ λκ΅¬ μ¬μ©μ μν λΌμ΄λΈλ¬λ¦¬

#### npm install redux-saga

- redux-sagaλ typeμ μμ²΄μ μΌλ‘ μ§μνκΈ° λλ¬Έμ @type/redux-sagaλ νμ μμ(deprecated λ¨)

#### npm i immer

- μμμ λΆλ³μ±μ μ§μΌμ£Όλ λΌμ΄λΈλ¬λ¦¬

#### npm i faker shortid

- npm i --save-dev @types/faker
- npm i --save-dev @types/shortid

- dummy data testλ₯Ό λμ μΌλ‘ νκΈ° μν΄ fakerμ shortidλ₯Ό μ€μΉ

#### npm i axios

- sagaμμ μ¬μ©, λΉλκΈ° httpν΅μ (Promise based HTTP client for the browser and node.js)

#### npm i -S @redux-saga/core

- eslintκ° μ§μ ν΄μ€μ μ€μΉν¨

### 2. redux tree

redux

- reducers
  - index
  - user
  - lecture
  - types
- sagas
  - index
  - user
  - lecture
- configureStore

#### 2-1. commonState class μ­μ 

- loading, done, errorμ λ°λ³΅λλ νμ΄νμ νΌνλ €κ³  νμΌλ doneμ μ κ±°νκ³  loading, errorλ§ μ¬μ©νλ©΄ μλκ² λ μ§κ΄μ μ΄λΌμ μλκ² λ«λ€κ³  νλ¨ ν¨
- dataλ class member λ³μλ‘ μμμΌλ λ§μ μ¬μ©ν΄λ³΄λ class λ΄ λ©€λ²λ³μμ μμ νμκ° μμμ

### 3. κΈ°ν

#### λ¦¬λμ€ μ€μΉ λ° μΈν μ€

- [x] State type μ μ ν΄μΌ λ¨
- [x] User, Lecture - reducer, saga μ€κ³
  - lectureλ§ μνλ‘ μμ±

#### eslint rule μ€ 'no-param-reassign': 'off' => immer μ¬μ©μ μν΄

#### main(home) page redux λμ νλ¦

- μ²μ νλ©΄μ λΆλ¬μ¬ λ LOAD_REQUEST actionμ μμμΌλ‘ λ°μ΄ν°(Lecture card)λ₯Ό λΆλ¬ μ΄
- add λ²νΌμ λλ₯Ό λλ§λ€ λ°μ΄ν°κ°(Lecture card) μΆκ° λ¨
- μ§κΈμ λλ―Έ λ°μ΄ν°λ‘ λΆλ¬ μ€μ§λ§ apiλ₯Ό μμ²­ν  κ²½μ° requestμμ νΈμΆ νλ λΆλΆλ§ μΆκ°νλ©΄ λ¨

#### λ³μ  νμ λ°©μ

- μμμ  λ μ§Έ μλ¦¬μμ λ°μ¬λ¦Ό ν μμμ  μ²« μ§Έ μλ¦¬ μ μ₯
- n.2 ~ n.8 κΉμ§ λ³ λ°κ°(3.2~3.8μ 3κ° λ°)
- n.1 μ κΉμ§ λ²λ¦Ό(3.1μ λ³ 3κ°λ‘ νμ)
- n.9 μ μ μ¬λ¦Ό(3.9λ λ³ 4κ°λ‘ νμ λ¨)

### 4. μ°Έκ³  λ¬Έν

- https://jktech.tistory.com/46
- μΈνλ° λΈλλ²λ κ°μ
- https://medium.com/@raphat/next-js-typescript-redux-3fbc990cb901
- [next-redux-wrapper κ³΅μλ¬Έμ](https://github.com/kirill-konshin/next-redux-wrapper)
- [RootState](https://stackoverflow.com/questions/60777859/ts2339-property-tsreducer-does-not-exist-on-type-defaultrootstate)

### 5. νλ‘ νΈ νμ μκ±΄

- [ ] νμ μ μ₯ μμΉ : interfaceλ typeμ ν΄λΉ νμΌμ λμ κ²μΈμ§ λ°λ‘ νμΌμ λ§λ€μ΄μ μ λ¦¬λ₯Ό ν  κ² μΈμ§
- [ ] λ¦¬λμ€κ° μ μ²΄ κ°μ λ‘λνλ λΆλΆμ μνλ‘ λ§λ€μλλ° μμ μ΄ λ§λ€ UIκ΄λ ¨ λ¦¬λμ€λ μ§μ  λ§λλ κ²μ΄ μ’μ κ² κ°μ
- [ ] κ΄λ¦¬μ νμ΄μ§λ₯Ό λ§λ€μ΄μΌ νλ..? slider λ°°κ²½μμ DBμμ κ°μ ΈμμΌ λ  κ² κ°μλ° μ΄κ±Έ λ§€λ² λ°±μλ κ°λ°μκ° μ μ₯νλ κ² λ³΄λ€ κ΄λ¦¬μνμ΄μ§κ° μμΌλ©΄ μ’μ κ² κ°μ
  - μ°μ μμ λ?μ

</details>

<details>
<summary>2021.08.10(Tony)</summary>

μ¬λΌμ΄λ λ¦¬λμ€ μ°κ²°
slider νλ λλ¬Έμ reducerμ sagaμ νμΌμ νλμ© λ§λ€κΈ° λ²κ±°λ‘μμ
lectureνμΌμ ν©μ³μ μμνμ΅λλ€.

</details>

<details>
<summary>2021.08.10(NOAH)</summary>

### μμλ΄μ©

- signup page error case
  - Material-UI( CSS)
    - useStyle: material-uiμ μ§μ  classNameμΌλ‘ μ€νμΌμ μ μ©νκΈ° μν hook, μ μ©νκ³ μνλ μμ±μ κ°μ²΄λ‘ μμ±νκ³  μ μ©
    - createTheme: meterial-uiμμ μ΄λ―Έ λμμΈλ μμ±λ€μ λ³κ²½νκ³  μΆμ κ²½μ° μ¬μ©, ex) μμ, ν¬κΈ°, ν¨λ©.. λ±
  - react-hook-form( form)
    - Controller: material-uiμ κ°μ λΌμ΄λΈλ¬λ¦¬λ₯Ό μ°λνκΈ° μν wrapper
    - useFormContext: μ€μ²© λ κ΅¬μ‘°μμ λ°μ΄ν°λ₯Ό μ λ¬νκ³ μ ν  λ μ¬μ©, ex) νΉμ  formμ componentλ‘ λΉΌμ κ΄λ¦¬νκ³  react-hook-formμ μ μ©νλ κ²½μ°
    - FormProvider: userFormContextκ° μ μ©νκ³ μ νλκ³³μ wrapper
    - useForm: react-hook-form κΈ°λ³Έ hook
  - yup( signup rule)
    - error νΈλ€μ schema κ°μ²΄μ μλ¬ νΈλ€μ νκ³ μνλ μ¬ν­λ€μ μ λ¦¬νκ³  react-hook-formμ formStateμ errorμμ λ°μμ μ¬μ©, ex) errors.email?.message
    - yupμ νκ·Έμ μ μ©ν λ νκ·Έ nameκ³Ό yupμμμ μ μ μ΄λ¦μ κ°κ² ν΄μΌ μ μ©μ΄ λ¨, ex) name: email / email: yup.string().min(10).max(30)....
    - matches: μ κ·ννμμ μ¬μ©νκΈ° μν method
    - oneOf([yup.ref('email'), null]: λ€λ₯Έ inputκ³Ό κ°μ΄ μΌμΉνλμ§ μ¬λΆλ₯Ό νμΈνκ³ μ ν  λ μ¬μ©
    - error κ°μ²΄μ κ²½μ° submitνκ³  λμ μ μ© λ¨
    - νμ¬ μ κ·ννμμ μλ¬ νΈλ€μ errors κ°μ²΄μ message methodλ₯Ό νμΈνμ¬ μΌμΉνλ λ°©μμΌλ‘ μ μ©

### μ€λ₯ν΄κ²°

- Warning: Failed prop type: Invalid prop `error` of type `object` supplied to `ForwardRef(TextField)`, expected `boolean`
  - TextField νκ·Έμ errorμλ booleanκ°λ§ κ°λ₯νλ° yupμμμ μλ¬ λ©μμ§λ λ¬Έμμ΄μ΄ μμ±λκΈ° λλ¬Έμ λ¬Έμ κ° λλ νμ
    - error νκ·Έμ !!λ₯Ό λλ² λ£μ΄ boolean λ³μλ‘ λ§λ€μ΄μ£Όλ©΄ λ¨, ex) !!error.password

### ν₯ν κ³ν

- Reduxμ μ°κ²°
- λ‘κ·ΈμΈ λͺ¨λ¬ κ΅¬ν
- κ³΅ν΅ λ μ΄μμ κ΅¬ν

#### νμκ°μ rule

- [x] yupμ μ¬μ©νμ¬ νμκ°μ rule μ€μ 
- [x] ruleμ λ§μ§ μμ κ²½μ° error λ©μμ§ μΆλ ₯
- [ ] μ΄μ©μ½κ΄, κ°μΈμ λ³΄μ·¨κΈλ°©μΉ¨ νμ΄μ§ μμ±

</details>

<details>
<summary>2021.08.12(Tony)</summary>

### λ©μΈνμ΄μ§ λ¦¬μ€νΈμ λ‘λ© μ€νΌλ μΆκ°

- μλ²μ¬μ΄λ λ λλ§μ΄κΈ° λλ¬Έμ νμ μμ κ² κ°κΈ°λ ν¨
- μ¬λ―Έλ‘ μΆκ° ν΄λ΄

### λ©μΈνμ΄μ§ κ°μ λ¦¬μ€νΈ

- λ§μ°μ€ νΈλ² μ λμ€λ description μΆκ°
- [ ] μ₯λ°κ΅¬λ, μ’μμ λ± μμ΄μ½μ μ€λͺ λΌλ²¨ μΆκ° ν΄μΌ ν¨
- [ ] μΉ΄λ μ μ²΄μ μΌλ‘ ν¬κΈ° ν€μμΌ ν¨

### κΈ°ν

- μ»΄ν¬λνΈ νμΌλͺ μ²«κΈμ λλ¬Έμλ‘ λ³κ²½(λΈμλ μμ²­μ¬ν­)

### μ°Έκ³ λ¬Έν

- [react onHover event handling](https://upmostly.com/tutorials/react-onhover-event-handling-with-examples)

</details>

<details>
<summary>2021.08.13(Noah)</summary>

### Update Nextjs version 11

- Conformance
  - `npx next lint` λͺλ Ήμ΄λ₯Ό μΉλ©΄ νμ¬ appμ ESLintλ₯Ό μ μ²΄μ μΌλ‘ μνν΄μ λ©μμ§λ‘ CLIμ λ³΄μ¬μ€
- Improved Performance
  - 11λ²μ  μλ°μ΄νΈλ₯Ό νλ©° appμ μ΄κ³  startup timeμ 24%μ΄μ κ°μμν€κ³  React refresh κ΄λ ¨νμ¬ νλ‘μΈμ± νμμ 40%μ΄μ κ°μμν΄
  - Babel κ΄λ ¨ startup time κ°μ
  - μλ‘μ΄ Babel loader κ΅¬μΆ
  - λ‘λ©, λ©λͺ¨λ¦¬ μΊμ±κ³Ό κ΄λ ¨νμ¬ μ΅μ ν
  - κ°λ°μκ° μ€μ λ‘ ν  κ²μ μκ³  updateλ§μΌλ‘ μ΄λ―Έ μ μ©μ΄ λλ μ¬ν­
- Script Optimization

  - `next/script`
  - μΉμ¬μ΄νΈμ λ€λ₯Έκ³³μμ κ°μ Έμμ μ¬μ©νλ κΈ°λ₯λ€μ μΆκ°ν λ λΌμ΄λΈλ¬λ¦¬κ° λ¬΄κ²κ±°λ μ΅μ νμ λ¬Έμ κ° μλλ° μ΄κ²μ Nextjsμ Script νκ·Έκ° ν΄κ²°ν΄μ€( polyfill, widgets λ±)
  - Script νκ·Έμ strategy μμ±μ μΆκ°νλ©΄ μλμ μΌλ‘ μ΅μ ν λ° μ±λ₯ ν₯μ
    - third party λΌμ΄λΈλ¬λ¦¬μ μ€ν μμλ₯Ό μλ§μ λ§κ² μ€μ  ν  μ μμ
    - beforeInteractive, afterInteractive( default), lazyOnload μμ±

- Image Improvements
  - `next/image`
  - Image λ‘λ©κ³Ό κ΄λ ¨νμ¬ μ±λ₯ κ°μ 
    - Nextjsμ Image νκ·Έλ₯Ό μ¬μ©νλ©΄ μ μ μ΄λ―Έμ§μ κ°λ‘/μΈλ‘ ν¬κΈ°λ₯Ό μλμΌλ‘ μ μν΄μ€
    - μΈν°λ·μ΄ λλ¦° μ¬μ©μλ₯Ό μνμ¬ blur μ΄λ―Έμ§λ₯Ό Nextjsμμ νκ·Έ μμ±μΌλ‘ μ κ³΅
- Webpack 5
  - `next.config.js`
  - μΉν©5μ κ΄λ ¨νμ¬ λ€μν νΉμ§ λ° κ°μ μ λ€μ΄ κ΅¬μΆλ¨
- Create React App Migration (Experimental)
  - μλ‘μ΄ ν΄ `@next/codemod` κ°λ°
  - Create React Appμ μλμ μΌλ‘ Nextjsλ‘ λ³κ²½ν΄μ£Όλ ν΄
- Next.js Live (Preview Release)
  - νμμ μν κΈ°λ₯
  - μΉμ¬μ΄νΈλ₯Ό λμλμ μνμμ λΌμ΄λΈλ‘ λ§μ°μ€λ‘ κ³΅κ°μ μ§μ  ν  μ μκ³  μ€μκ° μ±νλ κ°λ₯ν κΈ°λ₯

### μ°Έκ³ λ¬Έν

- [Nextjs docs](https://nextjs.org/blog/next-11#upgrade-guide)
- [Conformance](https://web.dev/introducing-aurora/)
- [Script](https://github.com/vercel/next.js/discussions/24938)
- [Script](https://docs.google.com/document/u/0/d/1ZEi-XXhpajrnq8oqs5SiW-CXR3jMc20jWIzN5QRy1QA/mobilebasic#)
- [Image](https://vercel.com/blog/core-web-vitals#cumulative-layout-shift)
- [Image](https://nextjs.org/docs/basic-features/image-optimization)
- [Webpack](https://nextjs.org/docs/messages/webpack5)

</details>

<details>
<summary>2021.08.14(Tony)</summary>

### μμ λ΄μ©

- κ°μ μΉ΄λ λ§μ°μ€ μ€λ² ν  λ λμ€λ μ€λͺ λ° μμ΄μ½ 3κ°μ λ§νμ  μΆκ°
- lectureCard ν΄λλ₯Ό λ§λ€μ΄μ componentsν΄λ μ λ¦¬
- node notifierκ° μλμΌλ‘ μ€μΉλ¨(μλ°μ΄νΈ νλ €κ³  npm i νλ μ€μΉ λ¨)
  - cross platform(windows, mac, linux)μμ μλμ λμΈ μ μλ λͺ¨λ

### μ°Έκ³ λ¬Έν

- [CSSλ‘ λ§νμ  λ§λ€κΈ°](https://ungdoli0916.tistory.com/753)

</details>

<details>
<summary>2021.08.16(Tony)</summary>

### μμ λ΄μ©

- AppLayout, CourseLayoutμ components ν΄λμμ layouts (μ κ·)ν΄λλ‘ μ΄λ
- [ ] create course νμ΄μ§μμ μ λͺ© μλ ₯ ν κ°μ λ§λ€κΈ°λ₯Ό λλ₯΄λ©΄ μμ  νμ΄μ§λ‘ μ΄λ
- κ°μ μμ± ν idλ₯Ό μ μ₯ν  νμλ μμ κ² κ°μμ λ¦¬λμ€λ₯Ό μ¬μ©νμ§ μμ
  - μ΄λ»κ² νλκ² μ’μμ§ ν λ‘  νμ

```typescript
const inputTitle = useRef<HTMLInputElement>(null);
```

- μ΄κΈ°κ°μ nullμ λ°μμ€μΌ λλ€. -> HTMLInputElement | null

#### nextμμ redirect

```typescript
import { useRouter } from 'next/dist/client/router';
const router = useRouter();
router.push(`/course/${id}/edit/course_info`);
```

### λ‘μ»¬ μλ² μΈν

```typescript
// app.ts or index.ts
app.use(
  cors({
    origin: true,
    // credentials: false
  })
);
app.use(express.json()); // frontμμ jsonννμ dataλ₯Ό λ³΄λΌλ κ·Έκ²μ req.bodyμ λ£μ΄μ€
app.use(express.urlencoded({ extended: true })); // form&submitμ νλ©΄ url encodedλ°©μμΌλ‘ dataκ° λμ΄μ€λλ° κ·Έκ²μ req.bodyμ λ£μ΄μ€

app.use('/create_course', lectureRouter);
```

```typescript
// lectureRouter
import * as express from 'express';

const router = express.Router();

router.post('/', (req, res) => {
  console.log('body', req.body);
  res.json({ id: 1234, result: 'ok' });
});

export default router;
```

### λμ€μ μΆκ°ν΄μΌ λ  λΆλΆ

- `/course/${id}/edit/course_info`μΌλ‘ μ΄λ μ λ΄ κ°μκ° μλ κ³³μΌλ‘ μ΄λν  κ²½μ° 404 λμμ€μΌ ν¨
  - μ μ κ° GETλ°©μμΌλ‘ μ μμ μλ ν  λ μλ²μμ κ²μ¦ ν μμ νμ΄μ§λ₯Ό λ³΄μ¬μ€μ§ λ§μ§ κ²°μ 

</details>

<details>
<summary>2021.08.19(Tony)</summary>

### create_course page

- create_courseμμ κ°μ λ§λ€κΈ° λλ₯΄λ©΄ `/course/1/edit/course_info`λ‘ μ΄λνκ² ν¨
  - λμ€μ μλ² λΆμΌ λ μ£Όμ ν΄μ νλ©΄ λ¨
- μ λͺ© μλ κ²½μ° alert λμ  κ²½κ³  λ©μΈμ§κ° λ¨λλ‘ ν¨

### create_course -> edit κ°μ μ λͺ© λκΈ°κΈ°

- λ¦¬λμ€ μ¬μ©
- κΈ°μ‘΄ axiosλ§ μ¬μ©νλ κ²μ reduxλ₯Ό μ΄μ©νλλ‘ λ³κ²½
  - saga effectμ putμ dispatchλ λΉμ·ν¨

### saga call type

- `Generator<T, TReturn, TNext>`
- [x] generator functionμμ type μ§μ νλ λ² μμλ³΄κΈ°
  - https://github.com/microsoft/TypeScript/issues/26959

### test.css νμΌ μμ±

- styled component μμ μλμμ±μ μ μ§μνμ§ μμΌλ―λ‘ cssνμΌμ νμ€νΈλͺ©μ μΌλ‘ λ§λ€μ

### create course btnμ λ‘λ© μ μ©

- λ‘λ© μκ° λμ ν΄λ¦­ λ°©μ§(pointer-events), ν¬λͺλ λ³κ²½(opacity)

### μ°Έκ³ λ¬Έν

- [styled component props](https://styled-components.com/docs/basics)
- [css prevent mouse click](https://stackoverflow.com/questions/44719980/how-to-prevent-the-click-event-using-css)
- [css pointer-events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events)
- [typescript styled components with props](https://stackoverflow.com/questions/47077210/using-styled-components-with-props-and-typescript)

</details>

<details>
<summary>2021.08.20(Tony)</summary>

### Things to do

- [x] create-courseμμ storeμ μ μ₯ν title κ°μ Έμ€κΈ°
- [ ] edit course info μ± λ μ΄μμ μμ 

</details>
<details>
<summary>2021.08.20, 21(Tony)</summary>

### μμ μ¬ν­

- childrenμ type μ μ©
- header, footer μ΄λ¦μ HeaderLayout, FooterLayoutμΌλ‘ λ³κ²½( Nextμ μ‘΄μ¬νλ μ΄λ¦μ΄κΈ° λλ¬Έμ κ²ΉμΉ¨)
- μ»΄ν¬λνΈμ μ¬μ¬μ©μ±μ μν΄μ κΈ°μ‘΄ stylesλ₯Ό μ§μ°κ³  μ»΄ν¬λνΈλ‘ μ΄λ

### styled(Link) μλ¨

```typescript
const SeeTheLecture = styled.button`
  font-weight: 800;
  width: 160px;
  height: 48px;
  font-size: 18px;
  border-radius: 3px;
  border: 0;
  background-color: #fff;
  border-color: #dbdbdb;
  border-width: 1px;
  color: #363636;
  cursor: pointer;
  justify-content: center;
  padding: calc(0.375em - 1px) 0.75em;
  text-align: center;
  white-space: nowrap;
`;

<Link href={`/course/${id}`}>
  <SeeTheLecture>κ°μλ³΄κΈ°</SeeTheLecture>
</Link>;
```

- Linkμμ buttonνκ·Έ λ£λ λ°©μμΌλ‘ μ€νμΌλ§ μ μ©

  - aνκ·Έλ‘ νλ € νμΌλ widthκ° μ μ©μ΄ μλ¨

- [ ] κ°μ μ μ columnμ ν΄λΉ νμ΄μ§ μΌ λ κΈμ μ λ³ν
  - course_info νμ΄μ§ -> κ°μ μ λ³΄ κΈμ μ μ§νκ²

</details>
<details>
<summary>2021.08.22(NOAH)</summary>

### Things to do

- [ ] λ²νΌμ μ€νμΌ μ μ©
- [ ] responsive νλ©΄ κ΅¬μ±

### μμ μ¬ν­

- νμκ°μ νμ΄μ§ λ° μ»΄ν¬λνΈ λ¦¬ν©ν λ§
- useStyles κ΅¬μ‘°λΆν΄

```typescript
const { classname } = useStyles();
```

### μ μ©μ¬ν­

- Header κ΅¬ν
  - AppBar : λ€λΉκ²μ΄μ μ»¨νμ΄λ
  - ToolBar : μμ μ»¨νμΈ λ₯Ό λ£μΌλ©΄ Flexμ κ°μ΄ μλμ λ ¬
- μ μ©ν΄μΌ ν  λ²νΌμ headerDataλ‘ νμ¬ μΆκ°
  - μΆ ν λ³κ²½μ΄ μμλ μ½κ² μ μ©νκΈ° μν¨

### λ¬Έμ μ¬ν­

- nextjsμμ html,body νκ·Έκ° μ μ²΄νλ©΄μ΄ λμ§ μμ \_app.tsxμ μλ μ€νμΌμ μ μ©νμμΌλ λ©μΈνμ΄μ§μμ μ μ©λμ§ μλ νμ
  - htmlμ΄ μ μ²΄ λ³΄μ΄λ νλ©΄μ ν¬κΈ°κ° μλκΈ° λλ¬Έμ stickyκ° μ€κ°μ μ§€λ¦Ό

```typescript
<style global jsx>
  {`
    html,
    body,
    body > div:first-child,
    div#__next,
    div#__next > div {
      height: 100%;
    }
  `}
</style>
```

</details>

<details>
<summary>2021.08.22, 23(Tony)</summary>

- [ ] edit course layout
  - [x] column sticky
  - [x] νμ¬ νμ΄μ§μ ν΄λΉνλ λΆλΆ κΈμ μ§νκ²
  - [ ] modal : λκΈΈμ λλ μ λͺ© μμ± κΏν
  - [ ] νμ΄μ§ λ‘λ μ κ΄λ ¨ λ°μ΄ν° κ°μ Έμμ νμ μ‘°κ±΄ μμ±λ νμ΄μ§λ μ΄λ‘μμΌλ‘ v νμ
- [ ] course_info νμ΄μ§ κ΅¬μ±

### CourseLayout.tsx

CourseHeaderContainer height + CourseLayoutGrid padding top(24px) + CourseNav padding top(0.75rem == 12px) μ λμ΄μ sticky

- StepContainerμ headerHeight propμ λ°λ‘ λ£μ΄ μ£Όλ©΄ CourseHeaderContainer heightκ° μΈ‘μ λμ§ μμ μν(undefined)λ‘ κ³μ°μ΄ λμ stickyμ topμ NaNμ΄ λ€μ΄κ°(sticky μ μ© μλ¨)
- νμ΄μ§ λ‘λν  λ useStateμ headerHeightμ κ°μ λ£μ΄μ λμ€μ κ³μ°λ heightκ°μ΄ λ°μ λλλ‘ ν¨

### create_course.tsx

- κ°μ idλ₯Ό μ λ¬ λ°κ³  sagaμμ μ§μ  redirectμν€λλ‘ ν¨(λ€λ‘κ°κΈ° μλλ λ¬Έμ  ν΄κ²°)

</details>

<details>
<summary>2021.08.24(Tony)</summary>

### create_course

- κ°μ λ§λ€κΈ° λ²νΌμ λλ₯΄μ§ μκ³  input textμμ μ λͺ© μλ ₯ ν μν°λ‘λ κ°μ μμ±λλλ‘ λ³κ²½

### CourseLayout

- window.location.pathnameμμ κ°μ μμ±ν μμ νμ΄μ§λ‘ λμ΄κ° λ windowκ°μ²΄λ₯Ό μΈμνμ§ λͺ»ν΄μ useRouterλ₯Ό μ¬μ©ν΄μ νμ¬ κ²½λ‘λ₯Ό μΆμ νλλ‘ ν¨

### λ°μ΄ν° λ‘λν΄μ λ£μ΄μΌ ν¨

- [ ] λ―Έλ¦¬ μ μ₯νλ λ°μ΄ν° λΆλ¬μμ λ°μ΄ν° λ‘λν΄μ λ£μ΄μΌ ν¨

</details>

<details>
<summary>2021.08.25(Tony)</summary>

### μΉ΄νκ³ λ¦¬ λ²νΌ μ€ λ€λ₯Έ μΉ΄νκ³ λ¦¬ μ ννλ©΄ νμ¬ μ νλ μΉ΄νκ³ λ¦¬ μμ μλλλ‘ λλ¦¬κΈ°

- μ¬μ©νλ κ³³μμ useStateλ‘ λ³μ νλ λ§λ€κ³  κ·Έκ²μ propμΌλ‘ μ λ¬

```typescript
// course_info.tsx
const [selectedId, setSelectedId] = useState<string>('');

<CourseCommonButton id="1" text="κ°λ°, νλ‘κ·Έλλ°" selectedId={selectedId} setSelectedId={setSelectedId} />;
```

- λ²νΌ μ»΄ν¬λνΈμ onClickμμ λ²νΌ ν΄λ¦­ν κ²μ λν μ λ³΄(id)λ₯Ό μ μ₯
- λ²νΌ μ»΄ν¬λνΈ μμ useEffectμμ κ·Έκ²κ³Ό μΌμΉνλμ§ μ¬λΆμ λ°λΌ true/falseλ₯Ό styled componentμ μ λ¬

```typescript
// CourseCommonButton.tsx
const CourseCommonButton = ({ id, text, selectedId, setSelectedId }: Props) => {
  const [isSelected, setIsSelected] = useState(false);

  function onClickButton() {
    setSelectedId(id);
  }

  useEffect(() => {
    if (id === selectedId) {
      setIsSelected(true);
    } else {
      setIsSelected(false);
    }
  }, [selectedId]);

  return (
    <CourseCommonButtonStyle onClick={onClickButton} key={id} isSelected={isSelected}>
      {text}
    </CourseCommonButtonStyle>
  );
};
```

### μΆκ° νκΈ° λ²νΌ λλ₯΄λ©΄ add components dynamically

- λ¦¬λμ€μμ state(array)λ₯Ό κ°μ Έμμ μΆκ°ν΄μΌ λ  κ² κ°λ€

#### μμ λ°μ΄ν° κ΅¬μ±

```typescript
data : {
  createLecture : {
    courseInfo : {
      title: string, // κ°μ μ λͺ©
      whatYouCanLearn: string[], // μ΄λ°κ±Έ λ°°μΈ μ μμ΄μ
      expectedStudents: string[], // μ΄λ° λΆλ€μκ² μΆμ²ν΄μ
      requiredKnowledge: string[], // μ μμ§μ
      category: { // μΉ΄νκ³ λ¦¬
        id: string,
        name: string,
      },
      level: string // κ°μ μμ€
    }
    // μμΈμκ°, μ»€λ¦¬νλΌ, μ»€λ²μ΄λ―Έμ§ μ λ³΄λ λμ€μ
  },
  setting : {
    // κ°μμ€μ 
    // μ§μκ³΅μ μ μ€μ 
  }
}
```

### μ°Έκ³  λ¬Έν

- [dynamically-add-child-components-in-react](https://stackoverflow.com/questions/36651583/dynamically-add-child-components-in-react)

</details>

<details>
<summary>2021.08.27(NOAH)</summary>

### HeaderLayout

- λ©λ΄λ° ν¬μ§μ μμ 

  - λ©λ΄λ°κ° νμμλ relativeμλ€κ° λ©λ΄λ° ν¬κΈ°λ§νΌ λ΄λ €μ¬ κ²½μ° stickyλ‘ λ°λλλ‘ μμ 
  - scroll μ΄λ²€νΈκ° λλ¬΄ μμ£Ό λΆλ¦¬κΈ° λλ¬Έμ lodash λΌμ΄λΈλ¬λ¦¬μ throttle κΈ°λ₯μ μ¬μ©νμ¬ 0.3μ΄μ ν λ²λ§ λΆλ¦¬λλ‘ κ΅¬ν

```typescript
const throttledScroll = useMemo(
  () =>
    throttle(() => {
      if (window.scrollY > 64) {
        setIsNavOn(true);
        return;
      }
      setIsNavOn(false);
    }, 300),
  []
);
```

- λͺ¨λ°μΌμ© λ©λ΄λ°
  - μΈνλ° νμ΄μ§μ κ°μ΄ λͺ¨λ°μΌ νλ©΄( 1025px)μ΄νλ‘ λ΄λ €κ° κ²½μ° Layoutμ΄ λ³κ²½λλλ‘ κ΅¬ν
  - λ©λ΄λ₯Ό νμμΌλ‘ λμμ§λλ‘ ν¨

### HeaderLayout κ΅¬νν΄μΌ ν  κ²

- λ‘κ·ΈμΈ λͺ¨λ¬μ°½
- κ²μμ°½ κΈ°λ₯
- λ©λ΄ νμ κΈ°λ₯
- λͺ¨λ°μΌ λ©λ΄ νμ μ€νμΌλ§

### μΆ ν νμΈ

- μΌλ¨ λ μ΄μμμ΄ λλλ‘ CSSλ₯Ό λμ§λμ§ λΆμ¬λ¨λλ° ν¨μ¨μ μΌλ‘ ν  μ μλλ‘ κ²ν ν΄μΌ ν¨

</details>

<details>
<summary>2021.08.27(Tony)</summary>

### κ°μμμ± ν window apiλ‘ νμ΄μ§ μ΄λμ λ°μ΄ν° λ λΌκ°λ λ¬Έμ 

- window.location.href λ₯Ό μ¬μ©νλ©΄ νμ΄μ§κ° μλ‘κ³ μΉ¨λλ©΄μ μλ°μ€ν¬λ¦½νΈ(λ¦¬λμ€ μ€ν μ΄)μ μλ λͺ¨λ  λ°μ΄ν°κ° λ λΌκ°

- reactλ nextμμ μ κ³΅νλ routerλ₯Ό sagaμμ μ¬μ©ν΄μΌ λλλ°
  useRouterλ useHistoryλ hookμ΄κΈ° λλ¬Έμ componentκ° μλ sagaμμ  μ¬μ©μ΄ λΆκ°λ₯ ν¨(hooks rule)

- λ¬Έμ  ν΄κ²°
  - sagaμμ νμ΄μ§ μ΄λμ μν€λ € νμΌλ μμ κ°μ λ¬Έμ λ‘ μ λμ§ μμ
  - 'history', 'react-router-redux' λΌμ΄λΈλ¬λ¦¬ λλ€ μ¨λ΄€λλ° typescriptλ¬Έμ μΈμ§ nextλ¬Έμ μΈμ§ λ­μ§ μ λμ§ μμ
  - κΈ°μ‘΄ λ°©μ λλ‘ μ»΄ν¬λνΈμμ νμ΄μ§λ₯Ό μ΄λ μν€λ λμ  flagλ‘ μ¬μ©μ€μΈ doneλ³μλ₯Ό falseλ‘ λ§λλ dispatchλ₯Ό μ€νλ¬Έ λ§μ§λ§μ μΆκ°ν΄μ μ±κ³΅

</details>

<details>
<summary>2021.08.28(Tony)</summary>

### κ°μ μμ  νμ΄μ§ λ‘λ μ λ°μ΄ν° λ°μμ€κΈ°(redux saga)

- νμΈ

### children componentμ props μ λ¬νκΈ°

```typescript
<CourseMain>
  {console.log('React.isValidElement(children)', React.isValidElement(children))}
  {React.isValidElement(children) && React.cloneElement(children, { lectureData })}
  {/* {React.Children.map<React.ReactNode, React.ReactNode>(children, (child) => {
            if (React.isValidElement(child)) {
              return React.cloneElement(child, { lectureData });
            }
          })} */}
  {/* {children} */}
</CourseMain>
// κ²°λ‘  μλ¨ => each childμμ storeμμ λ°μ΄ν° κ°μ Έμ€κΈ°
```

- each childμμ storeμμ λ°μ΄ν° κ°μ Έμ€κΈ°

### typescriptμμ initial data λ₯Ό νλνλ λ€ λ£μ΄μ€μΌλλκ±΄μ§ μμλ³΄κΈ°

- μ΄κΈ°κ°μ λ€ λ£μ΄μ€μΌ λ  κ² κ°μ

### μ°Έκ³ λ¬Έν

- [children componentμ props μ λ¬νκΈ°](https://eomtttttt-develop.tistory.com/203)
  - `This JSX tag's 'children' prop expects a single child of type 'ReactElement<any, string | JSXElementConstructor<any>>', but multiple children were provided.` => μλ¨
  - https://stackoverflow.com/questions/42261783/how-to-assign-the-correct-typing-to-react-cloneelement-when-giving-properties-to
    - μλ¨ : React.isValidElement(children) ν΅κ³Όκ° μλ¨
  - https://www.geeksforgeeks.org/how-to-use-react-cloneelement-function/
  - [λ¦¬μ‘νΈ μμ κ²μ¦νκΈ°](https://webisfree.com/2020-08-26/[react]-%EB%A6%AC%EC%95%A1%ED%8A%B8-%EC%9A%94%EC%86%8C-%EA%B2%80%EC%A6%9D%ED%95%98%EA%B8%B0-isvalidelement)
    - νλ μ§λ¦¬λ§ λ¨(`<div>νλ<div>` κ°μ)
      - νλ μ§λ¦¬λ props μ λ¬μ΄ μ μλ¨
- [react-children with typescript](https://www.carlrippon.com/react-children-with-typescript/)

</details>

<details>
<summary>2021.08.31(Tony)</summary>

### eslint => react/require-default-props : off

- https://stackoverflow.com/questions/63696724/eslint-problem-with-default-props-in-functional-component-typescript-react

### onClickDelete

#### 1μ°¨ μλ : store state is read-only

```typescript
const onClickDelete = (_list: string[], index: number) => {
  _list.splice(index, 1);
};
<button onClick={() => onClickDelete(list, index)} type="button">
  <DeleteIcon />
</button>;
```

- reduxμ μλ λ°μ΄ν°λ read-only μ
- dispatchλ₯Ό μ΄μ©ν΄μ reducerμμ μμμ νλ €κ³  νμλλ° componentμ λ€μ΄μ€λ string[]μ΄ storeμ κ°κ° λ€λ₯΄κ² μ μ₯λμ΄ μκΈ° λλ¬Έμ κΈ°μ‘΄μ draft.initialState.data κ°μ λ°©μμΌλ‘ μμ ν  μ μμ

#### 2μ°¨ μλ : read-only μ κ±° - setAutoFreeze(false);

```typescript
// storeμμ read-only μμ± μ κ±°
import { setAutoFreeze } from 'immer';
setAutoFreeze(false);

// TextListBox.tsx
const onClickDelete = (_list: string[], index: number) => {
  _list.splice(index, 1);
};
<button onClick={() => onClickDelete(list, index)} type="button">
  <DeleteIcon />
</button>;
```

- storeμ μλ κ°μ μ§μ  λ³κ²½ κ°λ₯νμ§λ§ re-renderκ° μλ¨
  - μλ reducerλ‘ storeμ κ°μ λ³κ²½νλ©΄ re-renderκ° λλλ° μ΄λ°μμΌλ‘ λ°λ‘ λ°κΏλ²λ¦¬λκΉ μλλ λ―

#### 3μ°¨ μλ : useStateμ storeμ stateλ₯Ό λ£κ³  setStateλ₯Ό μ»΄ν¬λνΈμ μ λ¬

```typescript
// course_info.tsx
const [textArray, setTextArray] = useState<string[]>();
<TextListBox list={textArray} setTextArray={setTextArray} />;

// TextListBox.tsx
type Prop = {
  list?: string[];
  setTextArray: React.Dispatch<React.SetStateAction<string[] | undefined>>;
};

const TextListBox = ({ list = [], setTextArray }: Prop) => {
  const onClickDelete = (textList: string[], index: number) => {
    textList.splice(index, 1);
    setTextArray([...textList]);
    console.log('after remove', textList);
  };

  return (
    <button onClick={() => onClickDelete(list, index)} type="button">
      <DeleteIcon />
    </button>
  );
};
```

- setStateλ₯Ό μ λ¬μ ν΄λ setTextArray(textList) stateλ₯Ό μ§μ  λ³ννκ³  κ·Έκ²μ κ·Έλλ‘ μ λ¬νλ©΄ λ λλ§μ΄ λμ§ μμ
- setTextArray([...textList]); κ°μ΄ λ°°μ΄μ μλ‘ ν λΉν΄μ μ λ¬ν΄μΌ λ λλ§μ΄ λ€μ λ¨
- TextListBoxλ₯Ό μ¬μ©νλ κ°μλ§νΌ useStateλ₯Ό λ§λ€μ΄μ κ°κ° μ λ¬ν  μμ 

#### 'react/no-array-index-key': 'off'

- indexλ₯Ό keyλ‘ μ¬μ©ν  λ λμ€λ eslint κ²½κ³ 
- λμ€μ eslintλλ¬Έμ λ¬Έμ λ  κ² κ°μμ λ―Έλ¦¬ μ κ±°

### μ°Έκ³ λ¬Έν

- [javascript removing element of array cleanest way](https://stackoverflow.com/questions/47023975/what-is-the-cleanest-way-to-remove-an-element-from-an-immutable-array-in-js)
- [Cannot test reducer: Cannot assign to read only property](https://github.com/reduxjs/redux-toolkit/issues/424)

### κ³Όμ° μ΄ λ°©λ²μ΄ μ΅μ μΈκ°?

- μ»΄ν¬λνΈ μ¬μ¬μ©μ μν΄ λ¦¬λμ€μ read-onlyμμ±μ μμ κ³  useStateλ₯Ό κ°κ° λ§λ€λ©΄μ μ¬μ©ν΄μΌλλ κ±΄μ§, λ€λ₯Έ λ μ’μ λ°©λ²μ μλμ§ μ°Ύμλ΄μΌ ν¨

### λ€μ μ§ν μμ 

- [ ] drag and dropμΌλ‘ array μμ λ³ν

</details>

<details>
<summary>2021.09.01(Tony)</summary>

### λΆλ³μ± λ³΄μ₯ νλ©΄μ arrayμμ μμ μ­μ  νκΈ°

```javascript
const arr = ['a', 'b', 'c', 'd', 'e'];

const indexToRemove = 2; // the 'c'

const result = [...arr.slice(0, indexToRemove), ...arr.slice(indexToRemove + 1)];

console.log(result);

// sliceλ ...arrλ₯Ό λλ²μ΄λ νλ λ²κ±°λ‘μμ΄ μμΌλ―λ‘
const textArray = [...textList];
textArray.splice(index, 1);
// λ°°μ΄ λ³΅μ¬ ν spliceλ₯Ό μ¬μ©
```

### typescript function type

- parameter νμ, return νμμ μ μν΄μ£Όλ©΄ λλ€.

```typescript
fn: (a: string) => void
```

### reduxλ₯Ό typescriptμμ μ¬μ©νλ©΄ initialStateλ μ λΆ μ΄κΈ°κ°μ΄ μμ΄μΌ λλ€.

- reducerμμ action.dataλ₯Ό λ°μμ λ£μ λ optional chainingμ μ¬μ©ν  μ μλ€κ³  λμ΄

### μ°Έκ³  λ¬Έν

- [typescript function type](https://www.typescriptlang.org/docs/handbook/2/functions.html)

</details>

<details>
<summary>2021.09.02(Tony)</summary>

## TextListBox delete button

### High order function μ μ©

- HOFλ‘ λ°κΏλ μ»΄ν¬λνΈμ ν¨μνμμ κ·Έλλ‘ μ μ©ν΄λ μ μ©λ¨
- [ ] HOFμ μμλ₯Ό λ μ°Ύμλ³΄κ³  μ₯μ μ μμλ³΄κΈ°

### λ²κ·Έ μμ 

- `μ΄λ° λΆλ€μκ² μΆμ²ν΄μ` μμ TextListBoxλ₯Ό μ¬μ©ν  λ list arrayλ₯Ό expectedStudentsκ° μλ whatYouCanLearnμΌλ‘ μ€νκ° μλ λΆλΆμ μμ ν¨

</details>

<details>
<summary>2021.09.05(NOAH)</summary>

## νμκ°μ error λ©μμ§

- err.response.dataμ μλ²μμ λ°μμ¨ μλ¬ λ©μμ§κ° μμ
- AxiosError typescript μ²λ¦¬

```typescript
onError: (err: AxiosError) => {
  console.error(err.response?.data);
};
```

- useInput μ»€μ€ν ν nodebird κ°μμμ κ°μ Έμ΄

```typescript
import { ChangeEvent, Dispatch, SetStateAction, useCallback, useState } from 'react';

type ReturnType<T = any> = [T, (e: ChangeEvent<HTMLInputElement>) => void, Dispatch<SetStateAction<T>>];

const useInput = <T>(initialData: T): ReturnType<T> => {
  const [value, setValue] = useState(initialData);

  const handler = useCallback((e: ChangeEvent<HTMLInputElement>) => {
    setValue(e.target.value as unknown as T);
  }, []);

  return [value, handler, setValue];
};

export default useInput;
```

## κ΅¬ν ν  κ²

- λΉλ°λ²νΈ μ°ΎκΈ° λͺ¨λ¬
- κ°νΈ νμκ°μ
- κ°νΈ λ‘κ·ΈμΈ

</details>

<details>
<summary>2021.09.14(NOAH)</summary>

## λΉλ°λ²νΈ μ°ΎκΈ° Modal κ΅¬ν (Portal μ¬μ©)

- \_document.js νμ΄μ§μ Modalμ λ£μ div tag μΆκ°

```html
<html lang="en">
  <head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap" />
  </head>
  <body>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=default%2Ces2015%2Ces2016%2Ces2017%2Ces2018%2Ces2019" />
    <main />
    <NextScript />
    <div id="find-password-modal" />
  </body>
</html>
```

- Portal wrapper μΆκ°

```typescript
export default function Portal({ children, selector }: IProps) {
  const [mounted, setMounted] = useState(false);

  useEffect(() => {
    setMounted(true);
    return () => setMounted(false);
  }, []);

  // eslint-disable-next-line @typescript-eslint/no-non-null-assertion
  return mounted ? createPortal(children, document.querySelector(selector)!) : null;
}
```

- Contentκ° λλ component μΆκ°
- λΉλ°λ²νΈ μ°ΎκΈ° λ²νΌμ λ°λΌ showFindPasswordModal useState λ³μμ booleanκ°μ λ³κ²½νμ¬ μ μ΄

```typescript
{
  showFindPasswordModal && (
    <Portal selector="#find-password-modal">
      <FindPasswordModal handleCloseModal={handleCloseFindPasswordModal} />
    </Portal>
  );
}
```

## κ΅¬ν ν  κ²

- λ°±μλμͺ½μ Routerκ° κ΅¬νλ ν API μ°κ²° νμ€νΈλ₯Ό ν΄μΌ ν¨

</details>

<details>
<summary>2021.09.19(λν)</summary>

## κ΅¬νν κ²

- κ°μ νμ΄μ§ λ μ΄μμμ λλ΅μ μΌλ‘ κ΅¬ν
- κ°μ μΉ΄νκ³ λ¦¬μ νν°(λμ΄λ, μ Β·λ¬΄λ£ μ ν, μ¨λΌμΈ/μ€νλΌμΈ)λ₯Ό κ°κ° CategoryMenu μ»΄ν¬λνΈμ LectureFilter μ»΄ν¬λνΈλ‘ λΆλ¦¬
- κ°μ κ²μνκΈ° λΆλΆ λμμΈ κ΅¬ν
  - μΈνλ° CSS μ°Έκ³ ν¨.

## μμΌλ‘ μ§νν  μμ

- λλ―Έλ°μ΄ν°λ‘ κ°μ λ¦¬μ€νΈ λνλ΄κΈ°
- μΉ΄λ μ λ ¬ μ€νμΌμ μ ννλ Gridμ List λ²νΌ κ΅¬ννκΈ°

</details>

<details>
<summary>2021.09.13~19.(Tony)</summary>

## κ°μ μμ± λΆ drag and drop

![](https://images.velog.io/images/gth1123/post/f3f4e477-405e-428d-a5c9-2d931999fa2d/dragAndDrop.gif)

javascriptλ‘ μ§μ  κ΅¬ννλ € νμΌλ μ λλ©μ΄μλ°λ λμ€ DOMμ λ³κ²½νκ±°λ
(DOM μμΉκ° λ°λλ©΄ μ λλ©μ΄μμ΄ λ°λ μμΉλ₯Ό κΈ°μ€μΌλ‘ λμνκΈ° λλ¬Έμ κ³μ°μ΄ μ΄λ ΅λ€)
μ λλ©μ΄μμ΄ λλκΈ° μ μ μ λλ©μ΄μμ λμ°©μ§μ μ λ³κ²½νλ κ²μ΄ μ΄λ €μμ λΌμ΄λΈλ¬λ¦¬λ₯Ό μ¬μ©νκΈ°λ‘ νλ€

### sortablejs vs react-sortable-hoc vs react dnd

#### sortablejs

- Weekly Downloads : μ½ 80λ§
- μλ°μ€ν¬λ¦½νΈμμ μ¬μ©νκΈ° μν΄μ λ§λ€μ΄μ§ λΌμ΄λΈλ¬λ¦¬
- [sortablejs μμ ](http://sortablejs.github.io/Sortable/#simple-list)
- react-sortablejsλ₯Ό μ¬μ©νλ©΄ λ¦¬μ‘νΈμμλ νΈνκ² μ¬μ©κ°λ₯
  - Weekly Downloads : μ½ 8λ§

#### react-sortable-hoc

- Weekly Downloads : μ½ 46λ§
- μμ κ° μ λμ΄μλ€
- [react-sortable-hoc μμ ](http://clauderic.github.io/react-sortable-hoc/#/basic-configuration/basic-usage?_k=mpdxwt)

#### react dnd

- Weekly Downloads : μ½ 81λ§
- drag and drop react λΌμ΄λΈλ¬λ¦¬ μ€ κ°μ₯ λ§μ΄ μ¬μ©λλ€

#### μ μ  κΈ°μ€

- inflearn μ λλ©μ΄μκ³Ό κ°μ₯ μ μ¬ν κ²
- sortablejsκ° κ±°μ λκ°κ³  λλ¨Έμ§ mouseup κ³Ό mousedownμμ μ λλ©μ΄μμ΄ μ΄λλλ λ°©μμ΄μλ€(drag apiλ₯Ό μ¬μ©νμ§ μλ κ²μΌλ‘ λ³΄μ)

### react-sortablejs

```
npm install --save react-sortablejs sortablejs
npm install --save-dev @types/sortablejs
```

- force flagλ₯Ό μ¬μ©ν΄μ μ€μΉλ₯Ό νλ€.

- [npm cli flag: ` force` and ` legacy peer deps`](https://github.com/Ark-inflearn/inflearn-clone-front/wiki/npm-cli-flag:-%60--force%60-and-%60--legacy-peer-deps%60)

#### key !== index

DO NOT use the index as a key for your list items. Sorting will not work.

In all the examples above, I used an object with an ID. You should do the same!

I may even enforce this into the design to eliminate errors.

### type λ³κ²½ λ° μ€μ 

- [x] lectureData?.courseInfoμ μν λ°°μ΄ whatYouCanLearn, expectedStudents, requiredKnowledge νμλ³κ²½
  - string[] -> {name: string, order: number}[]
- [x] ReactSortable(sortablejs λΌμ΄λΈλ¬λ¦¬ μ»΄ν¬λνΈ)μ props type λ§κ² μ€μ 

### redux κ΄λ ¨ μΈν

- [x] λλκ·Έ μ€ λλ ν μ μ₯ λ²νΌ λλ₯΄λ©΄ λ³κ²½λ μμλ‘ λ³΄λ΄κΈ°(saga)
- [x] μ€κ° μ μ₯νλ©΄μ sagaμμ orderλ₯Ό λ΄κ° λ³κ²½ν΄μ λ³΄λ΄μ£Όλκ² λ§λκ±΄μ§ μκ°ν΄λ³΄κΈ°

  - κ·Έλ₯ νλ‘ νΈμμ λ³κ²½λ orderλ‘ λ³΄λ΄μ£Όμ - λμ€μ λ°±μλλ κ°μ΄ κ³ λ―Όν΄λ΄μΌ ν¨

- delete μμ΄μ½ ν΄λ¦­νλ©΄ μ­μ νλ λ°©μ λ³κ²½
  - κΈ°μ‘΄ : reducerμμ storeμ μλ κ²μ λ°λ‘ μ­μ 
  - λ³κ²½ : storeμ μλ κ²μ κ±΄λ€μ§ μκ³  useStateλ‘ μμλ‘ μ μ₯ ν μ­μ  λλ μμμ λ³κ²½μ ν΄λΉ νμ΄μ§μμ μ€κ°μ μ₯ λ²νΌμ λλ₯΄λ©΄ μλ²μ λ°μλλλ‘ λ³κ²½
    - λ³κ²½λ μμλ μλ‘κ³ μΉ¨μ νλ©΄ λ€μ μλ²μμ λ³κ²½ λ°μ΄ν°λ₯Ό storeμ μ μ₯νλ λ°©μ
    - storeλ μλ²μμ λ°μ μ λ³΄λ§μ μ μ₯
    - react-sortablejsμμ μ¬μ©νλ λ°©μκ³Ό λ§μΆλ κ²

## Things to do on this page

- [ ] μΉ΄νκ³ λ¦¬, κ°μ μμ€ λ§λ€κΈ°
- [x] μ€κ° μ μ₯λ²νΌκ³Ό redux, saga μ°κ²°νκΈ°
</details>

<details>
<summary>2021.09.19 ~ 20.(Tony)</summary>

## μΆκ° νκΈ° λ²νΌ κΈ°λ₯ κ΅¬ν

- μΆκ°νκΈ°λ₯Ό λλ₯΄λ©΄ storeκ° μλ setStateμμ λ³κ²½
  - redux storeμ μ§μ  λ³κ²½νμ§ μλ μ΄μ λ react-sortablejsμμ useStateλ₯Ό μ¬μ©νκΈ° λλ¬Έ

```typescript
// ReactSortable μ»΄ν¬λνΈμμ setList μμ±μ setStateκ° λ€μ΄κ°μΌ ν¨
<ReactSortable list={expectedStudents} setList={setExpectedStudents} animation={200} handle=".handle">
  {expectedStudents.map((item, index) => (
    <TextListBox key={item.id} item={item} list={expectedStudents} setList={setExpectedStudents} index={index} />
  ))}
</ReactSortable>
```

</details>
