# Web Score Generator

1. Set up jobs which score websites
2. Jobs return scores
3. View the scores

Websites are scored on the following criteria, out of 7 points.

1. 1 point for supporting HTTPS
2. 1-3 points depending on page load (3 points under 500 ms, 2 points under 1000 ms, 1 point under 2000 ms)
3. 1-3 points depending on payload size (3 points if under 1 MB, 2 points under 5 MB, 1 point under 10 MB)

# Architecture

See c1.plantuml and c2.plantuml for a description of architecture.

The web API will be a Django app using django-ninja as a REST API.

