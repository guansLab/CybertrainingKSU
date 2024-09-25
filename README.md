# Q-VTK Tutorial

<img width="150" img align="right" alt="NSF-logo" src="https://user-images.githubusercontent.com/5705572/95711667-1d953c00-0c18-11eb-817b-1cc6a90d504d.png">

**Project Title**: Q-VTK Tutorial: The Quantum Visualization ToolKit

**Presentor**:[Qiang Guan](http://www.guans.cs.kent.edu/)(KENT STATE UNIVERSITY)

**Sponsor**: NSF [2217021](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2217021) [2320957](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2320957) 

## Summary
This tutorial will focus on introducing Q-VTK, the quantum visualization toolkit. Q-VTK aims to provide a visual interface to help developers understand the quantum hardware, quantum compiler optimization, and result interpretation

## Authors
- Qiang Guan, Betis Behari and Priyabrata Senapati (Kent State University)
- Weiwen Jiang and Yuhong Song (George Mason University)
- Shaolun Ruan (Singapore Management University)
- Cheng-chang Lu (Cradle Inc)

## Learning outcomes and goals
We expect the trainees to be able to understand, interpret, and utilize the quantum systems and hardware efficiently and effectively through Q-VTK, while building practical quantum applications. 
- **Understanding Quantum Behavior and Errors**. The developers need to have the ability to understand and articulate how quantum algorithms operate and why they produce specific outcomes. This includes grasping the nuances of quantum behavior such as superposition, entanglement, and quantum interference, and understanding the nature and impact of quantum errors. For quantum applications to be reliable and useful, developers must accurately predict and mitigate the effects of quantum errors and noise.
- **Optimization of Quantum Algorithms**. Quantum application developers require a clear comprehension of how quantum compilers optimize algorithms through processes like transpilation, where high-level quantum algorithms are converted into lower-level quantum gate operations that specific quantum hardware can execute. The efficiency of quantum applications heavily depends on the optimization of quantum algorithms to reduce computational resources and improve execution speed. Explainability aids developers in choosing or designing quantum algorithms that are best suited for specific quantum hardware, thereby enhancing application performance.
- **Hardware Selection and Utilization**. Hardware selection entails an in-depth understanding of the variability in hardware quality across different quantum machines and how this variability affects algorithm performance. Quantum applications often require specific hardware capabilities to run effectively. Explainability in hardware performance allows developers to select the most appropriate quantum machine backend for their application, considering factors like qubit coherence times, gate fidelities, and connectivity.
- **Interpretation of Quantum Results**. Quantum applications in fields such as optimization and machine learning rely on the accurate interpretation of quantum results. Explainability ensures that developers can correctly analyze and utilize the outcomes of quantum computations, leading to more accurate and powerful quantum applications.

## Tutorial Contents
* Introduction: Welcome and explain the tutorial schedule and speaker.
* Quantum Noise: the existing quantum computers - aka Noisy Intermediate-Scale Quantum (NISQ) machines are intrinsically highly error-prone and produce output far from the quantum algorithms' correct output. We will primarily discuss the mitigation techniques for the noisy output and the role of the quantum system software in making erroneous quantum devices more usable and meaningful. In this tutorial, participants will explore the fundamentals of quantum noise, its distinction from classical noise, and its importance in the realm of quantum computing. The session will delve into the various origins of quantum noise, including decoherence, environmental interactions, and flaws in quantum hardware.
* VACSEN: Explain the design, implementation, and usage of VACSEN (TVCG 2023), the visualization tool for monitoring the hardware noise
![Alt text](/image/VACSEN-example.pdf "Optional title")
[!This is the image of ](/images/VACSEN-example.pdf)




 
