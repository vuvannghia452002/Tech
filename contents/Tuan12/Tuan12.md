

\subsection{Insider Threats}

Security threats can come from inside or outside of an organization. The attacks from insiders, be they from employees, suppliers, or other companies legitimately connected to a company’s computer system, pose a more pernicious threat than external attacks. These insiders have knowledge of the internal workings of the organization, and full possession of all the rights and privileges required to mount an attack that outsiders lack. Consequently, insiders can make their attacks look like normal operations \cite{gheyas2016detection}.

<!-- Các mối đe dọa bảo mật có thể đến từ bên trong hoặc bên ngoài tổ chức. Các cuộc tấn công từ nội bộ, có thể là từ nhân viên, nhà cung cấp hoặc các công ty khác được kết nối hợp pháp với hệ thống máy tính của công ty, gây ra mối đe dọa nguy hiểm hơn các cuộc tấn công từ bên ngoài. Những người trong nội bộ này có kiến ​​thức về hoạt động nội bộ của tổ chức và có đầy đủ sở hữu tất cả các quyền và đặc quyền cần thiết để tiến hành một cuộc tấn công mà người ngoài không có. Do đó, những người trong nội bộ có thể khiến các cuộc tấn công của họ trông giống như các hoạt động bình thường \cite{gheyas2016detection}. -->
 
  
To solve this problem, the goal is to classify knowledge organizations within the scope of threat research. By applying machine learning algorithms and analyzing large-scale studies on detecting internal threats, the development involves classifying current internal personnel into different categories, levels of access rights, and the motivations behind them.

<!-- Để giải quyết vấn đề này, mục tiêu là phân loại các tổ chức tri thức trong phạm vi nghiên cứu mối đe dọa. Bằng cách áp dụng các thuật toán học máy và phân tích các nghiên cứu quy mô lớn về phát hiện các mối đe dọa nội bộ, quá trình phát triển bao gồm việc phân loại nhân sự nội bộ hiện tại thành các danh mục, cấp độ quyền truy cập khác nhau và động cơ đằng sau chúng. -->
\subsubsection{Classification results}
<!-- \subsubsection{Kết quả phân loại} -->
According to research \cite{singh2022systematic},     by passing keywords to the   search engine.    The Boolean AND and OR were used to conduct the search. The search terms were: Insider Threats, Insider Threat Detection, Computer Threats, Security.  The platforms searched were:  IEEE Xplore Digital Library, ScienceDirect, SpringerLink,  ACM Digital Library,  Google Scholar. With the following criteria:



<!-- Inclusion Criteria  -->
The paper should focus on the insider threats and its types.

The paper should highlight the insider detection techniques.

The paper should focus on insider threats challenges and its prevention.

<!-- Exclusion criteria -->
The papers should not be about types of threats, it should focus only on insider threats to the cyber world.

Papers published after 2020.

The paper should focus on insider threats challenges and its prevention.

<!-- Summary of results received \cite{singh2022systematic}: -->
 ![alt text](image-1.png)
   All the papers has basic information about threat types and its detection. 

It is clear from Fig xxxxxxxxxx,  that majority of studies were focused on threat detection and threat mitigation in insider threats. 


Fig xxxxxxxxxx, shows the graphical representation of subdivided categories and their applications in insider threats. 


The themes found in primary studies shows
that threat detection and threat mitigation are the most popular security application in insider threats, with both comprising of 35 percent each respectively. 
 


The third most popular among the primary studies was, modeling human behaviors to detect the insider threat attack (behavior model). It comprises of 19 Percent of the total studies. 


At the last comes the types of threat, which makes up 11 Percent of the total studies.
 

\subsubsection{Detection and  Protection System}

<!-- - **Purpose of IDS**: Intrusion Detection System (IDS) is crucial for protecting organizational electronic assets[^1^][1]. It monitors and analyzes traffic to determine if it's malicious. -->
<!-- - **Mục đích của IDS**: Hệ thống phát hiện xâm nhập (IDS) rất quan trọng để bảo vệ tài sản điện tử của tổ chức[^1^][1]. Nó giám sát và phân tích lưu lượng truy cập để xác định xem nó có độc hại hay không. -->




