## DS 7200 Computing III Distributed Computing: Agenda 01



### Admin Items

- Due to travel, we won't meet on Labor Day
- Brief intro / background
- Review Syllabus
- Review Canvas
- Communications:
  - Teams for IM
  - Email TA for grading questions
    - Office Hours: possible times Thursdays 12–5pm or Fridays 10am–5pm  
- Review repo page: `setup.md`

---

### Upcoming Deliverables

Due by Friday, Sep 5 at 11:59pm ET
- Quiz 1: Big Data Intro
- Lab 1: Python Warmup and Logfile Analytics


---

### Activity

As time permits:

- Review [Rivanna OpenOnDemand](https://ood.hpc.virginia.edu/pun/sys/dashboard)
- Review file structure, notebooks
- Brief Review NB: Big Data Systems Foundations  
- Brief Review NB: Spark Getting Started  
- Brief Review: Lab

---

### Rivanna JupyterLab request page

Request PySpark server

| Key       | Value |
| ----------- | :-----------: |
| Rivanna Partition | Interactive, Standard |
| Work Directory | HOME |
| Allocation| ds7200-apt4c |
| Show Additional Options| No |

Notes:    
Interactive partition is free for  < 1 hour  
Start with small number of cores and increase as needed  
Number of hours: when time is up, compute will end. JupyterLab notebooks save contents regularly. Request what you need.

--- 
### Inside Rivanna

Rivanna used for most compute

**STORAGE**  
Shared space: `/standard/ds7200-apt4c` for project data  
You can use this space to organize files for your project: 
1. create folder
2. save relevant files
3. remove the folder and contents when the course ends

**COMPUTE SETUP**  
We have a Jupyter kernel called `DS7200 Spark 3.3`. To use this, you'll need to run the following command from a terminal:

`/standard/ds7200-apt4c/setup.sh`

If you run this in a JupyterLab terminal, you will need to refresh the browser tab. Otherwise, the next time you open JupyterLab, the kernel will be available. 
