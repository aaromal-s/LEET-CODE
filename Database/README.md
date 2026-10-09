# 🗄️ Database (SQL)

This folder contains solutions to LeetCode **Database / MySQL** problems focusing on joins, aggregations, date manipulation, and data cleanup.

---

## 📑 Problem List

| # | Problem Title | Difficulty | Core Concept | Time Complexity | Space Complexity | Solution Document |
| :-: | :--- | :-: | :--- | :-: | :-: | :--- |
| 175 | [Combine Two Tables](https://leetcode.com/problems/combine-two-tables/) | 🟢 Easy | `LEFT JOIN` | $O(N + M)$ | $O(N)$ | [175. Combine Two Tables.md](./175.%20Combine%20Two%20Tables.md) |
| 181 | [Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/) | 🟢 Easy | `INNER JOIN` (Self Join) | $O(N)$ | $O(N)$ | [181. Employees Earning More Than Their Managers.md](./181.%20Employees%20Earning%20More%20Than%20Their%20Managers.md) |
| 182 | [Duplicate Emails](https://leetcode.com/problems/duplicate-emails/) | 🟢 Easy | `GROUP BY` & `HAVING` | $O(N)$ | $O(U)$ | [182. Duplicate Emails.md](./182.%20Duplicate%20Emails.md) |
| 183 | [Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/) | 🟢 Easy | `LEFT JOIN ... WHERE IS NULL` | $O(C + O)$ | $O(C)$ | [183. Customers Who Never Order.md](./183.%20Customers%20Who%20Never%20Order.md) |
| 196 | [Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/) | 🟢 Easy | `DELETE` with Self Join | $O(N \log N)$ | $O(1)$ | [196. Delete Duplicate Emails.md](./196.%20Delete%20Duplicate%20Emails.md) |
| 197 | [Rising Temperature](https://leetcode.com/problems/rising-temperature/) | 🟢 Easy | Date Diff Self Join (`DATEDIFF`) | $O(N)$ | $O(N)$ | [197. Rising Temperature.md](./197.%20Rising%20Temperature.md) |
| 511 | [Game Play Analysis I](https://leetcode.com/problems/game-play-analysis-i/) | 🟢 Easy | `GROUP BY` & `MIN()` | $O(N)$ | $O(P)$ | [511. Game Play Analysis I.md](./511.%20Game%20Play%20Analysis%20I.md) |
