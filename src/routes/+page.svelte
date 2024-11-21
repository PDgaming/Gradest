<script>
    //*put if there is i am tired
</script>

<head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@400;700&family=Poppins:wght@400;700&display=swap">
</head>

<style>
    body {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        background: linear-gradient(135deg, #1e1e2f, #3a3a5f, #5a5a8f);
        color: white;
    }

    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 20px;
        background-color: rgba(30, 30, 47, 0.9);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .navbar h1 {
        margin: 0;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .nav-button {
        background-color: #444;
        color: white;
        text-decoration: none;
        padding: 10px 20px;
        margin-left: 10px;
        border-radius: 5px;
        transition: background-color 0.3s ease;
        font-family: 'Poppins', sans-serif;
    }

    .nav-button:hover {
        background-color: #666;
    }

    .hero {
        text-align: center;
        padding: 50px 20px;
        background: linear-gradient(135deg, #3a3a5f, #5a5a8f);
        box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .hero h2 {
        font-size: 36px;
        margin: 0;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .hero p {
        font-size: 16px;
        margin: 20px 0;
        font-family: 'Poppins', sans-serif;
    }

    .hero button {
        background-color: #444;
        color: white;
        border: none;
        padding: 15px 30px;
        cursor: pointer;
        margin: 10px;
        border-radius: 5px;
        transition: background-color 0.3s ease;
        font-family: 'Poppins', sans-serif;
    }

    .hero button:hover {
        background-color: #666;
    }

    .features {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
        padding: 50px 20px;
        background-color: rgba(46, 46, 79, 0.9);
        box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .feature {
        text-align: center;
        max-width: 300px;
        flex: 1 1 300px;
    }

    .feature h3 {
        font-size: 20px;
        margin-bottom: 10px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .feature p {
        font-size: 14px;
        font-family: 'Poppins', sans-serif;
    }

    .questions {
        padding: 50px 20px;
        background-color: rgba(30, 30, 47, 0.9);
        text-align: center;
        box-shadow: inset 0 0 10px rgba(0, 0, 0, 0.5);
    }

    .questions h2 {
        font-size: 28px;
        margin-bottom: 20px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .question-items {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 20px;
    }

    .question-item {
        max-width: 300px;
        background-color: rgba(58, 58, 95, 0.9);
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        flex: 1 1 300px;
    }

    .question-item h3 {
        font-size: 18px;
        margin-bottom: 10px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .question-item p {
        font-size: 14px;
        font-family: 'Poppins', sans-serif;
    }

    .contact {
        padding: 50px 20px;
        background-color: rgba(46, 46, 79, 0.9);
        text-align: center;
        box-shadow: inset 0 0 10px rgba(236, 234, 234, 0.5);
    }

    .contact h2 {
        font-size: 24px;
        margin-bottom: 20px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
    }

    .contact button {
        background-color: #444;
        color: white;
        border: none;
        padding: 15px 30px;
        cursor: pointer;
        margin: 10px;
        border-radius: 5px;
        transition: background-color 0.3s ease;
        font-family: 'Poppins', sans-serif;
    }

    .contact button:hover {
        background-color: #666;
    }

    .footer {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        align-items: center;
        padding: 20px;
        background-color: rgba(30, 30, 47, 0.9);
        box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
    }

    .footer div {
        text-align: center;
        max-width: 300px;
        margin: 10px;
    }

    .footer h3 {
        font-size: 18px;
        margin-bottom: 10px;
        font-family: 'Poppins', sans-serif;
        font-weight: 700;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .footer h3 img {
        margin-right: 10px;
        width: 30px;
        height: 30px;
    }

    .footer p {
        font-size: 14px;
        font-family: 'Poppins', sans-serif;
    }

    .footer .social i {
        font-size: 24px;
        margin: 0 10px;
        transition: color 0.3s ease;
    }

    .footer .social i:hover {
        color: #666;
    }

    /* Media Queries */
    @media (max-width: 768px) {
        .hero h2 {
            font-size: 28px;
        }

        .hero p {
            font-size: 14px;
        }

        .navbar button {
            padding: 8px 15px;
        }

        .hero button {
            padding: 10px 20px;
        }
    }

    @media (max-width: 480px) {
        .navbar h1 {
            font-size: 18px;
        }

        .navbar button {
            font-size: 12px;
        }

        .footer div {
            max-width: 100%;
        }
    }
</style>

<div class="navbar">
    <h1>Gradest</h1>
    <div> 
    <a href="/" class="nav-button">Home</a>
    <a href="/login" class="nav-button">Login</a>
    <a href="/register" class="nav-button">Register</a>
    </div>
</div>
<div class="hero">
    <h2 class="lft">Gradest</h2>
    <p>A smart test preparation app for Indian students, offering personalized tests, instant feedback, and performance tracking. Start your journey now by logging in or creating an account.</p>
    <a href="/login" class="nav-button">Login</a>
    <a href="/register" class="nav-button">Register</a>
</div>
<div class="features">
    <div class="feature">
        <h3>Personalized Test Creation</h3>
        <p>Create custom tests based on specific subjects, topics, difficulty levels, and exam patterns (CBSE, ICSE, State Boards, JEE, NEET, etc.)..</p>
    </div>
    <div class="feature">
        <h3>Offline Test Mode</h3>
        <p>Download tests for offline use and sync results once reconnected to the internet.</p>
    </div>
    <div class="feature">
        <h3>Parental Dashboard</h3>
        <p>Dedicated portal for parents to track their child’s performance and progress..</p>
    </div>
</div>
<div class="questions">
    <h2>Got Questions?</h2>
    <div class="question-items">
        <div class="question-item">
            <h3>What is Gradest?</h3>
            <p>Gradest is a sample test paper app for Indian students, offering personalized tests, pre-designed papers, instant evaluation, and performance tracking to help prepare for exams like CBSE, ICSE, JEE, and NEET..</p>
        </div>
        <div class="question-item">
            <h3>Can I use Gradest offline?</h3>
            <p>Yes, Gradest supports offline test mode. You can download tests and sync your results later when online.</p>
        </div>
        <div class="question-item">
            <h3>Is Gradest free to use?</h3>
            <p>Gradest offers a mix of free content and affordable subscription plans with premium features.</p>
        </div>
    </div>
</div>
<div class="contact">
    <h2>Contact us!</h2>
    <p>Have questions, need assistance, or want to share feedback? We'd love to hear from you! Reach out anytime.</p>
    <a href="/contactus" class="nav-button">Contact us</a>
</div>
<div class="footer">
    <div>
        <h3>
            <img src="https://placehold.co/30x30" alt="PD Enterprise logo">
            PD Enterprise
        </h3>
        <p>© 2024 PD Enterprise. All rights reserved.</p>
    </div>
    <div>
        <h3>Services</h3>
        <p>Cloud Storage</p>
        <p>Note Sharing</p>
        <p>Collaboration</p>
    </div>
    <div>
        <h3>Company</h3>
        <p>About</p>
        <p>Careers</p>
        <p>Contact</p>
    </div>
    <div class="social">
        <h3>Social</h3>
        <i class="fab fa-facebook"></i>
        <i class="fab fa-twitter"></i>
        <i class="fab fa-linkedin"></i>
    </div>
</div>



