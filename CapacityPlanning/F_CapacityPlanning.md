+----------------------------------+------------------------+----------+
| ![](vertopal_                    |                        |          |
| b550e5d73be94619af568c18b8ca14ad |                        |          |
| /media/image1.png){width="2.4in" |                        |          |
| height="0.5881944444444445in"}   |                        |          |
|                                  |                        |          |
| SCHOOL OF INFORMATION AND        |                        |          |
| TECHNOLOGY                       |                        |          |
+----------------------------------+------------------------+----------+
| **NAME:** Gerardo, Charles       | **DATE PERFORMED:**    | /50      |
| Hanzel\                          |                        |          |
| Lacar, Heart Angelo              |                        |          |
+----------------------------------+------------------------+----------+
| **Section:** IDC2                | **DATE SUBMITTED:**    |          |
+----------------------------------+------------------------+----------+

# SYSADM1 -- Capacity Management & Planning

**Part 2. Network Scalability Analysis**

Recall the e-commerce website scenario we discussed earlier. Given the
expected surge in traffic, analyze the provided network topology
diagram. Identify potential bottlenecks and areas where scalability
might be a concern. Propose specific strategies to improve the
network\'s scalability and performance to ensure a seamless user
experience during the peak traffic period. Consider factors such as
increased user demand, new applications, and security threats.

![](vertopal_b550e5d73be94619af568c18b8ca14ad/media/image2.png){width="5.052917760279965in"
height="3.8255161854768156in"}

![](vertopal_b550e5d73be94619af568c18b8ca14ad/media/image3.png){width="6.261290463692038in"
height="4.125575240594926in"}

**Network Analysis**

The network design identifies key potential issues that could impact its
efficiency and security. Bottlenecks are most likely to occur at the
access layer, where oversubscription may lead to congestion, or between
the distribution and core layers if link capacities are insufficient
during peak traffic. Security risks include single points of failure,
unauthorized access due to weak access controls, and the absence of
advanced protection mechanisms like intrusion detection systems (IDS).
Furthermore, the capacity of distribution switches could limit the
ability to handle increasing traffic from both end devices and servers
as the network grows. These issues highlight the need for robust traffic
management, redundancy, and security protocols.

**Scalability Planning**

To address scalability, the design proposes three key solutions:
hardware upgrades, software enhancements, and improved traffic
segmentation. Hardware upgrades include adopting stackable distribution
switches with modular capacity, enabling expansion as demand increases.
This approach supports higher-capacity uplinks to reduce congestion and
handle future traffic.

+----------------------+-----------------------+-----------------------+
| **Proposed           | **Drawbacks**         | **Benefits**          |
| solution**           |                       |                       |
+======================+=======================+=======================+
| **Hardware           |   ------------------  | Supports future       |
| Upgrades**           |                       | growth and higher     |
|                      |   ------------------  | capacity.             |
|                      |                       |                       |
|                      |   ------------------  |                       |
|                      |   High initial cost   |                       |
|                      |   and downtime for    |                       |
|                      |   installation.       |                       |
|                      |   ------------------  |                       |
|                      |                       |                       |
|                      |   ------------------  |                       |
+----------------------+-----------------------+-----------------------+
| **Software           | Complexity in         | Increases network     |
| Enhancements**       | configuration.        | efficiency and        |
|                      |                       | security.             |
+----------------------+-----------------------+-----------------------+
| **Improved           | Risk of               | Reduces broadcast     |
| Segmentation**       | misconfiguration.     | domains, improves     |
|                      |                       | control.              |
+----------------------+-----------------------+-----------------------+

  ----------------- ------------------ ------------------- ---------------------
  Criteria          Excellent \| 10pts Good \| 7pts        Needs Improvement \|
                                                           4pts

  **Network         Accurately         Identifies key      Identifies some basic
  Analysis**        identifies         network components  network components
                    potential          and some potential  but lacks a
                    bottlenecks,       bottlenecks.        comprehensive
                    security risks,                        analysis.
                    and capacity                           
                    limitations.                           

  **Scalability     Proposes multiple  Proposes some       Proposes limited
  Planning**        relevant solutions relevant            scalability
                    and provides       scalability         strategies.
                    detailed           strategies but      
                    explanations,      lacks detail.       
                    including                              
                    potential                              
                    drawbacks and                          
                    benefits.                              

  **Evaluation of   Proposes           Provides a basic    Does not evaluate the
  Solutions**       comprehensive      evaluation of the   proposed solutions or
                    scalability        proposed solutions, provides a
                    strategies,        but lacks depth.    superficial
                    including specific                     evaluation.
                    recommendations                        
                    for hardware                           
                    upgrades, software                     
                    configurations,                        
                    and network                            
                    optimizations.                         

  **Proposed        Provides a         Provides a basic    Does not provide a
  Design**          detailed and       design but lacks    clear and detailed
                    well-justified     specific details    design.
                    design, including  and justifications. 
                    network diagrams,                      
                    configuration                          
                    details, and                           
                    implementation                         
                    plans.                                 

  **Evaluation and  Provides a         Provides a basic    Does not evaluate the
  Justification**   thorough           evaluation of the   proposed solutions or
                    evaluation of the  proposed solutions, provides a
                    proposed           but lacks depth.    superficial
                    solutions,                             evaluation
                    considering                            
                    factors like cost,                     
                    complexity, and                        
                    potential impact.                      

  Score:                                                   /50
  ----------------- ------------------ ------------------- ---------------------
