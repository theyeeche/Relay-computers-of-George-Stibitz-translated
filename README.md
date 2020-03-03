  貝爾電話實驗室成立於1925年，是貝爾系統的基礎研究設施。此機構奠定了物理學、化學、以及其他各式各樣現代科學的基礎。在這令人興奮的地方締造了未來數十年之間無數的研究成果，其中更有許多獲得諾貝爾獎的發明家，與電腦相關的發明也創作於此，比如說:二極體(1942)、觸點式電晶體(1947)、首個完全晶體管電腦(TRADIC,1955)、第一個數據機（1960），第一個單芯片32位元處理器（1980），作業系統UNIX（1969），程式語言C（1973）和C ++（1983）等。
 
 在1937年十一月某一個深夜，一位名叫George Stibitz的貝爾實驗室數學家，離開他的工作場所回家，從貝爾儲藏室拿走了兩個電話繼電器，幾個手電筒燈泡，一根電線和一個乾電池。在家裡，他坐在廚房的桌子，組裝一個簡單的由上述部件和一個由錫罐製成的開關組成邏輯裝置。他很快有了一個設備，該設備被認為是第一個二進制繼電加法器，其中點亮的燈泡表示二進制數字"1"，而未點亮的燈泡表示二進制數字"0"。他的妻子Dorothea以"廚房桌子"將此裝置命名為"K-model"。隔天，Stibitz將K-model帶到實驗室向同事展示，他們推測是否有可能用繼電器構建全尺寸計算器，他的同事認為，任何使用二進制計算的實用繼電器電腦可能都需要數百個繼電器，因此，與當時在實驗室使用的商用機械計算器相比，它既龐大又昂貴。
  
  但是George Stibitz意識到，一個繼電器計算器不僅可以執行一個計算，還可以執行一系列的計算，繼電器電路指導順序，並根據需要存儲中間結果。具體來說，它可以執行複數乘法和除法所需的一系列運算:貝爾實驗室其他地方的研究人員經常在遠程電路的濾波器和放大器設計方面執行這兩種數學運算。1930年代，在實驗室里，一屋子的人類「電腦」用商用機械計算器算出了複數商數和乘積。計算本身非常簡單:複數乘法需要大約6個簡單的算術運算，而複數除法需要大約12個運算，每個運算都需要臨時存儲一些中間結果。
  
  當然，當時Stibitz不知道的是，在柏林，Konrad Zuse幾乎同時也在做和他同樣的事情。然而，Stibitz之所以成功，還有一個重要的因素是有個叫Claude Shannon
年輕人，在麻省理工學院讀研究生時也研究過符號邏輯語句與二進制繼電器電路的對應關係。還在1938年發表過關於該研究主題的畢業論文，畢業後他也來到了貝爾實驗室，從他那裏了解了很多二進制邏輯的思想。只不過當時Shannon並沒有積極參與Stibisz電腦的設計。顯然是因為當時使用繼電器來實現二進制邏輯的想法在那個年代並不普及。
  
  其實當Stibisz第一次向公司高管展示他的K-Model電腦時，並沒有給高管們留下太深刻的印象。Stibisz後來回憶當時的情景說"沒有煙火也沒有香檳"。不過不到一年
之後，貝爾的高管們就改變了對Stibisz發明的看法。因為當時貝爾實驗室面臨着越來越大的找到解決其日益複雜的數學問題方法的壓力，所以才同意為Stibisz發明的大
型實驗模型的建設提供資金。到了1938年2月，Stibisz完成了設計，貝爾實驗室安排當時的開關工程師Samuel Williams於1939年4月開始建造這台樣機。最終產品在半年後的1939年10月準備就緒，並在1940年1月8日首次投入使用，這台嚴格意義上的第一台真正意義上的電腦後來一直服役到1949年。貝爾實驗室在戰爭期間建造了其他繼電電腦時，其名稱從最初的"複數電腦(Complex Number Computer)"更改為“模型1(Model 1)”，成本約為20000美元。最初，複數電腦僅能執行複雜的乘法和除法，但後來進行了簡單的修改，使其也可以進行加法和減法。它使用了大約400-450個二進制繼電器，6-8個面板和10個稱為“交叉開關”的多位置，多極繼電器來臨時存儲數字，機器使用十進制系統，小數點固定在每個數字的開頭。 在內部，四個二進制繼電器對每個數字進行編碼，使用的代碼用n + 3的二進制代碼表示十進制數字n。這簡化了數字進位和減法的問題（今日多餘的三個二進制編碼的十進制仍稱為“ Stibitz碼”）。 機器在其寄存器中處理了十位數的數字，但顯示並打印了八位數的答案
（範圍為0.99999999）。 它使用“前綴”表示法：也就是說，運算符先輸入算術運算，然後再輸入操作數。比如說，要將兩個複數

