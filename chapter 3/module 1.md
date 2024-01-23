# **Module 1:** Understand Access  Control  Concepts

****What is Security Control?****

- Control - a safeguard or countermeasure designed to preserve Confidentiality, Integrity and Availability of data
- Access control - involves limiting what objects can be available to what subjects according to what rules

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/f8a42bb0-8360-4779-a713-e8f8ebbf1067/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/ff453aaa-5e68-4810-8702-b8c16537c3bc/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/46b08bf4-97f3-459d-bc43-a2a8e91a5534/Untitled.png)

****Defense in Depth****

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/08dccdfd-97b1-495c-9163-02903bcccabd/Untitled.png)

****Principle of Least Privilege****

- a standard of permitting only minimum access necessary for users or programs to fulfill their function

****Privileged Access Management****

- provides the first and perhaps most familiar use case

****Privileged Accounts****

- those with permissions beyond those of normal users, such as managers and administrators
- these accounts have elevated privileges and are used by many different classes of users, including:
    - Systems administrators, who have the principal responsibilities for operating systems, applications deployment and performance management.
    - Help desk or IT support staff, who often need to view or manipulate endpoints, servers and applications platforms by using privileged or restricted operations.
    - Security analysts, who may require rapid access to the entire IT infrastructure, systems, endpoints and data environment of the organization.
- Typical measures used for moderating the potential for elevated risks from misuse or abuse of privileged accounts include the following:
    - More extensive and detailed **logging** than regular user accounts. The record of privileged actions is vitally important, as both a deterrent (for privileged account holders that might be tempted to engage in untoward activity) and an administrative control (the logs can be **audited** and reviewed to detect and respond to malicious activity).
    - More stringent access control than regular user accounts. As we will see emphasized in this course, even nonprivileged users should be required to use MFA methods to gain access to organizational systems and networks. Privileged users—or more accurately, highly trusted users with access to privileged accounts—should be required to go through additional or more rigorous authentication prior to those privileges. Just-in-time identity should also be considered as a way to restrict the use of these privileges to specific tasks and the times in which the user is executing them.
    - Deeper trust verification than regular user accounts. Privileged account holders should be subject to more detailed background checks, stricter nondisclosure agreements and acceptable use policies, and be willing to be subject to financial investigation. Periodic or event-triggered updates to these background checks may also be in order, depending on the nature of the organization’s activities and the risks it faces.
    - More auditing than regular user accounts. Privileged account activity should be monitored and audited at a greater rate and extent than regular usage.

****Segregation of Duties (Separation of Duties)****

- practice of ensuring that an organizational process cannot be completed by a single person

Two-person integrity

- a security strategy that requires a minimum of two people to be in an area together, making it impossible for a person to be in the area alone
- to reduce insider threats

****How Users Are Provisioned****

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/ed088632-a349-4805-af44-0f6af1080df8/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/eb085508-b5e9-44fe-ae4c-af254e81c906/Untitled.png)

![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ee53c098-1147-4863-ac76-386e5e3ab25f/25149713-d4e7-4507-8d3d-8c385335eefa/Untitled.png)

****The Benefit of Multiple Controls****

- multiple controls include - physical, technical and administrative controls
