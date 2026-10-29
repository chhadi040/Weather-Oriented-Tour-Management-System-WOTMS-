# Weather-Oriented-Tour-Management-System-WOTMS-
Run @sql/schema.sql in SQL*Plus to create 9 tables, sequences/triggers and sample data (admin/admin123). Then in server/: npm install, copy .env.example to .env with your Oracle credentials, npm start. Express serves everything at http://localhost:3000 (admin at /admin), no build step. Flow: browser → fetch /api → Express → Oracle.
