
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Portal</title>
    <style>
        body {
            font-family: Arial, sans-serif;


            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        .job-card {
            background: white;
            margin: 10px 0;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .job-card h2 {
            margin: 0;
            font-size: 18px;
            color: #007bff;
        }
        .job-card p {
            margin: 5px 0;
            color: #555;
        }
        .apply-btn {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .apply-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Job in Baddi</h1>
        <p>Your destination for the latest job opportunities!</p>
    </header>
    <div class="container">
        <!-- Sample Job Card -->
        <div class="job-card">
            <h2>Job Title: Software Developer</h2>
            <p>Location: Baddi, Himachal Pradesh</p>
            <p>Experience: 2+ years</p>
            <a href="#" class="apply-btn">Apply Now</a>
        </div>
        <div class="job-card">
            <h2>Job Title: Marketing Executive</h2>
            <p>Location: Solan, Himachal Pradesh</p>
            <p>Experience: 1+ year</p>
            <a href="#" class="apply-btn">Apply Now</a>
        </div>
    </div>
</body>
</html>

