# README

- Our Twitter does not support multiple users (yet)
- Reimplement a single user's Twitter timeline with a Bootstrap / The Iron Yard flare.
- Make the root page be the list of tweets
    [COMPLETELY ignore rewtweets, favorites, replies, images, etc.]
- Tweets should be shown in the order of most currently posted first
- Use scaffold to create a tweet model that includes
    - text (limit it to 140 characters, e.g. reject any Tweet that has more than 140 characters)
    - user_name
    - created_at (NOTE: You get this for free from scaffolds)
- Implement a link to post a new tweet in the nav header. This should allow the user to submit a new tweet

- Fill in some tweets (bonus points if you use learn how to use seeds via db/seeds.rb -- see the rails guides)
- Don't allow a tweet without text or a user (See validations in the Rails Guides)

- If the text of a tweet starts with http:, instead of showing the text as plain text, show it as a link.
(e.g. if the tweet is http://google.com then the tweet text should be http://google.com but be a link to that URL.)
TOP TIP: You'll need an if/else condition in your view, and use link_to
