# System Patterns

## System Architecture
The project follows a simple, directory-based architecture. Each major statistical topic is contained within its own directory. This modular approach keeps the content organized and easy to navigate.

## Key Technical Decisions
- **Directory per Topic:** Each statistical concept (e.g., "Sampling Techniques," "Types of Data") has its own dedicated folder. This makes the project scalable, as new topics can be added simply by creating a new directory.
- **Jupyter Notebooks as Primary Interface:** The core content is delivered through Jupyter Notebooks (`.ipynb` files). This allows for a combination of code, text explanations, and visualizations in a single document.
- **Data Encapsulation:** Data files (e.g., `.csv`, `.xlsx`) used in a notebook are stored within the same directory as the notebook itself. This makes each module self-contained.

## Design Patterns in Use
- **Modular Design:** The project is broken down into smaller, independent modules (directories). This promotes separation of concerns and makes the codebase easier to manage.
- **Single Responsibility Principle:** Each notebook focuses on a single statistical concept, ensuring that the content is focused and easy to digest.

## Component Relationships
The components are largely independent. There are no complex dependencies between the different topic directories. A user can explore any topic without needing to have gone through others, although a logical progression is suggested by the naming of the directories.
