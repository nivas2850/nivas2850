<svg xmlns="http://www.w3.org/2000/svg" width="1000" height="2650" viewBox="0 0 1000 2650">

  <defs>
    <linearGradient id="headerGlow" x1="0" x2="1">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="50%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#00E5FF"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <style>
      .bg {
        fill: #000000;
      }

      .card {
        fill: #090909;
        stroke: #1f2937;
        stroke-width: 1.5;
      }

      .title {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 52px;
        font-weight: 700;
        fill: #ffffff;
      }

      .subtitle {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 23px;
        fill: #00E5FF;
      }

      .section {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 28px;
        font-weight: 700;
        fill: #00E5FF;
      }

      .company {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 21px;
        font-weight: 700;
        fill: #ffffff;
      }

      .role {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 17px;
        fill: #a78bfa;
      }

      .text {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 16px;
        fill: #d1d5db;
      }

      .small {
        font-family: Arial, Helvetica, sans-serif;
        font-size: 14px;
        fill: #9ca3af;
      }

      .tech {
        font-family: "Courier New", monospace;
        font-size: 14px;
        fill: #00E5FF;
      }

      .accent {
        fill: #a78bfa;
      }

      .line {
        stroke: #1f2937;
        stroke-width: 1;
      }
    </style>
  </defs>


  <!-- BLACK BACKGROUND -->
  <rect width="1000" height="2650" class="bg"/>


  <!-- TOP ACCENT -->
  <rect x="0" y="0" width="1000" height="7" fill="url(#headerGlow)"/>


  <!-- HEADER -->
  <text x="500" y="95" text-anchor="middle" class="title">
    NIVAS RAMAGIRI
  </text>

  <text x="500" y="140" text-anchor="middle" class="subtitle" filter="url(#glow)">
    FULL STACK &amp; AI ENGINEER
  </text>

  <text x="500" y="180" text-anchor="middle" class="text">
    Java • Python • Spring Boot • FastAPI • React • Generative AI
  </text>

  <text x="500" y="208" text-anchor="middle" class="text">
    LLMs • RAG • LangChain • AWS • Azure • Docker • Kubernetes
  </text>

  <text x="500" y="250" text-anchor="middle" class="small">
    Los Angeles, California • Open to Relocation
  </text>


  <!-- ABOUT -->
  <text x="60" y="335" class="section">01 / ABOUT ME</text>

  <rect x="50" y="365" width="900" height="235" rx="18" class="card"/>

  <text x="80" y="410" class="text">
    <tspan x="80" dy="0">
      Full Stack &amp; AI Engineer with 5+ years of experience building
    </tspan>
    <tspan x="80" dy="28">
      cloud-native and AI-powered enterprise applications across healthcare,
    </tspan>
    <tspan x="80" dy="28">
      mobility and telecom.
    </tspan>

    <tspan x="80" dy="42">
      I work across backend engineering, modern web development, Generative AI,
    </tspan>
    <tspan x="80" dy="28">
      Retrieval-Augmented Generation, microservices and cloud infrastructure.
    </tspan>

    <tspan x="80" dy="42">
      I enjoy transforming complex requirements into scalable,
    </tspan>
    <tspan x="80" dy="28">
      secure and production-ready software systems.
    </tspan>
  </text>


  <!-- CORE STACK -->
  <text x="60" y="675" class="section">02 / CORE ENGINEERING STACK</text>

  <rect x="50" y="705" width="430" height="210" rx="18" class="card"/>

  <text x="80" y="750" class="company">SOFTWARE ENGINEERING</text>

  <text x="80" y="790" class="tech">Java • Python • SQL</text>
  <text x="80" y="820" class="tech">Spring Boot • FastAPI</text>
  <text x="80" y="850" class="tech">React • Angular • TypeScript</text>
  <text x="80" y="880" class="tech">REST APIs • GraphQL • Microservices</text>


  <rect x="520" y="705" width="430" height="210" rx="18" class="card"/>

  <text x="550" y="750" class="company">AI / CLOUD</text>

  <text x="550" y="790" class="tech">Generative AI • LLMs • RAG</text>
  <text x="550" y="820" class="tech">LangChain • LangGraph • OpenAI</text>
  <text x="550" y="850" class="tech">AWS • Azure • Docker</text>
  <text x="550" y="880" class="tech">Kubernetes • CI/CD • Kafka</text>


  <!-- EXPERIENCE -->
  <text x="60" y="995" class="section">03 / PROFESSIONAL EXPERIENCE</text>


  <!-- CVS -->
  <rect x="50" y="1025" width="900" height="280" rx="18" class="card"/>

  <text x="80" y="1070" class="company">CVS HEALTH</text>
  <text x="80" y="1098" class="role">Senior Software Engineer • Jun 2024 – Present</text>

  <text x="80" y="1140" class="text">
    <tspan x="80">• Built enterprise AI applications with Python, FastAPI, React,</tspan>
    <tspan x="100" dy="25">PostgreSQL and OpenAI APIs.</tspan>

    <tspan x="80" dy="34">• Designed RAG pipelines using LangChain, embeddings, PGVector,</tspan>
    <tspan x="100" dy="25">semantic search and prompt engineering.</tspan>

    <tspan x="80" dy="34">• Developed secure REST APIs and microservices with JWT and OAuth2.</tspan>

    <tspan x="80" dy="34">• Deployed containerized applications using Docker, Kubernetes</tspan>
    <tspan x="100" dy="25">and GitHub Actions CI/CD.</tspan>
  </text>


  <!-- RESEARCH -->
  <rect x="50" y="1335" width="900" height="220" rx="18" class="card"/>

  <text x="80" y="1380" class="company">AI RESEARCH &amp; COLLABORATION HUB</text>
  <text x="80" y="1408" class="role">Research Assistant • Jan 2024 – May 2024</text>

  <text x="80" y="1450" class="text">
    <tspan x="80">• Evaluated NLP and Generative AI outputs across multi-million-record</tspan>
    <tspan x="100" dy="25">datasets using Python, Pandas, NumPy and SQL.</tspan>

    <tspan x="80" dy="34">• Developed ML evaluation pipelines using MLflow and transformers.</tspan>

    <tspan x="80" dy="34">• Performed model benchmarking with precision, recall, F1 and BLEU.</tspan>
  </text>


  <!-- VW -->
  <rect x="50" y="1585" width="900" height="260" rx="18" class="card"/>

  <text x="80" y="1630" class="company">VOLKSWAGEN GROUP TECHNOLOGY SOLUTIONS</text>
  <text x="80" y="1658" class="role">Software Engineer • Dec 2021 – Jul 2023</text>

  <text x="80" y="1700" class="text">
    <tspan x="80">• Built mobility applications using Angular, TypeScript, Node.js,</tspan>
    <tspan x="100" dy="25">Java Spring Boot and REST APIs.</tspan>

    <tspan x="80" dy="34">• Designed microservices processing 1M+ telemetry events daily.</tspan>

    <tspan x="80" dy="34">• Built event-driven systems with Kafka, Docker and Kubernetes.</tspan>

    <tspan x="80" dy="34">• Automated deployments using GitHub Actions, Jenkins and Terraform.</tspan>
  </text>


  <!-- VERIZON -->
  <rect x="50" y="1875" width="900" height="225" rx="18" class="card"/>

  <text x="80" y="1920" class="company">VERIZON</text>
  <text x="80" y="1948" class="role">Software Engineer • Jan 2020 – Nov 2021</text>

  <text x="80" y="1990" class="text">
    <tspan x="80">• Developed telecom backend services using Java, Spring Boot,</tspan>
    <tspan x="100" dy="25">REST APIs and Oracle SQL.</tspan>

    <tspan x="80" dy="34">• Built Angular and JavaScript customer dashboards.</tspan>

    <tspan x="80" dy="34">• Supported CI/CD using Jenkins, Maven, Git and Azure DevOps.</tspan>
  </text>


  <!-- PROJECT WORK -->
  <text x="60" y="2180" class="section">04 / FEATURED ENGINEERING WORK</text>

  <rect x="50" y="2210" width="430" height="190" rx="18" class="card"/>

  <text x="80" y="2255" class="company">ENTERPRISE GENAI &amp; RAG</text>

  <text x="80" y="2295" class="text">
    <tspan x="80">LLM-powered enterprise applications</tspan>
    <tspan x="80" dy="26">Semantic search &amp; embeddings</tspan>
    <tspan x="80" dy="26">LangChain &amp; PGVector</tspan>
    <tspan x="80" dy="26">FastAPI &amp; PostgreSQL</tspan>
  </text>


  <rect x="520" y="2210" width="430" height="190" rx="18" class="card"/>

  <text x="550" y="2255" class="company">CLOUD-NATIVE SYSTEMS</text>

  <text x="550" y="2295" class="text">
    <tspan x="550">Microservices architecture</tspan>
    <tspan x="550" dy="26">Kafka event processing</tspan>
    <tspan x="550" dy="26">Docker &amp; Kubernetes</tspan>
    <tspan x="550" dy="26">AWS &amp; CI/CD automation</tspan>
  </text>


  <!-- CERTIFICATION -->
  <text x="60" y="2480" class="section">05 / CERTIFICATION &amp; EDUCATION</text>

  <text x="80" y="2535" class="company">
    AWS Certified Developer
  </text>
  <text x="80" y="2565" class="small">
    Amazon Web Services • Valid through 2029
  </text>

  <text x="80" y="2610" class="company">
    Master of Science in Computer Science
  </text>
  <text x="80" y="2638" class="small">
    University of Alabama at Birmingham • GPA 3.70 / 4.00
  </text>

</svg>
