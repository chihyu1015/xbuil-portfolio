# Role workflows / 角色操作與權限導覽

Illustrative workflows based on recorded local acceptance; not a new browser test.

| Role | Project workspace | Salary workspace | Evidence |
|---|---|---|---|
| Admin 管理員 | Project list and administrative detail hub | Salary dashboard; detail access subject to permission | Local project and salary views checked |
| Worker 工人 | Limited project workspace; selected site stored in sessionStorage | Worker paystub page | Local site switch and reload checked; paystub calculation pending |
| Owner 業主 | Limited project workspace | Owner payments page | Local role sign-in checked; payment workflow pending |

## Admin / 管理員
1. Select Admin on demo login and sign in.
2. Open Projects and select a fictional project.
3. Inspect the project detail hub. Creation uses the list modal. Creation and editing are not certified by this guide.
4. Open Salary. Salary details are gated by management permission or own identity in the inspected card logic.
5. Open company monthly report. Recorded acceptance showed revenue, project cost, project gross profit, company cost and operating surplus.

## Worker / 工人
1. Select Worker on demo login.
2. Open project list and select an assigned site.
3. Open salary workspace for paystub review. Attendance submission and calculation require further validation.

## Owner / 業主
1. Select Owner on demo login.
2. Open project list and inspect the limited workspace.
3. Open salary workspace for owner payments view. Do not assume payment editing or unrestricted project access.

## Access boundaries

Role-specific views illustrate intended access boundaries; they do not certify hosted database security.
