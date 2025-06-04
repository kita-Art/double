더블 보더 레디어스 애니메이션 (Double Border-Radius Animation)
🚀 프로젝트 소개
이 프로젝트는 CSS border-radius 속성을 불규칙하게 사용하여 독특한 유기적인 모양을 만들고, 여기에 애니메이션과 호버(hover) 효과를 적용하여 동적인 디자인을 구현한 웹 페이지입니다. 각 카드에 마우스를 올리면 배경색이 바뀌고 테두리가 사라지면서 시각적인 인터랙션을 제공합니다.

✨ 주요 기능
유기적인 도형 디자인: border-radius의 다양한 값을 활용하여 물방울이나 세포 같은 독특한 형태의 박스 디자인.
회전 애니메이션: CSS @keyframes와 animation 속성을 사용하여 각 도형이 독립적으로 회전하는 효과.
인터랙티브 호버 효과: 마우스 오버 시 도형의 배경색이 변경되고 테두리가 사라지는 동적인 시각 효과.
반응형 레이아웃: flexbox를 사용하여 여러 개의 카드가 화면 크기에 따라 유연하게 배치됩니다.
🛠️ 기술 스택
HTML5: 웹 페이지 구조 및 콘텐츠 마크업
CSS3: 스타일링 및 애니메이션 (position, border-radius, transform, @keyframes, flexbox 등)
Google Fonts: 'Raleway' 폰트 사용
🖥️ 사용 방법
이 저장소를 클론(Clone)하거나 다운로드합니다.
Bash

git clone https://github.com/당신의-깃허브-아이디/더블-보더-레디어스-애니메이션.git
다운로드된 폴더로 이동합니다.
index.html 파일을 웹 브라우저에서 엽니다.
📂 파일 구조
더블-보더-레디어스-애니메이션/
├── index.html
└── style.css
💡 코드 하이라이트
CSS

/* 유기적인 border-radius */
border-radius: 40% 60% 65% 35% / 40% 45% 55% 60% ;

/* 회전 애니메이션 */
@keyframes circle {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}
.square span {
    animation: circle 5s linear infinite;
}

/* 호버 시 배경색 변경 및 테두리 제거 */
.square:nth-child(1):hover span {
    background-color: crimson;
    border: none;
}
🤝 기여 방법 (Contributing)
이 프로젝트에 기여하고 싶으시다면, 언제든지 환영합니다!

이 저장소를 Fork 해주세요.
새로운 기능이나 버그 수정 사항을 담은 브랜치를 생성합니다. (git checkout -b feature/your-feature-name)
변경 사항을 커밋하고 푸시합니다. (git commit -m 'feat: Add new feature')
Pull Request를 생성해주세요.
📄 라이선스
이 프로젝트는 MIT License를 따릅니다.

📞 문의
