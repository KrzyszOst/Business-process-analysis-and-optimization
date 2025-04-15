# 🧠 Business Process Analysis & Optimization – Recruitment at Intel 🏢

This project was created for the **Business Process Analysis and Optimization** course.  
It focuses on modeling and improving the **employee recruitment process** at **Intel**, specifically for three job roles.

---

## 🎯 Project Overview

The aim was to design a BPMN-modeled process, simulate its execution, and propose optimizations to improve:

- Recruitment speed  
- Candidate satisfaction  
- Process costs  
- Quality of new hires

The project compares a **default recruitment scenario** and an **optimized version**, providing measurable KPIs and improvements.

---

## 🏗️ Process Description

The recruitment process includes the following steps:

1. **Application** – Candidate selects a job, sends a CV, and completes a qualification test  
2. **CV Review** – Recruiters evaluate applications within 3 days  
3. **Interview Stages** – First and second round interviews with technical and soft skills evaluation  
4. **Job Offer** – Negotiation and final acceptance  
5. **Onboarding & Training** – Role-specific onboarding and internal training program  

---

## 📊 Optimization Goals

- ⏱️ **Reduce recruitment duration**  
- 💸 **Lower process cost**  
- 👨‍💼 **Improve candidate quality**  
- 🔁 **Shorten onboarding cycle**

---

## 🛠️ Simulation Tools & Parameters

- 📆 Work Schedule: Mon–Fri, 9AM–3PM  
- 🎯 Resources: 300 applicants, 5 recruiters, 2 HR specialists  
- ⏱️ Task Durations: Based on normal distributions  
- 📥 External Data: Imported via `.xlsx` with job_type, test_score, and priority

### Subprocesses:
- **Interview**: 5 structured steps, scoring both technical and soft skills  
- **Job Training**: Facility tour, tool/system introduction, responsibilities, Q&A

---

## ⚙️ Optimization Changes

In the improved scenario:
- Recruiters increased from 1 to 5  
- HR trainers increased from 1 to 2  
- Early CV filtering via test results (auto-reject < 55 pts)  
- Option to hire after first interview if scores are high  
- Longer workdays (1 hour more)

---

## 📈 Results Comparison

| Metric                          | Default        | Optimized       | Change        |
|---------------------------------|----------------|------------------|---------------|
| Recruitment Time (avg)         | 78.16 days     | 56.18 days       | -28%          |
| Average Cycle Time             | 5.57 days      | 1.8 days         | -68%          |
| Cost                           | $8189.74       | $4996.99         | -39%          |
| Candidates Hired               | 8              | 11               | +37.5%        |
| Avg. Technical Skills Score    | 8.5            | 9.0              | +6%           |
| Avg. Soft Skills Score         | 6.75           | 9.27             | +37%          |
| Wait Count                     | 695            | 416              | -40%          |

---

## 🔍 Key Insights

- **AI pre-filtering** boosts recruiter efficiency and reduces low-quality CV analysis  
- **Early hiring** for high performers shortens process and cuts dropouts  
- **Process restructuring** significantly improved output quality and time-to-hire  
- **Automation and clarity** reduce candidate withdrawals and internal delays

---

## 📌 Additional Features

- External applicant data imported from Excel  
- Simulation scenario comparison with dashboards  
- Clear use of transactional and scenario attributes (e.g. test score, soft skills, cycle time)

---

## 👨‍💻 Team

- Krzysztof Ostrzycki  
- Łukasz Turek

