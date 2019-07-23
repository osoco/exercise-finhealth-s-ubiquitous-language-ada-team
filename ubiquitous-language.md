# FinHealth: Ubiquitous Language

## Concepts

- **role**: defines a user's access to the application. A role is assigned by the user manager. Not everyone has a role, only users can have one if it is assigned. A user can have more than one role.
- **employee**: Company employee - works on projects but doesn’t have access to the application. Has no role unless is a user. 
- **user**: Has access to the application. 
- **user role manager**: Administrator - Can do everything. Creates and manages other users, etc. 
- **user role talent manager**: Creates employees and updates employee information. Assigns roles to users.
- **user employee**: Registers hours worked, adds and updates hours
- **user role cost manager**: Registers incoming and outgoing invoices
- **user role project manager**: Creates projects, creates tasks, assigns - profiles to employees, assigns employees to projects

- **task**: Predefined task within a project (only a project manager can create and update this but user employee can choose one). An employee can choose a default task for a given project. 
- **work**: Hours spent on a task (employees can add comments to this). To add work the hours can be counted during the work or added manually later. The three users that can add work are employee, manager and project manager. 
- **tariff**: Cost for each profile on a project. The tariff for the same profile can change between projects. 
- **profile**: Describes each person’s responsibilities within a project. A profile can be shared between projects. An employee can have more than one profile in a project or can have a different profile in different projects.  
- **project**: Services to be provided based on client’s needs (each project has a start date, end date, different profiles, tariffs, tasks and employees associated with it). Only a project manager can create a project and can't create one if there is no client. The project has tasks given by the project manager. 
- **client**: Company who has commissioned a project. To add a project a client is needed. 
- **quarter**: Three month financial period. Every quarter the application must calculate the balance of the enterprise. If in each querter there is an incoming invoice missing it should send a warning. 
- **incoming invoice**: Invoice received from provider or freelance worker
- **outgoing invoice**: Invoice issued by OSOCO


# Questions

- **user role client manager**: Creates clients and updates client information.
 *****This role doesn't add much value. We think it should be the project manager, the cost manager and the manager who  can create and update client information. 
 How would it work?. The project manager and costs manager can both modify the client's information? 
  **user role talent manager**: Assigns roles to users. Can the talent manager also create users or only assign roles?