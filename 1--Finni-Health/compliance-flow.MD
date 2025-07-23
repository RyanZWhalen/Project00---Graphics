graph TD
    A[BCBA Provider Onboarding] --> B{State Location?}
    
    B -->|Tennessee| C[TN Requirements]
    B -->|Ohio| D[OH Requirements]
    B -->|South Carolina| E[SC Requirements]
    B -->|New Mexico| F[NM Requirements]
    B -->|California| G[CA Requirements]
    
    C --> C1[TBI & FBI Fingerprints Required]
    C1 --> C2[IdentoGO Centers via IDEMIA]
    C2 --> C3[Finni Clustering & SMS Alerts]
    C3 --> H[License Processing]
    
    D --> D1[Ohio BCI & FBI Required]
    D1 --> D2[WebCheck Vendor E-Submission]
    D2 --> D3[Finni WebCheck Kit Shipping]
    D3 --> H
    
    E --> E1[SLED & FBI Required - Bill 630]
    E1 --> E2[SLED-Specified Forms]
    E2 --> E3[Finni Educational Seminars]
    E3 --> H
    
    F --> F1[No State Licensure Required]
    F1 --> F2[BACB National Framework Only]
    F2 --> F3[Optional Finni IDEMIA Screening]
    F3 --> I[Direct Practice Authorization]
    
    G --> G1[AB 1715 Pending]
    G1 --> G2[No Current Mandate]
    G2 --> G3[Finni DOJ Live Scan Preparation]
    G3 --> I
    
    H --> J[State License Issued]
    J --> K[Medicare Enrollment]
    K --> L[Practice Authorization]
    
    I --> K
    
    style A fill:#e1f5fe
    style H fill:#e8f5e8
    style I fill:#e8f5e8
    style L fill:#fff3e0
    
    style C fill:#ffebee
    style D fill:#ffebee
    style E fill:#ffebee
    style F fill:#e8f5e8
    style G fill:#fff3e0
