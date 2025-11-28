# **COAGULATION MASTER — OPTIMIZED MASTER PROMPT FOR EDUCATIONAL APP GENERATION**

A complete **mobile-first**, **dark-mode**, **offline-ready**, pathology-resident–level educational platform covering **coagulation** as taught in a **coagulation rotation**, coagulation laboratory, or standard hemostasis textbook.

This app must synthesize the **science of hemostasis**, the **function of the coagulation lab**, interpretation of **PT/PTT, mixing studies, factor assays**, and the logic behind **bleeding & clotting disorders**, **DIC**, **thrombophilias**, **heparin monitoring**, **warfarin effects**, and **quality control** in coag testing.

All examples are **synthetic**, **non-patient**, and all assessments are **session-only** with **no tracking**.

---

# **MASTER PROMPT — Coagulation Master Educational App Generator (SPECIALIZED VERSION)**

## **0. ROLE & MISSION**

You are:  
Product Manager • Senior Engineer • Instructional Designer • Hemostasis/Coag SME • Lab Medicine SME • QA Engineer • UX Writer

**Mission:**  
Build an educational platform that teaches *everything* a pathology resident must understand during a **coag rotation**, including:

- Coag physiology  
- Intrinsic/extrinsic/common pathways  
- PT/PTT interpretation  
- Mixing studies  
- Factor assays  
- von Willebrand disease testing  
- Platelet function testing  
- Heparin/warfarin/DOAC monitoring (conceptual)  
- Thrombophilias  
- DIC, liver disease, consumption patterns  
- Coag QC, pre-analytical variables  
- Coag instruments & methodologies  

---

# **1. INPUTS (Fill When Executing Prompt)**

- **Primary Topics:** {{TOPICS}}  
  *Default:* Hemostasis, coag pathways, PT/PTT, mixing studies, factor deficiencies, vWD, platelet function, thrombophilias, DIC, anticoag monitoring.

- **Target Levels:** {{LEVELS}}  
  *Default:* Pathology residents PGY1–PGY4, heme-path fellows, clinical pathology trainees.

- **Learning Context:** {{CONTEXT}}  
  *Default:* Coag rotation, coag bench, call consults, boards prep.

- **Learning Objectives:** {{LEARNING_OBJECTIVES}}  
  *Default:*  
  - Interpret PT/PTT and mixing study algorithms  
  - Understand factor deficiency vs inhibitor patterns  
  - Recognize lab patterns in DIC vs liver vs warfarin vs DOACs  
  - Understand vWD assays (ristocetin, antigen, activity)  
  - Use thrombophilia panels logically  
  - Recognize pre-analytic pitfalls in coag testing  

- **Constraints:** {{CONSTRAINTS}}  
  Required:  
  - Dark/light, mobile-first, offline-ready  
  - No user tracking  
  - Synthetic-only  
  - No treatment recommendations  

- **References:** {{REFERENCES}}  
  Conceptual alignment: CLSI coag guidelines (high-level), ASH conceptual models.

- **Tone:** {{VOICE_TONE}}  
  Default: Clean, structured, lab-oriented, pattern-driven.

---

# **2. EXECUTIVE SUMMARY & NAME OPTIONS**

**Goal:**  
Build an app that demystifies coagulation for pathology residents by breaking it down into **systems**, **algorithms**, **case patterns**, and **instrumentation**, making interpretation of coagulation labs intuitive and reproducible.

**Name Options:**  
- **Coagulation Master** — “PT → PTT → Mix → Factor → Diagnosis.”  
- **HemoCoag Atlas** — “From physiology to lab interpretation.”  
- **CoagLogic Lab** — “Think like the coag bench.”  

**Success Criteria:**  
- Residents can use PT/PTT/mix algorithms accurately.  
- Users understand the meaning of each coagulation factor.  
- Learners can reason through vWD testing.  
- Residents can distinguish liver disease vs DIC vs vitamin K deficiency.  
- Trainees know pre-analytical sources of coag error.

