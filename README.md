# 軟體工程 期中報告

11124212 謝家弘，11124203 黃恩維

# 實驗三、UML靜態建模之類的分析與設計

# 實驗目的
透過UML建模過程掌握類別的分析與設計方法。

# 實驗環境
starUML

# 實驗任務
針對「迷你圖書管理系統」的使用案例圖，進行分析，完成類別建模。

# 案例圖
![image](https://github.com/ytgh09050/Software_Engineering/blob/main/image/1.jpg)

# 實驗步驟
分析實驗任務內容，並利用UML完成類別的建模並產生對象，主要包括：

定義類別（包括類別名稱、屬性、操作等）
建模類別之間的關係（包含關聯、泛化、依賴、實作等）
建構完整的類別圖（至少包含抽象類別、組合、聚合、多重性、可見性和介面等）
根據類別圖，產生系統某一時刻的物件圖

# 類別圖
![image](https://github.com/ytgh09050/Software_Engineering/blob/main/image/2.jpg)

上圖總的來說共有六個類，其中分別是User,RegisteredUser,OrdinaryUser,LibraryManager,MailSystem, Library .

其中，MailSystem是介面。 User類別關聯RegisterUser和OrdinaryReader類，同時這兩個類別和User之間也存在聚集關係，LibraryManager和OrdinaryReader都繼承RegisterUser類別。 Library

類別依賴RegisterUser和OrdinaryReader類別；LibraryManager也實作了MailSystem介面,又

和Library之間存在著組成關係，各個類別都設定了一定的可見性，有的定義了一些操作方法。

# 對象圖
![image](https://github.com/ytgh09050/Software_Engineering/blob/main/image/3.jpg)

共三個物件
