<div align="center">

<!-- Optional: Place your profile picture in the repo root as "profile.png" -->
<img src="./profile.png" alt="Harshit Kumar" width="150" height="150" style="border-radius: 50%; border: 3px solid #6366f1; box-shadow: 0 0 25px rgba(99, 102, 241, 0.5);" onerror="this.style.display='none'"/>

# ⚡ HARSHIT KUMAR
### *Full-Stack Software Engineer | Founder & Chief Architect of MoodNest*

<p align="center">
  <a href="https://www.linkedin.com/in/harshit-kumar-a7b82b292/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect%20With%20Me-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://moodnest.in">
    <img src="https://img.shields.io/badge/Production%20App-moodnest.in-6366f1?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Website"/>
  </a>
  <a href="https://drive.google.com/file/d/1uRuODVzZfjqeEdMgVLEffIRxp6p_3yNu/view?usp=drivesdk">
    <img src="https://img.shields.io/badge/Self%20Intro-Watch%20Video-10b981?style=for-the-badge&logo=google-drive&logoColor=white" alt="Google Drive Intro"/>
  </a>
  <a href="https://www.instagram.com/moodnest.in/">
    <img src="https://img.shields.io/badge/Instagram-@moodnest.in-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram Page"/>
  </a>
</p>

<br/>

> **💡 RECRUITER & TECHNICAL HIRING BRIEF**  
> I am a Full-Stack MERN Engineer who builds **high-throughput, real-world distributed systems**. Rather than building basic tutorial projects, I engineer production platforms that handle real financial transactions, operate in zero-connectivity environments, and solve complex operational bottlenecks.  
> 
> 🔗 **[Watch my 2-Minute Technical Self-Introduction on Google Drive](https://drive.google.com/file/d/1uRuODVzZfjqeEdMgVLEffIRxp6p_3yNu/view?usp=drivesdk)**  
> 🌐 **[Test the Live Enterprise Platform at moodnest.in](https://moodnest.in)**

</div>

---

## 🎯 ENGINEER PROFILE & ARCHITECTURAL PHILOSOPHY

I specialize in the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** with a heavy focus on **concurrency control, webhooks processing, and offline-first PWA engineering**.

* 🚀 **Core Engineering Focus:** Building fault-tolerant software capable of handling real-world chaos (e.g., payment gateway dropouts, cellular dead-zones, and simultaneous seat contention).
* 🛠️ **System Design Mindset:** Decoupled client-server architectures, ACID database transactions, and custom automated background job schedulers.
* 📈 **Business Impact:** Directly responsible for engineering systems that eliminate third-party ticketing commissions and reduce attendee gate entry times to under 800 milliseconds.

---

## 🏛️ FEATURED PRODUCTION SYSTEM: MOODNEST
### **🌐 [Live Production Deployment: https://moodnest.in](https://moodnest.in)**

**MoodNest** is a full-stack, enterprise-grade event reservation, ticketing, and venue verification engine built to replace legacy ticketing providers with a zero-commission, organizer-first operating layer.

```text
+---------------------------------------------------------------------------------+
|                              CLIENT TIER (React PWA)                            |
|   Responsive Glassmorphic UI  |  Service Worker Caching  |  IndexedDB Storage   |
+----------------------------------------+----------------------------------------+
                                         |
                                         v  JSON REST APIs / Bearer JWT
+----------------------------------------+----------------------------------------+
|                            SERVER TIER (Node.js & Express)                      |
|  Multi-Gateway Webhook Handlers  |  Seat-Hold Cron Schedulers  |  P2P Engine    |
+----------------------------------------+----------------------------------------+
                                         |
                                         v  ACID Multi-Document Transactions
+----------------------------------------+----------------------------------------+
|                           DATABASE & CLOUD (MongoDB Atlas)                      |
|    Hashed Ticket Manifests  |  Automated Indexing  |  Vercel Edge Distribution  |
+---------------------------------------------------------------------------------+
