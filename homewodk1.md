班級：電子三丙
姓名：吳劭仟

學號：107360702



## 分析探討Proxy Logon

#### 起源

台灣資安公司 DEVCORE 發現存在於微軟 Exchange Server 的兩個安全漏洞命名為 Proxy Logon ，並在 01 月 05 日回報給微軟，但在 02 月下旬出現的大批 Exchange Server 中，攻擊封包內出現【Orange】 的網絡代碼，而正是最先發現漏洞研究員的名字。



#### 事件流程

> 2020年12月台灣資安業者 DEVCORE 發現漏洞
>
> 2021年01月05日 DEVCORE 通報微軟
>
> 2021年01月06日 微軟證實漏洞
>
> 2021年03月02日 微軟發布公告及修補程式



#### 事件嚴重性

此漏洞是發生在 Exchange Server 上，然而 Exchange Server 的普及率很高，所以才導致在公告漏洞後短短三天內就有數萬台伺服器收到攻擊。



#### 漏洞攻擊者

原先只有中國駭客組織 Hafnium 針對漏洞進行攻擊，帶微軟公告漏洞後，ESET 研究人員表示，至少超過10個APT駭客組織發動攻擊，這些駭客組織包括  LuckyMouse 、 Tick 及 Winnti Group 等等。



#### 漏洞修補後

> 1. 為防止駭客成功留下攻擊管道以便日後有所行動，微軟建議修補完 Exchange Server 漏洞的企業，還是要調查是否有其他駭入跡象，也得變更所有用戶帳號和本地管理員帳號密碼。
> 2. 微軟不斷釋出更多補救措施，包括涵蓋面更廣的第二波 Exchange Server 更新，以及一鍵式工具 EOMT (Exchange On-premise Migration Tool) 和更新 Microsoft Defender Antivirus 特徵檔。