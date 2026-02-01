## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Angel Gonzalez | Web Developer</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background-color: #0d1117;
            color: #c9d1d9;
        }

        a {
            color: #58a6ff;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 20px;
        }

        /* ===== Banner ===== */
        .banner {
            background: linear-gradient(90deg, #161b22, #0d1117);
            padding: 50px 20px;
            border-radius: 0 0 12px 12px;
            margin-bottom: 40px;
        }

        .banner h1 {
            font-size: 2.5rem;
        }

        .banner p {
            margin-top: 10px;
            color: #8b949e;
            font-size: 1.1rem;
        }

        /* ===== Sections ===== */
        section {
            margin-bottom: 40px;
        }

        h2 {
            margin-bottom: 15px;
            color: #58a6ff;
        }

        p {
            line-height: 1.6;
            max-width: 750px;
        }

        /* ===== Tags ===== */
        .tags {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .tag {
            background: #161b22;
            padding: 6px 14px;
            border-radius: 999px;
            font-size: 0.9rem;
            border: 1px solid #30363d;
        }

        .tag.soft {
            background: #0d1117;
            border: 1px dashed #30363d;
            color: #8b949e;
        }

        /* ===== Projects ===== */
        table {
            width: 100%;
            border-collapse: collapse;
        }

        td {
            padding: 15px;
            vertical-align: top;
        }

        .project {
            background: #161b22;
            border-radius: 10px;
            padding: 15px;
        }

        .project img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 10px;
        }

        .project h3 {
            margin-bottom: 8px;
        }

        footer {
            text-align: center;
            color: #8b949e;
            font-size: 0.9rem;
            margin: 50px 0 20px;
        }
    </style>
</head>

<body>

    <div class="banner">
        <div class="container">
            <h1>👨‍💻 Angel Gonzalez</h1>
            <p>Web Systems Developer · Student · Always learning</p>
        </div>
    </div>

    <main class="container">

        <section>
            <h2>About Me</h2>
            <p>
                Web systems developer working on real projects in a microbusiness.
                I analyze requirements, propose solutions, and build web systems.
                Currently a student, already applying my skills in real-world environments.
            </p>
        </section>

        <section>
            <h2>Tech Stack</h2>
            <div class="tags">
                <span class="tag">HTML</span>
                <span class="tag">CSS</span>
                <span class="tag">JavaScript</span>
                <span class="tag">Java</span>
                <span class="tag">PHP</span>
            </div>
        </section>

        <section>
            <h2>Soft Skills</h2>
            <div class="tags">
                <span class="tag soft">Problem Solving</span>
                <span class="tag soft">Self-learning</span>
                <span class="tag soft">Teamwork</span>
                <span class="tag soft">Adaptability</span>
                <span class="tag soft">Responsibility</span>
            </div>
        </section>

        <section>
            <h2>Current Projects</h2>

            <table>
                <tr>
                    <td width="50%">
                        <div class="project">
                            <img src="ismac.png" alt="ISMAC">
                            <h3>ISMAC</h3>
                            <p>
                                Development and maintenance of institutional web systems,
                                proposing improvements and implementing new features.
                            </p>
                        </div>
                    </td>

                    <td width="50%">
                        <div class="project">
                            <img src="ismac-capacitaciones.png" alt="ISMAC Capacitaciones">
                            <h3>ISMAC Capacitaciones</h3>
                            <p>
                                Web platform focused on training and courses, contributing
                                to system development and optimization.
                            </p>
                        </div>
                    </td>
                </tr>
            </table>
        </section>

        <footer>
            🚀 Building, learning and improving every day
        </footer>

    </main>

</body>
</html>

