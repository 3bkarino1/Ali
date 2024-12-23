<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بورتفوليو علي حاتم</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #00bcd4;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: #03a9f4;
        }

        header {
            background: linear-gradient(135deg, #1c1c1c, #2196f3);
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            margin: 0 15px;
            font-size: 1.1rem;
            font-weight: bold;
            color: #b3e5fc;
        }

        nav a:hover {
            color: #81d4fa;
        }

        main {
            max-width: 1000px;
            margin: 30px auto;
            padding: 20px;
            background: #1e1e1e;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.7);
        }

        section {
            margin-bottom: 40px;
        }

        h2 {
            font-size: 2rem;
            color: #81d4fa;
            margin-bottom: 15px;
            position: relative;
        }

        h2::after {
            content: '';
            display: block;
            width: 60px;
            height: 3px;
            background: #81d4fa;
            margin-top: 5px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            background: #3c4a60;
            margin: 10px 0;
            padding: 15px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            gap: 10px;
            border-left: 5px solid #03a9f4;
            transition: transform 0.2s;
        }

        ul li:hover {
            transform: scale(1.05);
        }

        .btn {
            display: inline-block;
            background: #03a9f4;
            color: #121212;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            font-size: 1rem;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #0288d1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.2rem;
            }

            nav a {
                margin: 0 10px;
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>علي حاتم</h1>
        <p>محرر فيديو ومطور برمجيات طموح</p>
        <nav>
            <a href="#about">عنّي</a>
            <a href="#contact">اتصل بي</a>
            <a href="#skills">المهارات</a>
            <a href="#education">التعليم</a>
            <a href="#projects">المشاريع</a>
            <a href="#awards">الجوائز</a>
            <a href="#hobbies">الهوايات</a>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>عنّي</h2>
            <p>
                علي حاتم، طالب في السنة الثانية من المدرسة الإعدادية من السويس، مصر، هو شخص مبدع وطموح ذو شغف قوي بالابتكار والتكنولوجيا. حصل على العديد من الجوائز، بما في ذلك المركز الأول في مسابقة Seaperch شمال أفريقيا (2023) والمركز الثالث في مسابقة Talent Bil Arabi (2021).
                علي لديه مهارات عالية في تحرير الفيديو، تصميم الشعارات، وإنشاء إعلانات السوشيال ميديا باستخدام أدوات احترافية مثل Adobe Premiere Pro وCanva وCapCut. كما أن لديه خبرة في البرمجة وتصميم وتطوير المواقع باستخدام JavaScript وHTML وCSS.
                مع اهتمام عميق بالذكاء الاصطناعي والبرمجة، يواصل علي تعزيز مهاراته في إدارة المشاريع والقيادة. من بين مشاريعه الشخصية المميزة هي Galaxy Wonders وWonders of Egypt وDecode Academy وDino World.
            </p>
        </section>

        <section id="contact">
            <h2>اتصل بي</h2>
            <p>📱 +20 1234567891</p>
            <p>📍 السويس، مصر</p>
            <p>✉️ <a href="mailto:example@gmail.com">example@gmail.com</a></p>
        </section>

        <section id="skills">
            <h2>المهارات التقنية</h2>
            <ul>
                <li>لغات البرمجة: JavaScript, HTML, CSS</li>
                <li>CapCut</li>
                <li>Canva</li>
                <li>Adobe Premiere Pro</li>
                <li>Notion</li>
                <li>Google Slides</li>
                <li>Microsoft PowerPoint</li>
            </ul>
        </section>

        <section id="education">
            <h2>التعليم</h2>
            <p>طالب في السنة الثانية من المدرسة الإعدادية، لا زلت أدرس.</p>
            <ul>
                <li>مدرسة أحمد زويل</li>
                <li>مدارس فتية الإسلام الخاصة</li>
            </ul>
        </section>

        <section id="projects">
            <h2>المشاريع الشخصية</h2>
            <ul>
                <li>Galaxy Wonders</li>
                <li>Wonders of Egypt</li>
                <li>Decode Academy</li>
                <li>Dino World</li>
                <li>Enviroment Friend</li>
                <li>Smart Home</li>
                <li>Helper</li>
                <li>Monorail App (For competition)</li>
                <li>A decent life App (For competition)</li>
                <li>100 million health App (For competition)</li>
            </ul>
        </section>

        <section id="awards">
            <h2>الجوائز والشهادات</h2>
            <ul>
                <li>المركز الرابع - شمال أفريقيا في مسابقة SeaPerch 2024.</li>
                <li>المركز الأول - الشرق الأوسط في مسابقة CoSpace Autonomous.</li>
                <li>المركز العاشر - على المستوى الوطني في مسابقة المبدع الصغير 2023.</li>
                <li>المركز الأول - على المستوى الوطني في مسابقة Creative Child 2020.</li>
                <li>المركز الأول - على مستوى الإدارات والمديريات في مسابقة المبدع الصغير 2022.</li>
                <li>المركز الثاني - على المستوى الوطني في مسابقة Maze Runner JR 2019.</li>
                <li>المركز الأول - على مستوى المحافظة في مسابقة "التطوير والتغيير" 2024.</li>
                <li>المركز الثاني - على مستوى المحافظة في مسابقة RC EGYPT 2020.</li>
                <li>المركز الأول - على المستوى الوطني في مسابقة RC EGYPT 2021.</li>
                <li>المركز الأول - على مستوى المحافظة في مسابقة المبتكر الشاب 2020.</li>
                <li>المركز الأول - شمال أفريقيا في مسابقة SeaPerch 2023.</li>
                <li>المركز الثامن عالميًا - مسابقة SeaPerch 2023.</li>
                <li>المركز الأول - على المستوى الوطني في مسابقة Ambition Creativity.</li>
                <li>المركز الثالث - على المستوى الوطني في مسابقة Talent Bil Arabi.</li>
                <li>المركز الأول - على مستوى المحافظة في مسابقة المبتكر الشاب 2019.</li>
                <li>المركز الأول - على مستوى المحافظة في مسابقة المبتكر الشاب 2023.</li>
                <li>المركز الأول - على المستوى الوطني في مسابقة Creative Child 2020.</li>
                <li>من بين العشرة الأوائل - في جائزة الدولة للمبدعين الشباب.</li>
                <li>المركز الثاني - على المستوى الوطني في تحديات Robot Academy 2019.</li>
            </ul>
        </section>

        <section id="hobbies">
            <h2>الهوايات والاهتمامات</h2>
            <p>الذكاء الاصطناعي | البرمجة | ألعاب الفيديو | تصميم المواقع</p>
        </section>
    </main>
</body>
</html>
