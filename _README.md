# Mica Wen — Engineering Portfolio

## Your Portfolio URL

**Your site**: <https://mica-wen.github.io/>

**Your resume**: <https://mica-wen.github.io/MicaWen-Resume.pdf>

Use `https://mica-wen.github.io/` as your portfolio link in all applications.

## How to Publish Your Own Site

### Step 1: Create a GitHub Account

1. Go to <https://github.com/join> in your browser
2. Fill in the signup form:
   - **Username**: `mica-wen`
   - **Email**: `micawen.sf@gmail.com`
   - Choose a strong password
3. Complete the verification puzzle and click **Create account**
4. Check your email for a verification link and click it

### Step 2: Create the Repository

1. Once logged in, click the **+** button in the top-right corner of GitHub, then click **New repository**
2. Fill in the form exactly like this:
   - **Repository name**: `mica-wen.github.io` (this exact name is required — it tells GitHub to host it as your website)
   - **Description**: (optional) `Mica Wen's engineering portfolio`
   - **Public**: make sure the **Public** radio button is selected (GitHub Pages requires this for free accounts)
   - Do **NOT** check "Add a README file" — leave it unchecked
   - Do **NOT** change the .gitignore or license dropdowns
3. Click **Create repository**
4. You'll land on a "Quick setup" page — keep this tab open, you'll need it in the next step

### Step 3: Upload Your Portfolio Files

