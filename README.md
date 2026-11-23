
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ganashri | Personal Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: 'Segoe UI', Arial, sans-serif;
    background: #f8f6f7;
    color: #39323a;
    line-height: 1.8;
}

header {
    background: linear-gradient(135deg, #382b3c, #79576f);
    color: white;
    text-align: center;
    padding: 45px 15px;
}

header h1 {
    font-size: 38px;
    letter-spacing: 4px;
}

header p {
    font-size: 16px;
    margin-top: 8px;
}

nav {
    background: #49394b;
    padding: 15px 8px;
    text-align: center;
    position: sticky;
    top: 0;
    z-index: 10;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 7px 10px;
    font-size: 14px;
    display: inline-block;
}

nav a:hover {
    color: #f3c8dc;
}

.hero {
    background: linear-gradient(135deg, #eadce7, #f6e9ed);
    text-align: center;
    padding: 85px 20px;
}

.hero h2 {
    color: #503950;
    font-size: 38px;
    margin-bottom: 12px;
}

.hero p {
    font-size: 17px;
}

.hero .tagline {
    color: #805e7b;
    margin-top: 15px;
    font-style: italic;
}

section {
    max-width: 1000px;
    margin: auto;
    padding: 55px 22px;
}

section h2 {
    text-align: center;
    color: #704e6c;
    font-size: 29px;
    margin-bottom: 28px;
}

.card {
    background: white;
    padding: 28px;
    margin: 18px 0;
    border-radius: 14px;
    box-shadow: 0 4px 16px rgba(65, 40, 65, 0.08);
}

.card h3 {
    color: #805c79;
    margin-bottom: 12px;
}

.card p {
    text-align: justify;
}

.card ul {
    padding-left: 25px;
}

.card li {
    padding: 5px 0;
}

.skills {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 15px;
}

.skill {
    background: #f1e7ef;
    padding: 17px;
    text-align: center;
    border-radius: 10px;
    color: #684c66;
    font-weight: 600;
}

.highlight {
    color: #805c79;
    font-weight: bold;
}

footer {
    background: #382b3c;
    color: white;
    text-align: center;
    padding: 28px 15px;
}

@media(max-width:600px) {
    header h1 {
        font-size: 29px;
    }

    .hero h2 {
        font-size: 29px;
    }

    nav a {
        margin: 5px;
        font-size: 12px;
    }

    .card {
        padding: 20px;
    }
}
</style>
</head>

<body>

<header>
    <h1>GANASHRI</h1>
    <p>PERSONAL PORTFOLIO</p>
    <p>Learning • Growing • Achieving</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#activities">Activities</a>
    <a href="#achievements">Achievements</a>
    <a href="#skills">Skills</a>
    <a href="#interests">Interests</a>
    <a href="#goals">Goals</a>
</nav>

<div class="hero" id="home">
    <h2>Hello, I'm Ganashri!</h2>
    <p>Welcome to my personal portfolio website.</p>
    <p class="tagline">
        "Every experience is an opportunity to learn something new."
    </p>
</div>

<section id="about">
    <h2>About Me</h2>
    <div class="card">
        <p>
        Hello! My name is Ganashri, and I am from Vijayapura,
        Karnataka. I am currently pursuing my first year of
        Bachelor of Engineering in Civil Engineering at
        KLS Gogte Institute of Technology.

        I am an enthusiastic student who believes in continuous
        learning, self-improvement and personal development.
        I enjoy exploring new opportunities, accepting
        responsibilities and participating in different
        activities.

        My school journey has given me many valuable experiences.
        Being involved in sports, extracurricular activities
        and leadership responsibilities has helped me develop
        confidence, discipline and teamwork.

        I believe that success comes through dedication,
        patience and consistent effort. My aim is to continue
        learning, improve my abilities and make the best use
        of every opportunity that comes my way.
        </p>
    </div>
</section>

<section id="education">
    <h2>Educational Background</h2>

    <div class="card">
        <h3>Bachelor of Engineering</h3>
        <p class="highlight">KLS Gogte Institute of Technology</p>
        <p><b>Branch:</b> Civil Engineering</p>
        <p><b>Year:</b> First Year</p>
        <p>
        I am currently pursuing Civil Engineering and building
        my foundation in engineering concepts and technical
        knowledge. This field interests me because it contributes
        to the development of infrastructure such as buildings,
        roads, bridges and other essential structures.

        I look forward to gaining practical knowledge, improving
        my problem-solving abilities and understanding how
        engineering concepts are applied in real life.
        </p>
    </div>
</section>

<section id="activities">
    <h2>Social Activities & Leadership</h2>

    <div class="card">
        <h3>School Volunteer</h3>
        <p>
        I had the opportunity to serve as a school volunteer.
        This experience helped me understand the importance
        of responsibility, cooperation and active participation.
        It also encouraged me to contribute positively to
        school activities.
        </p>
    </div>

    <div class="card">
        <h3>Student Captain</h3>
        <p>
        Serving as a student captain helped me develop
        leadership qualities and confidence. It taught me
        how to take responsibility, coordinate with others
        and work towards common goals.
        I learned that leadership involves listening,
        supporting others and setting a good example.
        </p>
    </div>

    <div class="card">
        <h3>Participation in Group Activities</h3>
        <p>
        I actively participated in school activities,
        competitions and group events. These experiences
        helped me improve my communication, teamwork
        and ability to work with different people.
        </p>
    </div>
</section>

<section id="achievements">
    <h2>Achievements & Sports Participation</h2>

    <div class="card">
        <p>
        Sports have played an important role in my personal
        development. I have participated in various sports
        competitions at district and state levels.
        These experiences have taught me discipline,
        determination, teamwork and sportsmanship.
        </p>

        <h3>My Participation</h3>
        <ul>
            <li>State-level Relay competition.</li>
            <li>District-level Kabaddi competition.</li>
            <li>District-level Kho-Kho competition.</li>
            <li>District-level Relay competition.</li>
            <li>Hurdles competitions.</li>
            <li>Long Jump competitions.</li>
            <li>Dance activities and competitions.</li>
        </ul>

        <p>
        Every competition has given me an opportunity
        to learn, challenge myself and gain valuable
        experience. I consider participation and continuous
        improvement important achievements in my journey.
        </p>
    </div>
</section>

<section id="skills">
    <h2>My Skills & Strengths</h2>

    <div class="card">
        <p>
        Through my academic journey and extracurricular
        activities, I have developed several qualities
        that help me in both individual and group tasks.
        </p>
        <br>

        <div class="skills">
            <div class="skill">Leadership</div>
            <div class="skill">Teamwork</div>
            <div class="skill">Communication</div>
            <div class="skill">Time Management</div>
            <div class="skill">Responsibility</div>
            <div class="skill">Discipline</div>
            <div class="skill">Adaptability</div>
            <div class="skill">Willingness to Learn</div>
        </div>
    </div>
</section>

<section id="interests">
    <h2>Interests & Hobbies</h2>

    <div class="card">
        <h3>Sports and Physical Activities</h3>
        <p>
        I enjoy sports and physical activities because
        they encourage an active lifestyle and teach
        important values such as discipline, teamwork
        and determination.
        </p>
        <br>

        <h3>Dance and Extracurricular Activities</h3>
        <p>
        I have participated in dance activities and enjoy
        being involved in events that encourage creativity,
        confidence and self-expression.
        </p>
        <br>

        <h3>Learning New Things</h3>
        <p>
        I am interested in learning new skills, exploring
        different subjects and gaining knowledge beyond
        my regular academic studies.
        </p>
        <br>

        <h3>Social Interaction</h3>
        <p>
        I enjoy spending time with friends, sharing
        experiences and creating memorable moments.
        I believe positive relationships and teamwork
        make student life more meaningful.
        </p>
    </div>
</section>

<section id="goals">
    <h2>My Future Goals</h2>

    <div class="card">
        <p>
        My immediate goal is to complete my engineering
        education with a strong understanding of technical
        concepts and practical applications.

        Along with my engineering studies, I aspire to
        prepare for competitive government examinations
        and work towards a responsible position in public
        service.

        I want to continue developing my knowledge,
        confidence and abilities. I believe that hard work,
        consistency, discipline and determination are
        important for achieving long-term goals.

        My aim is to build a meaningful career and use
        my knowledge and skills in a positive way.
        </p>
    </div>
</section>

<section id="contact">
    <h2>Thank You!</h2>

    <div class="card">
        <p>
        Thank you for visiting my personal portfolio.
        This website represents my educational journey,
        experiences, achievements, interests and aspirations.

        I believe that learning is a lifelong process and
        every new experience helps us grow. I look forward
        to exploring new opportunities and achieving
        my future goals.
        </p>
        <br>
        <p class="highlight" style="text-align:center;">
        Keep Learning • Keep Growing • Keep Achieving
        </p>
    </div>
</section>

<footer>
    <p>© 2026 Ganashri | Personal Portfolio</p>
    <p>Designed as part of Essentials of IT Course Project</p>
</footer>

</body>
</html>
