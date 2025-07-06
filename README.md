# Espresso

A project for the 2025 CDS and H4I NME hackathon. 
Contributors:
Rahul Basak,
Rohit Vakkalagadda,
Mukund Gaur,
Boss Lertdamrongwong

Espresso is a powerful tool that leverages a Proxycurl LinkedIn API to enhance networking opportunities. It identifies university alumni in specific roles at a target company, auto-generates meeting requests based on user resume and availability, and supports email sending/editing.

Under the hood:

Authentication (OAuth)

Storing resume if already uploaded (FireBase)

Searching LinkedIn for people who attended your university and currently work at the company (ProxyCurl)

Building email & subject (Groq)

Finding email for intended target (Apollo)

Providing functionality to send/update the email (Gmail)
