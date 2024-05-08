Hello every one,

Today, I'm here to talk about "Distributed Denial of Service - DDoS Attack".

<!-- !  -->

What is DDoS?

<!-- DDoS là gì? -->

DDoS[3] is one of the Network-Based Attacks, which come from the Internet.

<!-- • DDoS [3] là một trong những cuộc tấn công dựa trên mạng xuất phát từ Internet. -->

DDoS attacks are launched by affecting the victim in the following forms[4]:

<!-- • Các cuộc tấn công DDoS được phát động bằng cách tác động đến nạn nhân dưới các hình thức sau[4]: -->

▶ Attackers can find some bug or weakness in the software implementation to disrupt the service.

<!-- ► Những kẻ tấn công có thể tìm thấy một số lỗi hoặc điểm yếu trong quá trình triển khai phần mềm để làm gián đoạn dịch vụ. -->

▶ Some attacks deplete all the bandwidth or resources of the victims’ system.

<!-- ► Một số cuộc tấn công làm cạn kiệt toàn bộ băng thông hoặc tài nguyên của hệ thống nạn nhân. -->

<!-- !  -->

Attacker uses these resources as agents, called zombie machines.

<!-- Kẻ tấn công sử dụng những tài nguyên này làm tác nhân, được gọi là máy zombie. -->

The design of the internet gives rise to many conditions causing denial of service attacks. Security on the internet is dependent on hosts. Attackers compromise the security of hosts to launch DDoS attacks and use spoofed IP addresses making it difficult to trace attack source.

<!-- Thiết kế của Internet làm phát sinh nhiều điều kiện gây ra các cuộc tấn công từ chối dịch vụ. Bảo mật trên internet phụ thuộc vào máy chủ. Những kẻ tấn công xâm phạm tính bảo mật của máy chủ để khởi động các cuộc tấn công DDoS và sử dụng các địa chỉ IP giả mạo gây khó khăn cho việc truy tìm nguồn tấn công. -->

Further internet is full of hosts. It gives attackers various options, out of which vulnerable hosts are chosen

<!-- Hơn nữa internet có đầy đủ các máy chủ. Nó cung cấp cho kẻ tấn công nhiều lựa chọn khác nhau, trong đó các máy chủ dễ bị tổn thương được chọn -->

<!-- !  -->

Although widely known as a method of clogging transmission lines between Internet servers, DDoS seems to be more dangerous than people thought.

<!-- Mặc dù được biết đến rộng rãi như một phương pháp làm tắc nghẽn đường truyền giữa các máy chủ Internet nhưng DDoS dường như nguy hiểm hơn mọi người nghĩ. -->

In 1998s, the first DDoS tools were discovered. Although it had not been widely used, it was also the beginning of sophisticated attacks in the future.

<!-- Vào những năm 1998, công cụ DDoS đầu tiên được phát hiện. Dù chưa được sử dụng rộng rãi nhưng nó cũng là khởi đầu cho những cuộc tấn công tinh vi trong tương lai. -->

Almost 10 years later, jaxx.de, a gambling site was under DDoS attack and to stop this attack, the attacker demanded 40,000 euros .

<!-- Gần 10 năm sau, jaxx.de, một trang web cờ bạc bị tấn công DDoS và để ngăn chặn cuộc tấn công này, kẻ tấn công đã yêu cầu 40.000 euro. -->

On 4th July (Independence Day in the US) 27 websites of the White House, the Federal Trade Commission, the Department of Transportation, and the Department of the Treasury were attacked. On 1st August, the Blogging pages of many social networking sites (Twitter X, Facebook, etc.) were affected ...

<!-- Vào ngày 4/7 (Ngày Độc lập ở Mỹ), 27 trang web của Nhà Trắng, Ủy ban Thương mại Liên bang, Bộ Giao thông Vận tải và Bộ Tài chính đã bị tấn công. Vào ngày 1 tháng 8, các trang Blog của nhiều trang mạng xã hội (Twitter X, Facebook, v.v.) đã bị ảnh hưởng ... -->
<!-- !  -->

Constituents of DDoS attack

<!-- Các thành phần của cuộc tấn công DDoS -->

Many computers which make use of client-server technology are used for launching a DDoS Attack.

<!-- Nhiều máy tính sử dụng công nghệ máy khách-máy chủ được sử dụng để khởi động Cuộc tấn công DDoS. -->

In general, DDoS attack comprises of Master, Handler, Agents and victim.

<!-- Nhìn chung, cuộc tấn công DDoS bao gồm Master, Handler, Agent và nạn nhân. -->

The zombies (agents or bots) are the ones used by the master to form a botnet. The larger the number of zombies, the more disruptive the attack will be.

<!-- Zombie (đặc vụ hoặc bot) là những thứ được chủ nhân sử dụng để tạo thành mạng botnet. Số lượng zombie càng lớn thì cuộc tấn công sẽ càng rối loạn. -->

The Master communicates with agents via handlers.

<!-- Master giao tiếp với các đại lý thông qua các trình xử lý. -->

<!-- !  -->

Example

<!-- Ví dụ -->

Handlers can be programs on a set of devices (e.g., network servers) that attackers communicate with to send commands.

<!-- Trình xử lý có thể là các chương trình trên một tập hợp thiết bị (ví dụ: máy chủ mạng) mà kẻ tấn công liên lạc để gửi lệnh. -->

Attacker sends commands and controls their agent through handlers.

<!-- Kẻ tấn công gửi lệnh và điều khiển tác nhân của chúng thông qua các trình xử lý. -->

Bots are devices that the handlers have compromised.

<!-- Bot là thiết bị mà người xử lý đã xâm phạm. -->

Attacker uses many scanning techniques to find a vulnerable machine. Random Scan is the simplest strategy which randomly scans whole IPv4 address space as the worm doesn’t know where the host is present. It is effective only for IPv4 as the address space of IPv6 is too vast.

<!-- Kẻ tấn công sử dụng nhiều kỹ thuật quét để tìm ra một máy dễ bị tấn công. Quét ngẫu nhiên là chiến lược đơn giản nhất quét ngẫu nhiên toàn bộ không gian địa chỉ IPv4 vì sâu không biết máy chủ hiện diện ở đâu. Nó chỉ có hiệu quả đối với IPv4 vì không gian địa chỉ của IPv6 quá rộng. -->

Hitlist Scan maintains a list of vulnerable IP addresses and conducts scans accordingly. Once a vulnerable host is identified, the next step is to uncover its vulnerabilities to gain control.

<!-- Hitlist Scan duy trì danh sách các địa chỉ IP dễ bị tấn công và tiến hành quét tương ứng. Sau khi xác định được máy chủ dễ bị tấn công, bước tiếp theo là phát hiện các lỗ hổng của nó để giành quyền kiểm soát. -->
<!-- !  -->

<!-- !  -->
