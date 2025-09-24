# Blockchain vs Traditional Databases

## CRUD Operations in Databases
- Traditional databases support **CRUD**:
  - **Create** → add new records  
  - **Read** → query existing records  
  - **Update** → modify data in place  
  - **Delete** → remove data entirely  

This flexibility allows businesses to maintain and correct data, but it also means data can be **tampered with**.

## Blockchain’s Design
- Blockchain **restricts CRUD**:
  - ✅ **Create** → add a new transaction/block  
  - ✅ **Read** → view the ledger (public or permissioned)  
  - ❌ **Update** → not allowed  
  - ❌ **Delete** → not allowed  

Instead of modifying or deleting, blockchain is **append-only**.  
Once a transaction is confirmed, it becomes **immutable** and cannot be changed.

## Key Insight
Blockchain was created to **prevent tampering** with data — ensuring trust, auditability, and transparency without relying on a central authority.

## Analogy
- Database = a text editor (you can write, edit, and delete).  
- Blockchain = a permanent notebook (you can only write new pages, never erase old ones).
