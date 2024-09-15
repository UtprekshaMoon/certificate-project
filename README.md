# certificate-project

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Doctor of Medicine Certificate</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #e9ecef;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: #212529;
        }
        .certificate {
            width: 850px;
            padding: 30px;
            border: 5px solid #007bff;
            border-radius: 15px;
            background-color: #ffffff;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
            text-align: center;
            position: relative;
            font-size: 16px;
        }
        .certificate h1 {
            font-size: 42px;
            margin: 0;
            color: #007bff;
            font-weight: bold;
        }
        .certificate h2 {
            font-size: 30px;
            margin: 10px 0;
            color: #343a40;
        }
        .certificate p {
            font-size: 20px;
            margin: 10px 0;
            color: #495057;
        }
        .certificate .signature {
            margin-top: 40px;
            text-align: center;
        }
        .certificate .signature p {
            font-size: 18px;
            margin: 5px 0;
        }
        .certificate .date {
            margin-top: 20px;
            font-size: 18px;
            color: #6c757d;
        }
        .certificate .seal {
            position: absolute;
            bottom: 30px;
            right: 30px;
            font-size: 70px;
            color: #ffc107;
        }
        .certificate .line {
            border-top: 2px solid #007bff;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="certificate">
        <h1>[University/Institution Name]</h1>
        <h2>Certificate of Graduation</h2>
        <p>This is to certify that</p>
        <h2>[Student's Full Name]</h2>
        <p>has successfully completed the requirements for the degree of</p>
        <h2>Doctor of Medicine (M.D.)</h2>
        <p>with distinction</p>
        <p>on</p>
        <p class="date">[Month, Day, Year]</p>
        <div class="line"></div>
        <div class="signature">
            <p>Awarded by:</p>
            <p>[Dean’s Name]</p>
            <p>Dean, School of Medicine</p>
            <p>[University/Institution Name]</p>
        </div>
        <div class="seal">
            &#9733; <!-- Replace this with an actual seal image if desired -->
        </div>
    </div>
</body>
</html>

