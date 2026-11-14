<!-- PROFILE HEADER -->

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:12344A,100:087F70&height=215&section=header&text=Sajidur%20Rahman%20Siam&fontSize=44&fontColor=FFFFFF&animation=fadeIn&fontAlignY=35&desc=Backend%20Developer%20%7C%20Full-Stack%20Development%20and%20AI%20Integration&descAlignY=56&descSize=16"
    width="100%"
    alt="Sajidur Rahman Siam — Backend Developer, Full-Stack Development and AI Integration"
  />
</div>

<div align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=1100&color=35DDA5&center=true&vCenter=true&width=680&height=45&lines=Node.js+%2B+TypeScript+for+backend+development;PostgreSQL+%2B+Prisma+for+relational+data;React+%2B+Next.js+for+full-stack+apps;Python+%2B+FastAPI+for+AI+integration"
    alt="Node.js and TypeScript · PostgreSQL and Prisma · React and Next.js · Python and FastAPI"
  />
</div>

<p align="center">
  <a href="mailto:sajidursiam18@gmail.com">
    <img src="https://img.shields.io/badge/Open_to_work-Backend_%26_Full--Stack-087F70?style=for-the-badge&labelColor=162733" alt="Open to backend and full-stack roles" />
  </a>
  <a href="https://github.com/SajidurCodes?tab=followers">
    <img src="https://img.shields.io/github/followers/SajidurCodes?style=for-the-badge&logo=github&color=087F70&labelColor=162733&label=Followers" alt="GitHub followers" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=SajidurCodes&style=for-the-badge&color=087F70&label=Profile+views" alt="Profile views" />
</p>

<p align="center">
  <a href="#-featured-projects">Projects</a> ·
  <a href="#-technical-skills">Skills</a> ·
  <a href="#-github-activity">GitHub Activity</a> ·
  <a href="#-connect">Connect</a>
</p>

---

## 👋 About me

I'm a **Computer Science and Engineering graduate from BRAC University** in Dhaka, Bangladesh. I build backends with **Node.js, Express, and TypeScript**, and use **React and Next.js** to build the interfaces around them.

I enjoy working on the rules behind an API. In RentNest, for example, a tenant can pay only after the landlord approves the rental request. The backend then verifies Stripe's webhook signature before updating the payment status. My Python projects explore a different question: how can someone check the result an application gives them? In DocuMind, readers can follow an answer back to the page it came from.

## 🚀 Featured projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 RentNest</h3>
      <p><strong>Full-stack rental marketplace</strong></p>
      <p>Tenants search properties and submit rental requests. Landlords approve requests, and tenants pay through Stripe Checkout. The Express API enforces role permissions and verifies payment webhooks. A Next.js dashboard gives each user access to the actions their role allows.</p>
      <p><code>TypeScript</code> <code>Express</code> <code>PostgreSQL</code> <code>Prisma</code> <code>Next.js</code> <code>Stripe</code></p>
      <p>
        <a href="https://github.com/SajidurCodes/RentNest"><strong>Backend ↗</strong></a> ·
        <a href="https://github.com/SajidurCodes/RentNest-Frontend">Frontend</a> ·
        <a href="https://rent-nest-frontend-theta.vercel.app/">Live demo</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🗺️ Tour Management System</h3>
      <p><strong>Tour booking and payments in Bangladesh</strong></p>
      <p>Travelers can browse tours, book dates, pay through SSLCommerz, and check their booking status. The backend uses JWT access and refresh tokens. Role-protected routes let administrators manage tours, users, guides, and payments.</p>
      <p><code>Node.js</code> <code>Express</code> <code>MongoDB</code> <code>Mongoose</code> <code>React</code> <code>SSLCommerz</code></p>
      <p><a href="https://github.com/SajidurCodes/Tour-Management"><strong>Repository ↗</strong></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📄 DocuMind</h3>
      <p><strong>Document Q&amp;A with page citations</strong></p>
      <p>Upload a PDF or text file and ask a question in the browser. DocuMind retrieves passages by keyword and sends them to a language model through Groq. It preserves PDF page numbers during extraction so readers can check the cited passage themselves.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>SQLite</code> <code>Groq</code> <code>Render</code></p>
      <p>
        <a href="https://github.com/SajidurCodes/DocuMind"><strong>Repository ↗</strong></a> ·
        <a href="https://documind-vc21.onrender.com/">Live demo</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🔌 DataBridge MCP</h3>
      <p><strong>CSV inspection through an API and MCP tools</strong></p>
      <p>Exposes CSV inspection through FastAPI and the Model Context Protocol (MCP). An API client or an MCP client can request an inspection. The repository includes profiling benchmarks and a suite of <strong>91 passing tests</strong>.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>MCP</code> <code>CSV</code></p>
      <p><a href="https://github.com/SajidurCodes/Databridge-MCP"><strong>Repository ↗</strong></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>📈 ChurnLens</h3>
      <p><strong>Customer churn prediction and model serving</strong></p>
      <p>Compared baseline models, evaluated calibration, and selected a decision threshold before serving the frozen model through FastAPI. On the held-out test set, the model achieved <strong>0.9723 ROC-AUC</strong> and <strong>0.8872 average precision</strong>. A fresh checkout passed 78 tests.</p>
      <p><code>Python</code> <code>scikit-learn</code> <code>FastAPI</code></p>
      <p><a href="https://github.com/SajidurCodes/ChurnLens"><strong>Repository ↗</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>💬 LangChain Runnable Chatbot</h3>
      <p><strong>Question routing and structured LLM responses</strong></p>
      <p>A keyword classifier routes programming, math, and general questions without an extra LLM call. Each route generates an answer, summary, and keywords in parallel. Pydantic validates the response before Streamlit displays it.</p>
      <p><code>Python</code> <code>LangChain</code> <code>Pydantic</code> <code>Groq</code> <code>Streamlit</code></p>
      <p><a href="https://github.com/SajidurCodes/LangChain-Chatbot"><strong>Repository ↗</strong></a></p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/SajidurCodes?tab=repositories">
    <img src="https://img.shields.io/badge/Browse_all_repositories-162733?style=for-the-badge&logo=github&logoColor=35DDA5" alt="Browse all repositories" />
  </a>