（2 + 3i）乘以（4 + 5i），操作員將輸入（請參閱鍵盤的上方圖）：

M +.2 +i .3 +.4 -i .5 =
  
  字母M代表乘法（鍵盤上的字母D代表除法）。請注意小數點的位置在四個數字中的每個數字之前。機器實際上將計算（0.3 + 0.5i）x（0.4-0.2i），並輸出答案0.07000000 + i 0.22000000。操作員將不得不相應地縮放結果（乘以100）。一個簡單的加法運算大約需要100毫秒，而將2個複數相乘大約需要45秒。

https://history-computer.com/ModernComputer/Relays/images/StibitzTerminal.jpg  
這個計算器有4個暫存器，並且與作為特殊端子的輸入/輸出單元完全分開（請參見附近的照片）。電腦本身被保存在實驗室的一間偏僻房間中，很少有人見過。操作員使用三台經過修改的電傳機（鍵盤和打印設備）之一遠端存取它，該電傳機通過多線總線連接到處理器，並放置在其他位置，但是不能同時工作。 
  
  Stibitz進一步發展多路訪問電腦的想法。 1940年9月11日，美國數學學會在新罕布什爾州漢諾威的達特茅斯學院會面，它位於紐約貝爾實驗室大樓以北數百英里處，那裡是複數電腦。 Stibitz通過電話線（28線電傳打字電纜）將電腦連接到安裝在其中的電傳打字設備。它給使用它的人留下了深刻的印象。 許多美國最傑出的數學家以及後來領導重要計算項目的個人（例如， John von Neumann、John Mauchly、Norbert Wiener and Garrett Birkhoff）參加了會議。 達特茅斯（Dartmouth）學院預示了遠程計算的摩登時代，但是這種類型的遠端存取再過十年都不曾再見。 

