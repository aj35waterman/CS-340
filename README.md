# CS-340
Albert Waterman /n
I wrote maintainable, adaptable programs by separating responsibilities and avoiding repetition. In Project One, I created a reusable CRUD Python module that handled all database operations inside a 
single AnimalShelter class instead of mixing database logic directly into the dashboard. That structure made the code cleaner, easier to debug, and easier to expand later. When I connected the dashboard widgets in 
In Project Two, I reused the same module without rewriting queries, improving consistency and reducing errors. In the future, I could reuse this module for other MongoDB-backed applications, APIs, or 
dashboards by simply adjusting the database connection and queries.
When approaching a problem as a computer scientist, I would break everything into groups. For Grazioso Salvare, I identified what data fields were needed, designed queries to filter rescue types, and then 
connected those queries to dashboard callbacks. This differed from earlier assignments because it felt more like solving a real client problem rather than just completing a programming task. Moving forward, 
I would continue designing the data model first, testing database queries independently, and building modular components that can scale as client requirements evolve.
Computer scientists design systems that transform raw data into usable tools that support decision-making. In this project, the dashboard allows Grazioso Salvare to filter, visualize, and map animal data 
quickly instead of manually reviewing records. That improves efficiency, reduces human error, and supports better operational decisions
