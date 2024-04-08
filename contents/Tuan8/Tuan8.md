<!-- Hello everyone, -->

<!-- My name is Nghia. -->

Last week, my group presented "Loss of control" 
Today, I continue to talk about "Shortage of Transparency" and "Virtual Machine Related Challenges"
The first is xxxxxxx content

<!-- @Shortage of Transparency -->
<!-- !Malicious Insiders/Unauthorized Internal Access -->

Threats amplify due to the convergence of IT services under a single management domain; General lack of transparency into CSP processes \& procedures; less visibility into the hiring standard and practices of cloud employees’ lead to adversary.

A malicious insider, such as a system administrator, in an improperly designed cloud scenario can have access to potentially sensitive information.

<!-- Results: Espionage; hacker; organized crime; corporate espionage; spoofing; tampering, information disclosure; nation-state sponsored intrusion; Brand damage; financial impact; productivity losses; impact on business continuity, traditional security and disaster recovery . -->

<!-- @ Tiếp theo về -->
<!-- Next about -->

<!-- !Ambiguous ownership \& responsibility -->

Lack of clear ownership and defined responsibilities for data protection may responsibility result in failure of meeting regulatory and of data legal obligations.

Authentication and Authorization: Cloud building organizations has to authenticate each and every person who is using the cloud from the cloud utilizing organization.

They will provide authorizations to the users based on the service usage and payment.

The cloud building organization has to prevent unauthorized users by checking authorization.

The cloud utilizing organization has to remove or disable accounts of the ex-employees on day-to-day basis.

<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->
<!-- @ Virtual Machine Related Challenges -->

\begin{itemize}
\item Virtualization refers to the logical abstraction of computing resources from physical constraints. One representative example of virtualization technology is the virtual machine.
\item Despite of its substantial benefits, this technology also introduces security and privacy risks in the cloud computing environment.
\end{itemize}
<!-- ! Security threats sourced from host -->
\item The host machine there are implications that allow the host to monitor and communicate with VM applications up running.

\item It is more necessary to strictly protect the host machines than protecting distinctive VMs.

\item The enterprise can co-locate applications with different trust levels on the same host and can defend VMs in a shared multi-tenant environment.

$\Rightarrow$ This enables enterprises to maximize the benefits of virtualization.

\item The host can influence the VMs in the following ways \cite{hussein2016survey}:
\begin{itemize}
\item The host can start, shut down, pause, and restart VMs.
\item Monitoring and configuration of resources which are available to the VMs, these include: CPU, memory, disk, and network usage of VMs.
\item Adjust the number of CPUs, the amount of memory, the amount and number of virtual disks, and several virtual network interfaces that are available to a VM.
\item Monitoring the applications which are running inside the VM.
\item View, copy, and possibly modify, data stored on the VM's virtual disks. Unfortunately, the system admin or any authorized user who has privileged control over the backend can misuse these procedures.
\end{itemize}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- ! Security threats sourced from other VM -->
\item Monitoring VMs could violate security and privacy, but could also be prevented by isolating security tools from an untrusted VM.
\item Communication between VMs: Sharing resources between VMs may strip security of each VM.
\item Denial of Service (DoS): A DoS attack is a trying to denial services that provide to authorize users.

\begin{block}{Example}
For example when trying to access site we see that due to overloading of the server with the requests to access the site, we are unable to access the site and observe an error. This happens when the number of requests that can be handled by a server exceeds its capacity, the Dos attack marking carting part of clouds inaccessible to the users.
\end{block}



<!-- ok, my presentation is done -->
<!-- Thank you for listening -->


    \subsection{Virtual Machine Related Challenges}
Virtualization refers to the logical abstraction of computing resources from physical constraints. One representative example of virtualization technology is the virtual machine (VM). Virtualization can also be performed on many other computing resources, such as operating system, networks, memory, and storage. In a virtualized environment, computing resources can be dynamically created, expanded, shrunk or moved according to users’ demand, which greatly improves agility and flexibility, reduces costs and enhances business values for cloud computing. 




Despite of its substantial benefits, this technology also introduces security and privacy risks in the cloud computing environment.


    \subsubsection{Security threats sourced from host}
Monitoring VMs from host The control point in virtual environment is the host machine there are implications that allow the host to monitor and communicate with VM applications up running. Therefore, it is more necessary to strictly protect the host machines than protecting distinctive VMs . VM-level protection is crucial in cloud computing environment. The enterprise can co-locate applications with different trust levels on the same host and can defend VMs in a shared multi-tenant environment. This enables enterprises to maximize the benefits of virtualization. VM-level protection allows VMs to stay secure in today’s dynamic data centers. Also, as VMs travel between different environments – from on-premise virtual servers to private clouds to public clouds, and even between cloud vendors 
      \cite{hussein2016survey}.




 Communications between VMs and host The data transfer between VMs and the host flow between VMs shared virtual resources; in fact the host can monitor the network traffic of its own hosted VMs. This can be considering useful features for attackers and they may use it such as shared clipboard which allows data to transfer between VMs and the host using cooperating malicious program in VMs. It is not generally considered a bug or limitation when one can initiate monitoring, change, or communication with a VM application from the host. The host environment needs to be more strictly secured than the individual VMs. The host can influence the VMs in   the following ways \cite{hussein2016survey}:



\begin{itemize}
\item     The host can Start, shutdown, pause, and restart VMs.
 \item     Monitoring and configuration of resources which are available to the VMs, these include: CPU, memory, disk, and network usage of VMs. 
\item     Adjust the number of CPUs, the amount of memory, the amount and number of virtual disks, and a number of virtual network interfaces which are available to a VM.
\item     Monitoring the applications which are running inside the VM.
 \item     View, copy, and possibly modify, data stored on the VM's virtual disks. Unfortunately, the system admin or any authorized user who has privileged control over the backend can misuse these procedures. 
\end{itemize}



    \subsubsection{Security threats sourced from other VM}
    
\textbf{Monitoring VMs from other VM:} Monitoring VMs could violate security and privacy, but the new architecture of CPUs, integrated with a memory protection feature, could prevent security and privacy violation. A major reason for adopting virtualization is to isolate security tools from an untrusted VM by moving them to a separate trusted secure VM.






 \textbf{Communication between VMs:} One of the most critical threads that threaten exchanging information between virtual machines is how it's deployed. Sharing resources between VMs may strip security of each VM for instance collaboration using application such as shared clipboard that allow exchanging data between VMs and the host assisting malicious program in VMs, this situation violate security and privacy. Also, a malicious VM can has chance to access other VMs through shard memory.




 
\textbf{Denial of Service (DoS):} A DoS attack is a trying to denial services that provide to authorize users. For example when trying to access site we see that due to overloading of the server with the requests to access the site, we are unable to access the site and observe an error. This happens when the number of requests that can be handled by a server exceeds its capacity, the Dos attack marking carting part of clouds inaccessible to the users. Usage of an Intrusion Detection System (IDS) one of the useful method of defense against this type of attacks.




