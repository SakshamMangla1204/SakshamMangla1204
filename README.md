<div align="center">

<img src="banner updated.gif" width="100%"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=16&duration=2500&pause=1200&color=F0E040&center=true&vCenter=true&width=860&height=50&lines=⚡+Data+is+the+new+oil+—+and+I'm+here+to+mine+it;sys%3A%3A+walk_forward_validation(btc)+→+DEPLOYED+✓;sys%3A%3A+risk_model.predict(vitals)+→+FastAPI+→+AWS+✓;sys%3A%3A+docker+build+%26%26+lambda+deploy+→+LIVE+✓)](https://github.com/SakshamMangla1204)

</div>

<div align="center">

![](https://img.shields.io/badge/PYTHON-000000?style=for-the-badge&logo=python&logoColor=f0e040)
![](https://img.shields.io/badge/XGBOOST-000000?style=for-the-badge&logoColor=f0e040)
![](https://img.shields.io/badge/FASTAPI-000000?style=for-the-badge&logo=fastapi&logoColor=00ffff)
![](https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=f0e040)
![](https://img.shields.io/badge/SKLEARN-000000?style=for-the-badge&logo=scikit-learn&logoColor=00ffff)
![](https://img.shields.io/badge/DOCKER-000000?style=for-the-badge&logo=docker&logoColor=00ffff)
![](https://img.shields.io/badge/TENSORFLOW-000000?style=for-the-badge&logo=tensorflow&logoColor=f0e040)
![](https://img.shields.io/badge/FLASK-000000?style=for-the-badge&logo=flask&logoColor=ffffff)

</div>

---

<table>
<tr>
<td width="54%" valign="top">

```python
# ░░ SYSTEM BOOT ░░  /src/saksham.py
# ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓

class SakshamMangla:

    ID     = "B.Tech ECS '27 · India 🇮🇳"
    STATUS = "ONLINE ◉"

    stack = {
        "ML"    : ["XGBoost", "sklearn", "TF"],
        "APIs"  : ["FastAPI", "Flask", "REST"],
        "cloud" : ["AWS S3", "Lambda", "Rekognition"],
        "tools" : ["Docker", "Git", "Jupyter"],
    }

    missions = [
        "📈  financial ML pipelines",
        "🧬  healthcare AI + blockchain",
        "🤖  autonomous research agents",
        "☁️   serverless inference @ AWS",
    ]

    def execute(self, idea: str) -> str:
        model = self.train(idea)
        api   = self.wrap_fastapi(model)
        return self.deploy_aws(api)  # LIVE ✓
```

</td>
<td width="46%" align="center" valign="middle">

<img src="gif%20banner.gif" width="96%"/>

</td>
</tr>
</table>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=36&text=◈%20ACTIVE%20DEPLOYMENTS%20◈&fontSize=14&fontColor=f0e040&fontAlignY=65&animation=twinkling" width="100%"/>
</div>

<br/>

### `01` — 📈 Bitcoin Return Predictor

```
┌─────────────────────────────────────────────────────────────────┐
│  INPUT  :  raw OHLCV data                                       │
│  OUTPUT :  return forecasts + risk metrics                      │
├─────────────────────────────────────────────────────────────────┤
│  raw_data → feature_eng()   # SMA · volatility · lag feats     │
│           → walk_forward()  # zero lookahead bias               │
│           → compare()       # LinearReg  ⚔  XGBoost            │
│           → metrics()       # RMSE · MAE · Sharpe · Drawdown   │
│           → export()        # prod-ready module ✓               │
└─────────────────────────────────────────────────────────────────┘
```

![](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=f0e040)
![](https://img.shields.io/badge/XGBoost-000?style=flat-square&logoColor=f0e040)
![](https://img.shields.io/badge/Pandas-000?style=flat-square&logo=pandas&logoColor=00ffff)
![](https://img.shields.io/badge/NumPy-000?style=flat-square&logo=numpy&logoColor=00ffff)

---

### `02` — 🧬 NeuroLedger

```
┌─────────────────────────────────────────────────────────────────┐
│  clinical_data ──► risk_model.predict() ──► FastAPI /infer     │
│                                         │                       │
│                                    AWS S3 ◄── store            │
│                                         │                       │
│                         blockchain_log(sha256, ts) ◄── audit   │
├─────────────────────────────────────────────────────────────────┤
│  MODELS : patient risk scorer · fatigue detector               │
│  STACK  : FastAPI · AWS S3 · integrity chain                   │
└─────────────────────────────────────────────────────────────────┘
```

![](https://img.shields.io/badge/FastAPI-000?style=flat-square&logo=fastapi&logoColor=00ffff)
![](https://img.shields.io/badge/AWS-000?style=flat-square&logo=amazon-aws&logoColor=f0e040)
![](https://img.shields.io/badge/sklearn-000?style=flat-square&logo=scikit-learn&logoColor=00ffff)
![](https://img.shields.io/badge/Blockchain-000?style=flat-square&logoColor=ffffff)

---

### `03` — 🤖 Founder Research Agent

```python
# AUTONOMOUS MULTI-STAGE PIPELINE
agent = FounderResearchAgent(
    memory   = "persistent_json",    # survives restarts
    fallback = "llm_orchestration",  # graceful degradation
    output   = "structured_report"
)
# ── query ──► web_search ──► extract ──► memory.store()
#          ──► llm_enrich ──► rank    ──► Flask /api/report
agent.run(founder_name)  # ──► full intelligence brief ✓
```

![](https://img.shields.io/badge/LLM_Agents-000?style=flat-square&logo=openai&logoColor=f0e040)
![](https://img.shields.io/badge/Flask-000?style=flat-square&logo=flask&logoColor=ffffff)
![](https://img.shields.io/badge/JSON_Memory-000?style=flat-square&logoColor=00ffff)

---

### `04` — 👾 Developer AI Agent

```bash
# ENDPOINT
POST /api/analyze
{ "code": "...", "tasks": ["bug_detection", "auto_docs"] }

# RESPONSE
{ "bugs": [...], "suggestions": [...], "docs": "..." }
# STATUS 200 ✓
```

![](https://img.shields.io/badge/Python-000?style=flat-square&logo=python&logoColor=f0e040)
![](https://img.shields.io/badge/REST_API-000?style=flat-square&logo=fastapi&logoColor=00ffff)
![](https://img.shields.io/badge/LLM_Powered-000?style=flat-square&logo=openai&logoColor=f0e040)

---

### `05` — ☁️ Face Recognition Attendance

```
TRIGGER  :  image ──► S3 bucket
PIPELINE :  S3 event ──► Lambda() ──► Rekognition.compare_faces()
                                   ──► attendance_db.write(id, ts)
ARCH     :  fully serverless · zero cold infra · event-driven
```

![](https://img.shields.io/badge/Rekognition-000?style=flat-square&logo=amazon-aws&logoColor=f0e040)
![](https://img.shields.io/badge/Lambda-000?style=flat-square&logo=aws-lambda&logoColor=00ffff)
![](https://img.shields.io/badge/S3-000?style=flat-square&logo=amazon-s3&logoColor=f0e040)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=36&text=◈%20TECH%20MATRIX%20◈&fontSize=14&fontColor=00ffff&fontAlignY=65&animation=twinkling" width="100%"/>
</div>

<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,c,cpp,java,html,css&theme=dark&perline=6"/>

<br/><br/>

![](https://img.shields.io/badge/scikit--learn-000000?style=for-the-badge&logo=scikit-learn&logoColor=00ffff)
![](https://img.shields.io/badge/XGBoost-000000?style=for-the-badge&logoColor=f0e040)
![](https://img.shields.io/badge/TensorFlow-000000?style=for-the-badge&logo=tensorflow&logoColor=f0e040)
![](https://img.shields.io/badge/NumPy-000000?style=for-the-badge&logo=numpy&logoColor=00ffff)
![](https://img.shields.io/badge/Pandas-000000?style=for-the-badge&logo=pandas&logoColor=00ffff)
![](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=python&logoColor=ffffff)

![](https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=00ffff)
![](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=ffffff)
![](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=00ffff)
![](https://img.shields.io/badge/AWS-000000?style=for-the-badge&logo=amazon-aws&logoColor=f0e040)
![](https://img.shields.io/badge/Streamlit-000000?style=for-the-badge&logo=streamlit&logoColor=f0e040)

![](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=f0e040)
![](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=ffffff)
![](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=f0e040)
![](https://img.shields.io/badge/VS_Code-000000?style=for-the-badge&logo=visual-studio-code&logoColor=00ffff)
![](https://img.shields.io/badge/Jupyter-000000?style=for-the-badge&logo=jupyter&logoColor=f0e040)

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=36&text=◈%20SYSTEM%20METRICS%20◈&fontSize=14&fontColor=f0e040&fontAlignY=65&animation=twinkling" width="100%"/>
</div>

<br/>

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SakshamMangla1204&show_icons=true&hide_border=true&bg_color=000000&title_color=f0e040&icon_color=00ffff&text_color=ffffff&border_radius=0" height="170"/>
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=SakshamMangla1204&hide_border=true&background=000000&ring=f0e040&fire=ff0080&currStreakLabel=f0e040&sideLabels=00ffff&dates=666666&border_radius=0" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SakshamMangla1204&layout=compact&hide_border=true&bg_color=000000&title_color=f0e040&text_color=00ffff&border_radius=0" height="150"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=SakshamMangla1204&theme=tokyo-night&hide_border=true&bg_color=000000&color=f0e040&line=00ffff&point=ff0080&area=true&area_color=00ffff"/>

</div>

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=36&text=◈%20NEURAL%20ACTIVITY%20◈&fontSize=14&fontColor=00ffff&fontAlignY=65&animation=twinkling" width="100%"/>
</div>

<br/>

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)"  srcset="https://raw.githubusercontent.com/SakshamMangla1204/SakshamMangla1204/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SakshamMangla1204/SakshamMangla1204/output/github-contribution-grid-snake.svg"/>
  <img src="https://raw.githubusercontent.com/SakshamMangla1204/SakshamMangla1204/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

---

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=SakshamMangla1204&theme=darkhub&no-frame=true&row=1&column=7&margin-w=4"/>
</div>

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GITHUB-000000?style=for-the-badge&logo=github&logoColor=ffffff)](https://github.com/SakshamMangla1204)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-000000?style=for-the-badge&logo=linkedin&logoColor=00ffff)](https://linkedin.com/in/saksham-mangla11)
[![Gmail](https://img.shields.io/badge/GMAIL-000000?style=for-the-badge&logo=gmail&logoColor=f0e040)](mailto:saksham.quant@gmail.com)

<br/>

![](https://komarev.com/ghpvc/?username=SakshamMangla1204&style=flat-square&color=f0e040&label=UPTIME+COUNT)

</div>

<br/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=14&duration=4000&pause=3000&color=F0E040&center=true&vCenter=true&width=860&height=45&lines=◢+train+→+validate+→+deploy+→+repeat+◣)](https://github.com/SakshamMangla1204)
