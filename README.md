# My-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edwards International LLC Checklist</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .checklist {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            font-size: 18px;
            color: #444;
            margin-bottom: 10px;
        }
        .checklist-item {
            margin: 10px 0;
        }
        .checklist-item label {
            margin-left: 10px;
            font-size: 16px;
            color: #555;
        }
        .btn {
            display: block;
            width: 100%;
            padding: 10px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            text-align: center;
        }
        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Edwards International LLC Checklist</h1>
    <div class="checklist">
        <div class="section">
            <h2>Before Submission</h2>
            <div class="checklist-item">
                <input type="checkbox" id="requirement1">
                <label for="requirement1">Contract requirements reviewed and understood.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement2">
                <label for="requirement2">Technical specifications matched to contract.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement3">
                <label for="requirement3">Certifications completed (FAR, DFARS, DLAD, Section K).</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement4">
                <label for="requirement4">Pricing verified for compliance with C13 (if applicable).</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement5">
                <label for="requirement5">Packaging and marking comply with MIL-STD-129 or ASTM D3951.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement6">
                <label for="requirement6">Delivery date and logistics confirmed.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="requirement7">
                <label for="requirement7">Required documents uploaded to DIBBS.</label>
            </div>
        </div>

        <div class="section">
            <h2>Post-Award</h2>
            <div class="checklist-item">
                <input type="checkbox" id="post1">
                <label for="post1">Product inspections scheduled before delivery.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="post2">
                <label for="post2">Labeling and marking reviewed before shipment.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="post3">
                <label for="post3">Buyer communication maintained for updates.</label>
            </div>
        </div>

        <div class="section">
            <h2>Final Review</h2>
            <div class="checklist-item">
                <input type="checkbox" id="final1">
                <label for="final1">All deliverables meet contract specifications.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="final2">
                <label for="final2">Submission and delivery deadlines met.</label>
            </div>
            <div class="checklist-item">
                <input type="checkbox" id="final3">
                <label for="final3">Confirm receipt of acknowledgment from the buyer.</label>
            </div>
        </div>

        <button class="btn" onclick="submitChecklist()">Submit Checklist</button>
    </div>

    <script>
        function submitChecklist() {
            alert("Checklist completed! Make sure to review all steps thoroughly before proceeding.");
        }
    </script>
</body>
</html>