---

# **3. PERSONAS & USE CASES**

### PERSONAS
1. **PGY-1 Resident on Coag Month**  
   - Needs: Understand basic PT/PTT/mix interpretation.  
   - Goal: Use algorithmic pathways with confidence.

2. **Senior Resident**  
   - Needs: Integrate factor assays, vWD tests, thrombophilia patterns.  
   - Goal: Master coag consult calls.

3. **Heme-Path Fellow**  
   - Needs: Grasp factor inhibitors & complex coagulopathies.  
   - Goal: Advanced differential reasoning.

### USE CASES
- “PT prolonged. PTT normal.” → What’s next?  
- “Mixing study corrects vs fails to correct.”  
- “vWF antigen vs activity mismatch.”  
- “Heparin contamination vs true prolongation.”  
- “DOAC interference with coag assays.”  
- “Factor VIII inhibitor pattern.”  
- “Which labs distinguish liver disease from DIC?”  
- “Platelet function analyzer abnormal—interpret why.”

---

# **4. CURRICULUM MAP & KNOWLEDGE GRAPH**

## MODULE A — Hemostasis Foundations
- Primary vs secondary hemostasis  
- Platelets, vWF, coag factors  
- Intrinsic/extrinsic/common pathways  
- Physiology of thrombin generation  
- Natural anticoagulants: Protein C/S, Antithrombin  
- Fibrinolysis basics  

---

## MODULE B — Lab Testing Basics
- PT: extrinsic + common  
- PTT: intrinsic + common  
- Thrombin time  
- Fibrinogen assays  
- D-dimer  
- ACT (conceptual)  
- Anti-Xa assay basics  
- Platelet function analyzer (PFA-100/200 conceptual)  

---

## MODULE C — Mixing Studies
- Purpose: deficiency vs inhibitor  
- Immediate vs incubated mix  
- Patterns:
  - Corrects → deficiency  
  - Doesn’t correct → inhibitor  
  - Partial correction → borderline patterns  
- Inhibitors:  
  - Lupus anticoagulant  
  - Factor VIII inhibitors  

---

## MODULE D — Factor Assays
- One-stage vs chromogenic assays  
- Factor VIII  
- Factor IX  
- Factor XI  
- Factor VII  
- Factor X, V, II  
- Interferences  
- Congenital vs acquired deficiency patterns  

---

## MODULE E — von Willebrand Disease
- vWF antigen  
- vWF activity (ristocetin cofactor or equivalent conceptual)  
- Multimer analysis (high-level)  
- Types:  
  - Type 1  
  - Type 2A / 2B / 2M / 2N  
  - Type 3  
- Platelet-type vWD vs Type 2B  
- Diagnostic interpretation tables  

---

## MODULE F — Bleeding Disorders (Non-Platelet)
- Hemophilia A & B  
- Rare factor deficiencies  
- Acquired hemophilia  
- Vitamin K deficiency  
- Liver disease  
- Disseminated intravascular coagulation (DIC)  
- Hyperfibrinolysis (conceptual)  

---

## MODULE G — Platelet Function Disorders
- Glanzmann  
- Bernard-Soulier  
- Storage pool disorders  
- Drug-induced dysfunction (aspirin, P2Y12 inhibitors)  
- PFA patterns  

---

## MODULE H — Thrombosis & Thrombophilias
- Factor V Leiden  
- Prothrombin G20210A  
- Protein C/S deficiency  
- Antithrombin deficiency  
- Lupus anticoagulant  
- Antiphospholipid syndrome logic  
- Hypercoagulability workup rules (timing, meaning)  

---

## MODULE I — Anticoagulant Monitoring (Conceptual)
- Warfarin effects on PT/INR  
- Heparin effects on PTT  
- LMWH & anti-Xa  
- DOAC impact on PT/PTT/TT (conceptual interference)  

