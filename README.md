# Watch Together Telegram Bot

Telegram bot for selecting movies to watch together.

## Bot commands

- `/start`
- `/help`
- `/create_group`
- `/join_group id`
- `/suggest_movie Movie_Name`
- `/vote Movie_Name`
- `/list_movies`
- `/watched Movie_Name`
- `/veto Movie_Name`

## Development

### Install

```bash
git clone https://github.com/gpont/watch_together.git
cd watch_together
npm i
```

### Run

```bash
npm start
```

### Testing

```bash
npm test
```

### Lint and format

```bash
npm run lint:fix
npm run format
```

### Build

```bash
npm run build
```

### Run Docker

```bash
docker build -t watch_together .
docker run -p 3000:3000 watch_together
```
