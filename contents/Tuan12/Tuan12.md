\subsection{Insider Threats}

Security threats can come from inside or outside of an organization. The attacks from insiders, be they from employees, suppliers, or other companies legitimately connected to a company’s computer system, pose a more pernicious threat than external attacks. These insiders have knowledge of the internal workings of the organization, and full possession of all the rights and privileges required to mount an attack that outsiders lack. Consequently, insiders can make their attacks look like normal operations \cite{gheyas2016detection}.

<!-- Các mối đe dọa bảo mật có thể đến từ bên trong hoặc bên ngoài tổ chức. Các cuộc tấn công từ nội bộ, có thể là từ nhân viên, nhà cung cấp hoặc các công ty khác được kết nối hợp pháp với hệ thống máy tính của công ty, gây ra mối đe dọa nguy hiểm hơn các cuộc tấn công từ bên ngoài. Những người trong nội bộ này có kiến ​​thức về hoạt động nội bộ của tổ chức và có đầy đủ sở hữu tất cả các quyền và đặc quyền cần thiết để tiến hành một cuộc tấn công mà người ngoài không có. Do đó, những người trong nội bộ có thể khiến các cuộc tấn công của họ trông giống như các hoạt động bình thường \cite{gheyas2016detection}. -->

To solve this problem, the goal is to classify knowledge organizations within the scope of threat research. By applying machine learning algorithms and analyzing large-scale studies on detecting internal threats, the development involves classifying current internal personnel into different categories, levels of access rights, and the motivations behind them.

<!-- Để giải quyết vấn đề này, mục tiêu là phân loại các tổ chức tri thức trong phạm vi nghiên cứu mối đe dọa. Bằng cách áp dụng các thuật toán học máy và phân tích các nghiên cứu quy mô lớn về phát hiện các mối đe dọa nội bộ, quá trình phát triển bao gồm việc phân loại nhân sự nội bộ hiện tại thành các danh mục, cấp độ quyền truy cập khác nhau và động cơ đằng sau chúng. -->

\subsubsection{Classification results}

<!-- \subsubsection{Kết quả phân loại} -->

According to research \cite{singh2022systematic}, by passing keywords to the search engine. The Boolean AND and OR were used to conduct the search. The search terms were: Insider Threats, Insider Threat Detection, Computer Threats, Security. The platforms searched were: IEEE Xplore Digital Library, ScienceDirect, SpringerLink, ACM Digital Library, Google Scholar. With the following criteria:

<!-- Inclusion Criteria  -->

The paper should focus on the insider threats and its types.

The paper should highlight the insider detection techniques.

The paper should focus on insider threats challenges and its prevention.

<!-- Exclusion criteria -->

The papers should not be about types of threats, it should focus only on insider threats to the cyber world.

Papers published after 2020.

The paper should focus on insider threats challenges and its prevention.

<!-- Summary of results received \cite{singh2022systematic}: -->

![alt text](Summary_of_results_Insider_Threats.png)


\begin{figure}[H]
    \centering
    \includegraphics{pictures/Attacking_vectors/Summary_of_results_Insider_Threats.PNG}
    \caption{Summary of results Insider Threats} 
    \label{fig:Summary_of_results_Insider_Threats}
\end{figure}



All the papers has basic information about threat types and its detection.

It is clear from Fig xxxxxxxxxx, that majority of studies were focused on threat detection and threat mitigation in insider threats.

Fig xxxxxxxxxx, shows the graphical representation of subdivided categories and their applications in insider threats.

The themes found in primary studies shows
that threat detection and threat mitigation are the most popular security application in insider threats, with both comprising of 35 percent each respectively.

The third most popular among the primary studies was, modeling human behaviors to detect the insider threat attack (behavior model). It comprises of 19 Percent of the total studies.

At the last comes the types of threat, which makes up 11 Percent of the total studies.

\subsubsection{Detection and Protection System}

<!-- \subsubsection{Hệ thống phát hiện và bảo vệ} -->

To detect the intrusion, an Intrusion Detection System (IDS) is used. To detect the intrusion and respond in timely manner is its prime function.

<!-- Để phát hiện sự xâm nhập, Hệ thống phát hiện xâm nhập (IDS) được sử dụng. Chức năng chính của nó là phát hiện sự xâm nhập và phản hồi kịp thời. -->

Based on the deployment IDS broadly classified into 2 types: Host based Intrusion Detection System (HIDS) and Network based Intrusion Detection System (NIDS).  Here is an overview of the two types \cite{leu2015internal}:     

<!-- Dựa trên IDS triển khai được phân loại rộng rãi thành hai loại, tức là Hệ thống phát hiện xâm nhập dựa trên máy chủ (HIDS) và Hệ thống phát hiện xâm nhập dựa trên mạng (NIDS). -->

Host based Intrusion Detection System is configured on a particular system/server. It continuously monitor and analyzes the activities the system where it is configured. Whenever an intrusion is detected HIDS triggers an alert.

For instance, when an attacker tries to create/modify/delete key system files alert will be generated. Major advantages of the HIDS that it analyzes the incoming encrypted traffic which cannot be detected NIDS. To detect the attack like Denial of Service (DoS) attacks, Port Scans, Distributed Denial of Service (DDoS) attack, ...

<!-- Hệ thống phát hiện xâm nhập dựa trên máy chủ được cấu hình trên một hệ thống/máy chủ cụ thể. Nó liên tục theo dõi và phân tích các hoạt động của hệ thống nơi nó được cấu hình. Bất cứ khi nào phát hiện sự xâm nhập, HIDS sẽ kích hoạt cảnh báo. -->

<!-- Ví dụ: Khi kẻ tấn công cố gắng tạo/sửa đổi/xóa các tệp hệ thống chính, cảnh báo sẽ được tạo. Ưu điểm chính của HIDS rằng nó phân tích lưu lượng được mã hóa đến mà NIDS không thể phát hiện được. Để phát hiện cuộc tấn công như Denial of Các cuộc tấn công dịch vụ (DoS), Quét cổng, tấn công từ chối dịch vụ phân tán (DDoS), v.v. -->

Network Intrusion Detection System (NIDS) continuously monitor and analyze the network traffic. To classify as malicious or non-malicious traffic it examines the incoming network traffic. If any predefined patterns or signatures of malicious behavior are present it re-assembles the packets, examine the headers/payload portion and determine.

<!-- Hệ thống phát hiện xâm nhập mạng (NIDS) liên tục giám sát và phân tích lưu lượng mạng. Để phân loại là lưu lượng truy cập độc hại hoặc không độc hại nó kiểm tra lưu lượng mạng đến. Nếu có bất kỳ mẫu hoặc dấu hiệu xác định trước nào của hành vi nguy hiểm thì nó tập hợp lại các gói tin, kiểm tra phần tiêu đề/tải trọng và xác định -->


<!-- Dịch tiếng Việt bên dưới TA -->
<!-- Thêm vào báo cáo -->
<!-- Thêm vào slide -->