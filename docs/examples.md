# XActions examples

XActions - The Complete X/Twitter Automation Toolkit. Scrapers, MCP server for AI agents, CLI, and browser scripts. No API required. Open source by @nichxbt. Don't Panic.

## Example 1

```bash
npx xactions profile nasa
```

## Example 2

```text
⚡ @NASA

  Name:      NASA
  Bio:       Making the seemingly impossible, possible. ✨
  Location:  Pale Blue Dot
  Website:   http://www.nasa.gov/
  Joined:    2007-12-19
  Following: 119  Followers: 92.2M
  Tweets:    74.3K  Listed:    97.0K
  ✓ Verified
```

## Example 3

```bash
npx xactions tweets nasa --limit 100 --output nasa.csv   # timeline to a spreadsheet
npx xactions login                                        # unlock search, followers, DMs
npx xactions search "your brand" --limit 50               # what people are saying
```

## Example 4

```bash
# Quick start
docker build -t xactions .
docker run -it xactions xactions profile elonmusk

# Run the MCP server
docker run -p 3000:3000 xactions npm run mcp

# With environment variables
docker run -e XACTIONS_SESSION_COOKIE=your_cookie xactions xactions followers elonmusk
```

## Example 5

```bash
docker compose up
```

## Example 6

```bash
npm install xactions
```

## Example 7

```bash
npm install -g xactions
xactions --help
```

## Example 8

```bash
xactions login
xactions non-followers YOUR_USERNAME --output non-followers.json
```


Every snippet above is taken from the [repository documentation](https://github.com/nirholas/XActions#readme).
