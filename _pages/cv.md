<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>CV</title>
    <style>
        /* 页面整体的基本设置 */
        body {
            font-family: 'Arial', sans-serif;  /* 使用简洁的无衬线字体 */
            background-color: #ffffff;         /* 白色背景 */
            color: #333333;                    /* 深灰色字体，易读 */
            line-height: 1.8;                  /* 行距适中，增加可读性 */
            margin: 0;
            padding: 0;
        }

        /* 页面容器 */
        .container {
            max-width: 800px;                  /* 页面最大宽度 */
            margin: 0 auto;                    /* 居中 */
            padding: 20px;                     /* 增加边距 */
        }

        /* 主标题样式 */
        h1 {
            font-size: 28px;                   /* 主标题字体大小 */
            color: #333333;                    /* 深灰色字体，不使用黑色 */
            text-align: center;                /* 居中对齐 */
            margin-bottom: 30px;               /* 标题下方留白 */
        }

        /* 二级标题样式 */
        h2 {
            font-size: 22px;                   /* 二级标题字体稍小 */
            color: #555555;                    /* 更浅的灰色，避免太过沉重 */
            margin-top: 40px;                  /* 标题上方留白 */
            margin-bottom: 15px;
            border-bottom: 1px solid #e0e0e0;  /* 增加浅灰色底边，保持分层 */
            padding-bottom: 5px;
        }

        /* 列表样式 */
        ul {
            list-style-type: none;             /* 移除项目符号 */
            padding-left: 0;                   /* 无左侧内边距 */
        }

        li {
            margin-bottom: 10px;               /* 每个列表项之间增加间距 */
        }

        /* 时间段样式，文本颜色与正文保持一致 */
        .timeline {
            color: #333333;                    /* 使用与正文一致的深灰色 */
            margin-right: 5px;                 /* 与内容保持适当间距 */
        }

        /* 表格样式 */
        table {
            width: 100%;                       /* 表格宽度 100% */
            border-collapse: collapse;         /* 移除表格间距 */
            margin-bottom: 20px;               /* 表格下方留白 */
        }

        th, td {
            text-align: left;                  /* 左对齐 */
            padding: 10px;                     /* 表格单元格内边距 */
            border-bottom: 1px solid #e0e0e0;  /* 添加浅灰色边框 */
        }

        th {
            background-color: #f9f9f9;         /* 表头背景为浅灰色 */
            font-weight: bold;                 /* 表头加粗 */
        }

        /* 响应式设计：适用于小屏幕 */
        @media (max-width: 768px) {
            h1 {
                font-size: 24px;               /* 小屏幕下缩小标题字体 */
            }

            h2 {
                font-size: 20px;               /* 缩小二级标题字体 */
            }

            .container {
                padding: 15px;                 /* 小屏幕下减少内边距 */
            }

            th, td {
                font-size: 14px;               /* 缩小表格字体 */
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>CV</h1>

        <h2>Education</h2>
        <ul>
            <li><span class="timeline">2017–2022:</span> Ph.D. in Hydraulic Structure Engineering, Wuhan University</li>
            <li><span class="timeline">2021–2022:</span> Visiting Ph.D. in Geotechnical Engineering, National University of Singapore</li>
            <li><span class="timeline">2013–2017:</span> B.E. in Water Resources & Hydropower Engineering, Northwest A&F University</li>
        </ul>

        <h2>Work Experience</h2>
        <ul>
            <li><span class="timeline">2022–Present:</span> Postdoc Fellow, The Hong Kong Polytechnic University</li>
        </ul>

        <h2>Selected Awards</h2>
        <ul>
            <li><span class="timeline">10/2024:</span> PolyU Distinguished PDFs, The Hong Kong Polytechnic University</li>
            <li><span class="timeline">03/2024:</span> Hubei Provincial Science & Technology Progress Award (2023年湖北省科学技术进步奖), Hubei Provincial People's Government, China</li>
            <li><span class="timeline">12/2023:</span> Academic Innovation Award, Wuhan University</li>
            <li><span class="timeline">10/2022:</span> Centrally Funded Postdoctoral Fellowship, The Hong Kong Polytechnic University</li>
            <li><span class="timeline">06/2022:</span> Outstanding Graduate Award, Wuhan University</li>
            <li><span class="timeline">03/2021:</span> Excellence in Teaching Award, Wuhan University</li>
            <li><span class="timeline">10/2020:</span> Top 10 Academic Star, Wuhan University (University-wide, only 10 recipients)</li>
            <li><span class="timeline">12/2019:</span> YuGang & SongXiao Scholarship, Wuhan University (Top 1%, University-wide)</li>
            <li><span class="timeline">10/2019:</span> Second Prize, Graduate Academic Report Competition, 10th National Youth Conference on Geomechanics & Geotechnical Engineering, Chinese Institution of Soil Mechanics and Geotechnical Engineering</li>
            <li><span class="timeline">06/2019:</span> First Prize, 12th Civil Engineering & Mechanics Graduate Academic Forum, Wuhan University</li>
            <li><span class="timeline">04/2019:</span> Second Prize, Doctoral Academic Forum, Tsinghua University</li>
            <li><span class="timeline">12/2018:</span> Excellent Student Cadre, Wuhan University Outstanding Graduate Student, Wuhan University</li>
            <li><span class="timeline">09/2018:</span> First Class Scholarship, Wuhan University</li>
            <li><span class="timeline">12/2017:</span> Excellent New Student Award, Wuhan University</li>
            <li><span class="timeline">12/2016:</span> National Scholarship, Ministry of Education of the People's Republic of China</li>
            <li><span class="timeline">07/2016:</span> Top 10 Future Star Undergraduate, Ministry of Education of the People's Republic of China (Nationwide, only 10 recipients)</li>
        </ul>

        <h2>Research Fundings</h2>
        <table>
            <thead>
                <tr>
                    <th>Project</th>
                    <th>Funding Period</th>
                    <th>Funding Amount</th>
                    <th>Role</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Thermo-hydro-mechanical (THM) modelling for artificial ground freezing technique</td>
                    <td>01/2023 – 12/2024</td>
                    <td>HK$ 763,555</td>
                    <td>Principal Investigator (PI)</td>
                </tr>
                <tr>
                    <td>Physics-informed multi-fidelity neural network approach for intelligent rectification of shield machine attitude in layered soils</td>
                    <td>01/2024 – 12/2026</td>
                    <td>HK$ 1,132,781</td>
                    <td>Main Participant</td>
                </tr>
                <tr>
                    <td>Study of multi-physics coupling mechanism of deep sea pipeline and soft marine organic deposits interaction, considering time and temperature effects</td>
                    <td>01/2021 – 12/2024</td>
                    <td>HK$ 1,154,954</td>
                    <td>Main Participant</td>
                </tr>
                <tr>
                    <td>Seepage failure mechanism and risk control of earth-rockfill dams considering spatial variability of geomaterials</td>
                    <td>09/2020 – 01/2022</td>
                    <td>CNY¥ 580,000</td>
                    <td>Co-Investigator</td>
                </tr>
                <tr>
                    <td>Risk assessment for tunnel-induced subsidence under complex geological conditions using big data analysis</td>
                    <td>01/2018 – 07/2021</td>
                    <td>CNY¥ 4,100,000</td>
                    <td>Co-Investigator</td>
                </tr>
            </tbody>
        </table>
    </div>

</body>
</html>
