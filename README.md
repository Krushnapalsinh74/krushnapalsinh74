<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Krushnapalsinh Parmar Portfolio</title>
    <style>
        /* Reset and basic styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0f111a;
            color: #ffffff;
            line-height: 1.6;
            padding: 20px;
            scroll-behavior: smooth;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        h1,
        h2,
        h3 {
            margin-bottom: 10px;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 40px 20px;
        }

        .hero h1 {
            font-size: 2.8rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin: 10px 0;
            color: #cfd1d9;
        }

        .typing-img {
            margin: 20px auto;
            display: block;
            max-width: 90%;
        }

        /* Badges */
        .badges img {
            margin: 5px;
            transition: transform 0.3s;
        }

        .badges img:hover {
            transform: scale(1.1);
        }

        /* Sections */
        section {
            margin: 60px 0;
            text-align: center;
        }

        table {
            width: 80%;
            margin: 20px auto;
            border-collapse: collapse;
        }

        td {
            padding: 20px;
            vertical-align: top;
        }

        td h3 {
            margin-bottom: 10px;
        }

        td ul {
            list-style: none;
        }

        td ul li {
            margin-bottom: 8px;
            position: relative;
            padding-left: 20px;
        }

        td ul li::before {
            content: '•';
            position: absolute;
            left: 0;
            color: #ff9800;
        }

        /* Connect Section */
        .connect a {
            margin: 10px;
            display: inline-block;
            transition: transform 0.3s;
        }

        .connect a:hover {
            transform: scale(1.1);
        }

        /* Tech stack */
        .tech-stack img {
            max-width: 80%;
            margin: 10px 0;
        }

        /* GitHub stats */
        .stats img {
            max-width: 90%;
            margin: 15px auto;
            display: block;
            border-radius: 10px;
        }

        /* Builder Philosophy */
        .philosophy {
            font-style: italic;
            color: #a0a0a0;
            margin: 20px auto;
        }

        /* Horizontal rules */
        hr {
            border: 1px solid #2c2f3a;
            margin: 40px 0;
        }

        /* Responsive */
        @media(max-width:768px) {
            table {
                width: 100%;
                display: block;
            }

            td {
                display: block;
                width: 100%;
                margin-bottom: 20px;
            }

            .hero h1 {
                font-size: 2rem;
            }

            .hero p {
                font-size: 1rem;
            }
        }
    </style>
</head>

<body>

    <!-- HERO SECTION -->
    <section class="hero">
        <h1>👋 Hey, I’m Krushnapalsinh</h1>
        <p><b>Automation Engineer • Business Software Builder • Problem Solver</b></p>
        <img class="typing-img"
            src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&color=000000&center=true&vCenter=true&width=600&lines=Building+Real+World+Software;Automation+for+Business+%26+Schools;Child+Safety+Focused+Systems;Node.js+%7C+APIs+%7C+WhatsApp+Automation" />
        <div class="badges">
            <img src="https://img.shields.io/badge/Focus-Automation-success?style=flat-square" />
            <img src="https://img.shields.io/badge/Mindset-Product%20Builder-blue?style=flat-square" />
            <img src="https://img.shields.io/badge/Status-Building%20Daily-orange?style=flat-square" />
        </div>
    </section>

    <hr>

    <!-- WHAT I BUILD -->
    <section>
        <h2>🧠 What I Build</h2>
        <table>
            <tr>
                <td>
                    <h3>🚀 Active Projects</h3>
                    <ul>
                        <li>🧾 Inventory & Billing Systems</li>
                        <li>📲 WhatsApp Automation (Bills, Alerts, Messages)</li>
                        <li>🔔 School Bell & Timetable Automation</li>
                        <li>🛡️ Child Safety Software</li>
                    </ul>
                </td>
                <td>
                    <h3>🎯 Problem Areas I Solve</h3>
                    <ul>
                        <li>Manual business operations</li>
                        <li>Repetitive admin work</li>
                        <li>Poor communication systems</li>
                        <li>Lack of automation in schools & SMEs</li>
                    </ul>
                </td>
            </tr>
        </table>
    </section>

    <hr>

    <!-- COLLAB -->
    <section>
        <h2>🤝 Open for Collaboration</h2>
        <p class="connect">
            ✔ Business & School Automation 🚀 Automation Solutions for Businesses & Educational Institutions<br>
            ✔ Child Safety & Monitoring Systems 🛡️ Child Safety Tools<br>
            ✔ WhatsApp API & Messaging Automation 💬 WhatsApp API Workflows<br>
            ✔ Scalable Node.js Backend Projects ⚡ High-Performance Node.js Systems
        </p>
    </section>

    <hr>

    <!-- LEARNING -->
    <section>
        <h2>🌱 Currently Leveling Up</h2>
        <p>
            ⚙️ Advanced Node.js & Background Jobs ⚙️ Mastering Node.js & Background Processing<br>
            🔗 API Architecture & Integrations 🔗 Designing APIs & Seamless Integrations<br>
            📱 Android APK + Backend Bridge Concepts 📱 Android APK Development + Backend Sync<br>
            🔐 Secure & Ethical System Design 🔐 Building Secure & Ethical Systems
        </p>
    </section>

    <hr>

    <!-- ASK ME -->
    <section>
        <h2>💬 Ask Me About</h2>
        <p>
            Inventory Systems • Billing Software • Automation Ideas • Business Automation • WhatsApp API Integrations •
            Practical Software Deployments • Automation & Productivity Hacks • Smart Tools
        </p>
    </section>

    <hr>

    <!-- FUN FACT -->
    <section>
        <h2>⚡ Builder Philosophy</h2>
        <p class="philosophy">“I don’t build projects to show code. I build systems that actually get used.”</p>
    </section>

    <hr>

    <!-- CONNECT -->
    <section>
        <h2>🌐 Connect With Me</h2>
        <p class="connect">
            <a href="https://instagram.com/p_krushnapalsinh74">
                <img
                    src="https://img.shields.io/badge/Instagram-Connect-%23E4405F?logo=instagram&logoColor=white&style=for-the-badge" />
            </a>
            <a href="mailto:pkrushnapalsinh74@gmail.com">
                <img
                    src="https://img.shields.io/badge/Email-Contact-D14836?logo=gmail&logoColor=white&style=for-the-badge" />
            </a>
        </p>
    </section>

    <hr>

    <!-- TECH STACK -->
    <section class="tech-stack">
        <h2>🛠 Tech Stack</h2>
        <img
            src="https://skillicons.dev/icons?i=js,nodejs,java,kotlin,python,php,flutter,dart,nextjs,postgres,sqlite,firebase&perline=6" />
    </section>

    <hr>

    <!-- STATS -->
    <section class="stats">
        <h2>📊 GitHub Stats</h2>
        <img
            src="https://github-readme-stats.vercel.app/api?username=krushnapalsinh74&show_icons=true&theme=tokyonight" />
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=krushnapalsinh74&theme=tokyonight" />
        <img
            src="https://github-readme-stats.vercel.app/api/top-langs/?username=krushnapalsinh74&layout=compact&theme=tokyonight" />
    </section>

    <hr>

    <!-- TROPHIES -->
    <section>
        <h2>🏆 Achievements</h2>
        <img src="https://github-profile-trophy.vercel.app/?username=krushnapalsinh74&theme=matrix&margin-w=15" />
    </section>

    <hr>

    <section>
        <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" />
        <img src="https://visitcount.itsvg.in/api?id=krushnapalsinh74&icon=5&color=6" />
    </section>

</body>

</html>
