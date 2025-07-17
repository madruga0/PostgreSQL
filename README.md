# PostgreSQL Notes

## 🧱 1. DDL – Data Definition Language

Defines or changes the structure of database objects (tables, schemas, indexes, etc.).

| Command   | Description                                      |
|-----------|--------------------------------------------------|
| `CREATE`  | Creates a new table, database, index, etc.       |
| `ALTER`   | Modifies an existing object (e.g., add column)   |
| `DROP`    | Deletes an object permanently                   |
| `TRUNCATE`| Removes all data from a table (faster than DELETE) |
| `RENAME`  | Changes the name of an object                   |
| `COMMENT` | Adds comments to the schema objects             |

---

## 🧮 2. DML – Data Manipulation Language

Deals with the manipulation of data within tables.

| Command   | Description                                      |
|-----------|--------------------------------------------------|
| `SELECT`  | Retrieves data                                   |
| `INSERT`  | Adds new data                                    |
| `UPDATE`  | Modifies existing data                          |
| `DELETE`  | Removes data                                    |
| `MERGE`   | Merges data from one table into another (used in some DBs) |

---

## 🔐 3. DCL – Data Control Language

Controls permissions and access to data.

| Command   | Description                                      |
|-----------|--------------------------------------------------|
| `GRANT`   | Gives user access rights                        |
| `REVOKE`  | Removes access rights                           |

---

## 🔁 4. TCL – Transaction Control Language

Manages transactions to maintain data integrity.

| Command         | Description                                      |
|------------------|--------------------------------------------------|
| `COMMIT`        | Saves the changes made by a transaction          |
| `ROLLBACK`      | Undoes changes since the last `COMMIT`           |
| `SAVEPOINT`     | Sets a point within a transaction to roll back to |
| `SET TRANSACTION`| Defines properties of a transaction (like isolation level) |

---

## 🧠 Bonus Tip: Real-world Analogy

| SQL Category | Analogy in a Text Editor                          |
|--------------|---------------------------------------------------|
| DDL          | Creating/renaming/deleting files                 |
| DML          | Editing content inside the file                  |
| TCL          | Saving or undoing your changes                   |
| DCL          | Setting file read/write permissions              |
