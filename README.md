# jeopardy

## Usage
- Clone Repo
- Open index.html
- Enter search phrase

## Notes
- Run time can be improved, but networking is efficient
- Relies on random sampling
- Sorts by similarity of phrases
- CORS prevents me from hosting this on my website because the API doesn't serve content of https :(

## Improvements
- Runtime of comparison should be O(n*log(n))
- Should also request a random sampling from categories with similar names
- Remove common words such as "a","the","for"
- UI Design
