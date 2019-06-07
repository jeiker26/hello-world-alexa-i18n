# hello-world-alexa-i18n - Skill Internationalization (i18n) and Interceptors
Simple skill Alexa (Hello world: es/en)

## Milestones

1. Adding an extra locale (es-ES, translated from en-US)
2. i18next dependency, sprintf, languageStrings (embedded for now)
3. Request and Response Interceptors (loggers), Localisation Interceptor (simplest, no arrays)
4. Attributes Manager, Request Attributes, requestAttributes.t and requestAttributes.t with parameters (string replacement)

## Concepts

1. Multiple models per local
2. Key/value string resources
3. Enriching request attributes with t function
4. Attribute manager as key/value store
5. High level attribute type (request(short term), session(med term), persistent(long term))

## Utils
[https://developer.amazon.com/blogs/alexa/post/285a6778-0ed0-4467-a602-d9893eae34d7/how-to-localize-your-alexa-skills](https://developer.amazon.com/blogs/alexa/post/285a6778-0ed0-4467-a602-d9893eae34d7/how-to-localize-your-alexa-skills)
