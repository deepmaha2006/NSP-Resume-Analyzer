<p><small>Best View in <a href="https://github.com/settings/appearance">Light Mode</a> and Desktop Site (Recommended)</small></p><br/>

<div align="center">
  <h1>🌴 RESUME ANALYSER 🌴</h1>
  <p>A Tool for Resume Analysis, Predictions and Recommendations</p>
  <!-- Badges -->
  <p>
    <img src="https://img.shields.io/github/last-commit/stutiagrawal255-prog/NSP-Resume-Analyzer" alt="last update" />
    <img src="https://badges.frapsoft.com/os/v2/open-source.svg?v=103" alt="open source" />
    <img src="https://img.shields.io/github/languages/top/stutiagrawal255-prog/NSP-Resume-Analyzer?color=red" alt="language" />
    <img src="https://img.shields.io/github/languages/code-size/stutiagrawal255-prog/NSP-Resume-Analyzer?color=informational" alt="code size" />
    <a href="https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/main/LICENSE">
      <img src="https://img.shields.io/github/license/stutiagrawal255-prog/NSP-Resume-Analyzer.svg?color=yellow" alt="license" />
    </a>
  </p>
  
  <!--links-->
  <h4>
    <a href="#preview-">View Demo</a>
    <span> · </span>
    <a href="#setup--installation-">Installation</a>
  </h4>
  <p>
    <small align="justify">
      Built with 🤍 by
      <a href="https://github.com/stutiagrawal255-prog">Stuti Agrawal</a> &
      <a href="https://github.com/deepmaha2006">Deepesh Mahawar</a>
     </small>
  </p>
  <small align="justify">🚀 NSP Resume Analyzer — AI-powered Resume Analysis Tool</small>
</div><br/><br/>

## About the Project 🥱
<div align="center">
    <br/><img src="https://raw.githubusercontent.com/stutiagrawal255-prog/NSP-Resume-Analyzer/main/screenshots/RESUME.png" alt="screenshot" /><br/><br/>
    <p align="justify"> 
      A tool which parses information from a resume using natural language processing and finds the keywords, cluster them onto sectors based on their keywords. 
      And lastly show recommendations, predictions, analytics to the applicant / recruiter based on keyword matching.
    </p>
</div>

## Scope 😲
i. It can be used for getting all the resume data into a structured tabular format and csv as well, so that the organization can use those data for analytics purposes

ii. By providing recommendations, predictions and overall score user can improve their resume and can keep on testing it on our tool

iii. And it can increase more traffic to our tool because of user section

iv. It can be used by colleges to get insight of students and their resume before placements

v. Also, to get analytics for roles which users are mostly looking for

vi. To improve this tool by getting feedbacks

<!-- TechStack -->
## Tech Stack 🍻
<details>
  <summary>Frontend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript">JavaScript</a></li>
  </ul>
</details>

<details>
  <summary>Backend</summary>
  <ul>
    <li><a href="https://streamlit.io/">Streamlit</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
  </ul>
</details>

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.sqlite.org/">SQLite</a></li>
  </ul>
</details>

<details>
<summary>Modules</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/">pandas</a></li>
    <li><a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a></li>
    <li><a href="https://pypi.org/project/pdfminer3/">pdfminer3</a></li>
    <li><a href="https://plotly.com/">Plotly</a></li>
    <li><a href="https://www.nltk.org/">NLTK</a></li>
  </ul>
</details>

<!-- Features -->
## Features 🤦‍♂️
### Client: -
- Fetching Location and Miscellaneous Data

  Using Parsing Techniques to fetch
- Basic Info
- Skills
- Keywords

Using logical programs, it will recommend
- Skills that can be added
- Predicted job role
- Course and certificates
- Resume tips and ideas
- Overall Score
- Interview & Resume tip videos

### Admin: -
- Get all applicant's data into tabular format
- Download user's data into csv file
- View all saved uploaded pdf in Uploaded Resume folder
- Get user feedback and ratings
  
  Pie Charts for: -