---

## MODULE J — Coag Lab Operations
- Specimen type & handling (citrate tubes)  
- Pre-analytical variables: hemolysis, underfilling, delays  
- Hematocrit correction for citrate volume (conceptual)  
- QC:  
  - Westgard rules in coag  
  - Calibration  
- Instrumentation overview (optical vs mechanical clot detection)  

---

## MODULE K — Integrated Coag Case Reasoning
- PT/PTT algorithm  
- Mix → factor assays → inhibitor logic  
- DIC vs liver vs warfarin patterns  
- DOAC interference clues  
- vWD integration  
- Platelet function integration  
- Hypercoagulability decisions  

---

# **5. INTERACTIVE MODELS (TABLE)**

| Interactive | Purpose | Inputs | Outputs | Visuals | Guardrails |
|-------------|---------|---------|----------|----------|------------|
| PT/PTT Interpreter | Apply algorithmic reasoning | PT, PTT values | Differential categories | Pathway diagram | Not diagnostic |
| Mixing Study Simulator | Practice correction patterns | Patient/PTT mix values | Suggest deficiency vs inhibitor | Mix graphs | Educational only |
| Factor Assay Mapper | Understand factor roles | Factor levels | Pattern interpretation | Factor wheel | Synthetic only |
| vWD Analyzer | Classify vWD type | Ag, activity, multimer clues | vWD category | Tile-based UI | No clinical advice |
| DIC vs Liver Decision Tool | Interpret abnormal panels | PT/PTT/fibrinogen/d-dimer | Pattern match | Matrix view | Conceptual |
| Platelet Function Logic Tool | Interpret PFA-like patterns | Closure times | Possible causes | Dual-channel diagram | Synthetic |
| Thrombophilia Panel Interpreter | Pattern logic | Genetic + coag tests | Possible category | Flowchart | Conceptual |
| Anticoagulant Interference Checker | Detect assay interference | PT/PTT/TT + medication | Likely interference | Drug icons | Educational |
| Integrated Coag Case Builder | Full case reasoning | Multiple labs + clues | Summary interpretation | Report mockup | Not for patient care |

---

# **6. ASSESSMENT & MASTERY (Session-Only)**

- MCQs  
- PT/PTT pattern recognition  
- Mixing study questions  
- vWD interpretation  
- Factor deficiency vs inhibitor matching  
- Thrombophilia cases  
- Platelet function cases  
- DIC/Liver/wK deficiency differentiation  
- Mixed coag consult vignettes  

End of quiz:
- “You answered X/Y correctly this session.”  
- No data saved  

---

# **7. COAGULATION REASONING FRAMEWORK**

1. Check **specimen quality**  
2. Evaluate **PT & PTT**  
3. Decide **intrinsic vs extrinsic vs common**  
4. Perform **mix** if prolonged  
5. If mix corrects → consider deficiency  
6. If mix fails → suspect inhibitor  
7. Add **factor assays**  
8. Evaluate **vWD** if mucocutaneous bleeding  
9. Consider **DIC vs liver vs VK deficiency** patterns  
10. Integrate anticoagulant context  
11. Produce conceptual interpretation  

**Pitfalls:**  
- Misreading partial correction in mix  
- Forgetting that lupus anticoagulant prolongs PTT but is pro-thrombotic  
- Misinterpreting DOAC interference  
- Confusing vWD type 2 variants  
- Overinterpreting thrombophilia testing during acute events  

---

# **8. ACCESSIBILITY, EQUITY, SAFETY**

- WCAG 2.2 AA  
- High-contrast, dark-mode optimized  
- Icons instead of real patient samples  
- Inclusive case set  
- Clear disclaimers: “Educational only, not for diagnosis or treatment.”  

---

# **9. TECH ARCHITECTURE**

Stack:
- React + TypeScript  
- Tailwind + shadcn/ui  
- Zustand (session-only)  
- Service Worker for offline mode  

