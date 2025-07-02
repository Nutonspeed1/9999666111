# 9999666111

This project includes SQL definitions for core tables used by the app. The schema is stored in `database/schema.sql`.

## Applying the schema

### Supabase SQL editor
1. Log in to your Supabase dashboard.
2. Open the **SQL Editor** and create a new query.
3. Copy the contents of `database/schema.sql` and run the query to create the tables.

### Supabase CLI
If you prefer using the CLI, ensure you have it configured and run:

```bash
supabase db execute --file database/schema.sql
```

This will execute the script against your configured database.
