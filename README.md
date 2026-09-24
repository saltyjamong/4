<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>캐릭터 소개</title>
</head>

<!-- 메뉴 -->
<nav class="menu">
  <a href="#intro">INTRO</a>
  <a href="#relation">RELATION</a>
  <a href="#story">STORY</a>
</nav>


<!-- INTRO -->
<section id="intro" class="section">
  <h1>INTRO</h1>
  <p>캐릭터의 기본적인 소개를 적는 공간입니다.</p>
</section>


<!-- RELATION -->
<section id="relation" class="section">
  <h1>RELATION</h1>
  <p>{{user}}와 캐릭터의 관계를 적는 공간입니다.</p>
</section>


<!-- STORY -->
<section id="story" class="section">
  <h1>STORY</h1>
  <p>캐릭터의 배경과 이야기를 적는 공간입니다.</p>
</section>

<!-- INTRO 영역 -->
<section class="intro-section">

    <!-- 섹션 제목 -->
    <div class="intro-title">
        <span class="intro-number">01</span>
        <h2>INTRO</h2>
        <div class="intro-line"></div>
    </div>

    <!-- 인트로 내용 -->
    <div class="intro-content">

        <p class="intro-subtitle">
            CHARACTER INTRODUCTION
        </p>

        <div class="intro-text">
            <p>
                이곳에 캐릭터의 이야기를 작성해주세요.
            </p>

            <p>
                캐릭터가 어떤 인물인지, 어떤 상황에서
                이야기가 시작되는지 자유롭게 적을 수 있습니다.
            </p>

            <p>
                긴 문장을 작성해도 자연스럽게 이어지도록
                충분한 여백을 두었습니다.
            </p>
        </div>

    </div>

</section>


<style>

/* =========================
   INTRO SECTION
========================= */

.intro-section {
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
    padding: 140px 30px;
    box-sizing: border-box;
}


/* 제목 영역 */

.intro-title {
    display: flex;
    align-items: center;
    gap: 18px;
    margin-bottom: 60px;
}

.intro-number {
    font-family: "Arial", sans-serif;
    font-size: 13px;
    letter-spacing: 2px;
    color: #777;
}

.intro-title h2 {
    margin: 0;
    font-family: "Georgia", serif;
    font-size: 30px;
    font-weight: 400;
    letter-spacing: 5px;
    color: #111;
}

.intro-line {
    flex: 1;
    height: 1px;
    background: rgba(0, 0, 0, 0.2);
}


/* 본문 */

.intro-content {
    padding-left: 45px;
    padding-right: 45px;
}


/* 작은 제목 */

.intro-subtitle {
    margin: 0 0 35px 0;

    font-family: Arial, sans-serif;
    font-size: 11px;
    letter-spacing: 4px;

    color: #777;
}


/* 인트로 글 */

.intro-text {
    max-width: 750px;

    font-family: "Noto Sans KR", sans-serif;
    font-size: 15px;
    line-height: 2.2;

    color: #222;
}


/* 문단 */

.intro-text p {
    margin: 0 0 28px 0;
}


/* 첫 문단 강조 */

.intro-text p:first-child {
    font-size: 19px;
    line-height: 1.9;
    color: #111;
}


/* 모바일 */

@media (max-width: 600px) {

    .intro-section {
        padding: 100px 20px;
    }

    .intro-title {
        margin-bottom: 45px;
    }

    .intro-title h2 {
        font-size: 24px;
        letter-spacing: 3px;
    }

    .intro-content {
        padding-left: 10px;
        padding-right: 10px;
    }

    .intro-text {
        font-size: 14px;
        line-height: 2;
    }

    .intro-text p:first-child {
        font-size: 17px;
    }

}

</style>
  
<body>
    /* =========================
         CHARACTER INTRODUCTION
    ========================== */
    <section class="character-profile">
        <!-- CHARACTER INTRODUCTION -->
        <h1>Character Introduction</h1>
        <!-- 기본 정보 -->
        <div class="basic-info">
            <p>
                <strong>나이</strong>
                <span>00세</span>
            </p>
            <p>
                <strong>성별</strong>
                <span>남성 / 여성</span>
            </p>
        </div>
        <!-- 외형 -->
        <div class="profile-section">
            <h2>외형</h2>
            <p>
                캐릭터의 외형을 작성하는 공간입니다.
                머리카락, 눈동자, 체격, 피부색, 분위기,
                평소의 옷차림 등을 자유롭게 작성할 수 있습니다.
            </p>
        </div>
        <!-- 성격 -->
        <div class="profile-section">
            <h2>성격</h2>
            <p>
                캐릭터의 성격을 작성하는 공간입니다.
                평소 성격이나 말투, 행동 방식,
                다른 사람을 대하는 태도 등을 작성할 수 있습니다.
            </p>
        </div>
        <!-- 특징 -->
        <div class="profile-section">
            <h2>특징</h2>
            <p>
                캐릭터만의 특징을 작성하는 공간입니다.
                습관, 버릇, 특이한 행동, 능력,
                신체적 특징 등을 작성할 수 있습니다.
            </p>
        </div>
        <!-- 좋아하는 것 -->
        <div class="profile-section">
            <h2>좋아하는 것</h2>
            <ul>
                <li>좋아하는 것 1</li>
                <li>좋아하는 것 2</li>
                <li>좋아하는 것 3</li>
            </ul>
        </div>
        <!-- 싫어하는 것 -->
        <div class="profile-section">
            <h2>싫어하는 것</h2>
            <ul>
                <li>싫어하는 것 1</li>
                <li>싫어하는 것 2</li>
                <li>싫어하는 것 3</li>
            </ul>
        </div>
    </section>
</body>
</html>