https://history-computer.com/ModernComputer/Relays/images/CNCofStibitz.jpg
  
  由於複數電腦無法編譯，因此繼電器電路的組合可永久控制其操作順序。這些用於處理數字的繼電器具有相同的類型，但是沒有單獨的繼電器清楚地定義部分來處理計算序列的“控制”。 （後來的貝爾實驗室電腦採用了這種方法。）只有在複雜數字電腦建構之後，貝爾實驗室才出現了可編譯性的概念，因為它的建構者看到其基本計算元素受到其結合的過分限制，以至於控制電路只能將其與複雜的運算聯繫起來。（除了複數運算外，他們還嘗試使機器執行多項式運算，其中複數運算是一種特例。不過這對機器來說太受限制了。）
  
  複數電腦的成功鼓舞了Stibitz提出更具野心的設計，其中包括可以通過穿孔的磁帶修改計算器的操作。 起初，實驗室拒絕了他的提議，但隨著美國在1941年12月加入第二次世界大戰，貝爾實驗室將其優先重點轉移到了軍事用途上，該項目所涉及的計算量超過了和平時期的研究。他們大部分的戰時成就都在模擬電腦的設計中。 不過他們也建造了五台用於軍事的數字中繼電腦，並在戰爭結束後又建造了一台供自己使用的數字中繼電腦，總共製造七台數字電腦。
  
  這些用於軍事用途的計算器中的第一個是中繼插值器，該插值器於1943年安裝在華盛頓特區，後來稱為Model II。它由440個繼電器構成，存儲容量為7個數字。乘法運算速度為4秒（通過重複加法乘法）。它主要通過執行一系列算術運算來ㄌ解決與指揮防空火有關的問題，這些算術運算對通過紙帶提供給機器的功能值進行插值。像複數電腦一樣，它是一台專用電腦。但是，其算術序列不是永久連接的中繼計算器，而是由膠合成環路的“公式膠帶”（五通道紙帶）提供的。因此，不同的磁帶允許人們採用不同的插值方法。 Model II除了插值之外並不能做很多事情，但是由於插值過程可以解決科學和工程學中的許多問題，因此機器在戰爭結束後很久就被其他政府部門所徵用。
   
   接下來的兩台由Stibitz設計的機器是彈道電腦和Mark 22錯誤檢測器（後來稱為Model III和IV），它們是相同的機器，第一台安裝於1944年，位於德克薩斯州的布利斯堡，第二台安裝於1945年初。華盛頓（每個花費65000美元）。它們包含約1400個繼電器，並具有10個數字的存儲容量。乘法速度為1秒（通過查表乘法）。這些機器還將紙帶用於數據和公式輸入，其算術序列由紙帶循環提供。與模型II一樣，模型III和IV也解決了與高射砲瞄準和跟蹤有關的問題。但是，它們是更複雜的機器，不僅具有執行插值的能力，而且還能夠評估描述目標飛機和防空砲彈路徑的彈道方程。附加的紙帶指示機器要評估哪些功能。因此，Model III和Model N是貝爾實驗室中第一個具有一定程度的通用可編譯性的數字計算器，儘管它們都不是完全通用的計算器。他們的內存和算術單元具有適度的功能，比如精度只有十進制的十進制數字，每台機器只能存儲十個數字。
   
   該系列中最大的電腦也是最後一台電腦，由Stibitz設計，是Model V，貝爾實驗室在1946年和1947年為軍方製造了兩台昂貴的巨型電腦（重10噸）。每個繼電器包含九千多個繼電器，並以科學計數法表示處理的數字。該商店最多可以容納三十個數字，並且紙帶閱讀器可以同時輸入程序步驟和數字數據。乘法速度0.8秒。 V型設計最有趣的方面是它具有兩個獨立的算術單元，每個算術單元都可以作為具有自己的內存寄存器和輸入輸出設備的獨立計算機進行操作。小型問題可以在計算機上成對運行，從而節省時間，而較大的問題可以接管兩個處理器。與每個處理器相關聯（使用現代術語）是15個存儲寄存器，整個機器總共有30個。主控制單元根據其可用性將指令定向到一個或兩個處理器。該控制單元與處理器中控制算術，存儲器和輸入/輸出操作順序的控制單元是分開的。它可以控制控件，可以這麼說。 （Stibitz稱其為“超級分支”功能。）因此，從真正的意義上講，Model V具有所謂的“操作系統”，即控制和管理通過計算機的工作流程的控制單元。
   
   除了編譯能力，後來的貝爾計算機還強調了非凡的可靠性。 用作邏輯和存儲器操作的基本元素的繼電器有間歇性故障的跡象。 如果在兩個繼電器觸點之間有灰塵積聚，即使繼電器的其餘部分都正常運作，該電路仍會發生故障。 雖然多次使用後，灰塵顆粒可能會自行晃動，然後都會一切恢復正常。 但整個計算可能會偏離，而在診斷會話期間不會出現任何機器故障。
  
  貝爾的工程師設計了計算機電路，可以在計算的每個步驟進行自我檢查。 此電路的設計不僅要增加，減去，存儲數字等等。 他們還設計檢查自己是否正確完成了這些操作，否則將機器停止。 貝爾的工程師還以其設計電話電路的經驗為基礎，這些電話電路必須在經常處於不利環境的情況下長時間無人看守。 這些電路設計為由半熟練的技術人員進行維修； 如果每次電話線掉線或客戶的電話壞了時都要打電話給工程師，電話服務的成本將非常高。 貝爾實驗室II至VI模型使用的系統中，每個十進制數字編碼的不是四個而是七個二進制繼電器。 它們分為兩組，每組兩個和五個繼電器； 十進制代碼如下：
  
Decimal       Relays

digit

0	                01	  00001

1	                01	  00010

2	                01	  00100

3	                01	  01000

4	                01	  10000

5	                10	  00001

6	                10	  00010

7	                10	  00100

8	                10	  01000

9	                10	  10000

  貝爾實驗室稱此系統為“二元”表示法，因為繼電器的重點為一或五。 實際上，它不是這些數字基礎的組合； 而是一個七位混合十進制代碼。 所有的貝爾實驗室中繼計算機都以十進制算法基礎。 一個特殊的電路檢查發現每個十進制數字有兩個，只有兩個繼電器通電。 另一個電路檢查了每個組中只有一個繼電器的接通狀態，雖然某些異常組合可能無法檢測到，但這防止了兩個單獨的錯誤相互抵消。

relay 中繼
diodes 二極管
pointer-transister 指針轉換
arithmetic 算術 
interim filter 臨時過濾器
thesis 論文
multiposition 多位置
multipole 多極
unduly 過分地
analog 類比
interpolation 插補
sophisticated 複雜的