1. On the "Quick setup" page, click the link that says **uploading an existing file** (it's in the middle of the page, in the sentence "…or upload an existing file")
2. Open a Finder window and navigate to the `portfolio-site` folder
3. Drag **all** of the following into the GitHub upload area:
   - `index.html`
   - `style.css`
   - `MicaWen-Resume.pdf`
   - The entire `images/` folder (drag the folder itself)
   - The `.github/` folder (this contains the auto-deploy workflow — **important!**)
     - Note: `.github` is a hidden folder. In Finder, press **Cmd + Shift + .** (period) to show hidden files, then drag it in
4. Scroll down to the **"Commit changes"** section at the bottom:
   - In the message box, type: `Initial portfolio upload`
   - Make sure **"Commit directly to the main branch"** is selected
5. Click **Commit changes**
6. Wait for the upload to finish — it may take 30–60 seconds depending on image sizes

### Step 4: Enable GitHub Pages

The `.github/workflows/deploy.yml` file you uploaded will handle deployment automatically. But you need to enable it:

1. In your repository, click the **Settings** tab (gear icon, top of the page)
2. In the left sidebar, scroll down and click **Pages**
3. Under **"Build and deployment"**, find the **Source** dropdown
4. Change it from "Deploy from a branch" to **GitHub Actions**
5. That's it — no other settings to change

### Step 5: Verify Your Site Is Live

1. Go to the **Actions** tab in your repository (top menu bar)
2. You should see a workflow run called "Deploy to GitHub Pages" — wait for the green checkmark (1–2 minutes)
3. Once it's green, visit <https://mica-wen.github.io/> in your browser
4. You should see your portfolio! If not, wait another minute and refresh

### Troubleshooting

- **Site shows 404**: Make sure the repository name is exactly `mica-wen.github.io` (no typos, all lowercase). Also check that GitHub Pages source is set to "GitHub Actions" (not "Deploy from a branch").
- **Images don't load**: Make sure the `images/` folder was uploaded and the filenames in `index.html` match exactly (including uppercase/lowercase).
- **Old content showing**: GitHub Pages can take up to 5 minutes to update. Try a hard refresh in your browser (Cmd + Shift + R on Mac).
- **Workflow failed (red X in Actions tab)**: Click on the failed run to see the error. Usually this means a file is missing or the `.github/workflows/deploy.yml` file wasn't uploaded.

---

## How to Add Your Images

1. Put all your project photos and CAD renders in the `images/` folder
2. Open `index.html` in a text editor
3. Find each `<div class="placeholder">` block and replace it with an `<img>` tag:

**Before:**
```html
<div class="placeholder">Robot photo<br>(replace with your image)</div>
```

**After:**
```html
<img src="images/ftc-robot.jpg" alt="FTC competition robot">
```

## How to Customize Text

Open `index.html` and search for `CUSTOMIZE` or `REPLACE` comments. These mark spots where you should fill in your specific details (e.g., which robot subsystems you worked on).

## How to Update the Live Site

After editing files locally, push changes to GitHub:

```
cd portfolio-site
git add .
git commit -m "Update portfolio content"
git push
```

The site auto-deploys in about 1 minute after each push.

---

## Application Checklist for Mica

Apply using your Gmail: **micawen.sf@gmail.com**

Portfolio link to paste: **https://mica-wen.github.io/**

---

### Priority 1: Portfolio Required — Apply First

**1. Terranova — Controls/Robotics Intern**

- Location: Berkeley, CA
- Duration: May–September (flexible)
- Pay: $28/hr + relocation
- Requirements: CS/Robotics degree, Python/C++, ROS2, control systems
- Why Mica fits: ROS 2 certification, Python/C++ skills, Gazebo simulation experience, drone research with computer vision pipeline
- [Apply here](https://jobs.ashbyhq.com/Terranova/58b4f28b-80eb-449a-ad41-63469edb8c6d?locationId=ad7f0008-9ffa-4a71-88ac-b759773a0e44)

**2. Collaborative Robotics (Cobot) — ME, Robotics Intern**

- Location: Santa Clara, CA (onsite)
- Duration: Summer 2026, 12 weeks
- Pay: $20/hr
- Requirements: ME/Robotics program, 3D CAD (SolidWorks), hands-on tool experience, rising sophomore/junior preferred
- Why Mica fits: SolidWorks + Fusion 360 proficiency, extensive fabrication training (CNC, 3D printing, welding, laser cutting), FTC robotics build experience, NER electromechanical work
- [Apply here](https://jobs.ashbyhq.com/cobot/71de3bf5-ff6d-4a47-b111-418bb662d89b)

**3. Zipline — Mechanical Engineering Intern**

- Location: South San Francisco, CA
- Duration: May/June–August 2026
- Pay: $38–42/hr + housing stipend
- Requirements: Completed 2nd year, multiple mechanical systems built outside classroom, CAD proficiency, Raspberry Pi experience
- Why Mica fits: FTC robot (full design-to-build lifecycle with awards), NER swirl pot design + SLA printing, Raspberry Pi + Arduino experience, extensive fabrication skills. Portfolio shows exactly what they ask for.
- [Apply here](https://www.zipline.com/careers/open-roles/7549493003)

**4. Atomic Semi — Mechanical Engineering Intern**

- Location: San Francisco, CA (onsite)
- Duration: 4–8 months starting May/June
- Pay: ~$50–60/hr equivalent + housing stipend + benefits
- Requirements: Hands-on prototyping, electromechanical assembly, SolidWorks, portfolio required ("show us what you've built")
- Why Mica fits: Strong hands-on fabrication (CNC, 3D printing, welding, soldering, PCB milling), SolidWorks + Fusion 360, FTC build experience, NER thermal system testing. Portfolio directly addresses their ask.
- [Apply here](https://atomicsemi.com/careers/?ashby_jid=6990e072-75a9-4892-a78f-62b94e0a6d3d)

---

### Priority 2: Apply ASAP

**5. Figure AI — Robotics Integration Intern**

- Location: San Jose, CA (5 days/week onsite)
- Duration: Summer 2026
- Pay: $40–50/hr
- Requirements: Robotics/ME/CS degree, C++/Python, ROS2 a bonus, hands-on lab environment
- Why Mica fits: ROS 2 certified, Python/C++ skills, Jetson Nano hardware experience from drone research, hands-on robotics background
- [Apply here](https://job-boards.greenhouse.io/figureai/jobs/4644676006)

**6. Amazon Robotics — Process Engineer Intern/Co-op**

- Location: Westborough/North Reading, MA
- Duration: 6-month co-op (spring/summer/fall options)
- Pay: $42–89/hr
- Requirements: Operations/Industrial/ME degree, process improvement knowledge
- Why Mica fits: ME degree, NER thermal testing involved process analysis, strong teamwork and communication from FTC mentoring and NER collaboration
- [Apply here](https://amazon.jobs/en/jobs/3088774/amazon-robotics-2026-process-engineer-intern-co-op-robotics-manufacturing-and-technical-operations)

**7. Apple — Engineering Program Management Internships**

- Location: United States (multiple)
- Duration: Not specified
- Requirements: ME/CS/EE degree, project management experience, cross-functional leadership
- Why Mica fits: Cross-functional team experience (NER powertrain integration, FTC robotics team lead), strong communication skills (Red Vest mentor, robotics camp counselor)
- [Apply here](https://jobs.apple.com/en-us/details/200606141-3810/engineering-program-management-internships?team=STDNT)

**8. Graphcore — Mechanical Engineering Intern**

- Location: Austin, TX
- Duration: Not specified
- Requirements: ME degree, 3D CAD (Creo preferred), lab experience, analytical skills
- Why Mica fits: Fusion 360 + SolidWorks CAD, NER thermal testing lab experience, strong analytical coursework (Thermo, Fluids, Materials)
- [Apply here](https://job-boards.greenhouse.io/graphcore/jobs/8386073002)

**9. Zoox — Hardware Integration and Test Intern**

- Location: Bay Area, CA (onsite)
- Duration: 12-week summer (May/June 2026)
- Requirements: Engineering degree, analytical and diagnostic skills
- Why Mica fits: FTC robotics hardware integration experience, NER system-level thermal testing, fabrication skills for building test fixtures
- [Apply here](https://jobs.lever.co/zoox/98429957-337e-459f-94b6-fa6acfce82b9)

**10. Zoox — Mechanical Engineering Intern**

- Location: Bay Area, CA (onsite)
- Duration: 12-week summer or 6-month co-op
- Pay: $6,500–9,500/month + housing stipend
- Requirements: BS/MS in ME, prior internship or relevant project experience, 2D/3D design
- Why Mica fits: SolidWorks + Fusion 360, FTC full robot design-to-build, NER vehicle-level integration work, extensive fabrication training
- [Apply here](https://jobs.lever.co/zoox/9563a5de-8361-4fd1-946a-be872332ae26)

---

### Priority 3: Robotics & ME Roles

**11. Apptronik — Perception Software Intern, Humanoid Robotics**

- Location: Austin, TX
- Duration: Not specified
- Requirements: CS/Robotics degree, Python/C++, deep learning, computer vision
- Why Mica fits: Python/C++ skills, drone research with stereo vision + COLMAP 3D reconstruction, ROS 2 + Gazebo, Jetson Nano sensor integration
- [Apply here](https://job-boards.greenhouse.io/apptronik/jobs/5789359004?gh_jid=5789359004)

**12. Proception — Mechanical Engineering Intern**

- Location: Palo Alto, CA
- Duration: 6–12 months
- Requirements: ME background, humanoid robotics interest (detailed reqs not on public page)
- Why Mica fits: ME degree, FTC robotics mechanical design, strong fabrication skills, CAD proficiency
- [Apply here](https://www.proception.ai/contact?subject=internship&position=%F0%9F%8C%B1%20Mechanical%20Engineering%20Intern%20(6-12%20months)&audience=public)

**13. Neptune Medical — Robotics Product Performance Engineering Co-op**

- Location: Burlingame, CA
- Duration: 6 months minimum, Spring/Summer 2026
- Pay: $31–38/hr
- Requirements: ME/Biomedical Engineering, SolidWorks, Python/MATLAB, electromechanical systems, test method development
- Why Mica fits: SolidWorks proficiency, Python skills, NER thermal testing experience (test design + data analysis), strong technical writing
- [Apply here](https://job-boards.greenhouse.io/neptunemedical/jobs/4643893005)

**14. Neptune Medical — Clinical Development Engineering Co-op, Robotics**

- Location: Burlingame, CA
- Duration: 6 months minimum
- Pay: $31–38/hr
- Requirements: ME/Biomedical Engineering, fabrication (machining, 3D printing), hands-on testing, self-directed
- Why Mica fits: Extensive fabrication training (CNC, 3D printing, soldering), hands-on prototyping from FTC + NER, walker redesign shows human-centered design thinking
- [Apply here](https://job-boards.greenhouse.io/neptunemedical/jobs/4643027005)

**15. Neptune Medical — Product Development Engineering Co-op, Robotics**

- Location: Burlingame, CA
- Duration: 6 months minimum, Winter/Spring/Summer 2026
- Pay: $31–38/hr
- Requirements: ME/Biomedical Engineering, CAD, fabrication, Python/MATLAB, prototyping and testing
- Why Mica fits: Full design-to-prototype experience (FTC, NER swirl pot), SolidWorks + Fusion 360, Python, extensive fabrication skills
- [Apply here](https://job-boards.greenhouse.io/neptunemedical/jobs/4643621005)

**16. Neuralink — Mechanical Engineering Intern, Robotics**

- Location: Fremont, CA (onsite)
- Duration: Winter 2026 (Jan–Apr) or Summer 2026 (May–Aug)
- Pay: $35/hr
- Requirements: 6+ months technical experience outside classroom, SolidWorks, machining + rapid prototyping, precision design
- Why Mica fits: SolidWorks + Fusion 360, NER swirl pot (concept-to-print), extensive fabrication training (CNC, SLA, soldering), FTC multi-season build experience exceeds the 6-month minimum
- [Apply here](https://neuralink.com/careers/apply/?gh_jid=6514169003&gh_src=c356a2533us)

**17. Shield AI — Mission Systems Engineering Co-op**

- Location: San Diego/Dallas
- Duration: June–December 2026 (6 months)
- Pay: $35–55/hr + housing stipend
- Requirements: EE/Aerospace/STEM degree, multidisciplinary team experience, rapid prototyping
- Why Mica fits: Strong team collaboration (NER, FTC), rapid prototyping and fabrication skills, embedded systems experience (Arduino, Raspberry Pi, Jetson Nano)
- [Apply here](https://jobs.lever.co/shieldai/0f9800ed-7967-485a-bd3d-6a6e42d8d581)

**18. Carnegie Robotics — Mechanical Engineering Intern**

- Location: Pittsburgh, PA (onsite)
- Duration: Summer 2026
- Requirements: SolidWorks (preferred), portfolio of self-designed projects, FEA/thermal analysis, FIRST Robotics or similar teamwork
- Why Mica fits: FIRST Robotics FTC with awards (they explicitly list this), SolidWorks + Fusion 360, NER thermal analysis, strong portfolio material
- [Apply here](https://carnegie-robotics.breezy.hr/p/d733482a2a42-mechanical-engineering-intern-summer-2026?source=www.carnegierobotics.com/careers&popup=true)

**19. Intuitive Surgical — Robotics & Controls Engineering Intern**

- Location: Sunnyvale, CA
- Duration: Not specified
- Requirements: Controls/Robotics/ME degree, C++/Python, control systems (PID), SolidWorks/AutoCAD, robotics project experience
- Why Mica fits: Python/C++ skills, SolidWorks, FTC robotics project experience, ROS 2 + Gazebo for control systems, NER thermal system (feedback-based testing)
- [Apply here](https://careers.intuitive.com/en/jobs/744000105927510/JOB211942/robotics-controls-engineering-intern/)

**20. Kodiak Robotics — Simulation Intern**

- Location: Mountain View, CA
- Duration: 12–16 weeks starting June 2026
- Pay: $10,000/month
- Requirements: C++ on production codebases, CS/EE/ME degree, junior/senior/grad, simulation frameworks a bonus
- Why Mica fits: C++ skills, Gazebo simulation experience, ROS 2 certification, ME degree with strong analytical coursework
- [Apply here](https://job-boards.greenhouse.io/kodiak/jobs/4024796009)

**21. Bosch — Robot Learning Engineering Intern**

- Location: Pittsburgh, PA
- Duration: Flexible start
- Pay: $27–51/hr
- Requirements: Robotics/ML degree, 3+ years testing interactive systems, VR/simulation familiarity, bug tracking tools
- Why Mica fits: Robotics software experience (ROS 2, Gazebo), hands-on robot operation from FTC, Python skills for data collection workflows
- [Apply here](https://jobs.bosch.com/en/job/REF276376K-robot-learning-engineering-intern)

**22. Nvidia — Autonomous Vehicles & Robotics Intern**

- Location: Santa Clara, CA
- Duration: 12 weeks minimum
- Pay: $20–71/hr
- Requirements: EE/CE degree, C++/Python/CUDA/ROS, sensor knowledge (LiDAR, cameras), deep learning frameworks
- Why Mica fits: ROS 2 certified, Python/C++, stereo camera + computer vision experience from drone research, Jetson Nano (NVIDIA platform)
- [Apply here](https://nvidia.eightfold.ai/careers?query=ROS&start=0&pid=893384237029&sort_by=relevance)

**23. Nvidia — Hardware Engineering Intern**

- Location: Santa Clara, CA
- Duration: 12 weeks minimum
- Pay: $20–71/hr
- Requirements: EE/ME degree, CAD (SolidWorks, Creo), MATLAB, lab tools, Python
- Why Mica fits: SolidWorks + Fusion 360, MATLAB, Python, NER lab testing experience, extensive fabrication training
- [Apply here](https://nvidia.eightfold.ai/careers?query=intern&start=30&location=Santa+Clara%2C+CA%2C+United+States&pid=893384237079&sort_by=relevance&filter_distance=160&filter_include_remote=1)

---

### Priority 4: General ME Roles

**24. Pacific Fusion — Mechanical Engineering Intern**

- Location: San Leandro, CA (onsite)
- Duration: 10+ weeks starting June 2026
- Pay: $38–48/hr + equity + benefits
- Requirements: Junior/Senior ME, CAD (Creo/SolidWorks), stress analysis, design for manufacturing, MATLAB/Python
- Why Mica fits: SolidWorks + Fusion 360, Python/MATLAB, NER design-for-manufacturing (swirl pot for SLA), strong ME coursework (Statics, Dynamics, Materials, Mechanics of Materials)
- [Apply here](https://job-boards.greenhouse.io/pacificfusion/jobs/4107842009)

**25. Lam Research — Mechanical Engineering Intern**

- Location: Fremont, CA
- Duration: Summer 2026
- Pay: $30–40/hr
- Requirements: Sophomore/Junior in ME, hands-on experience, heat transfer + fluid dynamics analysis
- Why Mica fits: ME sophomore with hands-on lab experience, NER thermal/fluid analysis work, Thermo + Fluid Mechanics coursework, fabrication skills
- [Apply here](https://careers.lamresearch.com/careers?start=0&pid=1099550614933&sort_by=timestamp)

**26. Johns Hopkins APL — Internships**

- Location: Laurel, MD
- Duration: Varies by position
- Requirements: Varies (search portal — browse for ME/robotics intern roles)
- Why Mica fits: ME degree, robotics + embedded systems experience, strong analytical background. Browse portal for specific ME/robotics openings.
- [Apply here](https://careers.jhuapl.edu/internships/jobs?keywords=intern)

**27. Teledyne FLIR — Mechanical Design Engineering Intern**

- Location: Camarillo, CA
- Duration: Full-time internship
- Pay: ~$24–32/hr
- Requirements: Pursuing BS in Engineering, SolidWorks/AutoCAD, ASME drawing standards, U.S. Citizen required
- Why Mica fits: SolidWorks proficiency, 3D CAD modeling experience from FTC + NER, ME coursework covers design fundamentals, fabrication + prototyping experience
- [Apply here](https://flir.wd1.myworkdayjobs.com/en-US/flircareers/jobs/details/Mechanical-Design-Engineering-Intern_REQ33034?q=intern)

---

### Removed Listings (verified dead/expired)

The following were on the original list but are no longer available:

- ~~Neptune Medical — Robotic Sys Eng (Job 4641211005)~~ — listing removed
- ~~Anyware Robotics — Mechatronics Intern~~ — returns 403, likely expired
- ~~Skydio — Hardware Test & Reliability Intern~~ — returns 404, removed
- ~~Think Surgical — Sustainable Engineer Co-op~~ — ADP portal, cannot verify listing

---

## File Structure

```
portfolio-site/
  index.html          ← The entire portfolio (single page)
  style.css           ← All styling
  MicaWen-Resume.pdf  ← Resume (linked from site)
  images/             ← Put your photos, CAD renders here
  _README.md          ← This file
```