- Ratings
- Predicted field / roles
- Experience level
- Resume score
- User count
- City
- State
- Country

### Feedback: -
- Form filling
- Rating from 1 – 5
- Show overall ratings pie chart
- Past user comments history 

## Requirements 😅
### Have these things installed to make your process smooth 
1) Python (3.9+) https://www.python.org/downloads/
2) Visual Studio Code **(Preferred Code Editor)** https://code.visualstudio.com/Download
3) Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe

## Setup & Installation 👀

To run this project, perform the following tasks 😨

Download the code file manually or via git
```bash
git clone https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer.git
```

Create a virtual environment and activate it **(recommended)**

Open your command prompt and change your project directory to ```NSP-Resume-Analyzer``` and run the following command 
```bash
python -m venv venvapp

cd venvapp/Scripts

activate

```

Downloading packages from ```requirements.txt``` inside ``App`` folder
```bash
cd../..

cd App

pip install -r requirements.txt

python -m spacy download en_core_web_sm

```

Go to ```venvapp\Lib\site-packages\pyresparser``` folder

And replace the ```resume_parser.py``` with ```resume_parser.py``` 

which was provided inside ```pyresparser``` folder

``Congratulations 🥳😱 your set-up 👆 and installation is finished 😵🤯``

I hope that your ``venvapp`` is activated and working directory is inside ``App``

Run the ```App.py``` file using
```bash
streamlit run App.py

```

Or simply double-click **RUN_OFFLINE.bat** or **RUN_SERVER.bat**

## Known Error 🤪
If ``GeocoderUnavailable`` error comes up then just check your internet connection and network speed

## Usage
- After the setup it will do stuff's automatically
- You just need to upload a resume and see it's magic
- Admin userid is ``admin`` and password is ``admin@resume-analyzer``

<!-- Roadmap -->
## Roadmap 🛵
* [x] Predict user experience level.
* [x] Add resume scoring criteria for skills and projects.
* [x] Added fields and recommendations for web, android, ios, data science.
* [ ] Add more fields for other roles, and its recommendations respectively. 
* [x] Fetch more details from users resume.
* [ ] View individual user details.

## Contributing 🤘
Pull requests are welcome. 

For major changes, please open an issue first to discuss what you would like to change.

## Acknowledgement 🤗
- <a href="https://www.academia.edu/32543544/Resume_Parser_with_Natural_Language_Processing">Resume Parser with Natural Language Processing</a>
- <a href="https://github.com/OmkarPathak/pyresparser">pyresparser</a>

## Preview 👽

### Client Side

**Main Screen**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/1-main-screen.png?raw=true)

**Resume Analysis**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/2-analysis.jpg?raw=true)

**Skill Recommendation**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/3-recom.png?raw=true)

**Course Recommendation**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/4-recom.png?raw=true)

**Tips and Overall Score**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/5-tipsscore.png?raw=true)

**Video Recommendation**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/user/6-recom.png?raw=true)

### Feedback

**Feedback Form**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/feedback/1-form.png?raw=true)

**Overall Rating Analysis and Comment History**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/feedback/2-analytics.png?raw=true)

### Admin

**Login**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/1-main-screen.png?raw=true)

**User Count and it's data**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/2-user-data.png?raw=true)

**Exported csv file**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/3-user-datacsv.png?raw=true)

**Feedback Data**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/4-feed-data.png?raw=true)

**Pie Chart Analytical Representation of clusters**

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/5-pieexp.png?raw=true)

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/6-piescre.jpg?raw=true)

![Screenshot](https://github.com/stutiagrawal255-prog/NSP-Resume-Analyzer/blob/master/screenshots/admin/7-pielocation.png?raw=true)

### Built with 🤍 by <a href="https://github.com/deepmaha2006">Deepesh Kumar Mahawar</a>
