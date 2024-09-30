```mermaid
graph TD;
    A[研擬計劃] -->|1天| B[任務分配];
    A -->|1天| C[取得硬體];
    B -->|4天| D[程式開發];
    C -->|17天| E[安裝硬體];
    D -->|70天| F[程式測試];
    E -->|10天| G[撰寫使用手冊];
    E -->|20天| H[轉換檔案];
    F -->|30天| I[系統測試];
    G -->|25天| J[使用者訓練];
    H -->|20天| J;
    I -->|25天| K[使用者測試];
    J -->|20天| K;

    style A fill:#f9f,stroke:#333,stroke-width:2px;
    style D fill:#f9f,stroke:#333,stroke-width:2px;
    style F fill:#f9f,stroke:#333,stroke-width:2px;
    style I fill:#f9f,stroke:#333,stroke-width:2px;
    style K fill:#f9f,stroke:#333,stroke-width:2px;

  
