<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }

        .question {
            margin-bottom: 20px;
            text-align: left;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            background-color: #f9f9f9;
        }

        .options {
            margin-top: 10px;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        input[type="radio"] {
            margin-right: 5px;
        }

        .button-container {
            text-align: center;
            margin-top: 20px;
        }

        button {
            background-color: #333;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .result-container {
            margin-top: 20px;
        }

        .incorrect {
            color: red;
        }
    </style>
</head>
<body>
    <h1>PC Assembly and Disassembly</h1>

    <div class="container">
        <div class="question">
            <p>Question 1: What is the main purpose of an anti-static wrist strap when assembling a computer?</p>
            <div class="options">
                <label><input type="radio" name="q1" value="a"> a. Keeps hands clean.</label>
                <label><input type="radio" name="q1" value="b"> b. Prevents electrostatic discharges that can damage components.</label>
                <label><input type="radio" name="q1" value="c"> c. Protects against computer viruses.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 2: What tool is commonly used to screw components in a computer?</p>
            <div class="options">
                <label><input type="radio" name="q2" value="a"> a. Screwdriver</label>
                <label><input type="radio" name="q2" value="b"> b. Hammer</label>
                <label><input type="radio" name="q2" value="c"> c. Wrench</label>
            </div>
        </div>

        <div class="question">
            <p>Question 3: What precaution should you take before touching any internal computer component?</p>
            <div class="options">
                <label><input type="radio" name="q3" value="a"> a. Wear rubber gloves.</label>
                <label><input type="radio" name="q3" value="b"> b. Ensure the computer is plugged in.</label>
                <label><input type="radio" name="q3" value="c"> c. Turn off and disconnect the computer from the power source and touch a metal surface to discharge static electricity from your body.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 4: What type of expansion slot is used to add sound cards, network cards, and graphics cards to a computer?</p>
            <div class="options">
                <label><input type="radio" name="q4" value="a"> a. PCI Express</label>
                <label><input type="radio" name="q4" value="b"> b. SATA</label>
                <label><input type="radio" name="q4" value="c"> c. USB</label>
            </div>
        </div>

        <div class="question">
            <p>Question 5: Which type of computer is typically easier to upgrade in terms of components like RAM or storage?</p>
            <div class="options">
                <label><input type="radio" name="q5" value="a"> a. Desktop PC</label>
                <label><input type="radio" name="q5" value="b"> b. Laptop</label>
                <label><input type="radio" name="q5" value="c"> c. Neither can be upgraded.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 6: What best describes the ease of upgrading laptops compared to desktop PCs?</p>
            <div class="options">
                <label><input type="radio" name="q6" value="a"> a. Laptops are generally easier to upgrade in terms of components like the graphics card.</label>
                <label><input type="radio" name="q6" value="b"> b. Laptops are more difficult to upgrade compared to desktop PCs.</label>
                <label><input type="radio" name="q6" value="c"> c. Laptops and desktop PCs have the same ease of upgrading.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 7: What is the purpose of thermal paste when assembling a CPU?</p>
            <div class="options">
                <label><input type="radio" name="q7" value="a"> a. Provides electrical power to the CPU.</label>
                <label><input type="radio" name="q7" value="b"> b. Facilitates communication between the CPU and motherboard.</label>
                <label><input type="radio" name="q7" value="c"> c. Helps dissipate heat from the CPU and maintain it at an appropriate temperature.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 8: Why is it important to use screws to secure components when assembling a computer?</p>
            <div class="options">
                <label><input type="radio" name="q8" value="a"> a. Screws are not necessary; components can fit without them.</label>
                <label><input type="radio" name="q8" value="b"> b. Screws help keep components secure and prevent them from moving or getting damaged.</label>
                <label><input type="radio" name="q8" value="c"> c. Screws complicate the assembly process and should be avoided.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 9: Which hardware component of a computer is typically installed in a specific bay inside the case?</p>
            <div class="options">
                <label><input type="radio" name="q9" value="a"> a. Motherboard</label>
                <label><input type="radio" name="q9" value="b"> b. Power supply</label>
                <label><input type="radio" name="q9" value="c"> c. Hard drive</label>
            </div>
        </div>

        <div class="question">
            <p>Question 10: When assembling a computer, what is the importance of ensuring that cables are routed and organized properly inside the case?</p>
            <div class="options">
                <label><input type="radio" name="q10" value="a"> a. It's not necessary to worry about cable organization.</label>
                <label><input type="radio" name="q10" value="b"> b. It helps maintain proper airflow and prevents cables from obstructing components or getting damaged by heat.</label>
                <label><input type="radio" name="q10" value="c"> c. It increases the overall computer performance.</label>
            </div>
        </div>

        <div class="question">
            <p>Question 11: Which of the following tools is commonly used to secure and organize cables inside a computer?</p>
            <div class="options">
                <label><input type="radio" name="q11" value="a"> a. Screwdriver</label>
                <label><input type="radio" name="q11" value="b"> b. Pliers</label>
                <label><input type="radio" name="q11" value="c"> c. Cable ties or zip ties</label>
            </div>
        </div>

        <div class="question">
            <p>Question 12: When assembling a computer, why is it important to connect cables correctly to the motherboard and other components?</p>
            <div class="options">
                <label><input type="radio" name="q12" value="a"> a. It doesn't matter how cables are connected as it doesn't affect the functioning.</label>
                <label><input type="radio" name="q12" value="b"> b. To avoid potential short circuits and ensure that components function properly and communicate with each other.</label>
                <label><input type="radio" name="q12" value="c"> c. To increase the computer's performance.</label>
            </div>
        </div>

        <div class="button-container">
            <button onclick="calculateScore()">Calculate Score</button>
        </div>

        <div class="result-container">
            <p id="score"></p>
            <p id="incorrectAnswers" class="incorrect"></p>
        </div>
    </div>

    <script>
        function calculateScore() {
            var score = 0;
            var answers = ["b", "a", "c", "b", "a", "b", "c", "b", "c", "b", "c", "b"];
            var userAnswers = [];

            for (var i = 1; i <= 12; i++) {
                var selection = document.querySelector('input[name="q' + i + '"]:checked');
                if (selection) {
                    userAnswers.push(selection.value);
                    if (selection.value === answers[i - 1]) {
                        score++;
                    }
                } else {
                    userAnswers.push("");
                }
            }

            var result = "Score: " + score + " out of 12 correct answers";
            document.getElementById("score").innerHTML = result;

            // Display incorrect answers
            var incorrectAnswers = [];
            for (var i = 0; i < answers.length; i++) {
                if (userAnswers[i] !== answers[i]) {
                    incorrectAnswers.push("Question " + (i + 1) + ": Your answer - " + userAnswers[i] + ", Correct answer - " + answers[i]);
                }
            }

            var incorrectAnswersText = incorrectAnswers.length > 0 ? "Incorrect Answers: " + incorrectAnswers.join(", ") : "All answers are correct";
            document.getElementById("incorrectAnswers").innerHTML = incorrectAnswersText;
        }
    </script>
</body>
</html>
