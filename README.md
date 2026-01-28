# 📲MELBUR POS – Android Application Demonstration Repository
Developed at Melbur Studios, for Melbur Foods<br>

🧩 *Overview*<br>
Melbur POS is an Android-based point-of-sale application designed and maintained at Melbur Studios for internal business use at Melbur Foods. The system was developed in 2022 and started operations that October, to align with Melbur Foods’ expansion to Ngara, Nairobi. It has undergone continuous improvements, technical refinements, and branding updates by Melbur Studios since then.<br>
This repository provides a limited, demonstration-only view of the application’s internal structure for portfolio and assessment purposes. Only selected, non-sensitive, non-executable files have been included. The application is fully functional in production, but the upload here intentionally excludes core runtime files, private modules, and commercially sensitive components.<br><br>

🎯 *Purpose of This Repository*<br>
This repository exists solely to demonstrate technical capability, app structure, and branding work performed at Melbur Studios. It includes:<br>
• Key configuration files<br>
• Resource structures<br>
• Branding-related assets<br>
• Screenshots documenting live usage<br>
• Version metadata<br>
• Internal documentation via extracted files<br>
The goal is to provide reviewers with a transparent, verifiable snapshot of the system’s architecture without distributing the full production source code.<br><br>

📂 *Files Included in This Repository*<br>
Only vital, non-sensitive files are provided here, sufficient to show the app’s internal structure, branding, resource definitions, and core configuration.<br>
a) AndroidManifest.xml<br>
This file defines the application’s structure, package name (com.melbur.pos), permissions, branding, entry activities, and app-level metadata. It reflects the latest version deployed and displays the official Melbur Studios development credit:<br>
<!-- Developed at Melbur Studios -->
b) apktool.yml<br>
Contains version metadata and decoding information. This file helps reviewers verify that the extracted resources match the genuine application installed at Melbur Foods.<br>
c) /res/values/ directory<br>
Key resource XML files used to define the app’s presentation and behavior, including:<br>
• strings.xml<br>
Contains user-facing text, alerts, messages, and labels. Also includes updated text elements that reflect the app's continuous improvements since it was first launched.<br>
• styles.xml<br>
Defines the application’s theme, typography, text styles, and interface visual consistency.<br><br>

🖼️ *Screenshots Included*<br>
The repository also includes visual evidence of the app in real use at Melbur Foods:<br>
• App Icon Screenshot<br>
Located in /screenshots/01-app-interface<br>
Shows the branded Melbur POS interface running on an Android device.<br>
• App Dashboard Screenshot<br>
Located in /screenshots/02-dashboard-interface.jpg<br>
Shows the app's dashboard showing the list of products we sell, arranged alphabetically<br>
• Digital Receipt Screenshot<br>
Located in /screenshots/03-digital-receipt.jpg<br>
A sample receipt generated directly by the POS system<br>
• Located in /screenshots/04-payment-methods<br>
Shows the modes of payment that can be used to finalize a transaction<br>
• Physical Receipt Photo<br>
Located in /screenshots/05-physical-receipt.jpg<br>
A photograph of a real printed receipt produced by the POS device using the Melbur POS app, demonstrating operational integration with Melbur Foods’ hardware setup.<br>
These pieces together demonstrate real-world operational usage, accuracy in sales logging, and integration between the software and printing hardware.<br><br>

⚙️ *Infrastructure & Technology*<br>
Melbur POS was created using a mixed Android stack using the following frameworks: <br>
a) Java – this is the main language originally used for the app<br>
b) Kotlin – we have been transitioning to Kotlin in later years, which is now the recommended Android language<br>
c) XML – used to make all UI layouts, styles, themes, and resources, including strings.xml, styles.xml, and more<br>
d) Gradle – used for building, dependency management, and versioning<br>
e) REST & JSON – to connect to online accounts, APIs, and cloud sync features.<br><br>

🧪 *Decompilation Note*<br>
To generate the files included in this repository:<br>
• The live production APK was decompiled for documentation purposes<br>
• Only high-level, non-sensitive assets were extracted<br>
• No executable classes (.dex, .smali) or proprietary modules are uploaded<br>
The upload includes enough structural data to show:<br>
• App identity<br>
• Branding<br>
• Resource organization<br>
• Version authenticity<br>
• Configuration structure<br>
This approach protects the integrity of the production application while still demonstrating technical competence.<br><br>

👀*Repository Scope and Visibility*<br>
This repository contains selected, representative files only, provided for technical review and demonstration purposes. The complete system includes additional proprietary components and configurations that are not publicly shared, as the software remains the intellectual property of Melbur Studios and is commercially licensed to partner organisations.<br>

The repository is intentionally maintained within a limited visibility window (1 January – 31 May 2026) for assessment and verification purposes. After this period, the repository may be restricted or made private to protect commercial IP.<br><br>

👨‍💻 *Author & Credits*<br>

    🛠️ Developed at Melbur Studios<br>
    🌐 https://studios.melbur.co.ke<br>
    👤 Project Lead: Benson Muya<br>
Melbur Studios is responsible for all updates, branding work, version management, technical maintenance, and refinement of the program.
