# <Lab title>

- **Topic:** <e.g. SQL injection>
- **Source:** <PortSwigger Web Security Academy / TryHackMe>
- **Lab link:** <url>
- **Difficulty:** <Apprentice / Practitioner / Expert>
- **Date solved:** <YYYY-MM-DD>
- **Tools:** <e.g. Burp Suite Community, browser dev tools>

## Summary

Two or three sentences: what the flaw is and what an attacker gains from it.

## The vulnerability

Explain in your own words why the application is vulnerable. What does the code most likely do wrong on the server?

## Finding it

What made you suspect the flaw? Which input did you test first, and how did the application respond?

## Exploiting it

Step by step, with the requests or payloads you used.

```http
GET /example?param=payload HTTP/2
```

Explain why each payload works, not only that it works.

## Impact

What could an attacker do with this in a real application?

## The fix

Show vulnerable code and the fixed version, in a language you know.

```python
# Vulnerable

# Fixed
```

Explain why the fix works, and mention any extra defence (input validation, least privilege, etc.).

## What I learned

One to three bullet points.

## References

- <link to the PortSwigger topic page, OWASP cheat sheet, etc.>
