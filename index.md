---
title: RECOVER
---

<p align="center">
<strong>Published at:</strong> IROS 2024 - <em>International Conference on Intelligent Robots and Systems </em>
</p>

## Paper summary

Recognizing failures during task execution and implementing recovery procedures is challenging in robotics. 
Traditional approaches rely on the availability of extensive data or a tight set of constraints, while more recent approaches leverage large language models (LLMs) to verify task steps and replan accordingly. 
However, these methods often operate offline, necessitating scene resets and incurring in high costs. 
To address this issues, we've developed RECOVER, a neuro-symbolic method combining ontologies, logical rules, and LLM-based planners for real-time failure recovery. 
By leveraging symbolic information, RECOVER enhances LLMs' ability to generate recovery plans and also to decrease the associated costs. 
We demonstrated the capabilities of our method in a simulated kitchen environment, by developing a new ontology, ONTOTHOR, describing the AI2Thor simulator setting. 
Our empirical evaluation shows that ONTOTHOR’s logical rules accurately detect all failures in the analyzed tasks, and that RECOVER considerably outperforms, for both failure detection and recovery, a baseline method reliant solely on LLMs.

### Summary Video

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/RECOVER-full_video_with_audio.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>



## Recovery videos

### Task 1

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T1.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 2

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T2.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 3

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T3.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 4

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T4.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 5

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T5.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 6

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T6.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 7

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T7.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 8

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T8.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 9

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T9.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 10

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T10.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 11

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T11.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>

### Task 12

<p align="center">
  <video style= "width:93%" controls>
    <source src="figures/video_tasks/T12.mp4" type="video/mp4" alt="Copyright Cornelio Cristina 2024">
  </video>
</p>



## The authors
<table>
   <tr>
      <td >
            <p align="center"><img style="display: block;" align="center" width="200vw" src="figures/CC.JPEG" alt="Cristina Cornelio"/> </p> 
      </td>
      <td > 
            <p align="center"><img style="display: block;" align="center" width="200vw" src="figures/MD.jpg" alt="Mohammed Diab"/> </p> 
      </td>
   </tr>
   <tr>
      <td >
              <h3 align="center" ><a href="https://corneliocristina.github.io"> Cristina Cornelio </a> </h3>
      </td>
      <td > 
            <h3 align="center"><a href="https://mdiabphd.wixsite.com/mdiab"> Mohammed Diab </a> </h3>
      </td>
   </tr>
   <tr>
      <td >
              <p align="center"> Samsung AI </p> 
      </td>
      <td > 
            <p align="center"> University of Plymouth </p> 
      </td>
   </tr>
</table>


## How to cite

```
@inproceedings{RECOVER_Cornelio,
  author = {Cornelio, Cristina and Diab, Mohammed},
  title = {RECOVER: A Neuro-Symbolic Framework for Failure Detection and Recovery},
  booktitle = {IROS 2024: IEEE/RSJ International Conference on Intelligent Robots and Systems},
  year = {2024}}
```

