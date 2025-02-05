<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Links</title>
    <style>
        .category {
            margin-bottom: 20px;
        }
        .category a {
            text-decoration: none;
            color: inherit;
        }
        .category a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="category">
        <h2>👩🏿 Education</h2>
        <p>Graduate from 2 programs from ALX, founder program and backend software engineering.</p>
        <ul>
            <li><a href="#" onclick="downloadImage('Founder Academy.png')">ALX Founder</a></li>
            <li><a href="#" onclick="downloadImage('Short Specializations.png')">Backend</a></li>
        </ul>
    </div>

    <div class="category">
        <h2>Frontend Skills</h2>
        <p>
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3">
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
            <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
            <a href="https://www.behance.net/kamoellenkganakga" target="_blank">
                <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white" alt="Figma">
            </a>
        </p>
    </div>

    <div class="category">
        <h2>Backend Skills</h2>
        <p>
            <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
            <img src="https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white" alt="C#">
            <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white" alt="C++">
            <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black" alt="C">
            <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js">
        </p>
    </div>

    <div class="category">
        <h2>Tools</h2>
        <p>
            <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
            <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
            <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white" alt="VS Code">
        </p>
    </div>

    <script>
        function downloadImage(imageName) {
            const link = document.createElement('a');
            link.href = imageName;
            link.download = imageName;
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);
        }
    </script>

</body>
</html>
