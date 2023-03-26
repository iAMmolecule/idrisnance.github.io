# Idris Nance

`<!DOCTYPE html>
<html style="font-family: sans-serif" lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Unit 3 Project First Draft</title>

  <script> src = "https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.0/jquery.min.js" >
  </script>

  <style>
    body {
      padding: 10% 3% 10% 3%;
      text-align: left;
    }

    img {
      height: 200px;
      width: 300px;
    }

    h1 {
      color: #ffffff;
    }

    .mode {
      float: right;
    }

    .change {
      cursor: pointer;
      border: 1px solid #555;
      border-radius: 40%;
      width: 20px;
      text-align: center;
      padding: 5px;
      margin-left: 8px;
    }

    .dark {
      background-color: #222;
      color: #e6e6e6;
    }
  </style>
</head>

<body>
  <nav>
    <a href="./home.html">Home</a>
    <a href="./about.html">About</a>
    <a href="./index.html">Unit 3 Project</a>
    <a href="./contact.html">Contact</a>
    <a href="./service.html">Service</a>
  </nav>
  <div class="mode">
    Dark mode:
    <span class="change">OFF</span>
  </div>
  <!-- https://Idris-Nance.idrisnance1.repl.co -->
  <div>
    <center>
      <h2>Idris Nance</h2>
      <p>
      <h3><i>How ChatGPT will affect jobs</i></h3>
      </p>

      <img
        src="https://imageio.forbes.com/specials-images/imageserve/63c64c5d2085183335766ebe/How-Will-ChatGPT-Affect-Your-Job-If-You-Work-In-Advertising-And-Marketing-/960x0.jpg?height=439&width=711&fit=bounds">
      </img>
    </center>
  </div>
  <p>ChatGPT, or Chat Generative Pre-training Transformer, is an artificial intelligence tool designed for natural
    language processing, and it is changing many jobs in our economy. Although it has improved the
    efficiency of businesses, it is also changing the job market across various industries, and taking thousands of
    people's jobs. This essay will explore the effects of AI like ChatGPT and how it affects people's jobs, it's
    benefits, and solutions to this problem. </p>

  <p>According to an article on Forbes, advertising and marketing jobs are at risk due to ChatGPT. It can analyze
    and understand customer needs, behaviors, and preferences, allowing businesses to personalize their marketing
    campaigns. However, this means that some marketing roles that focus on data analysis, segmentation, and targeting
    may become redundant as ChatGPT replaces them.</p>

  <p>Similarly, customer service jobs are also affected by ChatGPT's implementation. Forbes posits that businesses are
    using it to handle customer inquiries and complaints quickly and efficiently. This means that customer service
    roles that involve repetitive tasks and rely on scripted responses are at risk of automation. With ChatGPT
    becoming more advanced, it is expected that many customer service tasks will be entirely automated in the next
    decade.</p>

  <p>Business Insider also notes that repetitive and predictable jobs are at risk of being automated as ChatGPT
    advances. Roles such as administrative work or data entry, which require little creativity or decision-making,
    could become automated by ChatGPT. This means that jobs that do not require a high level of complexity or
    imagination may eventually phase out.</p>

  <p>UNCTAD suggests that jobs requiring social skills and emotional intelligence are likely to withstand ChatGPT
    automation. This includes areas such as healthcare, education, or creative industries where human interaction is
    necessary. In healthcare, ChatGPT could assist doctors in diagnosis or patient care, but it cannot replace their
    expertise in working with patients. Similarly, in creative industries, ChatGPT may enhance the creative process,
    but it cannot replace human imagination.</p>

  <p>CBS News reports that ChatGPT's impact is most significant in financial services, where it is transforming
    traditional banking. ChatGPT enables banks to personalize customer experiences, manage fraud, and predict
    financial trends accurately. Consequently, jobs in finance and accounting that require data processing, such as
    bookkeepers or financial analysts, are at risk of automation.</p>

  <p>Search Engine Journal notes that ChatGPT has the potential to create new jobs as it becomes more prevalent in
    businesses. With ChatGPT handling repetitive tasks, employees can focus on more creative and high-value tasks. New
    job roles associated with ChatGPT include chatbot developers and software engineers.</p>

  <p></p>

  <p>Overall, ChatGPT's impact on the job market depends on the roles' complexity, the need for human interaction, and
    the level of creativity required. With ChatGPT's continued advancement, some jobs requiring repetitive tasks, such
    as customer service, administrative tasks or financial analysis, may become obsolete. However, jobs that require
    human interaction, social skills, and creativity, such as healthcare, education, and creative industries, are less
    at risk of being automated. Nevertheless, employees are encouraged to adapt their skills continually and upskill
    to meet the existing market demands.</p>

  <!--<img src="https://media.geeksforgeeks.org/wp-content/uploads/20200122115631/GeeksforGeeks210.png">-->

  </div>

  <script>
      $(".change").on("click", function () {
        if ($("body").hasClass("dark")) {
          $("body").removeClass("dark");
          $(".change").text("OFF");
        } else {
          $("body").addClass("dark");
          $(".change").text("ON");
        }
      });
  </script>
</body>

</html>`