</p>

## 🛠️ Technical skills

<p align="center">
  <img
    src="https://skillicons.dev/icons?i=ts,js,nodejs,express,postgres,prisma,mongodb,react,nextjs,tailwind,python,fastapi,pytorch,git&theme=dark&perline=7"
    alt="TypeScript, JavaScript, Node.js, Express, PostgreSQL, Prisma, MongoDB, React, Next.js, Tailwind CSS, Python, FastAPI, PyTorch, Git"
  />
</p>

| Area | Hands-on experience |
| --- | --- |
| **Backend development** | REST APIs with Node.js, Express, TypeScript, and FastAPI. JWT authentication, role-based authorization, and request validation. |
| **Databases** | Relational modeling with PostgreSQL and Prisma, MongoDB with Mongoose, and SQLite for document storage. |
| **Full-stack development** | React and Next.js dashboards, protected routes, search and filters, and forms with Zod validation. |
| **Payments** | Stripe Checkout, signed payment webhooks, and SSLCommerz booking payments. |
| **AI integration** | Groq API, keyword-based retrieval, page citations, LangChain routing, Pydantic responses, and MCP tools. |
| **Machine learning** | Model comparison, calibration, threshold selection, scikit-learn, and PyTorch fundamentals. |

## 🎓 Education and research

**B.Sc. in Computer Science and Engineering, BRAC University**  
Dhaka, Bangladesh · September 2022 – September 2026

For our undergraduate thesis, my team studied crop-yield prediction under data scarcity. We compared centralized and federated learning using agricultural and climate records, then evaluated how fine-tuning a model for Bangladesh affected its prediction error.

## 📊 GitHub activity

<p align="center">
  <img src="./profile/stats.svg" width="48%" alt="Sajidur's GitHub statistics" />
  <img src="./profile/top-langs.svg" width="48%" alt="Language distribution across Sajidur's repositories" />
</p>

### 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SajidurCodes/SajidurCodes/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SajidurCodes/SajidurCodes/output/snake.svg" />
    <img src="https://raw.githubusercontent.com/SajidurCodes/SajidurCodes/output/snake.svg" width="100%" alt="Animated snake moving through Sajidur's GitHub contribution graph" />
  </picture>
</p>

## 🧩 Problem solving

<p align="center">
  <a href="https://leetcode.com/u/Sajidursiam/">
    <img
      src="https://leetcard.jacoblin.cool/Sajidursiam?theme=nord&font=Fira%20Code&ext=heatmap&border=0&radius=12"
      alt="Sajidur's LeetCode statistics and problem-solving heatmap"
    />
  </a>
</p>

## 🌐 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/sajidur-rahman-siam-17870b310">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:sajidursiam18@gmail.com">
    <img src="https://img.shields.io/badge/Email-B54135?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Sajidur" />
  </a>
  <a href="https://www.kaggle.com/sajidursiam">
    <img src="https://img.shields.io/badge/Kaggle-087BA3?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
  </a>
  <a href="https://medium.com/@sajidursiam18">
    <img src="https://img.shields.io/badge/Medium-162733?style=for-the-badge&logo=medium&logoColor=white" alt="Medium articles" />
  </a>
  <a href="https://x.com/SajidurSiamVai">
    <img src="https://img.shields.io/badge/X-162733?style=for-the-badge&logo=x&logoColor=white" alt="X profile" />
  </a>
</p>

<p align="center">
  <em>“My life is like a Christopher Nolan movie — confusing at first, but somehow it all comes together.”</em> 😅
</p>

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:087F70,50:12344A,100:0D1117&height=110&section=footer&text=Thanks%20for%20visiting&fontSize=20&fontColor=FFFFFF&fontAlignY=70&animation=fadeIn"
    width="100%"
    alt="Thanks for visiting"
  />
</div>
