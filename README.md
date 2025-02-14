<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Neonbyte Web Hosting Company Ltd.</title>
    <link rel="stylesheet" href="styles.css">
    <script defer src="script.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.4.0/jspdf.umd.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
    <style>
        body {
            background-color: #0a0a0a;
            color: #00d4ff;
            font-family: 'Arial', sans-serif;
            text-align: center;
        }
        header {
            background: linear-gradient(90deg, #000428, #004e92);
            padding: 20px;
            border-bottom: 3px solid #00d4ff;
            box-shadow: 0 0 15px #00d4ff;
        }
        .logo, .profile-pic {
            width: 100px;
            border-radius: 50%;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #00d4ff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ffffff;
        }
        section {
            margin: 40px 0;
            padding: 20px;
            background: rgba(0, 0, 0, 0.7);
            border: 2px solid #00d4ff;
            box-shadow: 0 0 10px #00d4ff;
            border-radius: 10px;
            display: inline-block;
            width: 80%;
        }
        button {
            background: #00d4ff;
            border: none;
            padding: 10px 20px;
            color: #000;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
            border-radius: 5px;
        }
        button:hover {
            background: #ffffff;
            color: #000;
        }
    </style>
</head>
<body>
    <header>
        <img src="Screenshot 2025-02-14 050038.png" alt="Neonbyte Logo" class="logo">
        <h1>Neonbyte Web Hosting Company Ltd.</h1>
        <img src="IMG_20241222_204244.jpg" alt="Prashant Kumar Singh" class="profile-pic">
        <p>Director & Co-founder: Prashant Kumar Singh</p>
    </header>
    
    <nav>
        <ul>
            <li><a href="#order">Order Now</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#govt-services">Govt. Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section id="order">
        <h2>Place Your Order</h2>
        <form id="orderForm" action="submit_order.php" method="POST" enctype="multipart/form-data">
            <input type="text" name="name" placeholder="Your Name" required><br>
            <input type="email" name="email" placeholder="Your Email" required><br>
            <select name="service">
                <option value="Web Development">Web Development</option>
                <option value="Web Design">Web Design</option>
                <option value="Web Hosting">Web Hosting</option>
                <option value="Thumbnail Design">Thumbnail Design</option>
                <option value="Logo Design">Logo Design</option>
                <option value="Government Documents">Government Documents</option>
            </select><br>
            <select name="govtService">
                <option value="NA">NA</option>
                <option value="Passport">Passport</option>
                <option value="Visa">Visa</option>
                <option value="Aadhar">Aadhar</option>
                <option value="PAN">PAN</option>
                <option value="Driving License">Driving License</option>
                <option value="Birth Certificates">Birth Certificates</option>
                <option value="Death Certificates">Death Certificates</option>
                <option value="Caste Certificate">Caste Certificate</option>
                <option value="Income Certificate">Income Certificate</option>
                <option value="Residence Certificate">Residence Certificate</option>
                <option value="EWS Certificate">EWS Certificate</option>
                <option value="OBC-NCL Certificate">OBC-NCL Certificate</option>
                <option value="Marriage Certificate">Marriage Certificate</option>
                <option value="Police Verification">Police Verification</option>
                <option value="EPFO/PF Transfer">EPFO/PF Transfer</option>
                <option value="Bank Account Opening">Bank Account Opening</option>
            </select><br>
            <input type="file" name="documentUpload" accept=".pdf,.jpg,.png,.doc,.docx"><br>
            <button type="submit">Submit</button>
        </form>
    </section>
    
    <section id="contact">
        <h2>Contact Information</h2>
        <p>Phone: 7067185187</p>
        <p>Email: <a href="mailto:prashantkumarsingh065@gmail.com">prashantkumarsingh065@gmail.com</a></p>
        <p>Instagram: <a href="https://www.instagram.com/o_o.prashantkumarsingh.o_o?igsh=em9tN3dlMGhwcDJ1" target="_blank">Instagram Profile</a></p>
        <p>Facebook: <a href="https://facebook.com/share/15d7hCXisD/" target="_blank">Facebook Profile</a></p>
    </section>
</body>
</html>
