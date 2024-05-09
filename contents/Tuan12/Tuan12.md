```
Hello every one,

Today, I'm here to talk about "Distributed Denial of Service - DDoS Attack".

```

<!-- !  -->

```

What is DDoS?

```

<!-- DDoS là gì? -->

```

DDoS[3] is one of the Network-Based Attacks, which come from the Internet.

```

<!-- • DDoS [3] là một trong những cuộc tấn công dựa trên mạng xuất phát từ Internet. -->

```

DDoS attacks are launched by affecting the victim in the following forms[4]:

```

<!-- • Các cuộc tấn công DDoS được phát động bằng cách tác động đến nạn nhân dưới các hình thức sau[4]: -->

```

▶ Attackers can find some bug or weakness in the software implementation to disrupt the service.

```

<!-- ► Những kẻ tấn công có thể tìm thấy một số lỗi hoặc điểm yếu trong quá trình triển khai phần mềm để làm gián đoạn dịch vụ. -->

```

▶ Some attacks deplete all the bandwidth or resources of the victims’ system.

```

<!-- ► Một số cuộc tấn công làm cạn kiệt toàn bộ băng thông hoặc tài nguyên của hệ thống nạn nhân. -->

<!-- !  -->

```

Attacker uses these resources as agents, called zombie machines.

```

<!-- Kẻ tấn công sử dụng những tài nguyên này làm tác nhân, được gọi là máy zombie. -->

```

The design of the internet gives rise to many conditions causing denial of service attacks. Security on the internet is dependent on hosts. Attackers compromise the security of hosts to launch DDoS attacks and use spoofed IP addresses making it difficult to trace attack source.

<!-- Thiết kế của Internet làm phát sinh nhiều điều kiện gây ra các cuộc tấn công từ chối dịch vụ. Bảo mật trên internet phụ thuộc vào máy chủ. Những kẻ tấn công xâm phạm tính bảo mật của máy chủ để khởi động các cuộc tấn công DDoS và sử dụng các địa chỉ IP giả mạo gây khó khăn cho việc truy tìm nguồn tấn công. -->

```

Further internet is full of hosts. It gives attackers various options, out of which vulnerable hosts are chosen

````

<!-- Hơn nữa internet có đầy đủ các máy chủ. Nó cung cấp cho kẻ tấn công nhiều lựa chọn khác nhau, trong đó các máy chủ dễ bị tổn thương được chọn -->

<!-- !  -->


```
Although widely known as a method of clogging transmission lines between Internet servers, DDoS seems to be more dangerous than people thought.
```

<!-- Mặc dù được biết đến rộng rãi như một phương pháp làm tắc nghẽn đường truyền giữa các máy chủ Internet nhưng DDoS dường như nguy hiểm hơn mọi người nghĩ. -->

````

In 1998s, the first DDoS tools were discovered. Although it had not been widely used, it was also the beginning of sophisticated attacks in the future.

```

<!-- Vào những năm 1998, công cụ DDoS đầu tiên được phát hiện. Dù chưa được sử dụng rộng rãi nhưng nó cũng là khởi đầu cho những cuộc tấn công tinh vi trong tương lai. -->

```

Almost 10 years later, jaxx.de, a gambling site was under DDoS attack and to stop this attack, the attacker demanded 40,000 euros .

```

<!-- Gần 10 năm sau, jaxx.de, một trang web cờ bạc bị tấn công DDoS và để ngăn chặn cuộc tấn công này, kẻ tấn công đã yêu cầu 40.000 euro. -->


```

On 4th July (Independence Day in the US) 27 websites of the White House, the Federal Trade Commission, the Department of Transportation, and the Department of the Treasury were attacked. On 1st August, the Blogging pages of many social networking sites (Twitter X, Facebook, etc.) were affected ...

````

