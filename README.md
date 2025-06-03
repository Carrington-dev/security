# Security
Notes on building cyber-attack proof applications
How to store passwords safely in the database?
Let’s take a look.
## 𝐓𝐡𝐢𝐧𝐠𝐬 𝐍𝐎𝐓 𝐭𝐨 𝐝𝐨
🔹 Storing passwords in plain text is not a good idea because anyone
with internal access can see them.
 Storing password hashes directly is not sufficient because it is
pruned to precomputation attacks, such as rainbow tables.
' To mitigate precomputation attacks, we salt the passwords.
## 𝐖𝐡𝐚𝐭 𝐢𝐬 𝐬𝐚𝐥𝐭?
According to OWASP guidelines, “a salt is a unique, randomly
generated string that is added to each password as part of the hashing
process”.
