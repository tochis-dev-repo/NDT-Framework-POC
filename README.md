# NDT-Framework-POC

## Overview
The **NDT-Framework-POC** is a proof-of-concept project aimed at creating a testing framework for evaluating the outputs of systems that exhibit non-deterministic behavior, such as generative AI bots.

Given an input `I`, the framework assesses whether the received output `O` meets the required standards based on specific metrics.

---

## Evaluation Metrics
The output `O` will be evaluated on the following metrics:

1. **Intent**  
   - Does the output correctly identify and match the intent of the input?

2. **Accuracy**  
   - Does the output provide correct and relevant responses to the input?

3. **Sentiment**  
   - Does the output respond in a polite tone and demonstrate empathy where necessary?

4. **Compliance**  
   - Does the output adhere to requirements regarding the use and handling of data, as well as any other specific compliance rules?

---

## Proposed Solution
To achieve the goals of this project, the following approach will be taken:

1. Utilize a **pre-trained library** to build the foundation of the framework.
2. Train the system with a **custom dataset** to enhance performance and fine-tune the model.
3. Pass in a set of **inputs** and evaluate the resulting **outputs**.
4. Use multiple **evaluation models** to score the outputs based on the defined metrics.

Each metric will be assessed separately to produce a comprehensive analysis of the system's performance.

---

## Goals
- Develop a scalable framework for testing non-deterministic systems.
- Ensure outputs meet high standards of intent, accuracy, sentiment, and compliance.
- Provide actionable insights into areas where the system can improve.

---

## Contributing
Contributions are welcome! Feel free to fork this repository, raise issues, or submit pull requests.

---

## License
This project is licensed under [MIT License].

---
