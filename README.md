<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Amazing Projects</title>
    <style>
        /* 제목 크기 조정 */
        h1 {
            font-size: 28px !important;
        }
        
        h2 {
            font-size: 28px !important;
        }
        
        h3 {
            font-size: 18px !important;
        }
        
        /* 기본 스타일 */
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            line-height: 1.6;
            color: #333;
            margin: 0;
            padding: 20px;
            background-color: #f8f9fa;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            padding: 40px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        
        .project-image {
            transition: transform 0.3s ease;
        }
        
        .project-image:hover {
            transform: scale(1.02);
        }
        
        table {
            width: 100%;
            border-collapse: collapse;
        }
        
        td {
            vertical-align: top;
            padding: 20px;
        }
        
        .badge {
            display: inline-block;
            margin: 2px;
        }
        
        .demo-button {
            margin: 5px;
            text-decoration: none;
        }
        
        .center {
            text-align: center;
        }
        
        .tech-stack {
            margin: 10px 0;
        }
        
        .achievements {
            margin: 15px 0;
            text-align: left;
            display: inline-block;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="center">
            <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=My%20Amazing%20Projects&fontSize=45&animation=fadeIn&fontAlignY=35&desc=Click%20to%20explore%20each%20project&descAlignY=51&descAlign=62" />
        </div>

        <h2>✨ Main Project</h2>

        <div class="center">
            <a href="https://riskkiller.streamlit.app/">
                <img src="riskkiller.png" alt="Risk Killer" class="project-image" width="85%">
            </a>
            
            <br><br>
            
            <h3>🎯 Risk Killer</h3>
            <p><sub>FDA 데이터 기반, 미국 식품 시장 규제 준수 및 위험 관리 통합 솔루션</sub></p>
            <br>
            
            <div class="tech-stack">
                <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" class="badge" />
                <img src="https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" class="badge" />
                <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" class="badge" />
                <img src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white" class="badge" />
                <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" class="badge" />
            </div>
            
            <div class="achievements">
                <strong>🎯 핵심 성과:</strong><br>
                • FDA 데이터 크롤링 및 정제<br>
                • 고급 RAG 챗봇 구현<br>
                • Tableau 기반 시장 동향 시각화<br>
                • AI 요약 및 데이터 추출<br>
                • 올인원 솔루션 제공
            </div>
            
            <p>
                <a href="https://riskkiller.streamlit.app/" class="demo-button">
                    <img src="https://img.shields.io/badge/🔗_Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
                </a>
                <a href="./toilet_analysis_report.pdf" class="demo-button">
                    <img src="https://img.shields.io/badge/📄_Report-DC143C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
                </a>
            </p>
        </div>

        <br><br>

        <h2>🎨 More Works</h2>

        <div class="center">
            <table>
                <tr>
                    <td width="50%" class="center">
                        <a href="https://miniproject-jr8xxsqb9p6kt67sspri2d.streamlit.app/">
                            <img src="class_0520.png" alt="네이버 블로그 분석 시스템" class="project-image" width="95%">
                        </a>
                        <h3>🔍 AI 기반 네이버 블로그 분석 시스템</h3>
                        <p><sub>협찬 글 범람 시대, 객관적 정보만 추출하는 스마트 솔루션</sub></p>
                        <br>
                        
                        <div class="tech-stack">
                            <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/Naver_API-03C75A?style=flat-square&logo=naver&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" class="badge" />
                        </div>
                        
                        <div class="achievements">
                            <strong>🎯 핵심 성과:</strong><br>
                            • 분석 시간 단축<br>
                            • 최대 100개 블로그 동시 분석 자동화<br>
                            • AI 기반 광고성 콘텐츠 필터링<br>
                            • 6가지 관점별 맞춤 분석 (가격/성능/디자인 등)<br>
                            • 경쟁 제품 실시간 비교 분석 기능
                        </div>
                        
                        <p>
                            <a href="https://miniproject-jr8xxsqb9p6kt67sspri2d.streamlit.app/" class="demo-button">
                                <img src="https://img.shields.io/badge/🔗_Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
                            </a>
                            <a href="review_photofolio2.pdf" class="demo-button">
                                <img src="https://img.shields.io/badge/📄_Report-DC143C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
                            </a>
                        </p>
                    </td>
                    <td width="50%" class="center">
                        <a href="https://toiletprojectlfs-ynkzmvwgtayrtclo8ikz5a.streamlit.app/">
                            <img src="toilet.png" alt="서울시 화장실 수급 현황 분석" class="project-image" width="95%">
                        </a>
                        <h3>🚻 서울시 화장실 수급 현황 분석</h3>
                        <p><sub>데이터로 풀어보는 도시 인프라 불평등 문제</sub></p>
                        <br>
                        
                        <div class="tech-stack">
                            <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" class="badge" />
                            <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" class="badge" />
                        </div>
                        
                        <div class="achievements">
                            <strong>🎯 핵심 성과:</strong><br>
                            • 여성 화장실 수급 부족 현상 통계적 검증<br>
                            • 화장실 수급 현황 정량화<br>
                            • 시간대별 화장실 대란 패턴 발굴<br>
                            • 지역별 우선순위 기반 정책 제안 도출<br>
                            • 수요 기반 수급 불균형 진단 로직 구축
                        </div>
                        
                        <p>
                            <a href="https://toiletprojectlfs-ynkzmvwgtayrtclo8ikz5a.streamlit.app/" class="demo-button">
                                <img src="https://img.shields.io/badge/🔗_Live_Demo-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
                            </a>
                            <a href="toilet_photofolio2.pdf" class="demo-button">
                                <img src="https://img.shields.io/badge/📄_Report-DC143C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
                            </a>
                        </p>
                    </td>
                </tr>
            </table>
        </div>

        <br><br>

        <div class="center">
            <h3>📫 Connect with Me</h3>
            <p>
                <a href="https://github.com/seungmin956">
                    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
                </a>
                <a href="mailto:seungminlee956@gmail.com">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
                </a>
            </p>
        </div>

        <br>

        <div class="center">
            <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" />
        </div>
    </div>
</body>
</html>
