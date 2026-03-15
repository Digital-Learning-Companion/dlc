# Digital Learning Companion (DLC)

Deterministic learning systems for writing and reasoning.

The **Digital Learning Companion (DLC)** is a reference implementation of the **Emergent State Machine (ESM)** architecture applied to education.

It demonstrates how instructional AI systems can provide structured guidance without relying on opaque model behavior.

---

# Architecture

The DLC uses a two-component architecture:

### dlc_web

Phoenix LiveView interface ("Bird")

Responsible for:

• student interaction  
• writing workspace  
• telemetry visualization  
• instructional messaging

---

### dlc_brain

FastAPI deterministic policy engine ("Brain")

Responsible for:

• signal extraction  
• writing state construction  
• instructional gating  
• policy projection  
• deterministic guidance generation

---

# The ESM Learning Loop

The DLC implements the full instructional reasoning loop defined by the Emergent State Machine architecture:

Observation  
→ Signal extraction  
→ Writing state construction  
→ Instructional gate  
→ Policy projection  
→ Instructional action  
→ Learning evolution

This allows the system to guide students through interpretable writing states rather than producing opaque feedback.

---

# CER Writing Example

The current MVP focuses on argumentative writing structure.

The system tracks the development of:

• Claim  
• Evidence  
• Reasoning  

and delivers deterministic instructional scaffolding as students revise their work.

*(Diagram illustrating this flow will appear here.)*

---

# Repository Structure
