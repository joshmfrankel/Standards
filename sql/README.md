# SQL

## Best Practices

### Tables
1. Each table **MUST** have an id column of type int
2. Table names **MUST** use PascalCase
3. Table names **MUST** be singular

### Columns (fields)
1. Columns **MUST** be lowercase
2. Columns **MUST** use the underscore(_) character to separate words
3. Column names **MUST** be logical and descriptive
4. Column names **MUST NOT** use reserved words

### Queries
1. All reserved words **MUST** be in uppercase to increase readability
2. All variables **MUST** be properly escaped

## Special Cases

### Many-to-Many Join
When dealing with two tables that can be related to each other with multiple joins an intermediate table is required.  These table's naming convention should attempt to remain semantic unless no logical semantic name exists.  If the latter is the case then, concatenating the two tables in PascalCase is preferred.

**Example**  
(Reader Table --- Newspaper Table)
1. Semantic Name: **Subscription**  
2. Concatenate names: **ReaderNewspaper**  
