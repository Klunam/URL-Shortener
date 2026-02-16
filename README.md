# URL-Shortener
Shorten long URLs, redirect when accessed 

#What is a URL Shortener?
The Problem It Solves

Long URLs are ugly and hard to share
Example: https://www.example.com/products/electronics/phones/iphone/models/iphone15/reviews?sort=rating&filter=verified
Shortened: https://short.url/abc123

#How It Works

*User gives you a long URL
*Your API generates a short code (like "abc123")
*You store the mapping (short code → long URL)
*When someone visits short.url/abc123, you redirect them to the long URL
*You track statistics (how many clicks, when last accessed, etc.)
