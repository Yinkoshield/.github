# YinkoShield – Elevating Mobile Security 🚀  

Welcome to the **YinkoShield** GitHub page! Here, we share cutting-edge research, insights, and tools to help developers secure their mobile applications.  

## 🔐 What is YinkoShield?  
YinkoShield is a **mobile application security SDK** designed to protect apps from tampering, reverse engineering, accessibility attacks, and unauthorized overlays. Our SDK seamlessly integrates with **OpenTelemetry** and connects to any **APM (Application Performance Monitoring)** tool, bridging the gap between **security, performance, and support** to provide a smooth user experience.  

## 📢 Join Our Community  
We are committed to **open research and knowledge sharing** to help developers strengthen mobile security.  
🔗 Follow us on **LinkedIn** for insights, updates, and security research:  
👉 [YinkoShield LinkedIn Showcase](https://www.linkedin.com/showcase/yinkoshield/)  

## 🔍 Latest Research & Projects  
We continuously share research and findings on mobile security, optimizations, and performance improvements. This section will be **updated regularly** with our latest work.  

### 📌 Current Project
 **pinscan: measure TLS certificate pinning instead of taking the app's word for it**  
 👉 [pinscan](https://github.com/Yinkoshield/pinscan) (Apache 2.0)  
   - Tells you, **per host**, whether a mobile app actually pins its TLS certificates, **how well**, and how sure you can be. No Frida, no hooks, no repackaging.  
   - **Never reports "secure" from silence**: a timeout or a silent connection is `inconclusive`, never a pass.  
   - Built for **CI**: exit codes, byte-stable baselines, a regression gate, SARIF and JUnit output.  
   ```sh
   go install github.com/yinkoshield/pinscan/cmd/pinscan@latest
   pinscan selftest   # proves the methodology end to end, no device needed
   ```

 **Crash-Proof Apps: YinkoShield's JNI Tips for Low-End Devices**  
 👉 [JNI Hardening Semgrep RuleSet](https://github.com/Yinkoshield/jni-hardening-with-semgrep)  
   - A deep dive into **improving JNI (Java Native Interface) resilience** for budget Android devices.  
   - Covers **best practices for JNI memory management**, preventing crashes, and optimizing JNI performance.  

Stay tuned for more **insights, code samples, and security techniques**! 🚀  

## 🤝 Contributing  
We welcome discussions, feedback, and collaborations! If you're passionate about mobile security and want to contribute, feel free to open an issue or start a discussion.  

## 📄 License  
This repository contains research, insights, and shared tools under the appropriate licensing model. See the LICENSE file for details.  

---  
📢 **Follow our journey & stay ahead in mobile security!**  
🔗 [YinkoShield on LinkedIn](https://www.linkedin.com/showcase/yinkoshield/)  
