*MELBUR POS* - Android Application Demonstration Repository
Developed at Melbur Studios

*Overview*
Melbur POS is an Android-based point-of-sale application designed and maintained at Melbur Studios for internal business use at Melbur Foods. The system was developed in 2022 and started operations that October, to align with Melbur Foods’ expansion to Ngara, Nairobi. It has undergone continuous improvements, technical refinements, and branding updates by Melbur Studios since then.
This repository provides a limited, demonstration-only view of the application’s internal structure for portfolio and assessment purposes. Only selected, non-sensitive, non-executable files have been included. The application is fully functional in production, but the upload here intentionally excludes core runtime files, private modules, and commercially sensitive components.

*Purpose of This Repository*
This repository exists solely to demonstrate technical capability, app structure, and branding work performed at Melbur Studios. It includes:
      •	Key configuration files
      •	Resource structures
      •	Branding-related assets
      •	Screenshots documenting live usage
      •	Version metadata
      •	Internal documentation via extracted files
The goal is to provide reviewers with a transparent, verifiable snapshot of the system’s architecture without distributing the full production source code.

*Files Included in This Repository*
Only vital, non-sensitive files are provided here, sufficient to show the app’s internal structure, branding, resource definitions, and core configuration.
    a)	`AndroidManifest.xml`
      This file defines the application’s structure, package name (`com.melbur.pos`), permissions, branding, entry activities, and app-level metadata. It reflects the latest version deployed at Melbur Foods and displays the official Melbur Studios development credit:
      <!-- Developed at Melbur Studios -->
    b)	`apktool.yml`
      Contains version metadata and decoding information. This file helps reviewers verify that the extracted resources match the genuine application installed at Melbur Foods.
    c)	`/res/values/` directory
      Key resource XML files used to define the app’s presentation and behavior, including:
        •	`strings.xml`
            Contains user-facing text, alerts, messages, and labels. Also includes updated text elements that reflect the app's continuous improvements since it was first launched.
        •	`styles.xml`
            Defines the application’s theme, typography, text styles, and interface visual consistency.

*Screenshots Included*
The repository also includes visual evidence of the app in real use at Melbur Foods:
      •	App Screenshot
        Located in `/screenshots/app-interface.png`
        Shows the branded Melbur POS interface running on an Android device.
      •	Digital Receipt Screenshot
        Located in `/screenshots/digital-receipt.png`
        A sample receipt generated directly by the Melbur POS system after completing a transaction.
      •	Physical Receipt Photo
        Located in `/screenshots/physical-receipt.jpg`
        A photograph of a real printed receipt produced by the POS device using the Melbur POS app, demonstrating operational integration with Melbur Foods’ hardware setup.
These three pieces together demonstrate real-world operational usage, accuracy in sales logging, and integration between the software and printing hardware.

*Infrastructure & Technology*
Melbur POS was created using a mixed Android stack using the following frameworks: 
      a)	Java – this is the main language originally used for the app
      b)	Kotlin – we have been transitioning to Kotlin in later years, which is now the recommended Android language
      c)	XML – used to make all UI layouts, styles, themes, and resources, including strings.xml, styles.xml, and more
      d)	Gradle – used for building, dependency management, and versioning
      e)	REST & JSON – to connect to online accounts, APIs, and cloud sync features.

*Decompilation Note*
To generate the files included in this repository:
      •	The live production APK was decompiled for documentation purposes
      •	Only high-level, non-sensitive assets were extracted
      •	No executable classes (`.dex`, `.smali`) or proprietary modules are uploaded
 The upload includes enough structural data to show:
      •	App identity
      •	Branding
      •	Resource organization
      •	Version authenticity
      •	Configuration structure
This approach protects the integrity of the production application while still demonstrating technical competence.

*Credits*
Developed at Melbur Studios
Website: https://studios.melbur.co.ke 
Lead Developer: Benson Muya
Melbur Studios is responsible for all updates, branding work, version management, technical maintenance, and refinement of the Melbur POS app.

*Visibility Window*
This repository is publicly accessible for review between:
15 December 2025 → 31 March 2026
After this period, the repository may be returned to private status for intellectual property protection.
