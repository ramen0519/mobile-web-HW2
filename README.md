# Markdown 사용법 실습

## Markdown이란?

Markdown은 간단한 문법을 사용하여 문서의 구조와 서식을 표현할 수 있는 마크업 언어이다.  
확장자는 `.md`를 사용하며 GitHub의 README 파일이나 프로젝트 문서 작성 등에 많이 사용된다.

이번 실습에서는 Markdown에서 사용할 수 있는 기본적인 기능과 작성 방법을 직접 확인해 보았다.

---

## 1. 제목

`#` 기호를 사용하여 제목을 표현할 수 있다.  
`#`의 개수에 따라 제목의 크기가 달라진다.

### 작성 문법

```markdown
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
```

### 결과

# 제목 1
## 제목 2
### 제목 3
#### 제목 4

---

## 2. 글자 강조

특정 문장을 굵게 표시하거나 기울임, 취소선 등의 효과를 적용할 수 있다.

### 작성 문법

```markdown
**굵은 글씨**

*기울임 글씨*

~~취소선~~
```

### 결과

**굵은 글씨**

*기울임 글씨*

~~취소선~~

---

## 3. 목록

순서가 없는 목록과 순서가 있는 목록을 작성할 수 있다.

### 작성 문법

```markdown
- Python
- Java
- C++

1. Markdown 파일 작성
2. GitHub Repository 생성
3. 파일 업로드
```

### 결과

- Python
- Java
- C++

1. Markdown 파일 작성
2. GitHub Repository 생성
3. 파일 업로드

---

## 4. 표

`|`와 `-` 기호를 이용하여 표를 작성할 수 있다.

### 작성 문법

```markdown
| 분야 | 사용 기술 |
| --- | --- |
| AI | Python |
| Backend | Java |
| Robotics | C++ |
```

### 결과

| 분야 | 사용 기술 |
| --- | --- |
| AI | Python |
| Backend | Java |
| Robotics | C++ |

---

## 5. 코드

백틱(`)을 사용하면 코드나 명령어를 다른 문장과 구분하여 표현할 수 있다.

한 줄의 코드는 다음과 같이 작성한다.

### 작성 문법

```markdown
`print("Hello Markdown!")`
```

### 결과

`print("Hello Markdown!")`

여러 줄의 코드는 코드 블록을 이용하여 작성할 수 있다.

### 작성 문법

````markdown
```python
def hello():
    print("Hello Markdown!")

hello()
```
````

### 결과

```python
def hello():
    print("Hello Markdown!")

hello()
```

---

## 6. 링크

대괄호 `[ ]`와 소괄호 `( )`를 이용하여 웹 사이트의 링크를 추가할 수 있다.

### 작성 문법

```markdown
[GitHub](https://github.com)
```

### 결과

[GitHub](https://github.com)

---

## 7. 인용문

`>` 기호를 사용하면 특정 문장을 인용문의 형태로 표현할 수 있다.

### 작성 문법

```markdown
> Markdown은 간단한 문법으로 문서를 작성할 수 있다.
```

### 결과

> Markdown은 간단한 문법으로 문서를 작성할 수 있다.

---

## 8. 체크박스

체크박스를 사용하여 할 일이나 진행 상태를 표시할 수 있다.

### 작성 문법

```markdown
- [x] Markdown 사용법 조사
- [x] README.md 작성
- [ ] GitHub 업로드
- [ ] 결과 화면 캡처
```

### 결과

- [x] Markdown 사용법 조사
- [x] README.md 작성
- [ ] GitHub 업로드
- [ ] 결과 화면 캡처

---

## 9. 구분선

하이픈 `---`을 사용하면 내용 사이에 구분선을 추가할 수 있다.

### 작성 문법

```markdown
---
```

### 결과

---

