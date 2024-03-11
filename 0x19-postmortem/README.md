Incident Report
Issue Summary:
Duration: The outage occurred from March 10, 2024, 18:00 EAT to March 11, 2024, 08:00 EAT.
Impact: The primary service affected was our e-commerce platform, resulting in a complete unavailability of the checkout process for approximately 30% of our users. Customers experienced prolonged loading times and timeouts during the outage.
Root Cause:
The root cause of the outage was identified as a misconfiguration in the load balancer settings, leading to an overload on the database servers.
Timeline:
March 10, 2024, 18:00 EAT: Issue detected through monitoring alerts indicating a significant increase in database response times.
March 10, 2024, 18:15 EAT: Engineers began investigating the issue, suspecting a potential database bottleneck.
March 10, 2024, 19:00 EAT: Initial investigation focused on database performance optimizations.
March 10, 2024, 21:00 EAT: Further analysis revealed load balancer misconfigurations affecting traffic distribution.
March 10, 2024, 23:00 EAT: Incident escalated to the infrastructure team for load balancer configuration review.
March 11, 2024, 08:00 EAT: The issue was resolved by adjusting load balancer settings to evenly distribute traffic among database servers.
Root Cause and Resolution:
Root Cause: Misconfiguration in the load balancer resulted in uneven distribution of traffic to the database servers, causing overload on some servers and impacting database performance.
Resolution: Load balancer settings were adjusted to distribute traffic evenly across all database servers, alleviating the overload and restoring normal database performance.
Corrective and Preventative Measures:
Improvements/Fixes:
Regular load balancer configuration audits to prevent similar misconfigurations.
Enhanced monitoring to quickly detect and respond to database performance issues.
Tasks to Address the Issue:
Conduct a comprehensive review of load balancer configurations to identify and rectify any potential misconfigurations.
Implement automated checks to ensure load balancer settings conform to best practices.
Enhance database monitoring to proactively detect and mitigate performance bottlenecks.
Schedule regular load testing to evaluate the system's ability to handle peak traffic loads and adjust configurations accordingly.
Provide additional training to the team on load balancer management and optimization techniques.
Conclusion:
The outage stemmed from a misconfiguration in the load balancer, resulting in an uneven distribution of traffic to the database servers. Through prompt detection and resolution, we were able to minimize the impact on our users. Moving forward, we will implement measures to prevent similar incidents and ensure the stability and reliability of our services.




