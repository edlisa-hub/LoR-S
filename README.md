I take pride in recommending Jyue-Ting. I am the Project Manager for the “Geo Fingerprint” effort. For approximately one year, Jyue-Ting reported to me directly as a Modem Machine Learning Engineer on our modem team. Over that period, she consistently showed a rare mix of traits: she executes quickly, makes careful engineering judgments, and can reason across layers of the system. She stands out as a top performer, ranking in the top 10% of junior engineers I have worked with. 

Jyue-Ting’s primary responsibility was implementing key components in our Geolocation Detection platform. The goal is easy to state but difficult to deliver in practice: using PHY-layer measurements, particularly Timing Advance, to infer user location patterns and accelerate network search behavior. To be precise, the feature performs optimizations that reduce network search time by 50% based on the detected location. This is an area where small modeling mistakes can create large real-world costs, and where software decisions must account for the constraints and noise characteristics of physical measurements. Jyue-Ting approached these constraints with maturity and discipline.

During the most time-sensitive phase of development, she owned the end-to-end feature engineering workflow. She first implemented the logic in Python to validate measurement transformations and establish baseline behavior, then translated the validated pipeline into C for integration into the modem protocol stack. We originally planned a typical two-week sprint for a complete first pass; she delivered a functioning end-to-end implementation in roughly one week without compromising stability. The result was not a demo-quality prototype—it met the standard required to move into structured testing earlier than expected and reduced overall project risk.

She also demonstrated strong architectural awareness and an instinct for catching failure modes early. While we were designing the feature’s activation triggers, she identified a flaw that would have produced excessive false positives for static user behavior. Rather than escalating and waiting for direction, she proposed a concrete mitigation: a clearer separation strategy for static detection to prevent erroneous activation. After the change was implemented and evaluated, we observed an approximately 25% reduction in false alarms. This improvement materially increased confidence in the feature and contributed to its acceptance for landing. In addition, she diagnosed a root cause for low precision in our initial field trials and refined the implementation and testing methods, improving our location detection accuracy from 30% to over 85%.

Beyond project execution, Jyue-Ting contributed positively to team momentum and cohesion. She helped build an internal community by organizing activities (including an internal yoga group), drawing on prior leadership experience from university organizations. For instance, she brought her experience as the President of the Yoga Club at National Chiao Tung University—where she led a staff of 10 and managed over 200 students—to help organize and arrange classes for our internal colleagues.

In summary, Jyue-Ting combines structured problem-solving with practical delivery. She learns quickly, makes sound technical tradeoffs, and improves system designs rather than merely implementing tickets. I recommend her without reservation, and I am confident she will excel in a demanding graduate research environment.

Sincerely,
Spencer Shih
MediaTek

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Overleaf: [[https://www.overleaf.com/read/mfghtgnmfpmd#035f82](https://www.overleaf.com/project/69539f9b22002e53ed1f0f0d)](https://www.overleaf.com/read/mfghtgnmfpmd#035f82)

有需要修正的地方請不吝指出 非常感謝Spencer!