<!-- Vào ngày 4/7 (Ngày Độc lập ở Mỹ), 27 trang web của Nhà Trắng, Ủy ban Thương mại Liên bang, Bộ Giao thông Vận tải và Bộ Tài chính đã bị tấn công. Vào ngày 1 tháng 8, các trang Blog của nhiều trang mạng xã hội (Twitter X, Facebook, v.v.) đã bị ảnh hưởng ... -->
<!-- !  -->

```
Constituents of DDoS attack

```

<!-- Các thành phần của cuộc tấn công DDoS -->

```
Many computers which make use of client-server technology are used for launching a DDoS Attack.

```

<!-- Nhiều máy tính sử dụng công nghệ máy khách-máy chủ được sử dụng để khởi động Cuộc tấn công DDoS. -->

```
In general, DDoS attack comprises of Master, Handler, Agents and victim.

```

<!-- Nhìn chung, cuộc tấn công DDoS bao gồm Master, Handler, Agent và nạn nhân. -->

```
The zombies (agents or bots) are the ones used by the master to form a botnet. The larger the number of zombies, the more disruptive the attack will be.
````

<!-- Zombie (đặc vụ hoặc bot) là những thứ được chủ nhân sử dụng để tạo thành mạng botnet. Số lượng zombie càng lớn thì cuộc tấn công sẽ càng rối loạn. -->

````

The Master communicates with agents via handlers.

```

<!-- Master giao tiếp với các đại lý thông qua các trình xử lý. -->



<!-- !  -->


```

Example

```

<!-- Ví dụ -->


```

Handlers can be programs on a set of devices (e.g., network servers) that attackers communicate with to send commands.

```

<!-- Trình xử lý có thể là các chương trình trên một tập hợp thiết bị (ví dụ: máy chủ mạng) mà kẻ tấn công liên lạc để gửi lệnh. -->


```

Attacker sends commands and controls their agent through handlers.

```

<!-- Kẻ tấn công gửi lệnh và điều khiển tác nhân của chúng thông qua các trình xử lý. -->


```

Bots are devices that the handlers have compromised.

```

<!-- Bot là thiết bị mà người xử lý đã xâm phạm. -->


```

Attacker uses many scanning techniques to find a vulnerable machine. Random Scan is the simplest strategy which randomly scans whole IPv4 address space as the worm doesn’t know where the host is present. It is effective only for IPv4 as the address space of IPv6 is too vast.
````

<!-- Kẻ tấn công sử dụng nhiều kỹ thuật quét để tìm ra một máy dễ bị tấn công. Quét ngẫu nhiên là chiến lược đơn giản nhất quét ngẫu nhiên toàn bộ không gian địa chỉ IPv4 vì sâu không biết máy chủ hiện diện ở đâu. Nó chỉ có hiệu quả đối với IPv4 vì không gian địa chỉ của IPv6 quá rộng. -->

```
Hitlist Scan maintains a list of vulnerable IP addresses and conducts scans accordingly. Once a vulnerable host is identified, the next step is to uncover its vulnerabilities to gain control.
```

<!-- Hitlist Scan duy trì danh sách các địa chỉ IP dễ bị tấn công và tiến hành quét tương ứng. Sau khi xác định được máy chủ dễ bị tấn công, bước tiếp theo là phát hiện các lỗ hổng của nó để giành quyền kiểm soát. -->
<!-- !  -->

```

DDoS Classification

```

<!-- Phân loại DDoS -->

```

In "DDoS attack" includes "Bandwidth Depletion" and "Resource Deplition"

```

<!-- Trong “Tấn công DDoS” bao gồm “Cạn kiệt băng thông” và “Cạn kiệt tài nguyên” -->

```

In "Bandwidth Depletion" includes "Flooding attack" and "Amplification attack"

```

<!-- Trong "Cạn kiệt băng thông" bao gồm “Tấn công lũ lụt” và “Tấn công khuếch đại” -->

```

In "Resource Deplition" include "Protocol vulnerability exploitation" and "Malformed packet"

