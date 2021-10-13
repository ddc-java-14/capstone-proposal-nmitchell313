## Summary

<i> Affirmation Generator </i> is an easy to use, interactive, mental health app. <i> Affirmation Generator </i> greets the user with a personal message,
takes input from user regarding their current mood ("happy", "sad", "upset", "angry", etc) and generates specific affirmations and quotes based on that input.

## Intended users

* Someone going through stress or needs a confidence boost.

> As someone down on their luck, I want an app I can use to generate a random, inspirational quote for me to analyze 
> and help brighten my mood.

* Someone wanting a daily affirmation message

> As someone looking for a daily dose of kind words to start my morning, I want an app that I can tell to wake me up daily with only positive quotes and affirmations.
 
## Client component

### Functionality

* User will be greeted at the beginning window and asked "how they are feeling today".

* Once interaction between app and user has been initiated, user will:

  * Interact with search bar or a drop window where they will query a desired quote/affirmation by author name, a daily generated quote/affirmation or one quote/affirmation at a time.

  * Receive a quote/affirmation and learn the author.


### Persistent data

* User's name and mood.

* List of quotes/affirmations.

* Saved author name and quote.
    
### Device/external services

* TBD
    
## Server component

### Functionality

* Quote database search .

* Save quotes and author of that quote.

### Persistent data

* Quote information (Author, quote and similar matches).

* Search history.

* Favorite quote.

* Favorite author.
    
### External services

* <p> <a href="https://premium.zenquotes.io/zenquotes-documentation/">
  Quote Generator API
</a> </p>

* Google sign-in.
    
## Stretch goals/possible enhancements 

* This app will, in its finished product, ask the user daily how they are feeling and provide specific quotes/inspiration to either,
 boost confidence, provide advice/words of encouragement, lift self-esteem or etc.

