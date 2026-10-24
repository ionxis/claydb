# Development of ClayDB

- Flask web app, use gunicorn or other WSGI for production ready, include it in requeriments.txt
- NocoDB like application, friendly GUI to manage tables and columns but with 
- SQLite3 to store data for faster access, reliable
- BeerCSS as library design

### Column types

| Column type | Description |
|---|---|
| text | Simple line text |
| longtext | Loing text with new lines |
| number | Integer |
| float | Float with decimals |
| email | Store as e-mail |
| url | Store a a link |
| bool | true or false only values |
| date | Date only DD/MM/YYYY |
| time | Time only 00:00:00 |
| formula | Use Excel-like formula |