Routes:
- `/foundations`  
- `/testing`  
- `/mixing`  
- `/factors`  
- `/vwd`  
- `/bleeding`  
- `/platelet-function`  
- `/thrombosis`  
- `/anticoagulants`  
- `/operations`  
- `/cases`  
- `/assessment`  
- `/settings`

Settings must only include:
- Dark/light toggle  
- About  
- Disclaimer  

---

# **10. DATA SCHEMAS**

### Mixing Study Schema

    {
      "id": "mix_case_3",
      "ptt": {"patient": 72, "immediate_mix": 38, "incubated_mix": 65},
      "interpretation": "Inhibitor pattern (immediate correction + incubated prolongation suggests time-dependent inhibitor)."
    }

### Coag Case Schema

    {
      "id": "coag_case_10",
      "pt": 22,
      "ptt": 65,
      "fibrinogen": 90,
      "d_dimer": "high",
      "question": "Most likely pattern?",
      "options": ["DIC", "Liver disease", "Vitamin K deficiency"],
      "correct": "DIC",
      "rationale": "Low fibrinogen + high D-dimer + prolonged PT/PTT = DIC pattern."
    }

---

# **11. SCREENS & WIREFRAMES**

### HOME  
Modules: Foundations • Testing • Mixing • Factors • vWD • Bleeding Disorders • Platelet Function • Thrombosis • Anticoagulants • Operations • Cases • Assessment

### MODULE OVERVIEW  
- Summary  
- Subsections  
- Quick quiz  

### LESSON PAGE  
- Pathway diagrams  
- Mix tables  
- vWD interpretation charts  
- Factor deficiency summaries  

### CASE ENGINE  
- PT/PTT + mix + factors + vWD + DIC patterns  
- Immediate feedback with rationale  

### ASSESSMENT  
- MCQs, patterns, cases  
- Session-only scoring  

### SETTINGS  
- Dark/light  
- About  
- Disclaimer  

---

# **12. COPY & CONTENT KIT**

Examples:
- “If both PT and PTT are prolonged, think common pathway or multiple deficiencies.”  
- “Failure to correct in the mix suggests an inhibitor.”  
- “Lupus anticoagulant prolongs PTT but is PRO-thrombotic.”  
- “Type 2 vWD: antigen normal-ish, activity LOW.”  
- “DIC shows low fibrinogen and high D-dimer.”  
- “DOACs interfere with PT/PTT unpredictably.”

Glossary items:
- LA, FXI, FVII, TT, fibrinogen, chromogenic assay, ristocetin, APC resistance, anti-Xa, etc.

---

# **13. CREATOR-SIDE A/B TESTING**  
(Not tracked in-app)

- Compare mix visualizers vs factor-based algorithms  
- Assess confusion in DIC vs liver disease  
- Evaluate user understanding of vWD patterns  

---

# **14. QA CHECKLIST**

- Coag pathways accurate  
- Mix and factor logic correct  
- vWD categories correct  
- DIC/liver/VK deficiency patterns accurate  
- Anticoagulant interference represented clearly  
- No patient care instructions  
- No real data  

---

# **15. ROADMAP**

- M0: Foundations + PT/PTT basics  
- M1: Mixing + Factors  
- M2: vWD + Platelet Function  
- M3: Thrombosis + Anticoagulants  
- M4: QA/Operations + Integrated Cases  
- M5: 100+ case bank  

---

# **ACCEPTANCE CRITERIA**

- Comprehensive coagulation curriculum at pathology PGY level  
- Covers lab logic, physiology, and interpretive algorithms  
- Mobile-first, offline-ready, dark-mode optimized  
- No user tracking  
- Synthetic-only  
- Clear, structured, pattern-driven  

---

## **NOW GENERATE**

Use the structure above to generate the full **Coagulation Master** app blueprint in the prescribed order.
