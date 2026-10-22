```mermaid
gantt
    title FYP Development Timeline (Automated Web Security Auditor)
    dateFormat  YYYY-MM-DD
    axisFormat  %w
    
    section Phase 1: Planning
    Requirement & Security Rules   :a1, 2026-10-01, 14d
    Literature Review               :a2, after a1, 14d
    Proposal Submission             :milestone, m1, after a2, 0d

    section Phase 2: Frontend & Cloud
    UI Wireframing & React Setup    :b1, after m1, 14d
    Firebase Auth & Firestore Setup :b2, after b1, 21d

    section Phase 3: Core Engine
    Python Header & SSL Scanner     :c1, after b2, 21d
    Animated Risk Gauges & Diagrams :c2, after c1, 14d

    section Phase 4: Remediation
    Code Diff & Fix Snippets        :d1, after c2, 14d
    PDF Report Exporter & Cloud Deploy:d2, after d1, 14d

    section Phase 5: Testing
    Diagnostic Accuracy Evaluation  :e1, after d2, 14d
    System Usability Scale (SUS)    :e2, after e1, 14d
    Final Report Submission & Viva  :milestone, m2, after e2, 0d