```

<!-- Trong “Cạn kiệt tài nguyên” bao gồm "Khai thác lỗ hổng giao thức" và "Gói không đúng định dạng" -->

<!-- !  -->

```

Bandwidth Depletion Attacks: This type of attack consumes the bandwidth of the victim or target system by flooding the unwanted traffic to prevent the traffic from reaching the victim network.

```

<!-- Tấn công làm suy giảm băng thông: Kiểu tấn công này tiêu tốn băng thông của nạn nhân hoặc hệ thống đích bằng cách làm tràn lưu lượng truy cập không mong muốn để ngăn chặn lưu lượng truy cập vào mạng nạn nhân. -->

```
Resource Depletion Attacks: The DDoS Resource depletion attack is targeted to exhaust the victim system’s resources, so that the users are not serviced.
```

<!-- Tấn công làm cạn kiệt tài nguyên: Cuộc tấn công làm cạn kiệt tài nguyên DDoS nhằm mục đích làm cạn kiệt tài nguyên của hệ thống nạn nhân, khiến người dùng không được phục vụ. -->

<!-- !  -->

```

Flood Attacks: launched by attacker sending a huge volume of traffic to the victim with the help of zombies that clog up the victim’s network bandwidth with IP traffic. A flood attack is initiated by UDP (User Datagram packets) and ICMP (Internet Control Message Protocol), with the following UDP attack steps:

```

<!-- Flood Attacks: do kẻ tấn công thực hiện gửi một lượng lớn lưu lượng truy cập đến nạn nhân với sự trợ giúp của zombie làm tắc nghẽn băng thông mạng của nạn nhân bằng lưu lượng IP. Một cuộc tấn công lũ lụt được bắt đầu bởi UDP (gói Datagram người dùng) và ICMP (Giao thức thông báo điều khiển Internet), với các bước tấn công UDP sau: -->

```
A large number of UDP packets are sent to the victim system’s random or specified ports.

```

<!-- Một số lượng lớn các gói UDP được gửi đến các cổng ngẫu nhiên hoặc cổng được chỉ định của hệ thống nạn nhân. -->

```
On receiving the packets, the victim system looks at the destination ports to identify the applications waiting on the port.

```

<!-- Khi nhận được gói tin, hệ thống nạn nhân sẽ nhìn vào các cổng đích để xác định các ứng dụng đang chờ trên cổng. -->

```
When there is no application, it generates an ICMP packet with a message “destination unreachable”.

```

<!-- Khi không có ứng dụng, nó sẽ tạo ra một gói ICMP với thông báo “không thể truy cập đích”. -->

```
The return packets from the victim are sent to the spoofed address and not to the zombies.

```

<!-- Các gói tin trả lại từ nạn nhân sẽ được gửi đến địa chỉ giả mạo chứ không phải đến zombie. -->

<!-- !  -->

```
ICMP attack steps:

```

<!-- Các bước tấn công ICMP: -->

```
Attacker sends a large number of ICMP ECHO REPLY i.e. ping packets to the victim system with the help of zombies (agents). This kind of packets requires a response message from the victim.
```

<!-- Kẻ tấn công gửi một số lượng lớn ICMP ECHO REPLY, tức là các gói ping đến hệ thống nạn nhân với sự trợ giúp của zombie (đặc vụ). Loại gói tin này yêu cầu một tin nhắn phản hồi từ nạn nhân. -->

````
The victim sends the responses to the packets received.

```

<!-- Nạn nhân gửi phản hồi cho các gói nhận được. -->


```
Now the network is clogged with request response traffic. The spoofed IP address may be used in the ICMP packet.

```

<!-- Bây giờ mạng bị tắc do lưu lượng phản hồi yêu cầu. Địa chỉ IP giả mạo có thể được sử dụng trong gói ICMP. -->



<!-- !  -->


```
Amplification attacks

```

<!-- Tấn công khuếch đại -->


```
This is a type of DDoS attack that uses the IP broadcast protocol.

```

