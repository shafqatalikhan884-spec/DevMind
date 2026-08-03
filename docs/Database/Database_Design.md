# Database Design

## Version
1.0

## Database

MySQL

## Initial Tables

1. users
2. projects
3. documents
4. ai_chats
5. settings

## Relationships

- One User can have many Projects.
- One Project can have many Documents.
- One User can have many AI Chats.
- One User has one Settings record.

## Naming Convention

- Table Names: plural (users, projects)
- Primary Key: id
- Foreign Key: user_id, project_id
- Timestamps: created_at, updated_at