Now a day, to safeguard the organization electronic assets, Intrusion Detection System (IDS) is crucial requirement. To 
determine whether the traffic is malicious or not Intrusion detection is a process of monitor and analyzes the traffic on a 
device  or  network.  It  can  be  a  software  or  physical  appliance  that  monitors  the  traffic  which  violates  organization 
security policies and standard security practices. To detect the intrusion and respond in timely manner as a result risks 
of intrusions is diminished it continuously watches the traffic. Based on the deployment IDS broadly classified into two 
types i.e. Host based Intrusion Detection System (HIDS) and Network based Intrusion Detection System (NIDS). Host-
based Intrusion Detection System is configured on a particular system/server. It continuously monitor and analyzes the 
activities  the  system  where  it  is  configured.  Whenever  an  intrusion  is  detected  HIDS  triggers  an  alert.  For  instance, 
when an attacker tries to create/modify/delete key  system files alert will be generated. Major advantages of the HIDS 
that  it  analyzes  the  incoming  encrypted  traffic  which  cannot  be  detected  NIDS.  To  detect  the  attack  like  Denial  of 
Service  (DoS)  attacks,  Port  Scans,  Distributed  Denial  of  Service  (DDoS)  attack,  etc  Network  Intrusion  Detection 
System (NIDS) continuously monitor and analyze the network traffic. To classify as malicious or non-malicious traffic 
it examines the incoming network traffic. If any predefined patterns or signatures of malicious behavior are present it 
re-assembles the packets, examine the headers/payload portion and determine [6]. 



Ngày nay, để bảo vệ tài sản điện tử của tổ chức, Hệ thống phát hiện xâm nhập (IDS) là một yêu cầu quan trọng. Để xác định xem lưu lượng có độc hại hay không Phát hiện xâm nhập là quá trình giám sát và phân tích lưu lượng trên thiết bị hoặc mạng. Nó có thể là một phần mềm hoặc thiết bị vật lý giám sát lưu lượng truy cập vi phạm chính sách bảo mật của tổ chức và các biện pháp bảo mật tiêu chuẩn. Để phát hiện sự xâm nhập và phản hồi kịp thời do đó giảm thiểu nguy cơ xâm nhập, nó liên tục theo dõi lưu lượng truy cập. Dựa trên IDS triển khai được phân loại rộng rãi thành hai loại, tức là Hệ thống phát hiện xâm nhập dựa trên máy chủ (HIDS) và Hệ thống phát hiện xâm nhập dựa trên mạng (NIDS). Hệ thống phát hiện xâm nhập dựa trên máy chủ được cấu hình trên một hệ thống/máy chủ cụ thể. Nó liên tục theo dõi và phân tích các hoạt động của hệ thống nơi nó được cấu hình. Bất cứ khi nào phát hiện sự xâm nhập, HIDS sẽ kích hoạt cảnh báo. Ví dụ: khi kẻ tấn công cố gắng tạo/sửa đổi/xóa các tệp hệ thống chính, cảnh báo sẽ được tạo. Ưu điểm chính của HIDS là nó phân tích lưu lượng được mã hóa đến mà NIDS không thể phát hiện được. Để phát hiện các cuộc tấn công như tấn công Từ chối dịch vụ (DoS), Quét cổng, tấn công từ chối dịch vụ phân tán (DDoS), v.v. Hệ thống phát hiện xâm nhập mạng (NIDS) liên tục theo dõi và phân tích lưu lượng mạng. Để phân loại lưu lượng truy cập độc hại hoặc không độc hại, nó sẽ kiểm tra lưu lượng truy cập mạng đến. Nếu có bất kỳ mẫu hoặc dấu hiệu xác định trước nào của hành vi độc hại, nó sẽ tập hợp lại các gói, kiểm tra phần tiêu đề/tải trọng và xác định [6].


<!-- - **Benefits of Digital Forensic Technique**: This technique helps maintain the integrity and reliability of evidence for later examination. Captured images can be used as evidence in court. -->
<!-- - **Lợi ích của Kỹ thuật Pháp y Kỹ thuật số**: Kỹ thuật này giúp duy trì tính toàn vẹn và độ tin cậy của bằng chứng cho việc kiểm tra sau này. Những hình ảnh được chụp có thể được sử dụng làm bằng chứng trước tòa. -->

![alt text](image.png)