<!-- Đây là một kiểu tấn công DDoS sử dụng giao thức quảng bá IP. -->


```
The attacker sends packets to the broadcast address, causing systems within that address range to respond to the victim's system, generating malicious network traffic.

````

<!-- Kẻ tấn công gửi các gói đến địa chỉ quảng bá, khiến các hệ thống trong phạm vi địa chỉ đó phản hồi lại hệ thống của nạn nhân, tạo ra lưu lượng truy cập mạng độc hại. -->

````
This type of attack takes advantage of the broadcast address feature in network devices such as routers.

```

<!-- Kiểu tấn công này lợi dụng tính năng địa chỉ quảng bá trong các thiết bị mạng như bộ định tuyến. -->


```
This can be done directly by the attacker or through control of the clients.

```

<!-- Điều này có thể được thực hiện trực tiếp bởi kẻ tấn công hoặc thông qua sự kiểm soát của khách hàng. -->


```
Typical examples of this type of attack include Smurf and Fraggle attacks

```

<!-- Các ví dụ điển hình của kiểu tấn công này bao gồm các cuộc tấn công Smurf và Fraggle -->



<!-- !  -->


```
Resource Depletion Attacks

```

<!-- Tấn công làm cạn kiệt tài nguyên -->


```
Protocol Exploit Attacks: The goal of these attacks is to consume the surplus quantity of resources from the victim by exploiting the specific feature of the protocol installed in the victim. TCP SYN attacks are the best example of this type. The other examples of Protocol exploit attacks are PUSH + ACK attack.

````

<!-- Tấn công khai thác giao thức: Mục tiêu của các cuộc tấn công này là tiêu thụ lượng tài nguyên dư thừa từ nạn nhân bằng cách khai thác tính năng cụ thể của giao thức được cài đặt trên nạn nhân. Các cuộc tấn công TCP SYN là ví dụ điển hình nhất của loại này. Các ví dụ khác về tấn công khai thác Giao thức là tấn công PUSH + ACK. -->

```
Malformed Packet Attacks: The term malformed packet refers to the packet wrapped with malicious information or data. The attacker sends these packets to the victim to crash it. This can be performed in two ways:

```

<!-- Tấn công gói không đúng định dạng: Thuật ngữ gói không đúng định dạng dùng để chỉ gói được bao bọc bằng thông tin hoặc dữ liệu độc hại. Kẻ tấn công gửi các gói này đến nạn nhân để phá hủy nó. Điều này có thể được thực hiện theo hai cách: -->
<!-- !  -->

```
Malformed Packet Attacks

```

<!-- Tấn công gói không đúng định dạng -->

```
IP Address attack: The malformed packet is wrapped with same source and destination IP address thus creating chaos in the operating system of victim. By this way it rapidly slows down and crashes the victim.

```

<!-- Tấn công địa chỉ IP: Gói không đúng định dạng được bọc cùng địa chỉ IP nguồn và đích, do đó tạo ra sự hỗn loạn trong hệ điều hành của nạn nhân. Bằng cách này, nó nhanh chóng chậm lại và đâm vào nạn nhân. -->

```
IP packet options attack: Each of the IP packets consists of the optional fields to carry additional information. This attack makes use of these fields to form the malformed packet. The optional fields are filled by setting all the quality of service bits to one. So the victim spends additional time to process this packet. This attack is more vulnerable when attacked by more than one zombie.

```

<!-- Tấn công tùy chọn gói IP: Mỗi gói IP bao gồm các trường tùy chọn để mang thông tin bổ sung. Cuộc tấn công này sử dụng các trường này để tạo thành gói không đúng định dạng. Các trường tùy chọn được điền bằng cách đặt tất cả các bit chất lượng dịch vụ thành một. Vì vậy nạn nhân dành thêm thời gian để xử lý gói tin này. Cuộc tấn công này dễ bị tổn thương hơn khi bị tấn công bởi nhiều zombie. -->
