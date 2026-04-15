# 📖 Anywaysoul92 / Study-Log

 
> 이 저장소는 HTML5와 CSS3의 핵심 메커니즘을 심층 학습하고, 실제 웹 레이아웃 구현 과정에서 발생하는 기술적 리스크를 관리하며 기록하는 공간입니다.

## 🛠 Tech Stack
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📂 Directory Structure (주요 파일 설명)

| File | Focus Area | Description |
| :--- | :--- | :--- |
| `box_model.html` | **Box Model** | Content, Padding, Border, Margin의 상호작용 및 박스 사이징 학습 |
| `display.html` | **Display** | Block vs Inline vs Inline-block 흐름 제어 및 특성 비교 |
| `flex.html` | **Flexbox** | 1차원 레이아웃 정렬(Main/Cross axis) 실습 |
| `position.html` | **Position** | Relative, Absolute, Fixed, Sticky의 기준점 및 스택 순서 실험 |
| `media_query.html` | **Responsive** | 브레이크포인트를 활용한 디바이스별 반응형 레이아웃 구현 |
| `resume.html` | **Project** | 웹 이력서 구현 |
| `todo.html` | **Project** | todo list 구현 |
| `timer.html` | **Project** | 카운트다운 구현 |

.. 등등 

기본 html CSS javascript 학습 및 실습 코드

---

## 📝 Learning Log & Troubleshooting

### **레이아웃 유지보수 및 리스크 관리**
* **유연한 단위 설계**: `px` 기반의 고정 너비는 다양한 해상도에서 레이아웃이 깨지는 치명적 리스크가 있습니다. 이를 방지하기 위해 `flex`의 `calc()`나 `%` 단위를 혼용하여 유연성을 확보했습니다.
* **시맨틱 마크업의 중요성**: `<div>` 과사용을 지양하고 `<header>`, `<main>`, `<section>` 등 의미 있는 태그를 사용하여 검색 엔진 최적화(SEO) 및 접근성을 고려한 마크업을 지향합니다.
  

---

**효율적인 CSS 작성은 단순히 예쁜 화면을 넘어, 코드의 재사용성을 극대화하고 브라우저의 렌더링 리스크를 최소화하는 것이 핵심입니다.**
