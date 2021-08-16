---
layout: post
title: "TIL"
subtitle: "[TIL]"
date: 
background: 
tag: [TIL, Github, Notion]
---
# TIL

## Today I Learned.

- React
    - 2021.08.16
        - Class로 Props 받을 때 : {this.props.propName}
        - Function으로 Props 받을 때 : 함수 파라미터로 props전달 → {props.propName}

            ![스크린샷 2021-08-16 오후 6.14.56.png](TIL%203ec87a85bd3a401d9b7ad5ddcdd954b8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.14.56.png)

            ![스크린샷 2021-08-16 오후 6.12.43.png](TIL%203ec87a85bd3a401d9b7ad5ddcdd954b8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.12.43.png)

            ---

            - Hook → function을 class처럼 사용하기 위해 (class에서는 내부 함수 bind(this)때문에 불편..)

                : 이름이 use로 시작 ex) useState..

                - useState → 2개의 값으로 이루어진 배열이 리턴됨

                    : 첫번째 값(0번째 인덱스)이 원하는 State값

                    ![스크린샷 2021-08-16 오후 6.26.21.png](TIL%203ec87a85bd3a401d9b7ad5ddcdd954b8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.26.21.png)

                    : 두번째 값이 state를 변경하기 위한 **함수** 

                    → 인자에 변경하기로 원하는 값 전달 ex) setNumber(Math.random())

                    ![스크린샷 2021-08-16 오후 6.31.25.png](TIL%203ec87a85bd3a401d9b7ad5ddcdd954b8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.31.25.png)

                    : 아래와 같이 많이 사용

                    → _date에는 state값, setDate에는 state를 변경하기 위한 함수

                    ![스크린샷 2021-08-16 오후 6.35.28.png](TIL%203ec87a85bd3a401d9b7ad5ddcdd954b8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2021-08-16_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.35.28.png)

-
