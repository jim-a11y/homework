```mermaid
gantt
    title 項目計劃
    dateFormat  YYYY-MM-DD
    section 研擬計劃
    研擬計劃            :a1, 2024-09-30, 1d
    任務分配            :after a1  , 4d
    取得硬體            :after a1  , 17d
    section 程式開發
    程式開發            :after a2  , 70d
    程式測試            :after a3  , 30d
    section 安裝與文件
    安裝硬體            :after a3  , 10d
    撰寫使用手冊        :after a5  , 25d
    轉換檔案            :after a5  , 20d
    section 測試與訓練
    系統測試            :after a6  , 25d
    使用者訓練          :after a7, 20d
    使用者測試          :after a9, 25d

    %% Add start and end dates
    %% Start and end dates can be added as comments in the task lines for clarity.
