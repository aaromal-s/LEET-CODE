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
| 577 | [Employee Bonus](https://leetcode.com/problems/employee-bonus/) | 🟢 Easy | `LEFT JOIN` & `IS NULL` | $O(E + B)$ | $O(E)$ | [577. Employee Bonus.md](./577.%20Employee%20Bonus.md) |
| 584 | [Find Customer Referee](https://leetcode.com/problems/find-customer-referee/) | 🟢 Easy | Three-Valued Logic / `IS NULL` | $O(N)$ | $O(N)$ | [584. Find Customer Referee.md](./584.%20Find%20Customer%20Referee.md) |
| 586 | [Customer Placing the Largest Number of Orders](https://leetcode.com/problems/customer-placing-the-largest-number-of-orders/) | 🟢 Easy | `GROUP BY` & `ORDER BY COUNT() DESC` | $O(N \log U)$ | $O(U)$ | [586. Customer Placing the Largest Number of Orders.md](./586.%20Customer%20Placing%20the%20Largest%20Number%20of%20Orders.md) |
| 595 | [Big Countries](https://leetcode.com/problems/big-countries/) | 🟢 Easy | `WHERE ... OR` Filter | $O(N)$ | $O(N)$ | [595. Big Countries.md](./595.%20Big%20Countries.md) |
| 596 | [Classes More Than 5 Students](https://leetcode.com/problems/classes-more-than-5-students/) | 🟢 Easy | `GROUP BY` & `HAVING COUNT() >= 5` | $O(N)$ | $O(K)$ | [596. Classes More Than 5 Students.md](./596.%20Classes%20More%20Than%205%20Students.md) |
| 607 | [Sales Person](https://leetcode.com/problems/sales-person/) | 🟢 Easy | Subquery with `NOT IN` | $O(O + C + S)$ | $O(U)$ | [607. Sales Person.md](./607.%20Sales%20Person.md) |
| 610 | [Triangle Judgement](https://leetcode.com/problems/triangle-judgement/) | 🟢 Easy | Triangle Inequality (`CASE WHEN`) | $O(N)$ | $O(1)$ | [610. Triangle Judgement.md](./610.%20Triangle%20Judgement.md) |
| 619 | [Biggest Single Number](https://leetcode.com/problems/biggest-single-number/) | 🟢 Easy | `GROUP BY` & `MAX()` Subquery | $O(N)$ | $O(U)$ | [619. Biggest Single Number.md](./619.%20Biggest%20Single%20Number.md) |
| 620 | [Not Boring Movies](https://leetcode.com/problems/not-boring-movies/) | 🟢 Easy | Filter (`MOD`) & `ORDER BY DESC` | $O(N \log N)$ | $O(K)$ | [620. Not Boring Movies.md](./620.%20Not%20Boring%20Movies.md) |
| 627 | [Swap Salary](https://leetcode.com/problems/swap-salary/) | 🟢 Easy | In-Place `UPDATE` with `CASE` | $O(N)$ | $O(1)$ | [627. Swap Salary.md](./627.%20Swap%20Salary.md) |
| 1050 | [Actors and Directors Who Cooperated At Least Three Times](https://leetcode.com/problems/actors-and-directors-who-cooperated-at-least-three-times/) | 🟢 Easy | `GROUP BY` & `HAVING COUNT(*) >= 3` | $O(N)$ | $O(P)$ | [1050. Actors and Directors Who Cooperated At Least Three Times.md](./1050.%20Actors%20and%20Directors%20Who%20Cooperated%20At%20Least%20Three%20Times.md) |
| 1068 | [Product Sales Analysis I](https://leetcode.com/problems/product-sales-analysis-i/) | 🟢 Easy | `INNER JOIN` on `product_id` | $O(S + P)$ | $O(S)$ | [1068. Product Sales Analysis I.md](./1068.%20Product%20Sales%20Analysis%20I.md) |
