# DBeaver — Remote MySQL Database Handbook (step-by-step)

> A compact, hands-on guide to connect to **remote MySQL databases** using **DBeaver Community Edition**. This file is written as a ready-to-use `.md` handbook with placeholders for screenshots. Save screenshots in the `images/` folder (see filenames in the “Screenshots included” section) so the images render in the markdown.

---

## Table of contents


2. Step 1 — Install DBeaver
3. Step 2 — Start the New MySQL Connection Wizard
4. Step 3 — Enter MySQL connection settings (host, port, database)
5. Step 4 — Driver download / Driver properties
6. Step 5 — Test & Save Connection
8. Step 7 — Basic usage: browse tables and run queries

---

## 2. Step 1 — Install DBeaver

1. Download DBeaver Community from the official site and follow the OS-specific installer steps.

![Install DBeaver](images/00-install.png)

2. Launch DBeaver after installation.

---

## 3. Step 2 — Start the New MySQL Connection Wizard

1. Open DBeaver.
2. Click **Database → New Database Connection** or use the **New Connection** (plug) icon in the toolbar.

![New Connection wizard](images/01-new-mysql-connection.png)

3. In the list, select **MySQL** and click **Next**.

---

## 4. Step 3 — Enter MySQL connection settings

1. Fill in the main fields shown in the connection dialog:
   - **Host**: `mysql.example.com` or `192.168.1.100`
   - **Port**: `3306`
   - **Database**: your MySQL schema name
   - **User name** & **Password**

```text
Example:
Host: mysql.example.com
Port: 3306
Database: employees
User: report_user
Password: ********
```

2. (Optional) Set **Connection name** to something descriptive (e.g., `mysql-prod-readonly`).

![MySQL Connection settings](images/02-mysql-connection-settings.png)

---

## 5. Step 4 — Driver download / Driver properties

- If the MySQL JDBC driver is not present, DBeaver will prompt to download it. Click **Download**.

![Driver download prompt](images/03-mysql-driver-download.png)

- Advanced: open **Driver properties** to add SSL, timezone, or character set parameters if needed.

---

## 6. Step 5 — Test & Save Connection

1. Click **Test Connection** to validate MySQL settings.
2. If the test is successful, click **Finish** to save the connection.

![Test MySQL connection success](images/04-test-mysql-connection.png)

3. Your MySQL connection will appear in the **Database Navigator**.

---

## 8. Step 7 — Basic usage: browse tables and run queries

- Expand the MySQL connection in **Database Navigator** → Schemas → Tables.
- Right-click a table → **View Data** to see rows.
- To run queries: Right-click the connection → **SQL Editor → New SQL Script** or press `Ctrl+Enter`.

![SQL editor and table view](images/06-sql-editor.png)

- Export data: Right-click table → **Export Data** → choose CSV / Excel / SQL.

---

*End of handbook*

