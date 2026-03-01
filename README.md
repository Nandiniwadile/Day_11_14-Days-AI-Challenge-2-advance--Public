
🚀 Day 11 – Time Travel & Data Recovery
📚 Concepts Covered

Delta Lake Versioning

Time Travel

Rollback Mechanism

Data Auditing

🛠 Tasks Completed

1️⃣ Appended new records to Delta table
2️⃣ Queried older version using versionAsOf
3️⃣ Compared record differences
4️⃣ Restored table to previous version

🔎 Key Observations

Every insert creates a new version.

Delta maintains full history using DESCRIBE HISTORY.

Historical versions can be accessed anytime.

Rollback does not delete data permanently — it creates a new restored version.

🎯 Outcome

Successfully demonstrated data version control and recovery using Delta Lake.
