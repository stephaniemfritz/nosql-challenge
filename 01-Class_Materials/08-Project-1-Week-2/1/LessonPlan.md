## 8.1: Install PostgreSQL and pgAdmin

### Overview

Most of today’s lecture will revolve around project work.

### Class Objectives

By the end of this lesson, the students will:

* Develop their projects.

* Confirm their PostgreSQL and pgAdmin installation with TAs.

---

### Instructor Notes

Today's class is primarily a project work day. However, it's also a great time to have the students verify their PostgreSQL and pgAdmin installation. User errors are common when installing new tools, so checking them today will set the students up for success when they reach the SQL unit.

---

### Time Tracker

| Start Time | Number | Activity                                           | Duration |
| ---------- | ------ | -------------------------------------------------- | -------- |
| 6:30 PM    | 1      | Everyone Do: Install Postgres                      | 0:15     |
| 6:45 PM    | 2      | Students Do: Project Work                          | 2:45     |
| 9:30 PM    |        | END                                                |          |

---

### 1. Everyone Do: Install Postgres (15 min)

**Corresponding Activity:** [01-Evr_Installations](Activities/01-Evr_Installations)

Send out the following supplemental guides for the students to use while installing pgAdmin and Postgres on their machines:

**Files:**

* macOS: [pgAdmin_and_Postgres_for_Mac.md](Activities/01-Evr_Installations/Resources/pgAdmin_and_Postgres_for_Mac.md)

* Windows: [pgAdmin_and_Postgres_for_Windows.md](Activities/01-Evr_Installations/Resources/pgAdmin_and_Postgres_for_Windows.md)

Announce to the class that they will need to install a coding environment that is capable of executing SQL queries.

Explain that the installations are identical&mdash;except for the visual components.

Begin guiding the class through the installation, explaining each step as you go:

* Visit the [Download page for PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads), and select the appropriate version for your operating system.

* After downloading the file, Mac users will click the `postgresql-16.1-1-osx.dmg` file.

* **Note**: Do not worry if the version here does not match the version on the download page; Postgres deploys updates frequently. However, ensure that the students download version 16.x and not a later version as these materials are only tested up to that version.

* Windows users will click on the `postgresql-16.1-1-windows-x64.exe` file. **Note:** The exact file version may be slightly different.

* Navigate through the Setup Wizard, and install PostgreSQL.
    * The default location for Windows users is `C:\Program Files\PostgreSQL\16`.
    * The default location for Mac users is `/Library/PostgreSQL/16`.

* Select the components to be installed. **Make sure to uncheck the "Stack Builder" box**.

* Mac users will encounter the following window:

  ![stack_builder_mac.png](https://static.bc-edx.com/data/dl-1-2/m8/lessons/1/img/stack_builder_mac.png)

* Windows users will encounter the following window:

  ![stack_builder_pc.png](https://static.bc-edx.com/data/dl-1-2/m8/lessons/1/img/stack_builder_pc.png)

* Next, add your data directory. Keep the default location:
    * For Windows users this location will be `C:\Program Files\PostgreSQL\16\data`.
    * For Mac users, this location will be `/Library/PostgreSQL/16/data`.

* When prompted, enter a password. **Make sure to record this password for later.**

* Keep the default port as `5432`, and, in the Advanced Options, locale can be set as `[Default locale]`.

* The final screen will be the “Pre Installation Summary.”

* Once the installation is complete, Mac users will find a folder in **Applications** with the installed files.

* Windows users will be able to access the same files by clicking the **Start** menu on their computer and scrolling to the **Postgres 16** folder.

* **Important:** If you are running the Big Sur update for macOS, you will need to download the latest version of pgAdmin. Use the following steps to do so:

* Visit the [pgAdmin download page](https://www.pgadmin.org/download/pgadmin-4-macos/), and select the latest version.

* Click the `.dmg` files, as in the following image, to start the download.

  ![pgAdmin dmg file](https://static.bc-edx.com/data/dl-1-2/m8/lessons/1/img/big_sur_pgadmin.png)

* Once the download is complete, click the `.dmg` file in your downloads to install.

* After it has finished installing, drag the `pgAdmin` file into your **Applications** folder. This will take a few minutes.

* Once the transfer completes, you will now be able to use `pgAdmin`. Note that you will still have a version in your PostgreSQL folder, but only use the version that you copied into **Applications**.

Open pgAdmin, which will open in a new browser tab, and verify that everyone is connected to a local Postgres server before proceeding to the next activity.

* Students will need to input their password to connect to the server

* **Note:** If the computer seems unresponsive when starting pgAdmin, reboot the machine and try again.

Make sure that everyone has Postgres installed and a server running before continuing the lesson.

---

### 2. Students Do: Project Work (165 min)

The students have the rest of class time to work on their projects.

---

© 2022 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
